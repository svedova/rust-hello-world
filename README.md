# Rust Hello World

This is a simple "Hello, World!" project written in Rust. It serves as a basic example to get started with Rust programming and deploying applications using [Stormkit](https://stormkit.io).

## Getting Started

### Prerequisites

- [Stormkit](https://www.stormkit.io/docs/welcome/self-hosting) installed for deployment.

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/rust-hello-world.git
   cd rust-hello-world
   ```

2. Build and run the project:

   ```bash
   cargo run
   ```

3. You should see the output:
   ```
   Hello, World!
   ```

## Notes

- Make sure the server listens on the PORT environment variable
- The Rust version is handled in `mise.toml`. This will also tell Stormkit to install Rust on the system.
- The server is designed to terminate after processing the first request. This behavior is a known limitation but does not impact functionality, as Stormkit effectively manages this scenario. Note that this is an example project intended for demonstration purposes.

## ⚡️ Deployment with Stormkit

1. Login to your self-hosted Stormkit. Here's [a guide](https://www.stormkit.io/tutorials/how-to-self-host-stormkit-on-hetzner-cloud) to set it up.
2. Import this project from URL
3. Configure the Build Settings:
   - Build command: `cargo build`
4. Configure the Server Settings:
   - Start command: `cargo run`
5. Click Save and Deploy

- 🛠️ [Setup Stormkit on Hetzner](https://www.stormkit.io/tutorials/how-to-self-host-stormkit-on-hetzner-cloud)
- 🍰 [How to deploy your Strapi CMS](https://www.stormkit.io/tutorials/how-to-deploy-your-self-hosted-strapi-instance)
- 📑 [Stormkit documentation](https://www.stormkit.io/docs/welcome/getting-started)
- 🌞 [Stormkit changelog](https://www.stormkit.io/blog/whats-new)
