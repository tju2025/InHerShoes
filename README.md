# InHerShoes
A continuation of a hackathon project by myself (tju2025), zamji96, and 616michelle

## What is it?

**In Her Shoes**
InHerShoes is an interactive empathy simulation that places players in everyday situations women often navigate, from public spaces to workplaces. Through branching choices, internal thoughts, and a visible mental-load system, players experience the layered calculations behind decisions that may look simple from the outside.

## Core Features

### 1. Scenario Engine
- Interactive narrative scenarios
- Branching decision paths
- JSON-based story structure

### 2. Interactive Decision System
- Player chooses responses
- Multiple narrative paths
- Every decision shapes the scenario

### 3. Stress Meter
- Visual meter representing the characters stress level
- Players choices affects the level
- Represents the mental and emotional load women face in such scenarios

### 4. AI Internal Dialgoue Generation
- AI generates internal thoughts and dialogues for scenarios
- Creates more dynamic and immersive storytelling
- Makes the playthrough feel less scripted

### 5. Reflection & Insight
- A reflect message is shown at the end of each scenario
- Encourages the user to refect and take another perspective on a situation they may not normally encounter
- Links gameplay to real-life experiences like a reminder to the user that these are actual scenarios many women face

### 6. Multiple Scenario Library
- Simulation has multiple scenarios
- It covers a wide range of locations such as public spaces, the workplace etc
- Each scenario has several decision points

## Aspirations
### Map
I would like to implement an interactive map which you can click around on to take you to different places with sliders for light level and popularity.

### Coloured text
I would like the text to be coloured appropriately

### Mulitple Characters
Mulitple characters to interact with

### Branching Paths
Much more branches and scenarios

# Stress Meter -> Mental Load

Stress: immediate emotional pressure
Safety Risk: perceived danger
Social Cost: fear of being judged, dismissed, labelled rude, overreacting, etc.

# Design the map as a scenario selector

## Map nodes:
- street
- bus stop
- office
- bar
- gym
- shop
- train station
- park

## Sliders: 
-# (modify scenario variants)
- light level
- crowdedness/popularity
- time of day
- familiarity with area

## E.G.
bus stop + low light + low popularity = isolated harassment scenario
office + high popularity = subtle sexism/microaggression scenario
gym + medium popularity = unwanted attention scenario



# Colour
- narration: neutral
- spoken dialogue: one accent colour
- internal thoughts: italic + softer contrasting colour
- stress/safety cues: warning tones
- reflection: distinct calm tone



# Others
- protagonist variations
- bystanders
- friends
- coworkers
- authority figures
- strangers

## Factors
- age
- race/ethnicity
- student/professional context
- familiarity with location
- confidence level



# Branches
short-term consequence branches
long-term memory flags

recurring patterns



# Tech Stack
## Frontend
- React or Next.js
- Tailwind for styling
- Framer Motion for transitions
- Zustand or Redux for game state

## Backend
- Node/Express or Next.js API routes
- AI generation endpoint
- scenario storage in JSON or database

## Data Model
- scenarios
- choices
- character_profiles
- state_flags
- reflections

## Runtime States
- current location
- current scene
- stress
- safety risk
- social cost
- previous choices
- character profile
- triggered flags


# Elevation
- A few touches could really elevate it:
- subtle pulse/shake when stress rises
- delayed appearance of internal thoughts after a choice
- soundscape per location
- visible “what are you optimizing for?” tension in choices
- post-scenario comparison like: “You chose safety over politeness”, “This reduced risk but increased social discomfort”


# Points
- being careful not to seem rude
- deciding whether to report something
- calculating whether a comment was intentional
- changing behaviour to avoid being blamed
- weighing discomfort against professional or social consequences
