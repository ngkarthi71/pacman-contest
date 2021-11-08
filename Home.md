# RMIT COSC1125/1127 AI Pacman Contest Project

## Table of contents

1. [Home and Introduction]()
2. [Design Choices (Offense/Defense)](Design-Choices)

    2.1 [Heuristics Algorithm](AI-Method-1)

    2.2 [Monte Carlo Search Algorithm](AI-Method-2)

    2.3 [Approximate Q-Learing Algorithm](AI-Method-3)
3. [Evolution and Experiments](Evolution)
4. [Conclusions and Reflections](Conclusions-and-Reflections)


# Home and Introduction

## Algorithms used

* ### Offense Agent - Heuristics Approach
* ### Defense Agent - Monte Carlo Search Algorithm
* ### Also implemented Approximate Q-Learning agent for Offense

## Team Members

* Varsha Chandrasekhar Bendre - s3831858@student.rmit.edu.au - 3831858
* PrabhatKumar Singh - s3833321@student.rmit.edu.au 3833321
* Karthi Narendrababu Geetha - s3835901@student.rmit.edu.au - 3835901

## How to run



## Help Section

```
Options:
  -h, --help            show this help message and exit
  -r RED, --red=RED     Red team [Default: baselineTeam]
  -b BLUE, --blue=BLUE  Blue team [Default: baselineTeam]
  --red-name=RED_NAME   Red team name [Default: Red]
  --blue-name=BLUE_NAME
                        Blue team name [Default: Blue]
  --redOpts=REDOPTS     Options for red team (e.g. first=keys) [Default: ]
  --blueOpts=BLUEOPTS   Options for blue team (e.g. first=keys) [Default: ]
  --keys0               Make agent 0 (first red player) a keyboard agent
  --keys1               Make agent 1 (second red player) a keyboard agent
  --keys2               Make agent 2 (first blue player) a keyboard agent
  --keys3               Make agent 3 (second blue player) a keyboard agent
  -l LAYOUT_FILE, --layout=LAYOUT_FILE
                        the LAYOUT_FILE from which to load the map layout; use
                        RANDOM for a random maze; use RANDOM<seed> to use a
                        specified random seed, e.g., RANDOM23 [Default:
                        defaultCapture]
  -t, --textgraphics    Display output as text only
  -q, --quiet           Display minimal output and no graphics
  -Q, --super-quiet     Same as -q but agent output is also suppressed
  -z ZOOM, --zoom=ZOOM  Zoom in the graphics [Default: 1]
  -i TIME, --time=TIME  TIME limit of a game in moves [Default: 1200]
  -n NUMGAMES, --numGames=NUMGAMES
                        Number of games to play [Default: 1]
  -f, --fixRandomSeed   Fixes the random seed to always play the same game
  --record              Writes game histories to a file (named by the time
                        they were played)
  --recordLog           Writes game log  to a file (named by the time they
                        were played)
  --replay=REPLAY       Replays a recorded game file.
  --replayq=REPLAYQ     Replays a recorded game file without display to
                        generate result log.
  --delay-step=DELAY_STEP
                        Delay step in a play or replay. [Default: 0.03]
  -x NUMTRAINING, --numTraining=NUMTRAINING
                        How many episodes are training (suppresses output)
                        [Default: 0]
  -c, --catchExceptions
                        Catch exceptions and enforce time limits

```