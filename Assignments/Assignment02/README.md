# CSA09 Assignment 2 – Java Programs

This repository contains separate Java solutions for Q1–Q7. Each task has its own folder and can be compiled independently.

## Before submission
- Replace the name/register number placeholders in this file.
- Run every program yourself using the Java version required by your course.
- Save your actual console output/screenshots in the matching `outputs/` folder.
- The benchmark numbers are generated on your computer; do not copy sample timings from another machine.
- Commit each task separately to GitHub as required by the assignment.

## Student details
- Name: YOUR NAME
- Register number: YOUR REGISTER NUMBER
- Java version: `java -version`
- GitHub repository: `CSA09-YOUR_REGISTER_NUMBER-Assignment2`

## Compile and run
Open a terminal in the task folder. For example:

```bash
javac *.java
java Q1StringBenchmark
```

Run the corresponding public class shown below:

| Folder | Compile | Run |
|---|---|---|
| Task01 | `javac *.java` | `java Q1StringBenchmark` |
| Task02 | `javac *.java` | `java Q2ListBenchmark` |
| Task03 | `javac *.java` | `java Attendance` |
| Task04 | `javac *.java` | `java Q4MapBenchmark` |
| Task05 | `javac *.java` | `java LeaderboardDemo` |
| Task06 | `javac *.java` | `java Triage` |
| Task07 | `javac *.java` | `java Q7StringRedesign` |

## Task result notes
- Q1: Compares String concatenation, StringBuilder and StringBuffer under three workloads. Reports repeated-run timing and approximate heap measurements.
- Q2: Compares ArrayList and LinkedList operations at three sizes; also demonstrates ArrayDeque for a double-ended queue.
- Q3: Demonstrates the equals/hashCode issue, a mutable-key hazard, and the corrected Student implementation.
- Q4: Compares HashMap, TreeMap and LinkedHashMap for lookups and report ordering.
- Q5: Implements a generic leaderboard using a reusable Comparator.
- Q6: Implements stable emergency triage with PriorityQueue and arrival sequence numbers.
- Q7: Measures the original repeated-concatenation design against a StringBuilder redesign using the same workload.

## Important evidence note
Timing and heap readings depend on the JVM, hardware, operating system and background load. Run each program multiple times and use your own results in the report. Heap deltas are approximate and are not a count of exact allocated objects. The source code includes comments explaining the measurements and algorithmic complexity.
