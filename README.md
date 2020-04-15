# dtree
### A tool to visualize basic Python data structures.

```dtree.py``` uses the ```ast``` module to parse data structures to an abstract syntactic
structure. This is then further parsed to output a decision tree of your data structure.
<hr>
Let's take a look at this nested list:

```>>> nested_list = ['ira', 'nanna', 'ghost', [1, 2, 3], {'a', 'b', 'c'}, ('do', 're', 'mi')]```
<br>
<br>
The decision tree output is as follows:
<p align = 'center'>
<img src=https://i.imgur.com/XN1QWpy.png alt="data structure tree"
    width=800><br>
</p>
<br>
Note: this program is not yet capable of handling dictionaries.
This project is still a work in progress. 




