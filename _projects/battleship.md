---
title: 'Multiplayer Battleship'
permalink: /projects/battleship/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
time_worked: "Jan 2020 - May 2020"
date: 2020-1-01
show_date: false
skills: [Java, socket networking, GUI development]
---

Developed online-multiplayer clone of Battleship with fully featured graphical user interface (GUI). Honors project for CS 1113 - Computer Science I.
<!--more-->

# Project Overview

My first major exploration of large-scale software development.

Objectives:

* Fully functional implementation of Battleship - ship selection and placement, tile targeting, hit notifications, etc.
* Online multiplayer functionality - real-time chatting, rematching, ship updates, etc. Uses peer-peer network architecture.
* Graphical User Interface - develop straightforward UI to show ships, menus, chat, prompts, etc.

# Implementation

* Used Java's net libraries to establish socket-based communication between hosts.
* Custom protocol to handle gameboard updates and chats.
* Players enter IP directly to connect to hosted game.
* Java Swing and AWT libraries to manage GUI, which emulates original game board.
* Quality of life features - rematching after game, showing surviving ships upon loss, two-way chat, etc.