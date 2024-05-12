[![docs.rs](https://img.shields.io/docsrs/rpgn?logo=docs.rs&label=docs.rs)](https://docs.rs/rpgn/)
[![crates.io](https://img.shields.io/crates/v/rpgn?logo=rust)](https://crates.io/crates/rpgn)
[![license](https://img.shields.io/crates/l/rpgn)](https://github.com/tigerros/rpgn/blob/master/LICENSE)

# RPGN

<ins>R</ins>ust <ins>P</ins>ortable <ins>G</ins>ame <ins>N</ins>otation.

A crate for parsing a PGN, built on [`shakmaty`](https://crates.io/crates/shakmaty) and [`pgn-reader`](https://crates.io/crates/pgn-reader).

`pgn-reader` only allows you to read individual, untyped parts of the PGN, but doesn't actually parse it into something useful.
This crate parses a PGN into the [`Game`](https://docs.rs/rpgn/latest/rpgn/struct.Game.html) struct.