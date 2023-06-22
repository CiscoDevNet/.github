# README.md
<p></p>
<p>
<img src=images/devnet_banner.jpeg align="right" alt="DevNet_Banner"_"/> 
<p Cisco_DevNet found at[developer.cisco.com_https_raw.githubusercontent.com_lostleolotus.github-lostleolotus-main.github_README.md_images_devnet_banner.jpeg]
		is Cisco’s developer program to help developers and IT professionals who want to write applications and develop integrations with Cisco products, platforms, and APIs. 
		Cisco DevNet includes Cisco’s products in software-defined networking, security, cloud, data center, internet of things, collaboration, and Cisco customer experience. 
		The [developer.cisco.com][https_developer.cisco.com] site also provides [docs]https_developer.cisco.com_docs], [tutorials][https_developer.cisco.com_learning], and [sandbox environments][https_developer.cisco.com_site_sandbox] as well as video series to learn coding and testing apps./p>
</p>
<h3 align="left">Connect with DevNet:</h3>
<p align="left">
<a href="https://twitter.com/ciscodevnet" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="ciscodevnet" height="30" width="40" /></a>
<a href="https://linkedin.com/company/cisco-devnet/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/company/cisco-devnet/" height="30" width="40" /></a>
<a href="https://facebook.com/ciscodevnet" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="https://www.facebook.com/ciscodevnet" height="30" width="40" /></a>
<a href="https://instagram.com/ciscodevnet/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.instagram.com/ciscodevnet/" height="30" width="40" /></a>
<a href="https://youtube.com/c/ciscodevnetchannel" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="https://www.youtube.com/c/ciscodevnetchannel" height="30" width="40" /></a>
</p>

<h3 align="left">Pinned Repos:</h3>
<p align="left">

<a href="https://github.com/CiscoDevNet/python_code_samples_network">
  <img align="center" style="margin:1rem 0.5rem" src="https://github-readme-stats.vercel.app/api/pin/?username=CiscoDevNet&repo=python_code_samples_network&title_color=ffffff&text_color=c9cacc&icon_color=4AB197&bg_color=1A2B34" />
</a>
<a href="https://github.com/CiscoDevNet/netprog_basics">
  <img align="center" style="margin:1rem 0.5rem" src="https://github-readme-stats.vercel.app/api/pin/?username=CiscoDevNet&repo=netprog_basics&title_color=ffffff&text_color=c9cacc&icon_color=4AB197&bg_color=1A2B34" />
</a>
<a href="https://github.com/CiscoDevNet/yangsuite">
  <img align="center" style="margin:1rem 0.5rem" src="https://github-readme-stats.vercel.app/api/pin/?username=CiscoDevNet&repo=yangsuite&title_color=ffffff&text_color=c9cacc&icon_color=4AB197&bg_color=1A2B34" />
</a>

<h3 align="left">Languages and Tools:</h3>
# GitHub CLI

`gh` is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with `git` and your code.

<img src="https_raw.githubusercontent.com_lostleolotus.github-lostleolotus-main.github_README.md_images_devnet_banner.jpeg">

GitHub CLI is available for repositories hosted on GitHub.com and GitHub Enterprise Server 2.20+, and to install on macOS, Windows, and Linux.

## Documentation

