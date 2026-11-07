# RPG web fork

Published player page: https://joaodlouro.github.io/atlas-vtt-connect/

This fork publishes the local RPG branch: a persistent token sidebar (HP, conditions and size), explicit token selection, shared numeric initiative, dice mode fixes and an optional local WebSocket relay. The parent projects retain their authorship and AGPL-3.0 licensing.

The release is based on the tested local RPG sources. Upstream AR/Tabletop additions remain available in upstream history; they are not part of this release. Runtime configuration, vault data, administrator keys and backups must never be committed.

Publish with the existing `Publish the player page` workflow on main. Local compilation alone does not update the public site. Release verification must open the published URL in a real browser and exercise the complete page with a separate test table.
