# SI_MiniProyecto3

[contributors-shield]: https://img.shields.io/github/contributors/basicallydanny/SI_MiniProyecto3.svg?style=for-the-badge
[contributors-url]: https://github.com/basicallydanny/SI_MiniProyecto3/graphs/contributors
[![Contributors][contributors-shield]][contributors-url]

<div align="left">
Presented by Daniela Gómez and Santiago Peña
</div>

<!-- PROJECT -->

<h3 align="center">MINI PROJECT #3</h3>
  <p align="center">
    README in regards to the project #3 for Interaction Systems 2472 - A
  </p>
  <p align="center">
    Link to final video: https://drive.google.com/drive/folders/1HmTkITeOMccG2puv3zI6kMZTPSu52pM_?usp=sharing
    
    Link en youtube: https://www.youtube.com/watch?v=5L00i8zQuhs
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#limitations">Limitations</a></li>
      </ul>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#roadmap">RoadMap</a>
      <a href="#decision-overview">Decision Overview</a>
  </ol>
</details>

## About The Project

Using OpenMusic (OM), they must develop an algorithm that generates a musical piece for a video game.

### Limitations

* OpenMusic must be used.
* Previously stored music material (wav, midi, mp3, etc.) cannot be used.
* The music piece must be consistent with the chosen video game.
* It must be at least 2 minutes long.
* It must be at least 1 minute of fresh music, that is, it must not be repeated.
* A video must be uploaded to YouTube showing gameplay of the video game with its music piece.

### Built With

* OpenMusic

## Roadmap

- [X] Choose a Videogame.
- [X] Learn the use of OP.
- [X] Brainstorm a new idea.
- [X] Develop a musical piece.
- [X] Edit videogame soundtrack with the new musical piece.
- [X] Publish

## Decision Overview

- Randomization Elements: om-random is used to generate stochastic variations. This allows for unpredictability in the musical output, creating dynamic shifts and variety.
-  Repetition Control: The use of repeat-n with different configurations (e.g., (0 300)) ensures the repeated sections of music are controlled, influencing rhythm, dynamics, or thematic consistency across repeated elements.
- Loop Structures: Loops are present in the form of ourloop, which apply iterative processing to some musical phrases.
- Grouping and Aggregation: The use of agruparseqs combines smaller musical segments into more extensive structures. These operations organize the piece into larger cohesive sections.
- Note Selection and Interpolation: Some note groups are generated through selection procedures (choosetwo), indicating a decision-making process to refine which notes get played. This suggests a controlled random element in note choices.

