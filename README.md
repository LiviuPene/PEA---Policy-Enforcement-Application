# PEA - Policy Enforcement Application
PEA implements the elements of the Framework for Policy Enforcement (FPE). Given a computer network system, no matter how complex, PEA allows you to build the network topology, generate the network specification using a dedicated calculus, specify policies with a modal logic, and calculate required enforcements based on quotient operator formulas.

The application was developed in Java using Eclipse, with Swing libraries being used for the GUI development. The architecture of our application contains three modules that implement the elements of FPE. One module translates topology information into an interprocess algebra-based specification. The second module is used for defining system security policies with logical formulas. Enforcement calculations are performed by the third module. Since we used Eclipse, it is easy to extend the application by adding new modules. The addition of libraries of other elements (services, other network hardware, etc.) is also straightforward. The internationalization feature of Java allows interface components (menu items, labels, etc.) to be defined in your language of choice. Currently, there are English and French versions of the application. The software and the complete code are vailable under GPL license.

The interface is intuitive and easy to use. The system’s topology is built by simply dragging predefined elements (computers, routers, firewalls, etc.) into the main window of the GUI. Associated details such as ambient names and keys, or processes, can be added as properties of the elements via a context-aware box. Once the components have been inserted, a dedicated button can be used to connect them by pointing to the ends of the link.

The network specification for the system built is displayed at the bottom of the main window. Any change to the topology or process details is automatically applied to the specification. All applicable process reductions are also taken into account and are transparently performed in the background.

Systems built with the aid of the application can be modified, copied, exported to XML files and imported for re-utilization. Links between components can be added and removed through a simple right-click. Parent-child ambient relations can be changed via drag-and-drop. Ambient names, keys, interfaces, and process details are easily defined through the graphical interface.

PEA also allows specifying security policies by using a GUI-style method. The policy is displayed both in logic formulas format and as an XML style structure showing the components.

The main window displays the topology and system specification. If the policy window, showing the logic formulas, is also open, one can calculate the necessary enforcement to be applied to the system. The quotient button permits the automated generation of an adequate enforcement.

The application is the first step in our effort to obtain automatic enforcements for the implementation of desired security policies. It can be employed for various network simulations: system design, policy verification, disaster recovery scenarios, etc.
