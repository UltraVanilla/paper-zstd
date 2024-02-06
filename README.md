paper-zstd
==========

This implements the Zstd compression algorithm, using the namespaced algorithm id 127 that Mojang provides in 1.20.5. It includes a pre-seeded dictionary, trained using a combination of a fresh world and five publicly available Hermitcraft maps.

`patches/server/8001-Backport-1.20.5-compression-to-1.20.4.patch` includes an implementation of the lz4 algorithm that will be available in 1.20.5.

**Current PaperMC commit hash: c5d168cef92148a6799141832fdb5f95732c1a38 (1.20.4-409)**

Do not submit bug reports if not compiling against this hash!

### License

Choose between GPLv3 and 0BSD. Attribution not required.
