# Git Push Producer Tag

A global Git post-push hook for Windows that plays a custom producer tag after a successful git push.

## Files

- post-push — Global Git hook.
- post-push.cmd — Windows command version.
- producer-tag.wav — Producer tag audio.

## Installation

Set the global Git hooks directory:

git config --global core.hooksPath "C:\Users\bafan\Git Hooks"

Copy post-push and producer-tag.wav into:

C:\Users\bafan\Git Hooks

## How It Works

After a successful:

git push

Git runs the global post-push hook and plays the producer tag locally.

The audio is played on the local computer. It is not played through GitHub.

## Requirements

- Windows
- Git
- PowerShell
- A valid PCM WAV file

Producer tag hook test.
