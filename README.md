# NOIR Library

The NOIR Asset Store's own catalogue (`catalog.json`, schema `noir.library/1`): content packs
(plugins that install into `content/packs/<id>/`) and curated collections of Poly Haven and
ambientCG assets. The editor reads it from
`https://raw.githubusercontent.com/K0KOCHINS/Kokochinss-noir-library/main/catalog.json` and falls back to
the copy shipped with NOIR (`<editor>/store/noir-library`).

Everything here is CC0. To add a pack: put its files under `packs/<id>/` (with a
`plugin.noir.json`), add an entry to `packs` listing every file, and a 256 x 256 picture in
`thumbs/`. Collections list members as `polyhaven:<id>` or `ambientcg:<id>`.
