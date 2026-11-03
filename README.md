# vault-assets-02

Asset packs for the Roblox Dev Mastery Vault: `audio.zip`, `catalog.zip`, `code.zip`, `hdris.zip` (see [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for author, licence and source of every pack). All packs are CC0, MIT, Apache-2.0 or MPL-2.0; each pack folder carries its licence file.

The zips are **Release assets** of this repository (release tag `assets`), not git files: https://github.com/romangigliotti123-arch/vault-assets-02/releases/tag/assets

| File | Size | SHA256 |
|---|---|---|
| [audio.zip](https://github.com/romangigliotti123-arch/vault-assets-02/releases/download/assets/audio.zip) | 15.1 MB | `d4091e26e5b10839d2927ea77d1d811892832e44298f7586bb948308a60a0d12` |
| [catalog.zip](https://github.com/romangigliotti123-arch/vault-assets-02/releases/download/assets/catalog.zip) | 0.1 MB | `1c4302a06be3de54184d913b61300fd7af1af4efd26ef1d259a360ba938c3f46` |
| [code.zip](https://github.com/romangigliotti123-arch/vault-assets-02/releases/download/assets/code.zip) | 67.8 MB | `789d39205c092abb1b6ccf9c362d9d768a92f9b80cb4f66aed88b0178ed3f94d` |
| [hdris.zip](https://github.com/romangigliotti123-arch/vault-assets-02/releases/download/assets/hdris.zip) | 47.8 MB | `b82dc83a334e4ddac3183dfe1b52e2b684f0bd16150a94bc620129a9653abd28` |

## How to get them

You normally do not download by hand: `/update-rbxdev-vault` in Claude (or the setup paste from the vault-kit repository) runs `claude-kit/tools/assets-sync.py`, which reads [repos.json](https://raw.githubusercontent.com/romangigliotti123-arch/vault-kit-01/main/repos.json), downloads the zips of every `vault-assets-NN` repository, checks the SHA256 and extracts them into `<vault>/Assets/`. By hand: download a zip from the table, check `sha256sum`, extract into `Assets/` (the zip has one top-level folder named after its type).

Series: vault-assets-01, vault-assets-02. A new repository `vault-assets-NN+1` is created when the newest one passes about 900 MB; `repos.json` lists them all.

## Licence

Third-party content under the licences in THIRD-PARTY-NOTICES.md. No licence is claimed over it by the repository owner. Contact: the owner of this repository (GitHub: romangigliotti123-arch); open an issue or write to the owner and the item is removed.
