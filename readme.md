# Test cases

1. Build local package managment on AMD64

    ```powershell
    docker buildx build -f dockerfile.lpm --no-cache .
    ```

2. Build global package managment on AMD64

    ```powershell
    docker buildx build -f dockerfile.gpm --no-cache .
    ```

3. Build local package managment on ARM64

    ```powershell
    docker buildx build -f dockerfile.lpm --no-cache --platform linux/arm64 .
    ```

4. Build global package managment on ARM64

    ```powershell
    docker buildx build -f dockerfile.gpm --no-cache --platform linux/arm64 .
    ```
