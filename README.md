# An exercise in data analysis, image processing, and NLP

This is a small exercise in the kinds of skills that may be required of you.  
The goal here is to evaluate how well you understand the problem, scope it, come up with a strategy to solve it, and execute it.  
More formally, we will look for the following in our evaluation:

## Expected deliverables and evaluation criteria
- Have a working prototype of the task described below.
- (We will) assess how well you scope and assess the different components involved which will solve this problem
- Assess how you divide your labor into the components you identify. Remember, there's a time budget of ~2 days.
- Assess how you wiggle out of situations when you're stuck.
- Assess how well you communicate and let all stakeholders know of your progress.

## Task 1
- You have been provided a PDF in `./data/electoral_rolls.pdf`. This is a collection of electoral rolls from a ward in the city of Bengaluru, Karnataka, India. The rolls has a list of all the registered voters in the ward, presented in the form of roll cards (page 3 onwards in the document) for each citizen. 

- Each roll card contains seven pieces of information: Name, Father's name, House number, Age, Gender, Serial number (top left), Voter roll ID (top right)

- Your task is to extract details from each voter card present in the PDF.

- The final deliverable from this exercise should be:
    - A CSV or XLSX file containing the list of all the voters, one in each row.
    - In each row, the seven fields need to be populated with the information from the roll card.
    - If there's a descrepancy or confusion in parsing the information, leave it blank.


## Task 2
- Have at least one plot, or one table which summarizes relevant statistics from the dataset. To begin with, for the task mentioned above, ask yourself what statistics you think are even relevant and would want answered?

- Evaluation -- How will you evalute whether your algorithm/strategy covers all cases? It could well be we're unsure of this no matter what we do.

## Instructions
- Do not fork this repo. Work on a local copy. Make it a habit to push changes upstream to your repo as frequently as feasible.
- Use `Python3.8+` for this work.
- We workship the lords of reproducability of results. Use `conda` to create an environment and set up your repository. 
- Use a `.gitignore` file to ensure you are not adding junk files to the repo.
- Have a `./src/` folder containing the source.
- Have a `./env/` folder containing the Conda environment file you create for this project.
- Have a `./data/` folder containing all the data your source accesses.
- Have a `./tests/` folder to write out unit tests for key functions. Look up the `unittest` package in Python if you haven't used it before.
- Keep updating this README with instructions which will help with the reproducability of your work/results. The topomst section of your readme file should be `Approach`, where you will concisely describe the overeall approach you have considered to solve this problem. Describe there the general strategy you have used, the key tools you have considered, and the different metrics you have considered, and any other detail relevant to the evaluation criteria mentioned above.

Setting these up can be a little painful and time consuming. Push through it. Focus on getting the core functionality right first, though.


