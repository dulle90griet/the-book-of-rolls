# The Book of Rolls

<p align="center"><img src="https://img.shields.io/badge/python-3.12-blue" alt="Python versions" title="Python versions" /></p>

A data pipeline and analytics platform for the analogue photographer. As this repository is currently at the planning stage, this Readme is also - for now - a planning document.

## 🌐 Overview

As an avid analogue photographer with a DIY spirit, I involve myself in almost every stage of the photographic process outside of industrial manufacture: I buy colour and B&W film in bulk rolls, load it by hand into individual cassettes, develop my own negatives, scan them myself at home and, when possible, print them in the darkroom.

Throughout this process, my note-taking generates a substantial amount of data, scattered across multiple different media and recording systems (each of them appropriate to its own context). My aim is, first, to create an automated system that synthesizes these many data sources and transforms the data for my own analysis and ease of querying; and then to ask how I might generalize the resulting pipeline as a useful tool for other photographers with their own systems of note-taking.

## 🧩 The Data Sources

All of my records refer to rolls of film according to one of two numbering systems, based on when in the whole process the note is made. An _emulsion-specific_ series assigns roll numbers at the point of first insertion into a camera, grouped by the film used. A _global_ series assigns roll numbers according to the sequence in which rolls (of any emulsion) have actually been finished.

1. Bulk-rolling notes - Paper notebook 📓

_Grouped by origin bulk roll (of 50ft, 100ft or 400ft). Key fields: cassette type, frames loaded, and emulsion series number. Handwritten, requiring manual entry of data into a spreadsheet._

2. Shooting notes - Lightme Logbook app on iOS 📱

_Grouped by camera used. Key fields: emulsion series number; film emulsion; ISO used; time and date of loading; time and date of unloading; text notes on lenses, lens hoods, filters, etc. As the developer does not provide for CSV export or allow external access to data, screenshots will have to be parsed automatically in the cloud to extract this data._

3. Cassette notes - iCloud Notes 📝

_A simple list allowing for tracing of problem cassettes by establishing lineages. Each entry gives the global series number of the last roll for which a cassette was used; a two-letter code, written on its new label, used to trace it; and, when the new roll in it is finished, the new global series number. Note will have to be exported manually prior to automatic parsing and data extraction._

4. Development notes - iCloud Notes 📝

_A list used for planning and tracking batches of development. Key fields: emulsion series number; global series number; development push/pull. Note will have to be exported manually prior to automatic parsing and data extraction._

## ️️⚙️ Technology Plan

Now under investigation. (16 Jan 2025)

