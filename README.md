Flight Ticket Search Engine
Overview
Welcome to the Flight Ticket Search Engine, an advanced tool created to assist users in finding customized and cost-effective travel itineraries. This application, built using the Clojure programming language, is designed to meet the varied requirements of our customers. It provides a smooth and effective method for locating the ideal flight schedule.
Features
1.	Personalized Search: Enter precise parameters such as the city of departure, desired destination, and relevant passenger information to customize your trip arrangements.
2.	Budget-Conscious Options: Find travel arrangements that are in line with your financial limitations, guaranteeing cost-effectiveness.
3.	Connection Constraints: Discover flights that align with your desired number of connections to enhance your trip journey with greater ease and convenience.
4.	Sorting by Total Price: Search results are arranged in descending order based on the total price, giving priority to solutions that are more expensive but perhaps more convenient.
5.	Interactive User Interface: Experience a seamless search process with a UI that is both user-friendly and interactive.
6.	Customer Feedback Loop: We value your input! The search engine continuously evolves based on your feedback, ensuring a platform that meets your expectations.

Technical Overview
The aircraft ticket search engine is constructed using a micro services architecture, making use of the functional programming features of Clojure. The search algorithm employs a Depth-First Search (DFS) methodology to uncover travel itineraries, taking into account budgetary and connectivity limitations for various categories of passengers.
Getting Started
Follow these steps to get the flight ticket search engine up and running on your local machine:
1.	Clone the Repository:
o	git clone [repository-url] 
o	cd flight-ticket-search-engine 
2.	Install Dependencies:
           # Assuming you have Leiningen installed 
o	lein deps 
3.	Run the Application:
lein run 
4.	Access the UI: 
o	Open your web browser and go to http://localhost:3000 to access the user interface.

Contributing
We welcome contributions from the community! If you'd like to contribute to the flight ticket search engine, please follow our Contribution Guidelines.
Issues and Feedback
At the moment, the program cannot gracefully handle invalid inputs (such as non-existent cities or negative budget values) or missing fields in the dataset.
References
•	Higginbotham, D. (2015). Clojure for the Brave and True: Learn the Ultimate Language and Become a Better Programmer. No Starch Press. ISBN: 9781593275914. Url: https://books.google.cz/books?id=mQLPCgAAQBAJ
•	Meier, C. (2015). Living Clojure: An Introduction and Training Plan for Developers. O’Reilly Media. ISBN: 9781491909294. URL: https://books.google.cz/books?id=b4odCAAAQBAJ.
•	McDonnell, M. (2017). Quick Clojure. Effective Functional Programming. ISBN: 9781484229521. URL: https://rb.gy/wmvbfh
•	Karumanchi, N. (2011). Data Structures and Algorithms Made Easy: Data Structure and Algorithmic Puzzles. CareerMonk Publications. ISBN: 9780615459813. URL: https://books.google.cz/books?id=FPIznwEACAAJ
•	Rathore, A. (2015). Clojure in Action. ISBN: 9781638355335. URL: https://rb.gy/esew7a
•	Naccache, R. (2015). Clojure Data Structures and Algorithms Cookbook. ISBN: 9781785287824. URL: https://rb.gy/eipm95

License
 This Search Flight Ticket Engine is licensed under the Eclipse Public License 2.0. See the LICENSE file for more details.
