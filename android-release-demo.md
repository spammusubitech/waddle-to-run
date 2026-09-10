---
layout: android
title: Android workout service demonstrations
permalink: /android/release-demo/
---
# Android workout service demonstrations

Waddle: Beginner Running Coach — package `com.spammusubi.gooserunning`.

These recordings demonstrate the actual Android app in a Google Play Android 15 test environment. The sessions use a synthetic test profile. Outdoor GPS is simulated; these recordings do not represent physical outdoor accuracy or battery testing.

## Outdoor workout tracking

This outdoor video joins the start/background recording and a short completion-screen recording of the same test session. The runner starts a workout, grants location access, and starts outdoor tracking. The ongoing workout continues while the app is in the background, with visible notification controls. Finishing ends tracking.

<video controls preload="metadata" playsinline style="width:100%;max-width:420px" src="{{ '/assets/android-release/waddle-fgs-outdoor-v7.mp4' | relative_url }}"></video>

## Indoor interval coaching

This indoor video joins two recordings of the same ongoing test session; elapsed time includes a recording gap. The runner selects indoor/timer mode and starts a workout without location. The foreground service maintains interval timing and coaching while the app is in the background. The runner can pause and finish through the visible controls.

<video controls preload="metadata" playsinline style="width:100%;max-width:420px" src="{{ '/assets/android-release/waddle-fgs-indoor-v7.mp4' | relative_url }}"></video>
