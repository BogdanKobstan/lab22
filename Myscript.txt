echo off
md Kobzev
cd Kobzev
md Bogdan
md Vadimovich
pause
cd Bogdan
echo > 19112003.txt
pause
cd ..
cd Vadimovich
echo > myasuscompkobzev2.txt
pause
cd ..
cd ..
del Kobzev /S /Q /F
pause
cd Kobzev
rd Bogdan
rd Vadimovich
cd .. 
rd Kobzev
pause

