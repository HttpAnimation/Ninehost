# Ninehost

Ninehost is a lightweight Docker container that allows you to quickly broadcast a website to your local network. It uses Nginx to serve the website content and is designed to be easy to set up and use.

## Features

- **Simple Setup**: With a Docker container, setting up Ninehost is a breeze.
- **Network Broadcasting**: Your website is broadcasted to the entire local network.
- **Customizable**: Easily replace the default website content with your own.

## Usage

### Prerequisites

Make sure you have [Docker](https://www.docker.com/get-started) installed on your machine.

1) Linux 
2) MacOS
3) Windows (Not tested)

### Quick Start

1. Clone this repository:

    ```bash
    git clone https://github.com/HttpAnimation/Ninehost.git
    cd Ninehost
    ```

2. Build the Docker image:

    ```bash
    docker build -t ninehost .
    ```

3. Run the Docker container:

    ```bash
    docker run -d --name ninehost --network host ninehost
    ```

4. Access your website by navigating to `http://localhost` or using the IP address of the machine where the container is running with the port of witch you are using.

### Customizing the Website

Replace the contents of the `Site` folder with your own website files, including an `index.html` file.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project not licensed under anything you allowed to use this for what ever.

