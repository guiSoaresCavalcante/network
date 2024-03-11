## Using Docker with Django REST Framework

### Prerequisites
- Docker installed and configured on your machine.

### Steps

1. **Clone the Repository:**
    ```shell
    git clone git@github.com:guiSoaresCavalcante/network.git
    ```
    ```shell
    cd network
    ```

3. **Build the Container:**
Execute the following command to build the container:
    ```shell
    docker compose up -d --build
    ```

4. **Apply Migrations:**
Run the following commands to apply migrations:
    ```shell
    docker compose exec django ash
    ```
   ```shell
    python3 manage.py migrate
    ```



The project will run on `localhost:8000`.

With these steps, you should have a Django REST Framework application running within a Docker container.
