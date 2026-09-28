<p align="center">
  <img src="https://raw.githubusercontent.com/kenlens-rtls/.github/main/profile/kenlens-logo.png" alt="KenLens" width="280" />
</p>

<h3 align="center">Self-hostable real-time location for indoor asset tracking</h3>

KenLens is a Real-Time Location System (RTLS) for factory floors. It ingests UWB
ranging from anchors over MQTT, computes tag positions, evaluates zone geofences and
raises alerts, and streams it all to a live, map-based dashboard in the browser.

It runs **fully self-contained** — one `docker compose up`, no cloud services, no
outbound telemetry — so it fits air-gapped and security-restricted sites, without
being limited to them.

### Install

> The first release is in preparation — the bundle and images appear with it.

➡️ **[kenlens-deploy](https://github.com/kenlens-rtls/kenlens-deploy)** — the install
bundle: a production Docker Compose stack for **amd64** and **arm64** (Raspberry Pi 4/5,
64-bit OS), with a setup script and step-by-step instructions.

Container images are published to
[GitHub Container Registry](https://github.com/orgs/kenlens-rtls/packages) under
`ghcr.io/kenlens-rtls` — pull them anonymously, no login required.
