# Project Planner tool

## About
The project planner tool project can be used by teams to manage team boards, where they can manage and track work done by the team members.This project will be helpful to the team to have single pane of view for all the team task. Also this project has enpoints which make it easy to manage and perform various operation on users, teams or team_boards.

## Features
 - Single Pane of Dashboard for teams to view and manage their update_task_status
 - User and teams can be managed using the API endpoints.
 - Simple and Modular Design

## Thoughts
 - Implemented all the endpoints in as simple way as possible by keeping in mind that the response time is lowest.
 - To have consistency and ease of handling data used the `CSV` file format ( which made the data storage similar to Database).
 - Tried to cover as much as test edge cases possible.
 - Where ever there was a need to use path used (os.sep) instead of writing `/` because this made the code to run smoothly on any OS(linux , windows etc)
 - Used the Pre-build library `UUID` for generating the Unique ID wherever needed - this was done as we had to use the file to save data and every time we need ID we needed to read the whole file to get the last used ID which would have resulted in increasing the response time.
 - Tried to implement all the functions with minimal use of library.

