central.auth.sys
====
Versioned database residing in distributed storage using SQL.
====
by Rahul Balamwar

https://linkedin.com/in/whorahul
https://hackerrank.com/whorahul

Hive was designed for centralized storage of user data orthogonal but related to the shove\_auth centralized
authentication system.  It uses git (through grit) to provide versioning and change tracking.

API
---

    >> public = Hive.new('public.hive', 'console_user')
    #=> public.inspect
    >> rahul = public['rahul']
    #=> rahul hash
    >> rahul['handsome'] = true
    #=> true
    >> rahul.save
    #=> rahul hash
    >> rahul.history
    #=> array of history items
    >> rahul.history.first
    #=> grit.commit.inspect
    >> newguy = public['newguy']
    #=> empty newguy hash
