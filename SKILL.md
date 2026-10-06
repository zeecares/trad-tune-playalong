---
name: trad-tune-playalong
description: Turn scanned traditional sheet music into a mobile play-along practice page with checked chords, synthesized audio, optional bodhran, a bar-following cursor, speed control, and mandolin chord diagrams. Use when someone shares sheet music and wants to practice along, add chords, clean up handwriting, or build a practice site.
---

# Trad tune play-along

Build from the supplied musical setting, not a different online version. Keep uncertain notes, chords, timing and image edits visible for review.

## 1. Read the sheets
- Render each PDF page as an image. Read scans visually and enlarge unclear bars.
- Transcribe the melody from the supplied sheet. Online settings are comparison aids, not substitutes.
- Check key signatures, accidentals, meter, pickups, repeats and alternate endings before rendering audio. Ask about unreadable passages rather than inventing notes.

## 2. Check chords
- Compare with session sources such as https://www.vashonceltictunes.net/irish/ and https://thesession.org/.
- Verify the actual melody and arrangement match. A matching title or bar count alone is not enough.
- Transpose source chords when needed, then check them against the supplied melody bar by bar. Include repeats and alternate endings.
- Use one or two chords per bar where musically appropriate. There can be several valid accompaniment choices; a source's setting is not the only correct answer.
- Label chords as source-checked, suggested, or unverified. Never present suggested chords as a teacher's chords.

## 3. Clean the sheet
- Keep an untouched copy. Remove handwriting only when requested; preserve printed notation, titles and other requested markings.
- Inspect the edited image beside the original to catch deleted notes, staff lines or printed text.
- Transcribe handwritten chords only when legible. Flag any removed musical information.
- Use one chord data set to drive labels above the bars and chord diagrams. Avoid conflicting labels baked into images.

## 4. Render audio
- Render from the transcribed melody. ABC to MIDI to audio is one possible route.
- Provide a clear melody and optional quiet click. Use the requested tempo; otherwise start at a moderate practice tempo, such as 72 BPM, stating whether beats are quarter notes or dotted quarters.
- Include a two-bar count-in, correctly timed pickups, printed repeats and alternate endings.
- Optional bodhran: a restrained session-style pattern with part-end fills. Toggling it must preserve playback position.
- Check durations and opening pitches programmatically, and listen when possible. State exactly what was and was not checked. Never imply an unheard render was checked by ear.

## 5. Build the mobile practice page
- Per tune: title, sheet with full-size view, optional mandolin chord panel, then a compact player.
- Player: play/pause, a draggable seek bar, current and total time, pitch-preserving speed controls, and optional bodhran toggle.
- Play-along cursor: follows bars through the count-in, pickups, repeats and endings. Seeking and speed changes update both the cursor and current chord.
- Mandolin: standard G-D-A-E tuning, current chord diagram and the tune's chord shapes. Check every displayed voicing produces the named chord, with string order and fret numbers clear.
- Allow only one tune to play at a time.
- Aim to fit a tune card on a phone screen without making notation unreadable. Preserve a full-size sheet view; allow scrolling for long or dense sheets.
- Match the requested visual style. Irish session styling can use cream, deep green, restrained gold accents and serif titles.

## 6. Verify and deliver
- Test at a 390px-wide viewport, with and without chord diagrams. Inspect actual screenshots for readability, clipping and horizontal overflow.
- Scrub both ways and check the cursor and chord at known bar boundaries, including repeat transitions and endings. Test play/pause, speed, track switching and bodhran synchronization.
- Distinguish simulated pointer checks from real phone touch tests.
- Choose hosting based on access, asset size, licensing and maintenance needs. A static page does not require server-side code.
- Publish only to the intended audience, and return a working link. Keep source files available for later edits.

## Rights and limitations
- Check permission before publishing scans, arrangements, recordings or copied chord material. Traditional melodies do not automatically make a modern edition or recording free to redistribute.
- Link to comparison sources and retain provenance. Do not bundle third-party source material without permission.
- Label approximate bar coordinates or estimated timing. Do not hide unresolved musical uncertainty behind a polished page.
