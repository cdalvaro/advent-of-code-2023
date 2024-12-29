<a href="https://www.ruby-lang.org"><img src="https://s3.cdalvaro.io/github.com/cdalvaro/advent-of-code/RubyLang.png" alt="Ruby" width="64px" align="right"/></a>

# Advent of Code

This repo contains my solutions to the [Advent of Code](https://adventofcode.com) challenges, written in
the [Ruby](https://www.ruby-lang.org) programming language.

The project is structured as follows:

- A script [`bin/create-files.rb`](bin/create-files.rb) to create the basic files for a new puzzle.
- A library, located in the [`lib/`](lib) directory, containing the code for the solutions.
- A set of tests, located in the [`test/`](test) directory, containing the tests for the solutions.
- The [`sig`](sig) directory, which contains the signatures of the project.

## Create Files

When starting a new puzzle, you can use the script [`bin/create-files.rb`](bin/create-files.rb) to create the basic files for the puzzle.

```bash
bin/create-files.rb --day 25 [--year=2024] [--force]
```

## Run Tests

Tests are written using the [minitest](https://github.com/minitest/minitest) framework.

To run the tests, simply run the following command:

```bash
bundle install
bundle exec rake test
```

Some tests are marked as slow, and they are skipped by default. To run them, you can set the environment variable `RUN_SLOW_TESTS` to `1`.

## Solved Puzzles

<a href="https://www.ruby-lang.org"><img src="https://s3.cdalvaro.io/github.com/cdalvaro/advent-of-code/Holly.png" width="230px" align="right"/></a>

<details open>
  <summary><b>Advent of Code - <a href="https://adventofcode.com/2024">2024</a></b></summary>
  <p>
  <table>
    <tr>
      <th>Day</th>
      <th>Solution</th>
      <th>Rank</th>
    </tr>
    <tr>
      <td>1️⃣ <a href="https://adventofcode.com/2024/day/1">Historian Hysteria</a></td>
      <td><a href="lib/puzzles/2024/day01"><code>lib/puzzles/2024/day01</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>2️⃣ <a href="https://adventofcode.com/2024/day/2">Red-Nosed Reports</a></td>
      <td><a href="lib/puzzles/2024/day02"><code>lib/puzzles/2024/day02</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>3️⃣ <a href="https://adventofcode.com/2024/day/3">Mull It Over</a></td>
      <td><a href="lib/puzzles/2024/day03"><code>lib/puzzles/2024/day03</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>4️⃣ <a href="https://adventofcode.com/2024/day/4">Ceres Search</a></td>
      <td><a href="lib/puzzles/2024/day04"><code>lib/puzzles/2024/day04</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>5️⃣ <a href="https://adventofcode.com/2024/day/5">Print Queue</a></td>
      <td><a href="lib/puzzles/2024/day05"><code>lib/puzzles/2024/day05</code></a></td>
      <td>🌟🌟</td>
    </tr>
  </table>
</details>

<details>
  <summary><b>Advent of Code - <a href="https://adventofcode.com/2023">2023</a></b></summary>
  <p>
  <table>
    <tr>
      <th>Day</th>
      <th>Solution</th>
      <th>Rank</th>
    </tr>
    <tr>
      <td>1️⃣ <a href="https://adventofcode.com/2023/day/1">Trebuchet?!</a></td>
      <td><a href="lib/puzzles/2023/day01"><code>lib/puzzles/2023/day01</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>2️⃣ <a href="https://adventofcode.com/2023/day/2">Cube Conundrum</a></td>
      <td><a href="lib/puzzles/2023/day02"><code>lib/puzzles/2023/day02</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>3️⃣ <a href="https://adventofcode.com/2023/day/3">Gear Ratios</a></td>
      <td><a href="lib/puzzles/2023/day03"><code>lib/puzzles/2023/day03</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>4️⃣ <a href="https://adventofcode.com/2023/day/4">Scratchcards</a></td>
      <td><a href="lib/puzzles/2023/day04"><code>lib/puzzles/2023/day04</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>5️⃣ <a href="https://adventofcode.com/2023/day/5">If You Give A Seed A Fertilizer</a></td>
      <td><a href="lib/puzzles/2023/day05"><code>lib/puzzles/2023/day05</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>6️⃣ <a href="https://adventofcode.com/2023/day/6">Wait For It</a></td>
      <td><a href="lib/puzzles/2023/day06"><code>lib/puzzles/2023/day06</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>7️⃣ <a href="https://adventofcode.com/2023/day/7">Camel Cards</a></td>
      <td><a href="lib/puzzles/2023/day07"><code>lib/puzzles/2023/day07</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>8️⃣ <a href="https://adventofcode.com/2023/day/8">Haunted Wasteland</a></td>
      <td><a href="lib/puzzles/2023/day08"><code>lib/puzzles/2023/day08</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>9️⃣ <a href="https://adventofcode.com/2023/day/9">Mirage Maintenance</a></td>
      <td><a href="lib/puzzles/2023/day09"><code>lib/puzzles/2023/day09</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>1️⃣0️⃣ <a href="https://adventofcode.com/2023/day/10">The Great Escape</a></td>
      <td><a href="lib/puzzles/2023/day10"><code>lib/puzzles/2023/day10</code></a></td>
      <td>🌟🌟</td>
    </tr>
    <tr>
      <td>1️⃣1️⃣ <a href="https://adventofcode.com/2023/day/11">Cosmic Expansion</a></td>
      <td><a href="lib/puzzles/2023/day11"><code>lib/puzzles/2023/day11</code></a></td>
      <td>🌟🌟</td>
    </tr>
  </table>
</details>
