# Music versions (-m), built Oct 27, 2026

All music is **synthesized on the box** by `build/mk.py` (numpy: sine-sweep kicks, noise snares/hats,
distorted saw bass in C minor, a stacked-sine pad, a sub boom with noise crash on each cut, and a noise riser into each cut).
No samples and no third-party audio are used. It's original work owned by Phantastic, so it's free for commercial use.
License: CC0 / public-domain dedication by the owner.

- Tempo: about 128 BPM. The tempo is adjusted per section, so every scene cut falls on a beat, and each cut restarts the bar so it lands on a downbeat with a boom hit.
- Cut times: v3 from the render.py segment starts plus the scdet hard cuts (21.43 and 5.63). v2 from the build.py xfade midpoints. v1 from build/timing/*.json.
- Ducking: the music sits 16 dB lower while VO is present (envelope detection with 80 ms smoothing). It's louder in gaps. There's a 2 s fade at the end.
- Loudness: about -13.8 LUFS integrated, true peak at or below -0.9 dBTP.
- Voice: v3 and v2 use the clean VO stems, and the old calm bed is replaced.
  v1 has no clean stem, so the new track is layered over the existing mix. The quiet calm bed is still underneath.
