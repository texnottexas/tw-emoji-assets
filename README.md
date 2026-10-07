# tw-emoji-assets

Top War chat emoji art and IDs for the 2864tw.com Ops Center "Fun Stuff" emoji sender.

- `catalog.json`: `{version, packs:[{id, name, icon}], emojis:[{id, kind, pack, name, file, thumb?}]}`
  - `kind: "static"`: a built-in emoji, sent with the game's `sendEmotionGroup(channel, id, uid, name)`.
  - `kind: "gif"`: an animated emoji, sent with `sendGIFGroup(channel, id, uid, name)`. `thumb` is its first frame.
- `static/<id>.png`, `packs/<packId>.png`, `gif/<id>.gif`, `gif-thumb/<id>.png`

Pulled from the H5 game client's own sprites. The packs every player already has are left out, and so are the
G123-only packs (the H5 client has no art for them). Game art only: no player data.
