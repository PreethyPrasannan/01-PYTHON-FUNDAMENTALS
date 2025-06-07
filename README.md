# 01-PYTHON-FUNDAMENTALS
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 98,
   "id": "682ac596-3481-4566-b53a-cb7cd089b522",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Name: Ajay Thomas\n",
      "Student_number: ST1001\n",
      "Email: ajaythomas@gmail.com\n"
     ]
    }
   ],
   "source": [
    "#1. print name, student number and email address\n",
    "\n",
    "print('Name:','Ajay Thomas')\n",
    "print('Student_number:','ST1001')\n",
    "print('Email:','ajaythomas@gmail.com')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 100,
   "id": "3ade94e5-945c-4043-8ad6-0d35524c8379",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Ajay Thomas\n",
      "ST1001\n",
      "ajaythomas@gmail.com\n"
     ]
    }
   ],
   "source": [
    "#2. print  name, student number and email address using escape sequences\n",
    "\n",
    "print(\"Ajay Thomas\\nST1001\\najaythomas@gmail.com\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "id": "9f953d50-13ae-4196-93f3-edc9e642ed91",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "14 + 7 = 21\n",
      "14 * 7 = 98\n",
      "14 - 7 = 7\n",
      "14 / 7 = 2.0\n"
     ]
    }
   ],
   "source": [
    "#3. add, subtract, multiply and divide the two numbers\n",
    "\n",
    "num1 = 14\n",
    "num2 = 7\n",
    "\n",
    "print(f\"{num1} + {num2} = {num1 + num2}\")\n",
    "print(f\"{num1} * {num2} = {num1 * num2}\")\n",
    "print(f\"{num1} - {num2} = {num1 - num2}\")\n",
    "print(f\"{num1} / {num2} = {num1 / num2}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 104,
   "id": "12931866-3063-4e67-8df3-d66520bf7b26",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "#4. print the numbers from 1 to 5 range\n",
    "\n",
    "for i in range (1,6):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 106,
   "id": "3b9a7603-6097-457d-a3f3-c2679bf7e25d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\"SDK\" stands for \"Software Development Kit\", whereas\n",
      "\"IDE\" stands for \"Integrated Development Environment\".\n"
     ]
    }
   ],
   "source": [
    "#5. Using print function with quotation mark and line breaks\n",
    "\n",
    "print ('\"SDK\" stands for \"Software Development Kit\", whereas\\n\"IDE\" stands for \"Integrated Development Environment\".')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 108,
   "id": "7b2f27f6-6aea-412c-91e4-8298467f78b2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "python is an \"awesome\" language.\n",
      "python\n",
      "\t2023\n",
      "I'm from Entri.\n",
      "5\n",
      "e\n",
      "Entri\n",
      "2023\n",
      "Entr2023\n",
      "Entri*20"
     ]
    }
   ],
   "source": [
    "#6. Practice and check the outputs\n",
    "\n",
    "print(\"python is an \\\"awesome\\\" language.\")\n",
    "print(\"python\\n\\t2023\")\n",
    "print('I\\'m from Entri. \\b')\n",
    "print(\"\\65\")\n",
    "print(\"\\x65\")\n",
    "print(\"Entri\", \"2023\", sep=\"\\n\")\n",
    "print(\"Entri\", \"2023\", sep=\"\\b\")\n",
    "print(\"Entri\", \"2023\", sep=\"*\", end=\"\\b\\b\\b\\b\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 110,
   "id": "66f7b1ff-eb3f-46d5-8c77-277365722afa",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Type of num: <class 'int'>\n",
      "Type of textum: <class 'str'>\n",
      "Type of decimal: <class 'float'>\n"
     ]
    }
   ],
   "source": [
    "#7. print the type of each variable\n",
    "\n",
    "num = 23\n",
    "textum = \"57\"\n",
    "decimal = 98.3\n",
    "\n",
    "print(\"Type of num:\",type(num))\n",
    "print(\"Type of textum:\",type(textum))\n",
    "print(\"Type of decimal:\",type(decimal))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 112,
   "id": "ff2a2f2f-a655-4788-8c88-7e93f42bfcf2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "sum of variables: 178.3\n",
      "Type of total: <class 'float'>\n"
     ]
    }
   ],
   "source": [
    "# Sum of varibales\n",
    "total = num + int(textum) + decimal\n",
    "print(f\"sum of variables: {total}\")\n",
    "print(f\"Type of total: {type(total)}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 114,
   "id": "fece8719-b9e7-405c-997a-7931e00584f7",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Total number of minutes in a year: 525600\n"
     ]
    }
   ],
   "source": [
    "#8. calculate number of minutes in a year \n",
    "\n",
    "days_in_year = 365\n",
    "hours_in_day = 24\n",
    "minutes_in_hour = 60\n",
    "\n",
    "total_minutes = days_in_year * hours_in_day * minutes_in_hour\n",
    "print(f\"Total number of minutes in a year: {total_minutes}\")\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 116,
   "id": "5bc6a970-e92c-4d8f-8bb5-7bec79af2a5d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Please enter your name Ajay Thomas\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hi Ajay Thomas, Welcome to python programming :)\n"
     ]
    }
   ],
   "source": [
    "#9. Ask user for their name and greet them\n",
    "\n",
    "name = input(\"Please enter your name\")\n",
    "print(f\"Hi {name}, Welcome to python programming :)\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 120,
   "id": "6956954a-b30b-405d-8075-0f3589bb1e6f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Please enter the amount in pounds: 50\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "£50.0 are $63.5\n"
     ]
    }
   ],
   "source": [
    "#10. Converting pounds to dollars\n",
    "\n",
    "Exchange_Rate = 1.27\n",
    "pounds = float(input(\"Please enter the amount in pounds:\"))\n",
    "dollars = pounds * Exchange_Rate\n",
    "print(f\"£{pounds} are ${dollars}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f3273b43-5b78-4f83-8c94-0c633a1f26a3",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
