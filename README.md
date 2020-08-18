# A Gentle Introduction to Data Science with Python
Python is a capable and free (open source) programming language well-suited for analysis of data, including microbiome data. Together, we will go through a real-life example, re-analyzing microbiome - immune checkpoint inhibitor studies. We will touch on both the basics (loading in data, transforming, graphing, basic statistical analysis, and outputting data and figures), and use the examples to compare and contrast with some equivalents in R. This introduction should be suitable for those with no data analysis with code experience, but have some added dimensions for those familiar with R.

## If you want to join along
1. Please install Python version 3:
https://www.python.org/downloads/release/python-385/
- I suggest starting with vanilla python3. There are _many_ different versions of python. 

2. Download this repository
- This can be done via Code -> Download Zip above. Then unzip to a directory

3. Open a command line (in windows, command; in mac, terminal)
- Change to the directory of the downloaded repository

4. Create a virtual environment
`python3 -m venv dang-env`

5. Activate the virutal environment
`source dang-env/bin/activate`

6. Upgrade pip3
`pip3 install pip --upgrade`

7. Install the required packages
`pip3 install -r requirements.txt`

8. Start jupyter
`jupyter notebook`