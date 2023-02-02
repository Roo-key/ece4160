---
layout: post
title: Lab 2
description: Bluetooth
image: 
nav-menu: true
---
<section id="content">

<h2>Objective</h2>

<p>The purpose of lab 2 was to establish a working bluetooth connection between the computer and Artemis board. Other goals include downloading the various tools required to establish said bluetooth connection, as well as to gain familiarity with the Bluetooth Low Energy (BLE) libraries.</p>

<h2>Setup</h2>
<p>For the current and all future labs, the latest version of python, version 3.10,  was installed from the <a href="https://www.python.org/downloads/">official website</a>. A virtual environment was set up using the command line actions: 
<blockquote>python3 -m pip install --user virtualenv</blockquote>
<blockquote>python3 -m venv FastRobots_ble</blockquote>
<blockquote>.\FastRobots_ble\Scripts\activate</blockquote>
Within the virtual environment, various packages were installed using the following command line action:
<blockquote>pip install numpy pyyaml colorama nest_asyncio bleak jupyterlab</blockquote>
The coding for this lab will be done via Jupyter notebook as a python IDE, as well as a course-provided code base.
</p>

<h2>Example:</h2>