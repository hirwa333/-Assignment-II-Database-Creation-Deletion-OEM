Hirwa Roy ID: 24174
Assignment II: Database Creation, Deletion & OEM
1: Create a New Pluggable Database (PDB)
Objective: Create a PDB for storing class work.
SQL Commands and CMD Output:


<img width="975" height="230" alt="image" src="https://github.com/user-attachments/assets/4b8eb1fa-2abe-47c9-9732-d4bfc0ed5749" />
<img width="975" height="702" alt="image" src="https://github.com/user-attachments/assets/53c4cba7-632b-47bc-8676-3042b0a8bd81" />


Explanation:
•	plsql_class2025db → Name of the new PDB
•	roy_plsqlauca_24174 → Your PDB admin user
•	Password: Roy@123
•	Default tablespace: users

2: Create and Delete a PDB
Objective: Practice creating and deleting a PDB.
SQL Commands and CMD Output:


 <img width="975" height="721" alt="image" src="https://github.com/user-attachments/assets/c737fe69-de91-466c-9828-5a8a3f0a30d1" />

 
Explanation:
•	ro_to_delete_pdb_24174 is created temporarily for deletion practice
•	INCLUDING DATAFILES removes all associated files

Task 3: Oracle Enterprise Manager (OEM)
Objective: Configure OEM to monitor PDBs.
CMD Simulation for OEM:


 <img width="975" height="565" alt="image" src="https://github.com/user-attachments/assets/086d76fd-5552-4c02-a7f6-f547e659e227" />

Explanation:
•	Shows OEM is running
•	PDB plsql_class2025db is active
•	Deleted PDB no longer listed



