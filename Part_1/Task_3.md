### ** Task 3: Create a File and Make Multiple Commits**
1. Create a new file and add content: 
   ```bash
    echo "My First Project" >README.md
    ```
    This will create a new file called README with a text My First Project written in it.
    

2. Stage the file:
    ```bash
   git add README.md
   ```
    This will stage the README file for the next commit

   

3. Commit the file:  
   ```bash
   git commit -m "Initial commit: Added README.md"
   ```
   This will commit a README file with the meaningful commit statement.


4. Make changes to the file:  
   ```bash
   echo "Added a description" >> README.md
   ```
   This will add a new line to README file with some different text.


5. Stage and commit the changes:  
   ```bash
   git add README.md
   git commit -m "Updated README with a description"
   ```
   This will commit the change to README file with a meaningful commit statement
   
