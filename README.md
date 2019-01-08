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
