{\rtf1\ansi\ansicpg1252\cocoartf2577
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica-Bold;\f1\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red32\green32\blue32;\red255\green255\blue255;\red0\green0\blue0;
\red242\green242\blue242;\red32\green32\blue32;}
{\*\expandedcolortbl;;\cssrgb\c16863\c16863\c16863;\cssrgb\c100000\c100000\c100000\c80000;\cssrgb\c0\c0\c0;
\cssrgb\c96078\c96078\c96078;\cssrgb\c16863\c16863\c16863;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\margl1440\margr1440\vieww18720\viewh9260\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\b\fs36 \cf0 # School_District_Analysis
\f1\b0\fs24 \
\

\f0\b\fs28 \ul Background
\f1\b0\fs24 \ulnone \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The school board has notified Maria and her supervisor that the\'a0\cf4 \cb5 \strokec4 students_complete.csv\cf2 \cb3 \strokec2 \'a0file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you\'92ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
\f0\b\fs28 \cf0 \cb1 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 \
\
\
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\ls1\ilvl0\cf0 \ul \ulc0 Results\
\ls1\ilvl0
\f1\b0\fs24 \cf2 \expnd0\expndtw0\kerning0
\ulnone \outl0\strokewidth0 \strokec2 -
\fs28 How is the district summary affected?\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 	\ul Before Data Cleanup\ulnone \
	Average Math Score = 79.0\
	Average Reading Score = 81.9\
	% Passing Math = 75%\
	% Passing Reading = 86%\
	% Overall Passing = 65%\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\ls2\ilvl0\cf6 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 	\ul After Data Cleanup\ulnone \
	Average Math Score = 78.9\
	Average Reading Score = 81.9\
	% Passing Math = 74.8%\
	% Passing Reading = 85.7%\
	% Overall Passing = 64.9%\
\
-How is the school summary affected?\
	Before Data Cleanup : Thomas High School overall % passing was 91% (2nd place)\
	After Data Cleanup : Thomas High School overall % passing was 65% (8th place)\
\
-How does replacing the with graders\'92 math and reading scores affect Thomas High School\'92s performance relative to the other schools?\
	Changed ranking from 2nd place to 8th.\
\
-How does replacing the with-grade scores affect the following:\
	Math and reading scores by grade :Math and Reading scores from THS turned to N/A (or 0), with student count decreasing from 1,635 to 1,174\
 	Scores by school spending: Similar trend observed as math and reading scores by grade\
	Scores by school size: Omitting THS 9th grades decrease the % passing math, reading and overall passing.\
	Scores by school type: Similar trend observed as scores by school size. \
\
\
\
\ls2\ilvl0
\f0\b \ul Summary
\f1\b0 \ulnone \
\ls2\ilvl0
\fs24 Four major changes in the updated school district analysis after readying and math scores for the ninth grade at Thomas High School have been replaced with NaNs:\
1. Average Math and Reading test scores\
2. Percentage of those who passed math and reading \
3. Funding for each student\
4. \'93Passing\'94 grade threshold}