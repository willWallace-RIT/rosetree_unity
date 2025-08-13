# rosetree_unity
rose tree class for unity

see it in action in this code made for global game jam '23

https://github.com/willWallace-RIT/treeGeneration


the code is fairly self documented with the excption of rRun which recursively runs a defined function on each traversed node farther down the line.

    //sample


      node.rRun((Dictionary<string, object> p, Node<Branch> node) => {
            string v = (string)p["variableDictEntry"];
       Debug.Log(v);
       Debug.log(id);
            return new Dictionary<string, object>(); 
        }, new Dictionary<string, object>() { { "variableDictEntry", "valueofarbitrarytype"} });
