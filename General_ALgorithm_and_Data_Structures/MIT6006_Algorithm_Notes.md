Introduction to Algorithm by MIT Press

HOMEPAGE FOR LECTURE VIDEOS:
https://www.youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb

Home page for Lecture Material:
https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/calendar/

Someones’s organized notes about the Lecture Videos:
https://catonmat.net/summary-of-mit-introduction-to-algorithms


——————————————————————————
Write things down!
If you don’t do it, you are finite  state automata.
If you do, you are a Turing Machine!
Since Turing Machine is just FSA with pencil and paper. 

I want to be a better Turing Machine :)

HeapSort
——————————————————————————




Part3. Data Structure(can be implemented to do operations on dynamic sets):

Heap


dictionary : a dynamic set that support operations like insert elements, delete elements, and test membership in a set 
	eg: Hash Table supports the dictionary operations.
	Time Complexity:	O(N) for worst case for search , expected O(1)
	eg: Binary Search Tree supports all dynamic-set operations below.
	Time Complexity:       
		worse case: O(n) for a tree with n elements.
		expected O(logN)
	eg: Rea-black Tree - a variant of BST. but guaranteed to have O(log N) in worst case!
	      property: a  balanced ST.
	      advantage: extent to dynamically maintain order statistics for a set of keys.
		Side Notes: Can I use this advantage in neural nets??
	      application: maintain the intervals between real numbers.ß
	eg: B Tree
	


Priority Queue (Ch7) :  heap data structure
	ability to:
	* inserting an element into
	* extracting the smallest element from a set

 
Operations on a dynamic set can be grouped into two categories:
	Queries: Simply return information about the set
