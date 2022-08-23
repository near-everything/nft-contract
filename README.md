<div id="top"></div>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/near-everything/nft-contract">
    <img src="docs/everything.png" alt="Logo" width="80" height="80">
  </a>

<h2 align="center">everything nft-contract</h3>

  <p align="center">
    The NFT Smart Contract for the inventory of everything.
    <br />
    <!-- <a href="https://documentation.everything.dev"><strong>Explore the docs »</strong></a> -->
    <!-- <br /> -->
    <br />
    <a href="https://everything.dev">Use App</a>
    ·
    <a href="https://github.com/near-everything/nft-contract/issues">Report Bug</a>
    ·
    <a href="https://github.com/near-everything/nft-contract/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

The everything nft-contract is an implementation of [NEAR](https://nomicon.io) Protocol's [Non-Fungible-Tokens](https://nomicon.io/Standards/NonFungibleToken/). This contract contains the logic to mint and manage "Things". It creates the NFTs that enable the [market-contract](https://github.com/near-everything/market-contract) and attaches a history of ownership to any single "Thing".
<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [![Rust][rust]][rust-url]
- [NEAR][near-url]

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- Rust per the prerequisites in [near-sdk-rs](https://github.com/near/near-sdk-rs)
- [near-cli](https://github.com/near/near-cli)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/near-everything/nft-contract.git
   ```
2. Build the contract (this will create a main.wasm in /out)
   ```sh
   sh ./build.sh
   ```
   

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [ ] TBD...

See the [open issues](https://github.com/near-everything/nft-contract/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Elliot Braem - elliot@everything.dev

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- Contract mostly derived from [near-examples/NFT](https://github.com/near-examples/NFT)
- README adapted from [Best-README-Template](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/near-everything/nft-contract.svg?style=for-the-badge
[contributors-url]: https://github.com/near-everything/nft-contract/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/near-everything/nft-contract.svg?style=for-the-badge
[forks-url]: https://github.com/near-everything/nft-contract/network/members
[stars-shield]: https://img.shields.io/github/stars/near-everything/nft-contract.svg?style=for-the-badge
[stars-url]: https://github.com/near-everything/nft-contract/stargazers
[issues-shield]: https://img.shields.io/github/issues/near-everything/nft-contract.svg?style=for-the-badge
[issues-url]: https://github.com/near-everything/nft-contract/issues
[license-shield]: https://img.shields.io/github/license/near-everything/nft-contract.svg?style=for-the-badge
[license-url]: https://github.com/near-everything/nft-contract/blob/main/LICENSE.txt
[logging-in-tutorial]: docs/logging-in.gif
[rust]: https://img.shields.io/badge/Rust-000?logo=rust&logoColor=fff&style=for-the-badge
[rust-url]: http://rust-lang.org
[near-url]: http://near.org