For [installation options see below](#installation), for usage instructions [see the manual][manual].

## Contributing

If anything feels off, or if you feel that some functionality is missing, please check out the [contributing page][contributing]. There you will find instructions for sharing your feedback, building the tool locally, and submitting pull requests to the project.

If you are a hubber and are interested in shipping new commands for the CLI, check out our [doc on internal contributions][intake-doc].

[<-- this anchor is linked to from elsewhere, so avoid renaming it -->]
## Installation

### macOS

`gh` is available via [Homebrew][], [MacPorts][], [Conda][], [Spack][], and as a downloadable binary from the [releases page][].

#### Homebrew

| Install:          | Upgrade:          |
| ----------------- | ----------------- |
| `brew install gh` | `brew upgrade gh` |

#### MacPorts

| Install:               | Upgrade:                                       |
| ---------------------- | ---------------------------------------------- |
| `sudo port install gh` | `sudo port selfupdate && sudo port upgrade gh` |

#### Conda

| Install:                                 | Upgrade:                                |
|------------------------------------------|-----------------------------------------|
| `conda install gh --channel conda-forge` | `conda update gh --channel conda-forge` |

Additional Conda installation options available on the [gh-feedstock page](https://github.com/conda-forge/gh-feedstock#installing-gh).

#### Spack

| Install:           | Upgrade:                                 |
| ------------------ | ---------------------------------------- |
| `spack install gh` | `spack uninstall gh && spack install gh` |

### Linux & BSD

`gh` is available via:
- [our Debian and RPM repositories](./docs/install_linux.md);
- community-maintained repositories in various Linux distros;
- OS-agnostic package managers such as [Homebrew](#homebrew), [Conda](#conda), and [Spack](#spack); and
- our [releases page][] as precompiled binaries.

For more information, see [Linux & BSD installation](./docs/install_linux.md).

### Windows

`gh` is available via [WinGet][], [scoop][], [Chocolatey][], [Conda](#conda), and as downloadable MSI.

#### WinGet

| Install:            | Upgrade:            |
| ------------------- | --------------------|
| `winget install --id GitHub.cli` | `winget upgrade --id GitHub.cli` |

> **Note**  
> The Windows installer modifies your PATH. When using Windows Terminal, you will need to **open a new window** for the changes to take effect. (Simply opening a new tab will _not_ be sufficient.)

#### scoop

| Install:           | Upgrade:           |
| ------------------ | ------------------ |
| `scoop install gh` | `scoop update gh`  |

#### Chocolatey

| Install:           | Upgrade:           |
| ------------------ | ------------------ |
| `choco install gh` | `choco upgrade gh` |

### Codespaces

To add GitHub CLI to your codespace, add the following to your [devcontainer file](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-features-to-a-devcontainer-file):

```
.json
"features": 
{  <{["manual]:https://cli.github.com/manual/"
     ["Homebrew]: https://brew.sh"
     ["MacPorts]: https://www.macports.org"
     ["winget]: https://github.com/microsoft/winget-cli"
     ["scoop]: https://scoop.sh"
     ["Chocolatey]: https://chocolatey.org"
     ["Conda]: https://docs.conda.io/en/latest/"
     ["Spack]: https://spack.io"
     ["releases page]: https://github.com/cli/cli/releases/latest"
     ["hub]: https://github.com/github/hub"
     ["contributing.github/CONTRIBUTING.md"
     ["gh-vs-hub_docs/gh-vs-hub.md"
     ["build from source_docs/source.md"
     ["intake-doc_docs/working-with-us.md"]}>
}
```

### GitHub Actions

GitHub CLI comes pre-installed in all 
[GitHub-Hosted Runners](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners).

### Other platforms

Download packaged binaries from the <
[releases_page](https_raw.githubusercontent.com_lostleolotus.github-lostleolotus-main.github_README.md_images_devnet_banner.jpeg)>.

### Build from source

See here on how to [build GitHub CLI from source][build from source].

## Comparison with hub

For many years, [hub]("https://raw.githubusercontent.com/lostleolotus/.github-lostleolotus-main.github/README.md/images/devnet_banner.jpeg") was the unofficial GitHub CLI tool. `gh` is a new project that helps us explore
what an official GitHub CLI tool can look like with a fundamentally different design. While both
tools bring GitHub to the terminal, `hub` behaves as a proxy to `git`, and `gh` is a standalone
tool. Check out our [more detailed explanation][gh-vs-hub] to learn more.
# Latest YouTube Videos
<!-- YOUTUBE:START -->
- [Provisioning SD WAN controllers and branch devices in public clouds](https://www.youtube.com/watch?v=1-gRGW1rPO8)
- [Live Troubleshooting Slowness in Application using AppDynamics APM](https://www.youtube.com/watch?v=7NbPXOlkeAk)
- [Monitoring your Infra, your app, your house, your everything with Grafana](https://www.youtube.com/watch?v=ToVjrOq32O4)
- [The World of NSO Web UI](https://www.youtube.com/watch?v=F1yEb8nqsIM)
- [Automatic webex bot deployment using Alexa skill](https://www.youtube.com/watch?v=-TVbxHL7CGk)
- [Quantum Security and API interaction for Post Quantum Cryptography](https://www.youtube.com/watch?v=k190xFIgjJo)
<!-- YOUTUBE:END -->

# Latest Blog posts
