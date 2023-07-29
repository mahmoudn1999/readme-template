# Bioinformatics Mini Tools V 1.0
> Bioinformatics tool

Through our program you can download databases, do pairwise alignment, or multiple sequence alignment.

## Prerequisites to run the program

To run the program you NEED to download these tools (efetch, BLAST, MAFFT, and FastTree). IF you use UBUNTU, use these commands:

(It`s RECOMMENDED to run this command first)
```sh
sudo apt-get update
```
```sh
sudo apt-get install efetch or sudo apt-get install -y efetch
sudo apt install ncbi-blast+
sudo apt-get install mafft
sudo apt-get install fasttree
```

To run the GUI correctly you NEED to download these packages ( Python3, PysimpleGUI, BioPython, and Matplotlib). IF you use UBUNTU, use these commands:

```sh
sudo apt install python3
pip3 install PySimpleGUI
pip3 install BioPython
pip3 install Matplotlib
```
(IF the error **externally-managed-environment** appeared to you while using pip3 command, add this line with each code **--break-system-packages**).

## Running the program

Download the program file then open the terminal in it, type **python3 main.py** or if you have VISUAL STUDIO CODE open the program file through it then run the program.

* After that you can choose what would you like to do, if you want to **RETRIEVE DATABASE**, **CHOOSE** it then **ENTER the accession number of the database**.

* If you want **PAIRWISE ALIGNMENT**, **CHOOSE** it then **add your reference and query sequence** then wait until the results are saved.

* If you want **MULTIPLE SEQUENCE ALIGNMENT**, **CHOOSE** it and **ENTER your accession numbers** then wait until the results are saved.

Finally i hope that our software met your expectations. **(:**
