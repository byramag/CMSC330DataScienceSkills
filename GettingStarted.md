# How to set up Python locally
The internet is bursting with guides, so I won't duplicate that work here. Instead, here's a link to a good getting started guide:

For Windows Users: [Click here](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)

For Mac Users: [Click here](https://medium.com/geekculture/installing-python-3-x-development-environment-on-macos-a64c0141b20c)

## Now that you have Python set up, you'll need an IDE

__What is an IDE?__ IDE stands for Integrated Development Environment. This is an application that will give you a space to edit, manage, and run your code. There are a lot of options out there and a lot of developers will fight to the death over one being the best IDE. End of the day, different IDEs have different things going for them depending on your priorities. [Here's](https://realpython.com/python-ides-code-editors-guide/) some light reading on Python options for anyone interested.

If you're not interested in searching around and just want a recommendation, I'm personally a fan of [Visual Studio Code](https://code.visualstudio.com/) for the straghtforward view and ability to customize your extensions. 


# Getting started with this project
First and foremost, you'll need to create a GitHub account if you haven't already. You'll also need to make sure Git is set up on your local machine. See the [guide here](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html) for more details.

If you are not taking this course for credit, then you can simply [clone this repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
If you are enrolled in CMSC330 and need to turn in assignments, then you'll need to [fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) into your own and then clone from there.

Either way, at this stage, you should have the files of this project ready on your local machine, which you can then open in your IDE of choice.

# Running your Jupyter Notebooks
To be able to run the labs, you'll need to make sure you have the required packages. To do that, open up a terminal in the project folder and run the command 

`pip install -r requirements.txt`

After this, you should be able to run your labs in two ways
1. Directly run the jupyter command in your terminal, which will open a browser window of your Jupyter notebook. Follow the [guide here](https://www.pluralsight.com/guides/jupyter-notebook-getting-started) for more direction on this method.
2. If your IDE has support for Jupyter notebooks, you can run your notebooks directly inside the IDE. See the [Visual Studio Code Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) for an example of this.

# Submitting Assignments
If you are in this course for credit, you'll need to submit your completed assignments by pushing your code into your personal fork of this repository. 

TODO - more detail on this item