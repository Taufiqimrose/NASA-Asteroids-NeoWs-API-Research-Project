# Boundary Analysis for NASA Asteroid Repository API

This project focuses on defining and testing boundary cases for an API designed to interact with the NASA asteroid repository. The primary objective is to ensure that the API adheres to specified boundaries and accurately handles different input scenarios. Our approach includes:

## Objectives

1. **Boundary Analysis**: Identify and document boundary cases that the API should pass or fail, ensuring it functions within prescribed limits.
2. **Equivalence Partitioning**: Utilize mathematical techniques to generate equivalence partition cases based on API input parameters, focusing on start and end dates.
3. **Parameter Testing**: Test four key parameters:
   - **Personal NASA API Key**
   - **Start Date (YYYY-MM-DD)**
   - **End Date (YYYY-MM-DD)**
   - **URL, API Key, Start Date, End Date**

## Findings

- The API can handle an infinite number of valid date combinations, including variations with leading zeros.
- These variations can be expressed with the regular expression `0*(date)`.

## Goals

Our comprehensive boundary analysis aims to ensure the robustness and accuracy of the NASA asteroid repository API, documenting any inaccuracies found during testing. The project will detail the strategy for boundary analysis and provide insights into the effectiveness of different input parameters in ensuring proper API functionality.

---

Feel free to explore our repository and contribute to the project by providing feedback, reporting issues, or submitting pull requests.
