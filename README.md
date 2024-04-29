# Nextcloud Compose setup

### Description

Painless setup of Nextcloud docker container with PostgreSQL database and caching with Redis

### Usage

- Clone the repository
- Make necessary changes in the docker-compose.yml file such as:

  - Mount volumes marked by `<drive_mount_point>`
  - Password marked by `change_this_password`
- Run the following command

  ```
  docker-compose up -d
  ```
- Enjoy. The nextcloud interface would be available at `http://server-ip:8080`
