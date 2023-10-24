# An exercise in data analysis, image processing, and NLP

This is a small exercise in the kinds of skills that may be required of you.  
The goal here is to evaluate how well you understand the problem, scope it, come up with a strategy to solve it, and execute it.  
More formally, we will look for the following in our evaluation:

## Expected deliverables and evaluation criteria
- Have a working prototype of the task described below.
- (We will) assess how well you scope and assess the different components involved which will solve this problem
- Assess how you divide your labor into the components you identify, and how quickly you're able to prototype and finish implementing those components. Remember, there's a time budget of a few days.
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

- Suggest some quick ways to ensure that the data you have extracted is correct. Describe what you find from your analysis.

## Task 2
- We would like to determine if the gender classification in the gathered data from the poll cards is indeed correct. Suggest a way to evaluate this.   
Hint: can you use an LLM to help solve this task?

## Task 3
- Use an image generation model to generate the images of voter cards of any five people from the curated dataset of voters.  
The voter card should contain all the seven fields present in a poll card.  
Be creative with the aesthetic of the generated images of the voter cards.  
The card should not contain faces of the people; just the text.

## Instructions to submit your work
- Do not fork this repo. Work on a local copy. Make it a habit to push changes upstream to your repo as frequently as feasible.
- Use `Python3.8+` for this work.
- We greatly value reproducability of results. Use `conda` to create an environment and set up your repository. 
- Use a `.gitignore` file to ensure you are not adding junk files to the repo.
- Have a `./src/` folder containing the source.
- Have a `./env/` folder containing the Conda environment file you create for this project.
- Have a `./data/` folder containing all the data your source accesses.
- Have a `./tests/` folder to write out unit tests for key functions. Look up the `unittest` package in Python if you haven't used it before. Also, not every function you write needs to be tested---exercise your judgement and prioritize which function you want tested.
- Keep updating this README with instructions which will help with the reproducability of your work/results.  
- The topmost section of your readme file should be titled `Approach`. In this section, concisely describe the overeall approach you considered to solve this problem. Describe the general strategy you used, the key tools you considered, the different metrics you considered to evaluate your work, and any other detail relevant to the task goals and the evaluation criteria mentioned above.

Focus on getting the core functionality right first, and have a working prototype of your solution.

On completing the task, share with us the URL to your repo local to your account.
