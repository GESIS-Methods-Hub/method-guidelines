# Method Title
The title should be meaningful and easy to follow. It should reflect relevance to social science research. 

## Description
- Provide a brief and exact description of the method clearly mentioning its purpose i.e., what it does in non-technical terms. The focus should be to emphasize on the functionality and get non-technical users interested as well as in a position to understand what the method is doing. Write a sentence about the input and output format of the data and DBD datasets that the method can work with. Writing about noteworthy features of the method. It can be structured as:
- 1 or 2 sentences on highlighting the functionality of the method to get non-technical users interested in the method
- A sentence about the input and output format of the method
- A sentence on the noteworthy functionality of the method
- A sentence about the demo example with sample input and output used with the method
- A sentence mentioning (and adding links to) relevant resources that the method uses or works with. The social science papers using the method or similar methods can also be cited to highlight its importance.

For example,
An easy-to-use method for continuously collecting data from the 4Chan social media platform. It collects all textual data (in JSON format) along with its metadata from all 4Chan discussion boards (live and archived ones), possibly updating every sec (recommended 10 sec).  The platform is popular as incubator for memes, viral content and political activism, and is known to have explicit, hateful and racist content across diverse topics. Users are mostly anonymous and threads comparably shortlived and focused on trending/recent issues. 

## Keywords
Few keywords placed after description highlighting the nature of the method 

## Science Usecase(s)
- Include one or more usecases from social sciences that would make this method applicable in a social science research scneario.
 
For example,
- A social scientist wants to collect 4Chan data on political discourse from dates 10.01.2024 to 10.06.2024.
- A social scientist interested in collecting 4Chan data to analyze toxicity and rasism on topics of interest.
 

## Repo Structure
- Explain the overall structure of the method, including directories, key files, and their functions.
For example,
The tool's architecture includes a src/ directory for core scripts, with requester.py handling data collection, board.py managing board-specific requests, and utils.py for auxiliary functions. Data is stored in a data/ directory created upon initiation, and documentation is available in docs/.


## Environment Setup
- Setting up the envornment to run this method locally
- Installing all the packages and libraries with specific versions required to run this method
For example, 
Requires Python 3.10.2 or 3.11.4. Suitable for environments focused on data collection and analysis.
Dependencies are listed in requirements.txt and can be installed via pip install -r requirements.txt to ensure the tool functions correctly.


## Hardware Requirements (Optional)
- The hardware requirements may be needed in specific cases when a method is known to require more memory/compute power. 
- The method need to be executed on a specific architecture (GPUs, Hadoop cluster etc.)
- *Remove this section if it doesn't apply to your method otherwise remove the (optional) from the title* 


## Input Data 
- The input data has to be a Digital Behavioral Data (DBD) Dataset
- You can provide link to a public DBD dataset. GESIS DBD datasets (https://www.gesis.org/en/institute/digital-behavioral-data)


## Sample Input and Output Data
- Show how the input data looks like through few sample instances
- Providing a sample output on the sample input to help cross check
- *The sample input and output should be meaningful values to demonstrate the use of the method on a smaller scale*


## How to Use
- Providing HowTos on the method for different types of usages
- Describe how the method should be used, including installation, configuration, and any specific instructions for users.
- *Following these steps should be sufficient to execute the method for sample input. Any one with non-technical background should be able to follow these steps.*

## Contact Details
- Provide contact information, such as your email or other means for users or contributors to reach out with questions or feedback.

## Publication (Optional)
- Include information on publications or articles related to the method.
- *Remove this section if it doesn't apply to your method otherwise remove the (optional) from the title* 

## Acknowledgements (if any)
- Acknowledgements if any
- *Remove this section if it doesn't apply to your method otherwise remove the (optional) from the title* 

## Disclaimer (Optional)
- Add any disclaimers, legal notices, or usage restrictions for the method, if necessary.
- *Remove this section if it doesn't apply to your method otherwise remove the (optional) from the title* 

