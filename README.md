<p>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="jamesmcpc: Infra · Tooling · Backend · Games" src="assets/banner-light.svg" width="100%">
</picture>
</p>

Hi, I'm James! I started out hosting game servers for my friends, and ended up building my own.
These days, I spend my time working on infrastructure, developer tooling, and games.
Most of that is private, so the changelog below tells the story instead!

## <img src="assets/icons/history.svg" width="20" height="20" align="absmiddle" alt=""> Changelog

#### [Unreleased]
- **Homelab** <img src="assets/tools/nix.svg" width="28" height="16" align="absmiddle" alt="Nix"> <img src="assets/tools/incus.svg" width="38" height="16" align="absmiddle" alt="Incus"><br>
  My home servers, declared in Nix.
- **Personal infrastructure** <img src="assets/tools/typescript.svg" width="65" height="16" align="absmiddle" alt="TypeScript"> <img src="assets/tools/podman.svg" width="51" height="16" align="absmiddle" alt="Podman"> <img src="assets/tools/systemd.svg" width="53" height="16" align="absmiddle" alt="systemd"><br>
  The services and tooling I run for myself.

#### [2025]

- **Civilisation event**<br>
  Worked on a high scale minecraft civilisation event in France (1000 players). [Watch it on YouTube](https://www.youtube.com/watch?v=bBTFzX0b8wE).
- **Quarkus service framework** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"> <img src="assets/tools/quarkus.svg" width="52" height="16" align="absmiddle" alt="Quarkus"><br>
  A Kotlin layer on top of Quarkus: commands, menus and endpoints are declared with annotations.
- **Terraform, pyinfra and GitOps** <img src="assets/tools/terraform.svg" width="60" height="16" align="absmiddle" alt="Terraform"> <img src="assets/tools/pyinfra.svg" width="46" height="16" align="absmiddle" alt="pyinfra"><br>
  The whole network provisioned with Terraform, configured with pyinfra and deployed from a GitOps repository.
- **Gradle conventions** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"> <img src="assets/tools/gradle.svg" width="44" height="16" align="absmiddle" alt="Gradle"><br>
  Gradle plugins that standardize builds across every project. (To make gradle less insane)
- **Ding** <img src="assets/tools/javascript.svg" width="63" height="16" align="absmiddle" alt="JavaScript"><br>
  A bot system for testing game servers.

#### [2024]

- **Continuum** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"> <img src="assets/tools/go.svg" width="26" height="16" align="absmiddle" alt="Go"> <img src="assets/tools/nats.svg" width="40" height="16" align="absmiddle" alt="NATS"><br>
  A microservice framework, with Kotlin and Go implementations sharing one set of RPC definitions.
- **Rassilon** <img src="assets/tools/go.svg" width="26" height="16" align="absmiddle" alt="Go"> <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"> <img src="assets/tools/docker.svg" width="46" height="16" align="absmiddle" alt="Docker"><br>
  Handles matchmaking and orchestrates game servers, starting and stopping them on demand.
- **Accounts** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"> <img src="assets/tools/go.svg" width="26" height="16" align="absmiddle" alt="Go"><br>
  The account service shared by every game server, with its RPC definitions and a Go client library.
- **Configs service** <img src="assets/tools/go.svg" width="26" height="16" align="absmiddle" alt="Go"><br>
  Serves and manages the configuration files for every server.
- **Doktor** <img src="assets/tools/go.svg" width="26" height="16" align="absmiddle" alt="Go"> <img src="assets/tools/pkl.svg" width="27" height="16" align="absmiddle" alt="Pkl"><br>
  A CLI for building, packaging and deploying game server containers, with server configs written in Pkl.
- **Game API** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"><br>
  A framework and project template for building mini-games.
- **13 mini-games** <img src="assets/tools/kotlin.svg" width="39" height="16" align="absmiddle" alt="Kotlin"><br>
  WarpStar, Racer, Bodyguard, GetRekt and many more, all built on the Game API.


## <img src="assets/icons/mail.svg" width="20" height="20" align="absmiddle" alt=""> Contact

Email: [james@mcpc.dev](mailto:james@mcpc.dev) | Discord: `@jamesmcpc`

<sub>Spot the references to Doctor Who in my project names :)</sub>