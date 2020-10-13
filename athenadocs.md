# Using Athena

Athena is a Competency management system.  
Every `competency` has an `object id`.

A `cluster` is an arbitrarily grouped set of `competencies`. Every `cluster` has an `object id`.  


## To evidence a competency
In order to evidence a `competency`, fill in your evidence below the `competency` object.


## To update the manual indexes

Pull master on the root repo. Run the `manual-index-sync` utility.

## Structuring the competencies
You can do it as you like, but do not:  
* change the competency objects, other than to update the status
* put anything outside of the evidence folder.

Athena will ignore and overwrite changes to competency objects and anything in her remit outside of the evidence folder.

---


---
---
# Plan

* Getting new competencies into root  
Different from getting new competencies into manual indexes
    * Approach 1: Build model manually into competency json file.
    * Approach 2: Make a little utility.

* Getting new competencies into manual indexes  
Including requirement indexes
    * Manually
    * Getting new competencies into root via a manual index
        * Approach option: Utility to parse given structure, and replace structure with a link to a cluster.

* Getting new files in to delegate repos
    * Approach 1:
        * Pull master
        * Manual copy and paste, root repo over delegate, Windows handles the file merge. Conflict resolution handled by always accepting root.
    * Approach 2:
        * Write pull-and-paste utility
* Detecting `competencies` at a given `status`
    * Approach 1:
        * "Find in files" for a search term
    * Approach x:
        * Display on a dashboard
* In-competency conflict detection
    * Approach 1: Be careful. Utility will use last occurance of competency as source of truth
    * Approach 2: Write a in-competency conflict detection tool.
        * Find all instances of that competency, compare the evidence. Alert if the evidence is different
* Finding competencies in directory structures
    *



# A sample `cluster` of `competencies`: 
<br/>
<br/>
<br/>
<br/>



<!--
    <athena>
    {
        "ObjectId": "12347",
        "Type": "Cluster",
        "DisplayName":"Create Service Principals",
    }
    </athena>
-->
# Create Service Principals
Make Service Principals by these methods. Include code snippets, and screenshots of responses where appropriate.

<!--
    <athena>
    {
        "ObjectId": "12345",
        "Type": "Competency",
        "DisplayName":"Make a Service Principal via Python Client Library",
        
        "Status": "Required"
    }
    </athena>
-->
# Make a Service Principal via Python Client Library
evidence
<!--
    <athena>
    {
        "ObjectId": "12346",
        "Type": "Competency",
        "DisplayName":"Make a Service Principal via PowerShell Client Library",
        "Status": "Required"
    }
    </athena>
-->
# Make a Service Principal via PowerShell Client Library

evidence

<!--
    <athena>
    {
        "ObjectId": "12348",
        "Type": "Competency",
        "DisplayName":"Make a Service Principal via C# Client Library",
        "Status": "Required"
    }
    </athena>
-->
# Make a Service Principal via C# Client Library

evidence

<!--
    <athena>
    {
        "ObjectId": "12349",
        "Type": "Competency",
        "DisplayName":"Make a Service Principal via Postman",
        "Status": "Required"
    }
    </athena>
-->
# Make a Service Principal via Postman

evidence