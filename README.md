# N86EC — Cherokee 140 Reference

Personal reference materials for **N86EC**, a Piper PA-28-140 Cherokee Cruiser.
Everything here is a companion to the printed POH — not a replacement.

---

## What's in this repo

| File | For | What it is |
|------|-----|-----------|
| [**poh.json**](poh.json) | **AI agents / apps** | Structured knowledge base — all specs, V-speeds, limits, emergency and normal procedures with keywords. 24 KB, ~6k tokens, loads whole into a context window. |
| [QUICK_REFERENCE.md](QUICK_REFERENCE.md) | Pilot, cockpit | One-page card. V-speeds, limits, weights, emergency memory items. Bookmark this. |
| [POH.md](POH.md) | Human reading | Full transcription of the original 144-page POH with embedded chart/diagram pages. Searchable. |
| [`pages/`](pages/) | Verification | Every page of the source POH as a JPEG. When something looks off, open the matching page here. |

---

## Aircraft summary

|  |  |
|---|---|
| **Model** | Piper PA-28-140 Cherokee Cruiser |
| **Engine** | Lycoming O-320-E2A or O-320-E3D, 150 HP @ 2700 RPM |
| **Propeller** | Sensenich M74DM or 74DM6, fixed pitch |
| **Fuel** | 36 gal standard (50 gal optional), AVGAS 80/87 min grade |
| **Gross weight** | 2150 lb |
| **Service ceiling** | 11,000 ft |

*Applicability: PA-28-140 s/n 28-7425001 through 28-7625275. Verify your specific aircraft's config against the paperwork on board.*

---

## Safety note

**Read this first if you're using anything here in the airplane.**

This repo is OCR'd from a scanned 1970s Piper POH, then cleaned up by hand. Numbers and procedures should be right, but:

- OCR reads tables poorly. Column alignment is often off.
- The FAA-approved sections here are transcriptions — the **printed, currently-effective Airplane Flight Manual and Weight and Balance Report that live in the aircraft** are the legal authority for flight.
- Airworthiness Directives, Service Bulletins, and STC supplements affect real limits and procedures. None of those are in this file.

If a number here doesn't match what's in the airplane's paperwork, **the airplane paperwork wins.**

---

## Related

- [Cherokee CoPilot app](https://mparisi78.github.io/testcheck/) — in-flight assistant that consumes this reference material.
