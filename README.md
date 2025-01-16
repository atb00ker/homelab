# Homelab

A public wiki of my homelabbing knowledge to help developers setup their own homelab.

Please go to the [latest version of the guide](https://atb00ker.github.io/homelab/) for more information.

## Contributing

Contributions are welcome!
However, If I have not used the product myself, the author's details should be clearly stated on the page.

## Setup

```bash
# Install the latest version of hugo
# Go here to download: https://github.com/gohugoio/hugo/releases
# If say, you're on debian,
# dpkg -i <hugo-downloaded-file>.deb

# Install other dependencies
# Note: I use pnpm, but you can use npm or yarn if you prefer
pnpm install

# Run the dev server
pnpm dev
```

Making the changes is simple, it's markdown files in given folder structure in the `content` directory.

### Update Github Pages

Firstly, commit your changes.
Then,

```bash
pnpm build
pnpm ghupdate
pnpm ghpush
```

