# Pomodoro Timer
A Pomodoro timer web application with customizable work/break cycles and progress tracking.
**[View Project](https://augus-dev.github.io/pomodoro-app/)**

## Features
- Adjustable focus, break, and long break durations
- Work/break cycle counter
- Configuration panel
- Cycle counter and long break indicator
- Auto-advance between timers

## Components:
- Timer display with mode indicators
- Control buttons (start, pause, reset)
- Settings panel with dropdowns
- Progress tracking

## Customization
- Focus Time: 15-60 minutes
- Break Time: 5-15 minutes
- Long Break: 10-30 minutes
- Cycle Count: 2-5 cycles

## Tech Stack
- HTML5, CSS3, JavaScript
- Google Fonts
- GitHub Pages

## Project Structure
pomodoro-app/
|--index.html
|-- style.css
|-- script.js
|-- images/
|-- README.md

# Bugs to Fix

## Current Issues

### 1. Missing Alarm Sound
- No audio notification when timer completes
- Need to implement browser audio API

### 2. Infinite Loop After Long Break  
- Timer continues cycling indefinitely after long break
- Requires cycle completion logic and auto-stop option

### 3. Static Image Display
- Work/break mode image doesn't change with timer state
- Need dynamic image switching based on current mode

## Priority Fixes

### High Priority:
- Add alarm sound on cycle completion
- Fix long break cycle reset logic  
- Implement dynamic image switching

### Medium Priority:
- Add auto-stop after completed cycles option
- Improve notification system
