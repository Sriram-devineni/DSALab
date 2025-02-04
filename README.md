## Project Description

This repo is mainly created to help each other in contributing test cases for DSA Lab and **Evaluating the assignment simliar to lab but with slightly more benefits .**
We welcome everyone to contribute to this repo . Anyone having potential edge case or find any bug or typo in this repo can keep a PR . We will be happy to merge it .

### How to contribute

- Fork the repository.
- Set up locally make your changes.
- And push your changes to your forked repository.
- Create a pull request to the main repository from Git Hub.

### Examples of Contributions

- Adding new test cases.
- Fix bugs in the old test cases.
- Opening an issues.
- Solving specific issues.
- Enhancing documentation.

### Automated Script evaluation similar to lab.

- Similar to lab you can only run script in the Linux environment.
- Only Prerequisite is to have Node installed on your machine.[Please refer documentation](https://nodejs.org/en/docs).

### Benefits of this Script.

- When your test cases gets failed there will be a directory created with WrongOutputs in the same directory as the script file which contains the failed testcase data which itself contains input to that specific test case and output which your code generated and the expected output and link to the explanation of the failed testcase.

- On successful run of your testcase you can see the total time taken to run that specific test case and memory it took in bytes.

- There will be an ScriptReport file . Which provides total report of the script.

- To avoid confusion , We implimented this script in a way that it will only run the script which is in the same directory as the script similar to lab.

- For example if you want to run script for Cycle1PartA then download the zip folder of git repository .Head to Scripts directory which contains the specific script for Cycle1PartA and test cases for each question .
- Keep your CFilesFolder in the Script directory.

### To run the script file just type the following command in the terminal.(for Q1 similarly for other questions same as lab).

```bash
node evaluate.js q1
```

### Things to notice.

- Beaware of infinte loops that can crash your system. We are not responsible for that.If that happens immediately restart the system or use htop command to know the status of your processors and can kill the instruction running on your processors.

- Running of all script files doesn't mean that your code is correct. It just means that your code is passing all the test cases which we included in the script file.

### Motivation behind this repository.

- "Lift others, lift yourself – that's the way we learn and grow."
