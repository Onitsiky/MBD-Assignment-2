# <center>Mobile Big Data Analytics & Management - Assignment 2</center>
## A. Quantitative Analysis
* Dataset statistics
    * Dataset shape, size, class count, class distribution:
![alt text](assets/dataset-content-summary.png)
    * Droping the duplicates in a dataset helps prevent Data Leakage
    * The dataset contained 1 missing value and no duplicated ones. One missing value was dropped, because since it was a categorical value, it won't be relevant to fill it with any place holder, or filling it with one of the most frequent data too (because we were just asked to drop duplicated value if there were).
    * Text characteristics
![alt text](assets/class-text-comparison.png)

    For the new added columns, the above image shows that the **EXTREMIST** class is more extreme in its length while the **NON-EXTREMIST** class is more dense.
    * Visualizations
![alt text](assets/class-distribution.png)
This bar chart shows that the classes are well balanced.

* Linguistic Analysis
    * Overall, the top 20 most frequent words are: `'the', 'a', 'to', 'you', 'and', 'of', 'i', 'is', 'are', 'bitch', 'not', 'in', 'that', 'it', 'with', 'they', 'all', 'kill', 'for', 'do'`
    * Per class, here are the top 20 most frequent words:
        * EXTREMIST: `'the', 'to', 'and', 'of', 'you', 'a', 'are', 'i', 'is', 'kill', 'not', 'they', 'it', 'all', 'in', 'with', 'that', 'them', 'us', 'get'`
        * NON-EXTREMIST: `'a', 'the', 'you', 'to', 'bitch', 'i', 'of', 'and', 'is', 'not', 'that', 'are', 'in', 'with', 'it', 'for', 'my', 'do', 'fucking', 'trump'`
    * After visual comparison, here are the 5 most prominent words per classes:
        * EXTREMIST: `U, Let, Kill, attack, people`
        * NON-EXTREMIST: `Bitch, Fucking, Trump, face, fuck`
## B. Qualitative Analysis
* Dataset annotation and validation: 