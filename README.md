# Web Scraping: Crawling FAP class timetable and schedule on Google Calendar 

A program that available to automatically scrape the class timetable data for a specific semester from my university academic portal website (fap.fpt.edu - FPT University).

The schedule information is subsequently automatically updated as events in my personal Google calendar so that I can receive notifications about the schedule via phone or email and be aware of any changes to the classroom, online/offline, lecturer, etc.

### Notes:
- Create and store edu email & password in `personal_credentials.txt` to access FAP.
- Predefine the information of the classes, semesters, subjects, etc. in [info.txt](/info.txt).
- [Authorizing Requests to the Google Calendar API](https://developers.google.com/calendar/api/guides/auth)
- Raw timetable data is stored in the `timetable.json` file

### Todo:
- [ ] Create json events list 
- [ ] Add more customization for displaying events in Google Calendar
- [ ] Login by using cookie with Selenium webdriver
- [ ] Retrieve semester ID with the semester name provided