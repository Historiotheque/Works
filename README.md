# Works

The artwork catalog of the Historiotheque: every work across the three streams —
images, sounds, texts — its metadata, and (optionally) a web-resolution display copy,
cross-referenced to the full-resolution masters.

## What this repo is (and isn't)

This repo is the **catalog**, not the vault. It holds metadata records; display copies
are optional. The full-resolution masters live on the **Internet Archive** (the vault:
`the-historiotheque` collection, one item per work); citable releases go to **Zenodo**
(DOIs). Every `work.md` links to its IA item; every IA item links back here.

Rule: work in GitHub, preserve on the Internet Archive, cite via Zenodo.

## Structure

- `index.md` — the catalog: the three streams, every series, every work.
- `<stream>/index.md` — a stream overview (images, sounds, or texts).
- `<stream>/<series>/index.md` — a series overview and its work list.
- `<stream>/<series>/<work-slug>/work.md` — the full metadata record for one work.
- `<stream>/<series>/<work-slug>/<work-slug>_web.<ext>` — optional display copy
  (web image, audio preview, text excerpt).

## Capture standard (going forward)

- **Images** — analog: minimum 4000 px longest edge, RAW+JPEG, tripod, diffuse light,
  no flash. Digital: minimum 6000 px longest edge, PNG/TIFF, keep the layered file.
- **Sounds** — masters: WAV or FLAC, minimum 44.1 kHz / 24-bit; keep the DAW project.
  Preview: MP3.
- **Texts** — masters: source format plus PDF; keep drafts. Excerpt or full text as the
  display copy, at your discretion.
- Display copies are always made *from* the master, never the reverse.
- AI upscaling/processing only for display copies, labeled in metadata. Masters are
  always true originals.

## Licensing

All Rights Reserved unless noted otherwise on the individual work.

- - - - - - -

**A note on what this is.** This repository belongs to an ongoing research-creation
project at the intersections of art, history, and philosophy — the open working
record of one artist-researcher's practice. It documents a method, not a manual:
nothing here is instruction, counsel, or advice on running an art operation, a
studio, or a creative life, and nothing here is presented as a model to follow.
What holds in this laboratory may not hold in yours.

All works are offered in good faith as contributions to public discourse and
aesthetic reflection. Take what is useful and leave the rest — the responsibility
for interpretation, and for whatever is done with it, remains with each participant
in that dialogue.

[A.G. (c) 2026. ![A.G. (c) 2026. All Rights Reserved](https://historiotheque.files.wordpress.com/2016/11/ag_signature_official_2015_50px_cropped.jpg) All Rights Reserved.](http://alexgagnon.com)
