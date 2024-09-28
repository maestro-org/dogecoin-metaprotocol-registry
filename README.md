<p align="center">
  <a href="https://www.gomaestro.org/">
    <img src="https://www.gomaestro.org/logos/LandingLogos/DarkLogo.svg" alt="Maestro Logo" width="425" />
  </a>
  <h2 align="center">Dogecoin Metaprotocols Registry</h2>
  <p align="center">
    <a href="https://docs.gomaestro.org/Doge/Intro">
      <img src="https://img.shields.io/badge/-Docs-blue?style=flat-square&logo=semantic-scholar&logoColor=white" />
    </a>
    <a href="./LICENSE">
      <img src="https://img.shields.io/github/license/maestro-org/dogecoin-metaprotocols-registry?style=flat-square&label=License" />
    </a>
    <a href="./CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" />
    </a>
    <a href="https://twitter.com/GoMaestroOrg">
      <img src="https://img.shields.io/badge/-%40GoMaestroOrg-F3F1EF?style=flat-square&logo=twitter&logoColor=1D9BF0" />
    </a>
    <a href="https://discord.gg/ES2rDhBJt3">
      <img src="https://img.shields.io/badge/-Discord-414EEC?style=flat-square&logo=discord&logoColor=white" />
    </a>
  </p>
</p>

Registry to house metadata about Dogecoin metaprotocol assets.

## Contributing

Simply add metadata for a particular metaprotocol using the template defined for each metaprotocol. If a template needs to be updated, you can open a PR for that as well.

## Doginals Collections Metadata
| Field            | Type     | Description                                                                 |
|------------------|----------|-----------------------------------------------------------------------------|
| `name`           | String   | The name of the metaprotocol asset.                                          |
| `description`    | String   | A brief description of the metaprotocol asset.                               |
| `avatar`         | String   | URL to an image representing the metaprotocol asset.                         |
| `tags`           | Array    | A list of tags associated with the metaprotocol asset.                       |
| `socials`        | Object   | Social media links related to the metaprotocol asset.                        |
| `socials.x`      | String   | Link to the Twitter profile.                                                 |
| `socials.discord`| String   | Link to the Discord server.                                                  |
| `socials.youtube`| String   | Link to the YouTube channel.                                                 |
| `socials.github` | String   | Link to the GitHub repository.                                               |
| `socials.website`| String   | Link to the official website.                                                |
| `sat_range`      | Object   | The range of satoshis associated with the metaprotocol asset.                |
| `sat_range.min`  | Number   | The minimum satoshi value in the range.                                      |
| `sat_range.max`  | Number   | The maximum satoshi value in the range.                                      |
| `inscription_ids`| Array    | A list of inscription IDs associated with the metaprotocol asset.            |

# TODOs
- [ ] Reference the Maestro Doginals API when available
