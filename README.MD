# PortIP

PortIP is a simple command-line tool written in Python for pinging websites and scanning for IP addresses and open ports. It provides an easy-to-use interface for network diagnostics and exploration.

![PortIP Banner](portip_banner.png)

## Features

- Ping a website to check connectivity.
- Scan for IP addresses and open ports of a website.
- Customize the number of threads, specify port ranges, enable verbose output, and use advanced scanning features.

## Installation (Via GitHub)

To install PortIP, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/pb2204/portip.git
   ```

2. Run the installation command:
   ```
   python3 portip.py
   ```

## Installation (Via Linux OS)

1. Run the installation command:
    ```
    sudo apt-get install portip
    ```

    or

    ```
    sudo apt install portip
    ```

## Usage

```
python3 portip.py [option] [--url URL] [--threads THREADS] [--port-range PORT_RANGE] [--verbose] [--advanced]
```

### Options:

- `1`: Ping a website to check connectivity.
   ```
   python3 portip.py 1 --url google.com
   ```

   or

   ```
   portip 1 --url google.com
   ``

- `2`: Scan for IP and open ports of a website.
    ```
    python3 portip.py 2 --url google.com --threads 50 --port-range 1-1024 --verbose --advanced
    ```
    or

    ```
    portip 2 --url google.com --threads 50 --port-range 1-1024 --verbose --advanced
    ```

### Additional Flags:

- `--url URL`: Specify the URL to ping or scan.
- `--threads THREADS`: Set the number of threads for scanning (default is 100).
- `--port-range PORT_RANGE`: Specify the port range to scan (e.g., 1-1024).
- `--verbose`: Enable verbose output for detailed information.
- `--advanced`: Enable advanced scanning features.

## Contributing

Contributions are welcome! If you'd like to contribute to PortIP, please follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## Contact

For any inquiries or feedback, feel free to reach out to the developer:

Pabitra Banerjee
Email: rockstarpabitra2204@gmail.com

Happy hacking!
