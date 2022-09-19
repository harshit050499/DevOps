# Project Planner tool

## About
The project planner tool project can be used by teams to manage team boards, where they can manage and track work done by the team members.This project will be helpful to the team to have single pane of view for all the team task. Also this project has enpoints which make it easy to manage and perform various operation on users, teams or team_boards.

## Features
1 - Single Pane of Dashboard for teams to view and manage their update_task_status
2 - User and teams can be managed using the API endpoints.
3 - Simple and Modular Design

## Thoughts
1 - Implemented all the endpoints in as simple way as possible by keeping in mind that the response time is lowest.
2 - To have consistency and ease of handling data used the `CSV` file format ( which made the data storage similar to Database).
3 - Tried to cover as much as test edge cases possible.
4 - Where ever there was a need to use path used (os.sep) instead of writing `/` because this made the code to run smoothly on any OS(linux , windows etc)
5 - Used the Pre-build library `UUID` for generating the Unique ID wherever needed - this was done as we had to use the file to save data and every time we need ID we needed to read the whole file to get the last used ID which would have resulted in increasing the response time.
6 - Tried to implement all the functions with minimal use of library.

