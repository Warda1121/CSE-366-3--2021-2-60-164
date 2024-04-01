# Assignment2: Robot Task Optimization Using Genetic Algorithm
The goal of this assignment is to develop and implement a Genetic Algorithm (GA) to optimize the
assignment of multiple robots to a set of tasks in a dynamic production environment. Your primary
objectives are to minimize the total production time, ensure a balanced workload across robots, and
prioritize critical tasks effectively. Additionally, you will create a detailed visualization to illustrate the final
task assignments, robot efficiencies, and task priorities.

**File**
[RobotTaskOptimization.ipynb](RobotTaskOptimization.ipynb)

**Report**

Approach:

Data Preparation: Mock data for tasks and robots was generated using random values within specified ranges for task durations, task priorities, and robot efficiencies.
Genetic Algorithm Implementation: The GA was implemented to optimize task assignments considering task duration, robot efficiency, and task priority. This involved initialization, evaluation (fitness function), selection, crossover, and mutation operations.
Visualization: A grid visualization was created to represent the task assignments, highlighting key information such as task durations, priorities, and robot efficiencies.

Changes Made in the Initial Code:

Improved Data Generation: The mock data generation function (generate_mock_data) was modified to accept parameters for the number of tasks and robots, allowing for greater flexibility in generating data for different scenarios.

Refined GA Placeholder: The placeholder function for the Genetic Algorithm (run_genetic_algorithm) was updated to include comments indicating where the initialization, evaluation (fitness function), selection, crossover, and mutation operations should be implemented. This provides clearer guidance for students implementing their solution.

Enhanced Visualization: The visualization function (visualize_assignments_improved) was improved to create a grid visualization of task assignments, highlighting key information such as task durations, priorities, and robot efficiencies. The function was also modified to include annotations for task priorities and durations in each cell, as well as a legend for task priorities. Additionally, a summary statistics section was added below the plot to provide insights into the task and robot characteristics.

