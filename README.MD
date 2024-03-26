<a name="readme-top"></a>

![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCgMjDy6Y7WISZ529S4VyXUg)
[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">

  <h1 align="center">Rust SurrealDB API (uses Axum)</h1>

</div>



<!-- ABOUT THE PROJECT -->
## About The Project

Akhil - I wanted to build an example that uses SurrealDB with Rust. I used SurrealDB a while back and noticed how simple it was to install it - just one command and ZERO configs and also start the DB with the username and password of my choice. I LOVED it and along with Rust, it's the perfect combo!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Rust][Rust]][Rust-url]
* [![Axum][Axum]][Axum-url]
* [![SurrealDB][SurrealDB]][SurrealDB-url]

<!-- GETTING STARTED -->
## Getting Started
### Prerequisites

You need SurrealDB on your PC. 
If you're on linux this is how to install it - 
`curl -sSf https://install.surrealdb.com | sh`

mac - `brew install surrealdb/tap/surreal`
windows - `iwr https://windows.surrealdb.com -useb | iex`

and then start surreal db with this command that sets the username and password - 
`surreal start --user root --pass root --auth memory`

If you to want the feature to run in watch mode, install `cargo-watch`
* cargo-watch
  ```sh
  cargo install cargo-watch
  ```

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/akhilsharma90/rust_surrealdb_API.git
   ```
2. Build the project to install the dependecies
   ```sh
   cargo build
   ```
4. Run with
   ```sh
   cargo run
   ```
   Or, for more dynamic development, run in watch mode
   ```sh
   cargo watch -q -c -w src/ -x run
   ```
   `-q` quiet mode <br>
   `-c` clear the console on reload <br>
   `-w` watch all change to files under `src/` <br>
   `-x` executes `run` command

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Working api structure
- [x] Clean Architecure
- [x] Database

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat: add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Akhil Sharma - [@akhilairi](https://twitter.com/AkhilAiri) - akhil.sharma@myrl.tech

Project Link: [https://github.com/akhilsharma90/rust_surrealdb_API](https://github.com/akhilsharma90/rust_surrealdb_API)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Axum](https://github.com/tokio-rs/axum)
* [SurrealDB](https://surrealdb.com/)
* [Serde](https://serde.rs/)
* [Chrono](https://docs.rs/chrono/latest/chrono/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/akhilsails/
[product-screenshot]: images/screenshot.png
[Rust]: https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white
[Rust-url]: https://rust-lang.org/
[Axum]: https://img.shields.io/badge/Axum-d97d0d?style=for-the-badge
[Axum-url]: https://github.com/tokio-rs/axum
[SurrealDB]: https://img.shields.io/badge/SurrealDB-cc108d?style=for-the-badge
[SurrealDB-url]: https://surrealdb.com/
