## wordpress-docker-template

It's a simple template for wordpress projects to run in a Dcker configuration.


## Requirements

* The latest version of Docker (can be downloaded here: [https://docs.docker.com/engine/installation/](https://docs.docker.com/engine/installation/))
* Docker compose (can be downloaded here: [https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/))


## Installation

1. Get the latest version of this repository running the command:

    ```
    git clone https://github.com/IanMirandaDev/wordpress-docker-template.git
    ```

2. Create a `.env` file based on the `.env.example` and update the environment variables into that. 

3. Run Docker Compose:

    **Please note**: the action must be performed with **root** rights.

    ```
    docker-compose up -d
    ```

    **Please note**: you might need to wait a couple of minutes when all the containers are up and running after the above command.

4. Access the app into the [localhost:8080](http://localhost:8080) address at your browser and follow the installation wizard.
