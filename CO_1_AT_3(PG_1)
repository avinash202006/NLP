{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyMktmzQsr8ZvokME/1aSZvQ",
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
        "<a href=\"https://colab.research.google.com/github/avinash202006/NLP/blob/main/CO_1_AT_3(PG_1).ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 1,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wFOr8I1inqm4",
        "outputId": "5d1d40f8-ccde-43ad-c952-8e55d05f23a4"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter Email: avinash202006@gmail.com\n",
            "Enter Password: avinash@5544\n",
            "Enter Mobile Number: 1234567890\n",
            "Valid Email\n",
            "Weak Password\n",
            "Invalid Mobile Number\n"
          ]
        }
      ],
      "source": [
        "import re\n",
        "\n",
        "# Input from user\n",
        "email = input(\"Enter Email: \")\n",
        "password = input(\"Enter Password: \")\n",
        "mobile = input(\"Enter Mobile Number: \")\n",
        "\n",
        "# Email Validation\n",
        "email_pattern = r'^[A-Za-z][A-Za-z0-9._]*@[A-Za-z]+\\.(com|org|edu|net|in)$'\n",
        "\n",
        "if re.fullmatch(email_pattern, email):\n",
        "    print(\"Valid Email\")\n",
        "else:\n",
        "    print(\"Invalid Email\")\n",
        "\n",
        "# Password Validation\n",
        "password_pattern = r'^(?=.*[a-z])(?=.*[A-Z])(?=.*\\d)(?=.*[@#$%&!])[A-Za-z\\d@#$%&!]{8,}$'\n",
        "\n",
        "if re.fullmatch(password_pattern, password):\n",
        "    print(\"Strong Password\")\n",
        "else:\n",
        "    print(\"Weak Password\")\n",
        "\n",
        "# Mobile Number Validation\n",
        "mobile_pattern = r'^[6-9]\\d{9}$'\n",
        "\n",
        "if re.fullmatch(mobile_pattern, mobile):\n",
        "    print(\"Valid Mobile Number\")\n",
        "else:\n",
        "    print(\"Invalid Mobile Number\")"
      ]
    }
  ]
}
