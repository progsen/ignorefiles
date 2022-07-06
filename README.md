# ignorefiles

ignore files for csharp (core, net5+) and unity
#csharp (core, net5+) 

basic cs ignore file, if you use .net framework you might still need to add the packages directory


#unity
unity's file is based on githubs only this version solves a problem students run into very often:
students sometimes have a subdirectory which contains the unity root. in that case the ignore file fails to do anything and leads to giant checkins & problems

this version ignores all directories whether they are in subdirs or not
