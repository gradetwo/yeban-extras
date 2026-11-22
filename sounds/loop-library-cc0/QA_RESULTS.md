# QA results — 2026-11-22

Checks per file: ffprobe format, full decode, peak level, loop seam wrap jump (last sample -> first sample, relative to peak).
factory_ready = decodes clean, stereo, sample rate >= 44100 Hz, bit depth >= 16, peak <= -0.05 dBFS, seam jump <= -14 dB rel.

Total: 49 files, factory_ready 31, flagged 18.

- #1 `drums/484630__loop_cult__lcc_120_drum_01_full.wav` — 44100 Hz, 24 bit, 2 ch, 8.000 s, peak -0.21 dBFS, seam -44.9 dB rel — READY
- #2 `drums/829176__looplicator__120-bpm-industrial-drum-loop-15378-wav.wav` — 44100 Hz, 16 bit, 2 ch, 16.000 s, peak -0.75 dBFS, seam -42.2 dB rel — READY
- #3 `drums/825400__looplicator__75-bpm-industrial-drum-loop-15015-wav.wav` — 44100 Hz, 32 bit, 2 ch, 25.600 s, peak -5.98 dBFS, seam -51.1 dB rel — READY
- #4 `drums/826008__looplicator__160-bpm-industrial-drum-loop-15091-wav.wav` — 44100 Hz, 32 bit, 2 ch, 12.000 s, peak 0.00 dBFS, seam -20.4 dB rel — FLAGGED peak-clips(0.00 dBFS)
- #5 `drums/86990__handfratze__odddrumloop.wav` — 44100 Hz, 16 bit, 2 ch, 6.000 s, peak 0.52 dBFS, seam -3.0 dB rel — FLAGGED peak-clips(0.52 dBFS); seam-jump(-3.0 dB rel)
- #6 `bass/611711__metalfortress__bass_loop_thex_150_f-002.wav` — 44100 Hz, 24 bit, 2 ch, 3.200 s, peak -6.30 dBFS, seam -123.7 dB rel — READY
- #7 `bass/588338__josefpres__bass-loops-028-short-loop-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 16.000 s, peak -4.55 dBFS, seam -46.9 dB rel — READY
- #8 `bass/573072__josefpres__bass-loops-009-short-loop-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 16.000 s, peak -3.29 dBFS, seam -59.8 dB rel — READY
- #9 `bass/483144__josefpres__electric-bass-guitar-loop-3-bpm-110.wav` — 44100 Hz, 16 bit, 2 ch, 8.727 s, peak -3.00 dBFS, seam -6.5 dB rel — FLAGGED seam-jump(-6.5 dB rel)
- #10 `bass/566115__stixthule__bass_loop_0055_a_120bpm.wav` — 44100 Hz, 16 bit, 2 ch, 8.000 s, peak 0.01 dBFS, seam -69.5 dB rel — FLAGGED peak-clips(0.01 dBFS)
- #11 `melodic/guitar/703347__neartheatmoshphere__tape-guitar-loop-w-melody.wav` — 96000 Hz, 24 bit, 2 ch, 41.568 s, peak -1.35 dBFS, seam -101.0 dB rel — READY
- #12 `melodic/guitar/629150__holizna__lofi-guitar-loop-em-119-bpm3.wav` — 192000 Hz, 32 bit, 2 ch, 38.319 s, peak -9.54 dBFS, seam -99.7 dB rel — READY
- #13 `melodic/guitar/575299__deadrobotmusic__emotional-pop-guitar-loop-3-normal-93bpm-e-minor.wav` — 44100 Hz, 32 bit, 2 ch, 5.161 s, peak -8.39 dBFS, seam -33.9 dB rel — READY
- #14 `melodic/guitar/789017__deadrobotmusic__sampled-plucky-guitar-loop-a-sharp-major-110bpm.wav` — 44100 Hz, 32 bit, 2 ch, 17.455 s, peak -10.68 dBFS, seam -13.9 dB rel — FLAGGED seam-jump(-13.9 dB rel)
- #15 `melodic/guitar/570839__deadrobotmusic__background-guitar-loop-156bpm-c-major.wav` — 44100 Hz, 32 bit, 2 ch, 12.308 s, peak -14.05 dBFS, seam -17.0 dB rel — READY
- #16 `melodic/guitar/874737__cat-fox_alex__electric-guitar-loop-1_150bpm.wav` — 44100 Hz, 32 bit, 2 ch, 12.883 s, peak 0.01 dBFS, seam -83.4 dB rel — FLAGGED peak-clips(0.01 dBFS)
- #17 `melodic/guitar/839387__bassimat__guitar-granular-loop-at-120bpm.wav` — 48000 Hz, 24 bit, 2 ch, 56.181 s, peak 0.00 dBFS, seam -120.0 dB rel — FLAGGED peak-clips(0.00 dBFS)
- #18 `melodic/piano/629176__holizna__lofi-vinyl-e-piano-loop-95-bpm.wav` — 44100 Hz, 24 bit, 2 ch, 40.421 s, peak -5.20 dBFS, seam -58.1 dB rel — READY
- #19 `melodic/piano/629167__holizna__lofi-e-piano-loop-95-bpm.wav` — 44100 Hz, 24 bit, 2 ch, 40.421 s, peak -4.89 dBFS, seam -74.7 dB rel — READY
- #20 `melodic/piano/832015__bassimat__ambient-piano-loop-002-dark-and-reflective-at-120-bpm.wav` — 48000 Hz, 32 bit, 2 ch, 15.999 s, peak 0.00 dBFS, seam -8.2 dB rel — FLAGGED peak-clips(0.00 dBFS); seam-jump(-8.2 dB rel)
- #21 `melodic/piano/640710__josefpres__piano-loops-024-octave-down-short-loop-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 34.000 s, peak -9.10 dBFS, seam -79.7 dB rel — READY
- #22 `melodic/piano/571390__josefpres__piano-strings-001-simple-mix-1-short-loop-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 36.000 s, peak -1.00 dBFS, seam -171.8 dB rel — READY
- #23 `melodic/strings/621179__holizna__125-bpm-string-melody.wav` — 44100 Hz, 32 bit, 2 ch, 34.560 s, peak -3.76 dBFS, seam -75.2 dB rel — READY
- #24 `melodic/strings/132910__shitefromaheight__strings-8-bar-140bpm-1.wav` — 44100 Hz, 24 bit, 2 ch, 13.714 s, peak -0.09 dBFS, seam -13.9 dB rel — FLAGGED seam-jump(-13.9 dB rel)
- #25 `melodic/strings/839571__cvltiv8r__contemplative-string-loop-violin-and-cello.wav` — 44100 Hz, 32 bit, 2 ch, 45.013 s, peak -12.73 dBFS, seam -99.8 dB rel — READY
- #26 `melodic/strings/566285__ehved__violin-strings-hiphop-loop.wav` — 44100 Hz, 32 bit, 2 ch, 41.034 s, peak -10.91 dBFS, seam -74.2 dB rel — READY
- #27 `melodic/strings/830084__bassimat__violin-and-alien-drum-loop-at-120bpm.wav` — 48000 Hz, 24 bit, 2 ch, 16.000 s, peak 0.00 dBFS, seam -18.0 dB rel — FLAGGED peak-clips(0.00 dBFS)
- #28 `melodic/synth/705427__airwavexv__supersaw-synth-loop-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 8.000 s, peak -0.17 dBFS, seam -14.3 dB rel — READY
- #29 `melodic/synth/709165__airwavexv__supersawsquare-synth-loop-1-120-bpm.wav` — 44100 Hz, 16 bit, 2 ch, 8.000 s, peak 0.11 dBFS, seam -9.2 dB rel — FLAGGED peak-clips(0.11 dBFS); seam-jump(-9.2 dB rel)
- #30 `melodic/synth/330889__edemson86__hypo-lead-150bpm.wav` — 48000 Hz, 32 bit, 2 ch, 25.621 s, peak -15.18 dBFS, seam -15.1 dB rel — READY
- #31 `melodic/synth/365189__furbyguy__square-bubble-lead.wav` — 44100 Hz, 24 bit, 2 ch, 9.600 s, peak -15.30 dBFS, seam -22.4 dB rel — READY
- #32 `melodic/synth/697732__harrisonlace__synth_loop_vertical_140_e.wav` — 44100 Hz, 32 bit, 2 ch, 13.714 s, peak -0.65 dBFS, seam -70.8 dB rel — READY
- #33 `melodic/winds/713117__dyekho__arabic-flute-01-130bpm.wav` — 44100 Hz, 16 bit, 2 ch, 14.769 s, peak -8.25 dBFS, seam -17.2 dB rel — READY
- #34 `melodic/winds/554480__johnnie_holiday__bollywood-flute.wav` — 44100 Hz, 32 bit, 2 ch, 7.505 s, peak -4.11 dBFS, seam -28.4 dB rel — READY
- #35 `melodic/winds/788186__cvltiv8r__flute-beat-by-cvltiv8r-93bpm-31.wav` — 44100 Hz, 32 bit, 2 ch, 20.645 s, peak 14.46 dBFS, seam -44.4 dB rel — FLAGGED peak-clips(14.46 dBFS)
- #36 `melodic/harp/718024__tukyoeth__95-bpm-happy-harp-loop.wav` — 48000 Hz, 24 bit, 2 ch, 10.105 s, peak -0.00 dBFS, seam -77.4 dB rel — FLAGGED peak-clips(-0.00 dBFS)
- #37 `chords/keys/570980__badoink__new-rhoads-105f.wav` — 44100 Hz, 16 bit, 2 ch, 73.174 s, peak 0.72 dBFS, seam -26.8 dB rel — FLAGGED peak-clips(0.72 dBFS)
- #38 `chords/keys/592850__systemshock79__organ-donor.wav` — 48000 Hz, 16 bit, 2 ch, 15.019 s, peak -6.17 dBFS, seam -17.8 dB rel — READY
- #39 `pads/825470__bassimat__ambient-loop-elorea-with-additive-granular-synthesis-120-bpm.wav` — 48000 Hz, 24 bit, 2 ch, 137.998 s, peak 0.00 dBFS, seam -109.5 dB rel — FLAGGED peak-clips(0.00 dBFS)
- #40 `pads/476772__andrewkn__decline-loop.wav` — 44100 Hz, 16 bit, 2 ch, 113.536 s, peak -20.89 dBFS, seam -39.9 dB rel — READY
- #41 `pads/318685__evanjones4__pinecone-ambient.wav` — 44100 Hz, 16 bit, 2 ch, 109.970 s, peak -1.32 dBFS, seam -83.6 dB rel — READY
- #42 `pads/831354__looplicator__80-bpm-industrial-ambient-loop-15477-wav.wav` — 44100 Hz, 32 bit, 2 ch, 24.000 s, peak -0.20 dBFS, seam -17.7 dB rel — READY
- #43 `pads/850754__looplicator__64-bpm-industrial-ambient-loop-16260-wav.wav` — 44100 Hz, 32 bit, 2 ch, 30.000 s, peak -0.07 dBFS, seam -32.7 dB rel — READY
- #44 `percussion/661751__harrisonlace__perc_loop_cortex_86bpm.wav` — 48000 Hz, 32 bit, 2 ch, 22.326 s, peak -0.37 dBFS, seam -16.1 dB rel — READY
- #45 `percussion/556931__dwaa__shaker_percussion_2-85bpm.wav` — 44100 Hz, 32 bit, 2 ch, 11.294 s, peak 0.54 dBFS, seam -29.2 dB rel — FLAGGED peak-clips(0.54 dBFS)
- #46 `percussion/188554__mika55__percussion-loop.wav` — 44100 Hz, 16 bit, 2 ch, 8.000 s, peak 0.03 dBFS, seam -66.3 dB rel — FLAGGED peak-clips(0.03 dBFS)
- #47 `percussion/678302__msx2plus__90.wav` — 48000 Hz, 24 bit, 2 ch, 2.666 s, peak 0.00 dBFS, seam -52.3 dB rel — FLAGGED peak-clips(0.00 dBFS)
- #48 `percussion/147273__strever953__120bpm-loop-p105.wav` — 44100 Hz, 24 bit, 2 ch, 8.000 s, peak -1.22 dBFS, seam -14.5 dB rel — READY
- #49 `other/380353__lezaarth__loop4_5_4_2bar_110_bpm.wav` — 44100 Hz, 24 bit, 2 ch, 5.455 s, peak -1.34 dBFS, seam -43.2 dB rel — READY

## Post-fix re-QA — 2026-11-22 (Wang ruling: gain-reduce, not discard)

The 18 flagged files were processed in place (originals preserved under
`originals/`): peak normalized to -1.0 dBFS; the 6 seam-flagged files also
got a 20 ms wrap crossfade, and 4 of them a full-length linear ramp that
removes the residual seam offset. Final re-QA against the same criteria:
**49 ready, 0 flagged.** Processing scripts: `fix_flagged.py`,
`fix_remaining4.py` in this directory.
