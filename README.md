Download Link: https://assignmentchef.com/product/solved-ch231a-assignment10-hash-tables
<br>
<h1></h1>

<ul>

 <li> Given the sequence <em>&lt; </em>3<em>,</em>10<em>,</em>2<em>,</em>4 <em>&gt;</em>, apply the double-hashing strategy for open addressing to store the sequence in the given order in a hash table of size <em>m </em>= 5 with hash functions <em>h</em><sub>1</sub>(<em>k</em>) = <em>k </em>mod 5 and <em>h</em><sub>2</sub>(<em>k</em>) = 7<em>k </em>mod 8. Document all collisions and how they are resolved. Write down your computations.</li>

 <li> Implement a hash table that supports insertion and querying with open addressing using linear probing. Select an <em>h</em><sup>0 </sup>function and explain why your selected <em>h</em><sup>0 </sup>is wellsuited for your test data. The implementation should be consistent with the following or equivalent class specifications:</li>

</ul>

class Node { public: int key; int value;

Node(int key, int value);

} class HashTable { private: Node <sup>∗ ∗</sup>arr; int maxSize; int currentSize; public:

HashTable(); hashCode(int key);

void insertNode(int key, int value); int get(int key); bool isEmpty();

}

<h2><strong>Problem 10.2 </strong>Greedy Algorithms</h2>

<ul>

 <li> Show that a greedy algorithm for the activity-selection problem that makes the greedy choice of selecting the activity with shortest duration may fail at producing a globally optimal solution.</li>

 <li><strong>Bonus </strong> Assuming an unsorted sequence of activities, derive a greedy algorithm for the activity-selection problem that selects the activity with the latest starting time. Your solution should not simply sort the activities and then select the activity.</li>

</ul>