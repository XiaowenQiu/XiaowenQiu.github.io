# Xiaowen Qiu's personal homepage

Static HTML/CSS homepage, adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron_website).

Open `index.html` directly, or serve this directory with `python -m http.server 8000`.

## Publications

The homepage contains six publications from [Google Scholar](https://scholar.google.com/citations?user=kqif8UsAAAAJ&hl=en), checked on October 12, 2026. LuciBot is omitted at the owner's request. Entries use the official conference year where verified, rather than the year of a later proceedings release. RobotSmith is NeurIPS 2025 even though Scholar lists 2026. Conference and preprint versions appear as a single entry.

`data/publications.json` records publication metadata, verification sources, and original image URLs. The page itself is static in `index.html` and requires no JavaScript or build step. Keep the JSON and HTML in sync when editing publications.

Publication media are stored in `images/publications/`. Five match those used on [Yian Wang's homepage](https://wangyian-me.github.io/): three PNGs for IM-ENGINE, PhyScensis, and RobotSmith, plus animated GIFs for Articulate AnyMesh and ARCHITECT. The GIFs are approximately 12.5 MB and 6.8 MB and load lazily. 3D-VLA uses the approximately 3.1 MB MP4 from [Haoyu Zhen's homepage](https://haoyuzhen.com/), with muted looping playback and controls. Original media source URLs are recorded in the metadata. The 3D-VLA project host could not be resolved, so its original URL is preserved in the metadata while its code link remains available.

The biography introduces the PhD program, advisor, research goals, and previous degrees. Portrait and additional contact links can be added in the next iteration.
