# How to Use Demucs to Shed
## Installation
### [Setup WSL - Windows](https://github.com/tissakhosla/tissa-docs/blob/main/wsl.md)
### Setup Environment - Mac
1. Open Terminal
2. `xcode-select --install`
4. Go to Software Update and Install the Command Line Tools that were requested
5. Install [HomeBrew](https://brew.sh/)
6. Remember to read the end of the output and add it to the part with those 2 commands
7. `brew install ffmpeg`

### Create Python VENV
1. `mkdir envs` I like to keep venvs all in one place
2. `python3 -m venv envs/demucs`
3. `source envs/demucs/bin/activate`
4. `python3 -m pip list -o` to see packages that need updating (probably pip)
5. `python3 -m pip install -U pip`
6. `python3 -m pip install -U demucs`
7. `mkdir demucs` (this is where the separated files will be stored`
8. `cd demucs` the directory we're in will be where things get stored
9. `demucs Path/to/file`

## Shedding with The Tracks
1. In your DAW of choice, insert the separated stems as separate tracks.
2. Solo or Mute as eneded

Use Cases and Video Demos Coming Soon...
