# Bioinformatics_Bootcamp
GOAL Bioinformatics Bootcamp
Code is run from informatics_bootcamp.ipynb. Please go to that file and click the colab link to open a code notebook

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyNbE31OUIfwZNe1TzWHhqhT",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Eitan177/Bioinformatics_Bootcamp/blob/main/informatics_bootcamp.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# Welcome to the GOAL Bioinformatics Bootcamp, 2024! To Setup this notebook please run the first two cells. This will download the packages you will need to participate"
      ],
      "metadata": {
        "id": "fKTuyMLINOKx"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# @title Click the traingle to the left (hit control-enter if you would like to use your keyboard instead) to run this first cell\n",
        "\n",
        "!pip install -q condacolab"
      ],
      "metadata": {
        "id": "oxAylDTIMlhs"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "# @title Click the traingle to the left (hit control-enter if you would like to use your keyboard instead) to run this second cell\n",
        "import condacolab\n",
        "condacolab.install()\n",
        "condacolab.check()\n",
        "!conda install bioconda::samtools\n",
        "!conda install bioconda::sambamba\n",
        "!conda install bioconda::fastp\n",
        "!conda install bioconda::fastqc\n",
        "!conda install bioconda::varscan==2.4.4\n",
        "!conda install bioconda::bwa\n",
        "!conda install bioconda::bwa\n",
        "!wget http://www.openbioinformatics.org/annovar/download/0wgxR2rIVP/annovar.latest.tar.gz\n",
        "!tar -zxvf annovar.latest.tar.gz\n",
        "!rm -r annovar.latest.tar.gz\n",
        "!rm -r annovar/humandb"
      ],
      "metadata": {
        "id": "cV3xSQhnHYCt"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
