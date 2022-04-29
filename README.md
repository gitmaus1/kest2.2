# kest2.2
<h1>13.2.3.7 Bitlocker and Bitlocker To Go</h1><br>


Why is it important to save a BitLocker recovery key?<br>
Type your answers here.<br>

annars er hætulegt að tapa likilorðinu<br>






When the computer restarts you will be prompted to enter your password to unlock the computer.
Question:
What is the function of a TPM in relation to BitLocker?<br>
Type your answers here.<br>

það stjórnar virkni bitlocker<br>


<h1>13.3.2.5 Configure Windows Local Security Policy</h1><br>

a. According to the security policy in Step 1, how many times is a user allowed to attempt to login before the
account is locked?<br>
Type your answers here.<br>


5<br>

b. How long should the user have to wait before attempting to log back in?<br>
Type your answers here.<br>

5 mínotur<br>




b. Although none of the security settings need to be modified to meet the security policy requirements,
spend some time viewing the default settings.
Question:
Are there any you would recommend changing? Why?<br>
Type your answers here.<br>





mere finst að ekki allir ætu að geta conectað við tölvuna over network

bypass traverse checking allir geta það í defolt það gæti valdið vandamálum <br>

mere finst að mikeð af default stilingum gefi of mikin aðgáng sestaklega fyrir fyrirtæki





<h1>13.3.3.6 Configure Users and Groups in Windows</h1><br>





b. In the Local Users and Groups Manager, select the Users folder.
Question:
What are the names of the accounts listed?<br>
Type your answers here.<br>
adfgh, Administrator, aefgrwer, agust, asdf, asdfaf, asdfaf, asdfgh25, assass, ast, DefaultAccount Properties, fhddfhdfh, guest, kytfyuofuti, nafn, nanana, WDAGUtilityAccount Properties<br>



c. Select the Groups folder. Name five groups from the list.<br>
Type your answers here.<br>

Administrators, Guests, Users, Replicator, Power Users<br>


d. Click the Users folder. Right-click your account and select Properties. Click the Member Of tab.
Question:
Which group does your account belong to?<br>
Type your answers here.<br>

Administrators<br>


Question:
What is Student01 required to do when logging in the first time?<br>
Type your answers here.<br>

nota passwordið ef það er stillt þanig þarf hann að búa til nít password



Double-click Student01. Unselect the User must change password at next logon.
Question:
What group does Student01 belong to?<br>
Type your answers here.<br>

Users<br>



f. Click the Groups folder. Double-click the Users group.
From the description, can the members of the Users group make system wide changes? What can the
Users group do on the computer?<br>
Type your answers here.<br>

geta ekki make system wide changes en geta notað flest applications<br>

Who are the group members?<br>
Type your answers here.<br>


asdfgh25, kytfyuofuti, NT AUTHORITY\Authenticated Users (S-1-5-11), NT AUTHORITY\INTERACTIVE (S-1-5-4), Student01<br>

d. Create a new user account using the name Test and password cisco12345.
Question:
Were you successful in creating the new account? Explain.<br>
Type your answers here.<br>



no an error gerðis Access is denied Users hafa ekki leifi til að búa til nía users<br>




e. Navigate to www.cisco.com using a web browser.
Question:
Were you able to navigate to www.cisco.com? Explain.<br>
Type your answers here.<br>




já Users geta notað netið Addmin getur breit stillingum og leifum<br>



e. In the Select Users or Groups window, enter ITEStaff under the heading Enter the object names to
select. Click Check Names for verification. Click OK to continue.
Question:
With the group ITEStaff highlighted, what can the members do in this folder?<br>
Type your answers here.<br>



Read & execute, list folder contents, read<br>




f. Repeat the same procedure to add permissions for the group ITEStudent. In addition, the members of
this group should have full control of this folder.
Question:
Which additional checkbox would you select?<br>
Type your answers here.<br>





Full control<br>




b. Navigate to the folder C:\Students. Create a folder named Student02 and create a text document in the
folder.
Question:
Were you successful? Explain.<br>
Type your answers here.<br>





yes ég gat það <br>


c. Navigate to the folder C:\Staff. Create a folder named Student02 and place a text file in the folder.
Question:
Were you successful? Explain.<br>
Type your answers here.<br>



yes ég gat það en það er auðvelt að koma í veg fyrir það með að nota deny<br>




e. Navigate to C:\. Can you place a text file in the Staff folder? Can you modify the text file in folder
Student02? Explain. (Note: A reboot may be necessary for Windows 8.1 to enable the change in file and
folder permission.)<br>
Type your answers here.<br>


já<br>



l. Navigate to the folder C:\Students.
Question:
Are you able to access the content in the Student01 and Student02 folders? Explain.<br>
Type your answers here.<br>



ég get notað anað en ekki hit út of deny stilingum<br>


n. Navigate to the folder C:\.
Question:
Were you able to access the content in the folders Staff, Student\Student01 and Student\Student02?
Explain.<br>
Type your answers here.<br>





já staff hefur aðgáng að þeim öllum<br>




Question:
Can you log on as Staff02? Explain.<br>
Type your answers here.<br>


no acountið er disabuld<br>




1. How would you give administrative privileges on the local computer to all the members of ITEStaff?<br>
Type your answers here.<br>


bæta ITEStaff í Administrator<br>



2. How would you deny access to a file for everyone except the owner?<br>
Type your answers here.<br>





fara í properties og gefa nodenda aðgáng og denya aðgang á alla aðra

