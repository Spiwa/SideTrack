# SideTrack 0.1.8 Preview

## New and improved

- Choose Bar, Waveform or Color wave in Settings > Appearance. The selection applies on Save; Waveform remains the default.
- Color wave uses five artwork colors, a flat baseline and a larger circular playhead without glow. Time labels align with the baseline.
- Color-wave animation follows each track's BPM at one cycle per eight beats, varying smoothly between BPM minus 20 and BPM. Tracks without BPM use gentle fixed animation. Playback progress stays independent.
- Rate the displayed track using five stars at the artwork's bottom-right. Unrated tracks reveal stars on hover; click the current rating to clear it.
- Artist Radio now starts immediately for the displayed track and no longer depends on JRiver's selected files. Perl, MCUtils and the smartlist fields are still required.
- Automatic snapshots omit both time labels and played-progress highlighting. Manual snapshots retain them.
- Fixed overlapping progress-style controls and help text in Settings.

## Install

Download SideTrack-Setup-0.1.8-preview-x64.exe. Close the running player before upgrading; existing settings are preserved. JRiver Media Center is required separately. Python is bundled.

This is an unsigned Windows x64 preview. Local automated checks passed; testing on a separate clean computer remains outstanding. SideTrack is freeware under LICENSE.txt; third-party components retain their licenses.
