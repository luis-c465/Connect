# Hotel Manager

Connect 4 game for AP Computer Science AB 2022-2023 in Ivan Rico's class

## Dependencies for running

- [Java 1.8](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html) or [higher](https://adoptium.net/)

## Running

- First download the **[Latest release](https://github.com/luis-c465/Connect/releases/latest)**
- Then run in the command line _(Or just double click on the file)_
  ```bash
  java -jar [path to downloaded jar file]
  ```

## Building

### Dependencies

- **[Maven v3.8.4](https://maven.apache.org/download.cgi)**

### How to build

Run the following in the [command line](https://www.freecodecamp.org/news/how-to-use-the-cli-beginner-guide/#how-to-locate-your-cli)

```bash
mvn clean compile assembly:single
```

- Then the **Executable Jar** `connect.jar` will be in the root folder 🎉

## Project Requirements

Due: **Mon, Feb 06 2023** @1 AM

- Explains rules to player
- First, decide who goes first what color each player will have.
- Players must alternate turns.
- Only one disc can be dropped in each turn.
- On your turn, drop one of your colored discs from the top into any of the seven slots.
- The game ends when there is a 4-in-a-row (either vertically, horizontally, or diagonally) or a stalemate.
- The starter of the previous game goes second on the next game.
- Exit anytime
- Keep score of wins and losses
