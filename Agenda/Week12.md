## Week 12: April 14/15, 2020

1. Quiz 5 results
2. Project Workshop 
    * A warning about dangerous queries that can BREAK the server
        * __Always__ test your SELECT queries BEFORE using them in  INSERT statements.
        * One bad cross join can write 100 GB of data!
        * Try this ...
            ```
            SELECT COUNT(*) 
            FROM (YOUR SELECT QUERY)
            
            ```
            to get a record count before writing ...
            
            ```
            INSERT INTO ...
            YOUR SELECT QUERY
            
            ```
            If you get a huge record count then you messed up. The biggest _sane_ record count given the source data is about 300,000. 
    * `CourseDataWarehouse.db` (Step 5)
        * Scope: What kinds of questions should the DW answer? Be very specific, as this will determine your facts and dimensions.
        * Design: Draw an ERD for each fact table in your DW; dimensions can appear on multiple ERDs.
        * Implementation: Create the dimension tables first, then the fact tables, which should have lots of FKs to the dimension tables. You can add new dimension tables if needed.  
3. Classwork and Homework
    * Continue to collaborate on class projects
    * Goal for next week's class is to clean up your notebooks and files and begin packging it all up in the final report. (It's just a `Readme.md` file with links.)

# Zoom Invitation
Need help? Follow these [instructions](https://quip.com/rULNAVPjKQlj).
Please do not join the meeting until the time given. 

__

Christopher Huntley is inviting you to a scheduled Zoom meeting.

Topic: BA510 Class Meeting
Time: This is a recurring meeting; join at 6:30pm on regular class days; password was emailed April 6 @2:34pm.

Join Zoom Meeting
https://Fairfield.zoom.us/j/403430571

Meeting ID: 403 430 571

One tap mobile
+16468769923,,403430571# US (New York)
+13126266799,,403430571# US (Chicago)

Dial by your location
        +1 646 876 9923 US (New York)
        +1 312 626 6799 US (Chicago)
        +1 301 715 8592 US
        +1 346 248 7799 US (Houston)
        +1 669 900 6833 US (San Jose)
        +1 253 215 8782 US
Meeting ID: 403 430 571
Find your local number: https://Fairfield.zoom.us/u/acvDnwFcGq



