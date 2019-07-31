---
title: RDA Images Update
author: Colton Grainger
date: 2019-07-17
revised:
---

## Done

- proved concept with Philip for metadata ingest
    - settled metadata schema
    - adopted Steve Worley's ocean area specifications (along with ISO place names)

- developed `rdai.py` utility script
    - tools for the metadata provider
        - `metadata`
        - `uuid` (should be delegated to file-system)
        - `bundle`
        - `database`
    - searches a directory hierarchy for metadata files
    - could allow for multiple input formats? JSON? XML? (Prefer JSON.)
    - relies on `rdai` python package

## Coming up

- Fedora RESTful API for queries
    - TODO add individual images to the UI
- Implementation on dssdb with Bob and Hua

## Questions

- stable image URLs?
- how to clean metadata? e.g., to avoid misspellings?
- work-flow for the metadata provider?
- maintenance and documentation?
- purpose of the presentation?
