# Secure_Voting_System_Through_Face_Recognition

## Overview

Now-a-days in India there are two types of methods are used for voting. The first method is secret ballot paper, in which lots of paper are used and second method is EVM(Electronic Voting Machine) which is used since 2003 but both of those methods have some limitations. There is a necessity for a method for online voting that is more secure than the existing system. In our proposed system we introduce a secure way for online voting by using face recognition system and email verification at the time registration of a new voter which is used to authenticate a person. Authorized Voter also can able to cast their vote only once and the tallying of the votes will be done automatically, thus saving a huge time and enabling administrator to announce the result to announce the result within a very short period.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Architecture](#architecture)
- [Requirements](#Requirements)
- [Usage/Workflow](#usage/Workflow)
- [License](#License)

## Prerequisites

Before setting up the AMI backup solution, make sure you have the following prerequisites in place:

- Front - end wen technologies using HTML, CSS, and Bootstrap
- Machine Learning Algorithm(Local Binary Pattern Histograms) for face recognition and OpenCV which is an open source library for machine learning for creating a infrastructure to vision.
- For storing data using MySQL and MySQLyog Enterprice for visualize purpose
- Flak Framework, which is a poweful web framework for creating API's in python
- Template Name    : Barber X - Barber Shop Template
- Template Link    : https://htmlcodex.com/barber-shop-template
- Template License : https://htmlcodex.com/license
- Template Author  : HTML Codex
- Author Website   : https://htmlcodex.com
- About HTML Codex : HTML Codex is one of the top creators and publishers of Free HTML templates, HTML landing pages, HTML email templates and HTML snippets in the world. Read more at (https://htmlcodex.com/about-us)
  

## Architecture

![Architecture Diagram](system_architecture)

Architecture diagrams can help system designers and developers visualize the high-level, overall structure of their system or application for the purpose of ensuring the system meets their users' needs.

## Requirements

1. The hardware requirements include the requirements specification of the physical computer resources for a system to work efficiently. The hardware requirements may serve as the basis for a contract for the implementation of the system and should therefore be a complete and consistent specification of the whole system.
         System Processor : Intel I3
         Hard Disk : 500 GB
         Ram : 4 GB
2. The software requirements are description of features and functionalities of the target system. Requirements convey the expectations of users from the software product. The requirements can be obvious or hidden, known or unknown, expected or unexpected from client‘s point of view.
         Operating system : Windows OS 7+
         Coding Language : Python
         IDE : Pycharm IDE
         GUI : Flask
## Usage/Workflow

1. Each new user must first register for voting by providing their information.
Registration is therefore the first thing we do.
2. Before capturing the voter images, email verification can be held to verify details.
After authenticating successfully, system allow voter for captures the images by
saving with pin number generated by the voter. Now registration of voter is
successfully completed.
3. At the time of election, we will use two levels of security first one is username
and p in Number verification and second one is face recognition.
4. System will check username and password entered by the voter is correct or not.
5. If username and password is correct then system allow to on web cam then the
face capturing through web ca m will compares with the respective image captured at
the time registration.
6. If the image matches then voter is allowed to cast a vote. If not voter is not
allowed
7. On the voting page, nominees images can be displayed and these nominees can
be added by administrator. So voter can cast their vote by selecting any one of them.
8. As soon as voter will give vote then voter is not allowed to vote more than once.
so we can say that a voter can give only one vote.

## License
All of the creative works by HTML Codex (https://htmlcodex.com) are licensed under a Creative Commons Attribution 4.0 International License (https://creativecommons.org/licenses/by/4.0).

Legal Attribution
HTML Codex creates and publishes free HTML website templates, landing page templates, email templates, and snippets. When you download or use our creative works, it will attribute the following conditions.

You are not allowed

  -  You are not allowed to remove the author’s credit link/backlink.
  -  You are not allowed to sell, resale, rent, lease, license, or sub-license.
  -  You are not allowed to upload on your template websites or template collection websites or any other third party websites without our permission.
    
You are allowed

  - You are allowed to use for personal and commercial purposes.
  - You are allowed to modify/customize however you like.
  - You are allowed to convert/port for use for any CMS.
  - You are allowed to share/distribute under the HTML Codex brand name.