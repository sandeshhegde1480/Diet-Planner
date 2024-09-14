# Diet-Planner
NUTRISIST
My project 'NUTRISIST' is an AI based under-developing nutrition assistant, which concentrates on providing suggestions for diet and nutritional requirements for a person who is interested to lose or gain his weight and achieve other goals.
Main Goal:
The project aims to achieve the generation of perfect diet plans based on the body weight, target weight considering multiple factors and medical abnormalities and complexities.
Current Updates:
Currently, the food suggestions are generated on the basis of the intention of the user, his physique (height and weight), and the other information like his daily routine (household, office work, sporting exercises, Gym trainings etc.,) and the extremity of the routine. 
The data then processed to get the calory consumption and diet is suggested.
The basic diet plan: 
	35% calories of the total calory intake in the breakfast
	45% calories of the total calory intake in the lunch
	25% calories of the total calory intake in the dinner
And the calories from the food suggested in the diet contains, 
	45 - 65% of calories from carbohydrates
	20 - 35% of calories from fat
	10 - 35% of calories from protein, which are considered as balanced in macronutrients
The body weight will be reduced at the rate of 0.14 kg/ day (0.5 to 1 kg per week) and gained at the rate of 0.1 kg/ day (0.5 to 0.7 kg/ week)
The application is made with the python library Django which based on MVT (Model, View, Template) model.



Used Libraries and classes:
	from django.db import models
	from django.contrib.auth.models import User
	from django.contrib.auth.forms import UserCreationForm
	from django import forms
	from django.shortcuts import render,redirect
	from django.contrib import messages
	from django.contrib.auth import authenticate, login, logout
	import math
	import pandas as pd
	import random
	import datetime
These libraries are used for models and views where HTML, CSS and Java Script are used as integrated html for Templates.

