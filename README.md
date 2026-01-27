# A.R.D.A.

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t arda .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> arda
```

<!-- ## Contributing

If you have suggestions for how arda could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md). -->

## License

This repo is licensed under an MIT license. A copy of the license is also provided.

---

[contributors-shield]: https://img.shields.io/github/contributors/jordandarlington/arda.svg?style=for-the-badge
[contributors-url]: https://github.com/jordandarlington
[forks-shield]: https://img.shields.io/github/forks/jordandarlington/arda.svg?style=for-the-badge
[forks-url]: https://github.com/jordandarlington/arda/network/members
[stars-shield]: https://img.shields.io/github/stars/jordandarlington/arda.svg?style=for-the-badge
[stars-url]: https://github.com/jordandarlington/arda/stargazers
[issues-shield]: https://img.shields.io/github/issues/jordandarlington/arda.svg?style=for-the-badge
[issues-url]: https://github.com/jordandarlington/arda/issues
[license-shield]: https://img.shields.io/github/license/jordandarlington/arda.svg?style=for-the-badge
[license-url]: https://github.com/jordandarlington/arda/blob/main/LICENSE.txt