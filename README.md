# Find-Bad-Revision
Just implemented merge sort to find a bad revision of code in a sorted list

#Find the Bad Version
#Somewhere in our code one revision has broken our solution.
#Our revisions are represented by an ordered list
#versions = [1,2,3,4,5,6,7,8,9,10,11,12,13]
#We are at the latest version ie 13. and we don't want to go backwards and check each version.
#We instead want to split array of versions in half and if the one in the middle is bad then
#that means that the last half of the array versions also bad.
#Basically if 7 is bad so is 8,9,10,11,12 so then we can then check 7/2 = 3 and see if that version is bad.
#Implementing divide and conquer to discover the bad version
