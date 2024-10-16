## SingleOS
I want to make an Operating System based on Linux Kernel. Focus on security and privacy just like smart phone OSes, android or iOS.

### Design Goal
- Isolation

Currently, PC OSes have bad isolation for user mode programs, including windows, MacOS and Linux distro OSes etc. No one will create a new user for each program for isolation. Just use all the programs in the same user. Then every program can read the program data of others. Some bad programs will stolen chrome's or firefox's saved history, passwords etc. That isn't the case on smart phone OSes. Each app on android or ios has isolated envirenment and can not access data out of self.

- Simple

Most people just use PC OSes as single user. That is the name of PC, Personal Computer. So why not just provide single user and simplify the implementation of OS. And use other method to handle isolation. Most users don't care if the OSes is single user or multi-user OS. We can't add new user on iOS, but it just OK. iOS still the one of the most pupular OSes on smart phone.

- Static

SSD is much cheaper nowadays. Shred libs cause many problems and time consuming to handle. So just build static kernel and static user program. Programming language like golong only provide static output. Good point.

- Tidy

Many programs save their data or resources everywhere. It's a big mess to handle when delete or backup these programs and their data. Package management like apt and dpkg are useless if the data is not from the package itself. Like new files created when the program running.
