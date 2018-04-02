Used command-line
-----------------
    ::

        $ mkdir batch_file_rename
        $ cd batch_file_rename
        $ python3 -m venv myvenv
        $ git init
        $ vim ../.gitignore
        # amend with :
        #    *.pyc
        #    *~
        #    __pycache__
        #    db.sqlite3
        #    .DS_Store
        #    csv/
        #    myvenv
        $ git config --global user.name "Yevgueny KASSINE"
        $ git config --global user.email ykassine@geekadomicile.com
        $ git remote add origin https://github.com/geekadomicile/batch_file_rename.git
        $ git add --all
        $ git commit -am "Init"
        $ cd myvenv
        $ . bin/activate
        $ pip install --upgrade pip
        $ git status
        $ git push -u origin master

