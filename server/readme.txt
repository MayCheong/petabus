This readme file stores version information as well as
features and changelogs. pls keep this up to date whenever
you commit.

use pip3 (python3-pip) to install the following modules
flask
flask_wtf
flask_sqlalchemy
flask_bootstrap
flask_login
flask_admin
flask_io

changelogs formatting
update<N>	<date:DD/MM/YY>---<time>
+	new updates
-	bug fixes
$	suggested
TODO:	todo
*	notice
>	additional notice


*Please format your updates accordingly so that we can view the changes
*easily. also comment on the code and functionality of some lines
*for labels of R1 - R9, they're are of the previous version of pyFlask
*please ignore. we will use U0 - Un to denote versions for this system

------------------------------------------------------------------------------------
---------------------------------CHANGELOGS-----------------------------------------

update0		8/12/18---1:22pm
[+	ported old pyflask server to setup petabus
[	  >ported useradd/userlist/usermod
[ 	>ported home
[   >ported admintools
[   >ported models/sqlite engine
[+	initialized git repo
[+	added new pkg architectures
[	  >source.py to provide the flask object
[   >introduced blueprinting, refer to flask
[   >introduced seperate wrapper files
[	  >flim.py renamed to limits.py
[   >const.py added to store constant vals
[	  >old changelogs can be viewed at pyFlask_old.txt (from pyflask)
[$	new db models
[$  revamp templates structure

update1   12/12/18---11:04pm
[+  ported flog.py from old pyflask to servlog.py
[+  added finally: clause in server.py (main)
