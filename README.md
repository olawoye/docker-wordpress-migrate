# docker-wordpress-migrate
Base Image code to dockerize existing WordPress sites

## features
- Easy WordPress setup
- Pre-installed with All-in-One WP Migration plugin

## using the image
To get started, follow the instructions below. This guide assumes **Docker** is installed on your machine. If you need to install **Docker**, [read up](https://docs.docker.com/get-docker/)

> * Step 1: Login to your existing **Wordpress** project and install the [All-in-One WP Migration plugin](https://wordpress.org/plugins/all-in-one-wp-migration/). Export the backup as file.
> * Step 2: Clone the repository: $ git clone https://github.com/olawoye/docker-wordpress-migrate.git my-wordpress-website/
> * Step 3: Navigate to the project folder and create an .env file: $ cd my-wordpress-website && cp .env.example .env
> * Step 4: Configure your setup by editing the .env file as necessary: $ nano .env
> * Step 5: Power up the **WordPress** installation: $ docker-compose up -d
> * Step 6: Open your browser and visit http://localhost:11000 (or your preferred configured port); login with the credentials as configured in your .env (resetting your password is recommended). Navigate the **All-in-One WP Migration** >> **Import** and import the backup file  generated in **Step 1**
> * Step 7: That's it folks!


## getting help
If you need additional help using the code, please [email](private_bj@yahoo.com)

## whats new
- customize environment variables

## license
This **Docker** image is released licensed under the [**GNU GPLv3**](https://opensource.org/licenses/GPL-3.0)
