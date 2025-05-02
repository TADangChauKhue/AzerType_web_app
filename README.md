# AzerType_web_app

AzerType is a web-based interactive application designed to help users improve their typing speed and accuracy through dynamic typing practice sessions.

## Introduction

Typing quickly and accurately is an essential skill in both professional and educational environments. AzerType helps users build this skill through real-time typing exercises and instant performance feedback.

Users can choose to practice with simple words or full sentences. After typing what is displayed on screen, they receive a score update and can even share their results via email.

**1. Business Question**

• How can users improve their typing speed in a structured and engaging way?

• Can real-time feedback help motivate users and enhance learning?

• Is it possible to make typing practice more accessible and enjoyable?

**2. Dataset**

The project works with two predefined lists in JavaScript: one with words and one with sentences.

1. **Input Data**:  
   - Randomly selected words or sentences displayed on screen  
   - User input typed into a designated field  

2. **Output Metrics**:  
   - Score (number of correct entries/ total attemps)
   - End-of-game message and email sharing option  

**3. Method: Typing Practice Game**

The app follows this process:

1. The user selects a mode: **words** or **sentences**
2. A prompt is shown in a dedicated area
3. The user types what they see into the input field
4. Clicking “Validate” checks their entry against the correct version
5. The score is updated in real time
6. At the end, the user can enter their name and email to share their score (with field validation)

## Interface Overview

![image](https://github.com/user-attachments/assets/a647356d-fbcd-4f45-873e-f842ed9a660f)

*Main interface showing mode selection, input zone, and score tracking*

## Key Features

- Choose between words and sentences
- Real-time scoring and feedback
- Share your score via email (with name & email validation)
- Input validation and error handling
- Responsive design, accessible on any browser
