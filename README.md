# Preface, Method, and Translation Notes

The public front matter and apparatus of **An AI Translation of the Hebrew and Greek
Scriptures** — the preface ("What This Is, and What I Am"), the complete *Sources and Method*
document, and the chapter-by-chapter translation notes, all reproduced in full and unaltered.

This repository exists to give the short videos a public, permanent link. Everything in it is
meant to be read by anyone.

## What is here

- `index.html` — the preface and *Sources and Method*, self-contained. No build step, no
  dependencies, no external requests.
- `genesis/` — the translation notes, **one page per chapter**: `genesis/3/` is the notes on
  Genesis 3. Chapters 1–45 are published; the rest follow as they clear review.
- `genesis/index.html` — the chapter list.
- `.nojekyll` — stops GitHub Pages running the pages through Jekyll.

Typography is not invented for the web. The palette and the typeface are taken from the
chapter builder that sets the printed volume, so a reader arriving from a video recognises
the page as the same object as the chapters.

## What is *not* here, and why

The translation text itself, the prompts, and the tooling that makes the videos stay in a
separate private repository. GitHub has no partial visibility — a repository is public or it
is not — so this second repository holds only what a reader is invited to read.

Anything committed here is public permanently, history included. The notes are extracted from
the chapter documents by a generator that audits every page for pipeline vocabulary before
writing it, and prints what it finds for a person to read rather than counting the hits and
declaring itself clean.

## Why one page per chapter

The notes are reached from a video description, and a video is one chapter, so the link has to
land on that chapter and nothing else. An anchor into a book-length page would still make a
phone download all 300KB of Genesis to reach one paragraph.

## Why this repository matters

Every video links here. The preface states plainly that the translator is a language model and
not a believer, and asks for that to be said at the front so nothing is mistaken for more than
it is. A description that makes that claim and then points at a page nobody can open argues
against itself, which is the whole reason this repository is public.

The notes are the second half of that argument. Where a verse could honestly be read more than
one way, they record which way it was read and why — including the places where the reading is
contested and the choice could have gone otherwise.

## Publishing

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
