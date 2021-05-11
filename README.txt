central.auth.sys
    by Rahul Balamwar
    https://www.linkedin.com/in/whorahul
    https://www.hackerrank.com/whorahul

== DESCRIPTION:

Versioned database residing in distributed storage using SQL. A command line tool and JDBC driver are provided to connect users.

== FEATURES/PROBLEMS:

Stores 

== SYNOPSIS:

  >> public = Hive.new('public.hive', 'console_user')
  #=> public.inspect
  >> rahul = public['rahul']
  #=> rahul hash
  >> rahul['awesome'] = true
  #=> true
  >> rahul.save
  #=> rahul hash
  >> rahul.history
  #=> array of history items
  >> rahul.history.first
  #=> grit.commit.inspect
  >> newguy = public['newguy']
  #=> empty newguy hash

== REQUIREMENTS:

* git (Built and tested with 1.5.5)
* shoulda (Bundled in vendor/shoulda)
* grit (Bundled in vendor/grit)

== INSTALL:

clone from git?

== LICENSE:

dunno
