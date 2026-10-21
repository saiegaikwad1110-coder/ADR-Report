# ADR-Report
# SLE-4: Linear Search and Binary Search

## Project Overview
This project compares Linear Search and Binary Search using Python. It focuses on time complexity and execution-time profiling for best, average, and worst cases.

## Objectives
- Implement Linear Search and Binary Search.
- Understand time complexity.
- Compare execution time.
- Analyze algorithm performance using profiling.
- Prepare an Architecture Decision Record (ADR).
- Create C4 architecture diagrams.

## Algorithms

### 1. Linear Search
Linear Search checks each element one by one until the target is found or the list ends.

- Works on sorted and unsorted lists.
- Simple to implement.
- Time Complexity: O(1) best case, O(n) average and worst cases.

### 2. Binary Search
Binary Search repeatedly divides a sorted list into two halves to find the target.

- Requires sorted data.
- Efficient for large lists.
- Time Complexity: O(1) best case, O(log n) average and worst cases.

## Time Complexity Comparison

| Case | Linear Search | Binary Search |
|---|---|---|
| Best Case | O(1) | O(1) |
| Average Case | O(n) | O(log n) |
| Worst Case | O(n) | O(log n) |

## Execution-Time Profiling
Both algorithms are implemented in Python and their execution times are measured to compare practical performance.

Profiling helps understand the effect of input size and target position on execution time.

## C4 Architecture
The project uses four levels of C4 architecture diagrams:

- **Level 1:** System Context
- **Level 2:** Containers
- **Level 3:** Components
- **Level 4:** Code

## Tools and Technologies
- Python
- Git and GitHub
- Execution-time profiling
- PlantUML
- C4 Model
- ChatGPT for AI assistance

## Architecture Decision Record (ADR)
The decision was to implement and compare both searching algorithms using Python.

Both algorithms were selected to understand their theoretical time complexity and practical execution time.

**Advantages:**
- Helps compare algorithm efficiency.
- Provides practical performance measurements.
- Improves understanding of software architecture.

**Limitations:**
- Binary Search requires sorted input.
- Linear Search may take longer for large lists.
- Execution time may vary depending on system conditions.

## Learning Outcomes
- Learned Linear Search and Binary Search.
- Understood best, average, and worst-case complexity.
- Learned execution-time profiling.
- Understood ADRs and C4 architecture diagrams.
- Gained experience documenting projects on GitHub.

## AI Contribution
ChatGPT helped explain algorithms, time complexity, and ADR preparation. The implementation, profiling, analysis, and architecture diagrams were completed with AI assistance.

## Student Details
- **Name:** Saie Suresh Gaikwad
- **PRN:** 25UAM053
- **Division:** A
- **Course:** 02AML204 – Introduction to Artificial Intelligence

## GitHub Repository
[Linear and Binary Search](https://github.com/saiegaikwad1110-coder/Linear-and-Binary-.git)
