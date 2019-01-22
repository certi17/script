# script

finding filename for win32

rem http://stackoverflow.com/questions/19540089/how-to-get-the-list-of-filenames-in-a-directory-and-store-that-in-a-variable-usi
rem http://stackoverflow.com/questions/15567809/batch-extract-path-and-filename-from-a-variable
rem http://superuser.com/questions/541575/comparing-part-of-a-filename-in-a-windows-batch-file
rem http://stackoverflow.com/questions/14954271/string-comparison-in-batch-file
rem http://mwultong.blogspot.com/2006/11/bat-if-dos-batch-file-if.html

convert %%~ni%%~xi -crop 1296x3888+1296+0 crop_temp_l.jpg
convert %%~ni%%~xi -crop 1296x3888+5184+0 crop_temp_r.jpg
convert crop_temp_l.jpg crop_temp_r.jpg +append crop_%%~ni%%~xi

rem reference https://ffmpeg.org/ffmpeg.html
rem reference http://horangi.tistory.com/290

https://hyundonghwang.github.io/2015/11/19/%ED%8C%8C%EC%9B%8C%EC%89%98-%EC%8A%A4%ED%84%B0%EB%94%94/


google calendar csv all day
Subject,Start Date,Start Time,End Date,End Time,All Day Event,Description,Location,Private
opic,01/21/2019,,01/21/2019,,True,,False
opic,02/25/2019,,02/25/2019,,True,,False
opic,03/25/2019,,03/25/2019,,True,,False
opic,04/22/2019,,04/22/2019,,True,,False
opic,05/27/2019,,05/27/2019,,True,,False
opic,06/24/2019,,06/24/2019,,True,,False
opic,07/22/2019,,07/22/2019,,True,,False
opic,08/18/2019,,08/18/2019,,True,,False
opic,09/16/2019,,09/16/2019,,True,,False
opic,10/21/2019,,10/21/2019,,True,,False
opic,11/18/2019,,11/18/2019,,True,,False
opic,12/6/2019,,12/6/2019,,True,,False


google calendar csv with time
Subject,Start Date,Start Time,End Date,End Time,All Day Event,Description,Location,Private
청소년분과 월례회,01/26/2019,5:30 PM,01/26/2019,6:30 PM,False,,False
상임위원회임시회의,01/27/2019,12:00 AM,01/27/2019,2:00 PM,False,점심식사,False
