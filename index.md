# Lab Report 4 - Vim (Week 7)

_Note: `some commands + <Enter>` means hit the enter key after typing the command._

* **Step 4: Log into ieng6:**
  
  Keys pressed: Open up a new terminal in vscode and type the command `ssh cs15lfa23bg@ieng6-202.ucsd.edu + <Enter>`.
  
  ![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/236e6458-b849-48a4-ab7b-714c4afe2cb7)

* **Step 5: Clone your fork of the repository from your GitHub account (using the SSH URL):**
  
  Key pressed: git clone the ssh URL of the provided GitHub repo by using `git clone git@github.com:Sam110120/lab7.git + <Enter>`.

  ![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/d1e69794-6dfd-4b0e-913d-91db34ec0aa4)

* **Step 6: Run the tests, demonstrating that they fail**
	
	Key pressed: type `cd lab7/ + <Enter>` into the lab7 file, then check the files by typing `ls + <Enter>`. Run the bash script by `bash test.sh + <Enter>`
	
	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/c2476310-e24a-41b1-a482-0648db302b10)


* **Step 7: Edit the code file ListExamples.java to fix the failing test**

	Key pressed: type `vim ListExamples.java` to enter the normal mode in vim.

	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/b725f558-2069-4b92-b957-fb472b5375be)

	From the lab I already know the bug is located at line 44 so I just type `:44 + <Enter>`.

	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/d89d5ff2-ec35-425b-9d96-f452df2b802e)

	
	It will jump to line 44 then by hitting the right 6 times `<right><right><right><right><right><right>`. Hit `I` to enter insert mode. Hit `<BackSpace>` to delete 1 and hit `2` to fix the bug. Then hit `ESC` to exit the insert mode and go back to normal mode.

	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/f0723e19-26cb-4936-a0bb-830e54550506)


	Then after fixing the code type `:wq + <Enter>` to save the change and exit the normal mode. It will go back to the terminal.

	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/6c2dbc34-7605-4187-8e82-41a49a45612d)


* **Step 8: Run the tests, demonstrating that they now succeed**
  
	Key pressed: type `bash test.sh + <Enter>` to run the test.

	![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/b9a799d1-f5ad-4c31-9dff-1b2bf86dc57f)


* **Step 9: Clone your fork of the repository from your GitHub account**

  Key pressed: Type `git add . + <Enter>` to add all the changes I have made. Type `git commit -m "Fix the bug" + <Enter>` to commit the changes and make a comment for this change. Type `git push` to push the request to the GitHub main repo.
  
  ![image](https://github.com/Sam110120/cse15l-lab-report4/assets/71369089/eebf09c0-2cde-40a6-b06d-338711a6c3a4)
