Rule of Database.
******* config.php file in update database parameters *******
1. include_once 'database/run.php';
2. $db = new Database;
3. db->insert('table', ['fname'=> "nitin", 'lname'=> "rathour", 'email'=> 'workinfoanalysis@gmail.com']);
4. db->update('table', ['lname'=> "sharma"], 'lname = "kumar"');
5. db->delete('table', 'id = "47"');
6. db->sql('SELECT * FROM useremail');
7. db->select('table', '*', null, null, null, "2");
8. db->pagination('table', null, null, "2");
9. db->tableExists('table');
10. db->tableList();
11. db->getResult();
