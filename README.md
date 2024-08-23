# Dataset Name

## Data Format
Plase process your data by transforming it into dataframe and save it as csv. We cut each text paragraph into pieces and store in each cell.

Our template dataset is:

[The Gutenburg dataset](https://huggingface.co/datasets/SouthernCrossAI/Project_Gutenberg_Australia)

## (Optional) Announcement

- Acknowledge people if there are any **usage limitations** or **law regulations** about the dataset.

  For example, if some datasets are not allowed to be used for commercial purposes 🙅‍♀️, or not even allowed to be downloaded by the public 🙅‍♂️, please note it here and provide URLs to their limitations or regulations if possible.

- If your dataset requires an **application**, **request**, or **permission** 🤲 from its data owner, please note it here. Meanwhile, please mention such information in the later **Data Source/Credit** section.

  For example, if you need to register an account, fill in an application form on its website, or send emails to the data owner, please record any necessary information 📝.

- If you are not confident about its usage, we suggest setting your repo to **private** and discussing such issues with our organiser Mattew via Matthew.Altenburg@anu.edu.au.

## Overview of the Dataset

Provide a **brief introduction** about the dataset. Any other people who know nothing about this repo should learn the **most basic information** and decide whether the dataset is what they are looking for 🧐.

You are expected to inform people the following information:

- The **time span** or **geopolitical information** of the dataset 🌏

  E.g., the dataset covers teenager vaping information in ACT from 2010 to 2020.

- The **background** of the dataset 📋

  E.g., the dataset is established by the ACT Government for the research of public health in Australia.

- The **data owner** if the dataset is not original 👩‍💼

  You should inform the essential information of the dataset owner and provide URLs to its publish page, GitHub repo, or personal website whenever possible.

## Data Source/Credit

- Where does this dataset come from?
  - Provide information on the website and data owner 👨‍💼.
- What license is the dataset under?
  - If it is not allowed for commercial use, modification, publication, or any other limitations 👩‍⚖️, please acknowledge regarding information in the announcement.

## Dataset Structure

After people read your **Overview of the Dataset**, it's time to let them know what the dataset looks like. In this section, you are suggested to provide a **bird's-eye view** 🦉or an **X-ray scan** 👩‍⚕️ of your dataset to help people understand the structure of the dataset.

For example,

- If the dataset is split into several **topics/categories**:

  - What does each topic/category mean?
  - Which file is corresponding to which topic/category?
  - How many files/data/rows/pictures/etc. is included?

- If the dataset has multiple **data formats**:

  - How many formats does the dataset have in total?
  - What are the different formats and what are they used for?

  - What is the size of the total files for each format?

- If the dataset has deep **paths/directories**:

  - Why is the dataset organised in this way?
  - Which part is responded to which data?
  
  - You can show a tree structure of your dataset by using [`tree`](https://www.geeksforgeeks.org/tree-command-unixlinux/) command. 

You don't need to necessarily follow the same idea, find the best way to treat your dataset 🙇‍♂️.

## Access to the Dataset

Remember the frustration when you first time used GitHub? Kindly remind you that not all GitHub users are tech-savvy 🤓, and your guidance here could enlighten a person's passion ❤️‍🔥 for programming. 

Please patiently entail each step as if you are teaching a 6-year-old elementary schooler 👶 (no offence to any 6-year-old elementary schooler), or the old yourself when you struggled with GitHub decades ago 🙆‍♀️. 

You've come a long way, you know how people will appreciate your work 💙.

- If your dataset can be downloaded from a **publish page** 🌐:

  Provide URLs to the original publish page and let users decide whether they want to use your code.

- Otherwise, if your dataset is collected by using **data-scraping** or **data-crawling** scripts 👩‍💻:

  Please provide a detailed tutorial to navigate people from **installing environments or dependencies**, and **running your code**, to **storing and post-processing the raw dataset** on their local machine. 

  For example, you are suggested to include

  - How to use `requirement.txt` to create and install a Python environment in `conda`?
  - How to use `python3 script_name.py` to run your Python code?
  - How to use `curl -o [dataset_name] [dataset_url]` to download from a link?
  - How to use `source script_name.sh` to run your Bash script?
  - How to follow your `notebook_name.ipynb` to walk through each step?

- If people want to **clone** your repo, how to set up Git/GitHub and use `git clone` command 🧑‍💻?

## License of the Repo

E.g., This repository is licensed under [MIT](https://opensource.org/license/mit).

For choosing your GitHub repo license 📄, please visit

- [Licensing a repository - GitHub](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
- [Choose an open source license - Choose a License](https://choosealicense.com/)
- [License Selector - ufal.github.io](https://ufal.github.io/public-license-selector/)

---

## (Optional) Other Things to Help You Organise the Repo

- Click the **gear icon ⚙️** on your repo webpage to set up:
  - Description: A short sentence about the repo.
  
    E.g., The Teenager Vaping Data from ACT Govt

  - Website: A link to the data owner.
  
  - Topics: Tags that help organise, classify and promote your repo.
  
    E.g., "australia", "dataset", "vape", "public-health"
  
- Find and add your `.gitignore` template from [gitignore - GitHub](https://github.com/github/gitignore)
  
- How to contribute to your repo 🤝?
  
  If you are looking for people to help you develop data-scraping scripts, or you need people to assist in data cleaning, please suggest people to open an **Issue** 🙋in your repo, and provide your **contact information** 📧 if necessary. You can also put this in the **(Optional) Announcement** section.
