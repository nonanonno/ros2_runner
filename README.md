# ros2_runner
GHA runner for ROS2

## Usage

1. Create an `ACCESS_TOKEN` in [Github](https://github.com/settings/tokens/new)
    - At least `workflow` scope is required
2. Create `.env` file at the top of this repository and add `ACCESS_TOKEN` line like the follows

    ```
    ACCESS_TOKEN=<your-token>
    ```

3. Up container

    ```shell
    docker-compose up -d
    ```
