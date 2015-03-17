The project aims to create a set of Restful APIs that allows developers to utilise the core reasoning mechanisms provided by a reasoner.  Exposing of the core functionalities of a reasoner as services is an important problem to be solved for many domains (e.g., sensor networks, handheld devices, and so on). This is due to a variety of reasons:

• Though knowledge-based reasoning has become very efficient with knowledge representation techniques such as OWL-DL, it is still a very computationally intensive operation (CPU, memory, etc.). This makes it impossible to create application which can utilise the power of reasoning in low powered devices such as handhelds.

• There are many reasoners for the Semantic Web implemented in many different languages. For example Pelletis implemented in java whereas Fact++ is implemented using C++. Thus, interacting with such reasoners would require the use of specific languages (java,c++,python) or a great deal of integration efforts (e.g., writing native code).

• Applications want to seamlessly integrate with different reasoners (i.e., reasoning mechanisms are loosely coupled with the applications) based on their needs.