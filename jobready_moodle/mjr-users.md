---
title: Users
keywords: moodle, 'job ready'
last_updated: March 20, 2016
tags: [moodle, job_ready, user, users, account]
summary: "User creationand update with the Moodle to Jobready Connector."
sidebar: mjr_sidebar
permalink: /jobready-2-moodle/users/
---

## Introduction

Create your user in JobReady as usual.

## Actions

SMSConnector synchronises user data beteween JobReady and Moodle.
The arrows symbolise the direction of the data synchonisation.

| enroll user into a course  | JOBREADY | => | Create user in MOODLE


## User fields

Required Jobready user account fields and their mapping to Moodle:

| JOBREADY      |    |  MOODLE
|---------------|----|-----------
| First Name    | => |  First Name
| Last name     | => |  Last Name
| Email         | => |  Email
| Login         | => |  Username

{% include important.html content="All these fields are required for the synchronisation to work." %}

### The ID Number Field


You find this field in the user settings uunder the *optional* fields.
This ID controls the Synchronisation to Jobready. If this number is changed the synchronisation would break.

{% include important.html content="Please do not touch the ID Number field in the Moodle user settings." %}
