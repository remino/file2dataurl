# file2dataurl

By Rémino Rem <https://remino.net/>

Create .htaccess file for Apache HTTPd to show a stylised directory index.

[Code & Download](https://github.com/remino/file2dataurl/)

- [Getting Started](#getting-started)
  - [Installation](#installation)
    - [Using Homebrew on macOS](#using-homebrew-on-macos)
    - [Using git](#using-git)
    - [Using cURL](#using-curl)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Installation

#### Using Homebrew on macOS

```sh
brew tap remino/remino
brew install file2dataurl
file2dataurl -h
```

#### Using git

```sh
git clone https://github.com/remino/file2dataurl.git
cd file2dataurl
./file2dataurl -h
```

#### Using cURL

```sh
curl -L https://github.com/remino/file2dataurl/raw/main/file2dataurl > file2dataurl
chmod +x file2dataurl
./file2dataurl -h
```

[Back to top](#file2dataurl)

## Usage

```
file2dataurl 1.0.0

USAGE: file2dataurl [<options>] <file>

Convert file to base64 data URL.

OPTIONS:

	-h        Show this help screen.
	-v        Show script name and version number.

```

[Back to top](#file2dataurl)

## Contributing

Contributions are what make the open source community such an amazing place to
learn, inspire, and create. Any contributions you make are **greatly
appreciated**.

If you have a suggestion that would make this better, please fork the repo and
create a pull request. You can also simply open an issue with the tag
"enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[Back to top](#file2dataurl)

## License

Distributed under the ISC License. See `LICENSE.txt` for more information.

[Back to top](#file2dataurl)
