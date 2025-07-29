# Software Developer Basic Test "The Musical Lake"
One day, an explorer began following some strange sounds. They soon arrived at a lake where they found the source: three small animals making sounds similar to a song. After a short while, the explorer could differentiate which animal produced each sound.

## Sounds
Frog: brr, birip, brrah, croac

Dragonfly: fiu, plop, pep

Cricket: cric-cric, trri-trri, bri-bri

After some time, the explorer discovered they were "singing" together. Whenever the frog started with "brr," the dragonfly would respond by rubbing its tail with a branch, producing a "fiu" sound. After the dragonfly, the cricket would continue with "cric-cric." However, every time the frog sounded like "brrah" or "croac," all the animals would go silent for a while and then resume. Before the sky darkened, the explorer managed to write down three "songs" they all performed together and came up with these notes:

## Songs
brr, fiu, cric-cric, brrah

pep, birip, trri-trri, croac

bri-bri, plop, cric-cric, brrah

## Exercise

Using the programming language you are most comfortable with, write a program that takes a given sound from the list of sounds each animal makes and returns the remaining sounds from any of the three songs the explorer wrote. For example:

- When given "brr", it should output "fiu, cric-cric, brrah" according to the first song.
- When given "birip", it should output "trri-trri, croac" according to the second song.
- When given "plop", it should output "cric-cric, brrah" according to the third song.
- When given "croac" or "brrah", it should output nothing, according to all songs.

## Technical Requirements

* You MUST use the **docker-compose.yml** file to run your local development environment.
* You MAY use JavaScript as your selected language.
* You MUST provide a **README** file with the instructions for setting up and running the application in the local development environment.
* Please review this hello world, for example.

## Final concerns

When delivering the code, please keep in mind the following practices:

* You MUST create a new branch named `feature/{first-name}-{last-name}-task-list`.
* You MUST assign a pull request from your new branch to the original project.
* Update this **README** to include the instructions for setting up and running the application.
* The code must be written in English.

## Installation and Execution (example)

1º Run the solution and wait for the response
```bash
  docker compose up
```
