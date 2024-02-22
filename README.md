<h1 align="center">Benchless: Streamlining Your Development Environment</h1>
<p align="center">
Benchless is your essential toolkit for efficiently setting up Python, NodeJS, or Empress/Empress environments.
<br />
<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/benchless/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/benchless/issues">Request Feature</a>
</p>

## About Benchless

Benchless is an accessible and streamlined solution for developers seeking to set up and manage Python, NodeJS, or Empress/Empress environments. It eliminates the hassle and saves valuable time, enabling you to focus on what matters most – building great software.

### Key Features
- Python setup via pyenv
- NodeJS setup via nvm
- Empress/Empress environment setup
- Development process management
- Site creation and deletion

## Getting Started

### Prerequisites
Ensure you have the following system prerequisites: Python 3, NodeJS, yarn, MariaDB, and Redis.

### Installation
Follow these steps to get your development environment up and running:

1. Clone the Benchless repository:
```sh
git clone https://github.com/empress-eco/benchless.git
```

2. Set up Python with pyenv:
```sh
pyenv install 3.7.6
```

3. Set up NodeJS with nvm:
```sh
nvm install 12
```

4. Install yarn:
```sh
npm install yarn -g
```

5. Set up Empress/Empress Environment:
```sh
./setup-Empress.sh
```

6. Start mariadb:
```sh
sudo systemctl start mariadb.service
```

7. Start development processes:
```sh
./env/bin/honcho start
```

8. Create a new site:
```sh
./benchless.py Empress new-site mysite.localhost --install-app Empress
```

9. Drop a site:
```sh
./benchless.py Empress drop-site mysite.localhost
```

## Usage
Explore various Benchless commands with:
```sh
./benchless --help
```

## Contributing
We welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Benchless repository
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License.

We extend our heartfelt gratitude to the Empress Community for their foundational contributions to this project. Their innovative tools and unwavering support have been instrumental to the success of Benchless.