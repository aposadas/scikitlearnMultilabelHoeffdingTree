
HOEFFDING TREES's Classifier code!
=================================================================
.. automodule:: my_classifier
:members:

**class HoeffdingTreeClassifier ():**
This class classifies a Hoeffding Tree and initializate its structure.

**def __init__(self):**
Constructor of the class, contains essential parameters for the hoeffding tree creation

**def fit(self, X, Y):**
Just starting an empty tree and adding the x to it.

**def partial_fit(self, x, y=None):**
constructs the root node if has not been created, fills the statistics of the root nodein the case there is already a root node, then it is been called the update statistic for the node.

**def predict(self, X):**
for calling the prediction of the node.