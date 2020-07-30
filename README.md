# Video Poker Hand Analysis Benchmarks
The goal of this project is to identify the fastest code for calculating the optimal discard strategy for a random video poker hand and payout table.

Please create an issue or pull request if you know of projects that I missed.


## Test System
MacBook Pro (15-inch, 2017) running macOS 10.15.5
- CPU: Intel(R) Core(TM) i7-7820HQ CPU @ 2.90GHz
- RAM: 16 GB 2133 MHz LPDDR3

Using [Hyperfine](https://github.com/sharkdp/hyperfine) for benchmarking:
`hyperfine --warmup 3`


# C++
Compiled using Xcode Version 11.6

## [VPAnalysis](https://github.com/nbhalodia/VPAnalysis) by nbhalodia
```
  Time (mean ± σ):      2.988 s ±  0.021 s    [User: 2.914 s, System: 0.063 s]
  Range (min … max):    2.959 s …  3.019 s    10 runs
```
Appears to be exhaustive search of all 32 possible holds/discards.

## [CocoaVideoPoker](https://github.com/mikemcqueen/CocoaVideoPoker) by mikemcqueen


# C#
[VideoPokerAssistant](https://github.com/kihyo9/VideoPokerAssistant) by kihyo9
Appears to use pre-generated look up table.

# Java
## [pokertraining](https://github.com/markmadej/pokertraining) by markmadej

[Video-Poker-Hand-Evaluator](https://github.com/ali3hamodi6/Video-Poker-Hand-Evaluator) by ali3hamodi6

# Javascript / Typescript
## [videopoker.js](https://github.com/richardkiss/videopoker.js) by richardkiss

## [video-poker](https://github.com/ronbout/video-poker) by ronbout

## [VideoPokerStrategySimulation](https://github.com/briandkim93/VideoPokerStrategySimulation) by briandkim93

## [video-poker-calculator](https://github.com/MoonCha/video-poker-calculator) by MoonCha

## [videopoker.academy](https://github.com/Hyprtxt/videopoker.academy) by Hyprtxt

# Python
Tested using Python 2.7
## 🏆 [video_poker_analyzer](https://github.com/BradAJ/video_poker_analyzer) by BradAJ
```
  Time (mean ± σ):     228.4 ms ±   4.7 ms    [User: 439.6 ms, System: 219.6 ms]
  Range (min … max):   220.3 ms … 234.5 ms    13 runs
```
This is fast.

## [video-poker-tutor](https://github.com/ksu-is/video-poker-tutor) by ksu-is

## [videopoker](https://github.com/kortox/videopoker) by kortox

[videopoker](https://github.com/fprefect/videopoker) by fprefect
[video-poker-hand-analyzer](https://github.com/thehomebrewnerd/video-poker-hand-analyzer) by thehomebrewnerd


# Ruby

## [VideoPoker](https://github.com/WJLiddy/VideoPoker) by WJLiddy


# Others
## [v10.wasm](https://www.vpfree2.com/play_perfect/wasm/evaluate/v10.wasm) by Play Perfect
From: https://www.vpfree2.com/video-poker/hand-evaluator/
