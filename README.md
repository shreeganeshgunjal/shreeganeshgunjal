- 👋 Hi, I’m @Ganesh Gunjal
- 👀 I’m interested in coding
- 🌱 I’m currently learning

<!---
shreeganeshgunjal/shreeganeshgunjal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#include <stdio.h>

IMT MAIN

{

Printf("Hello Self"),

return0,

};




import sqlite3

# Connect to database (creates it if it doesn't exist)
conn = sqlite3.connect('example.db')

# Create a cursor object to execute SQL commands
cur = conn.cursor()

# Create a table
cur.execute('''CREATE TABLE IF NOT EXISTS users (
                id INTEGER PRIMARY KEY,
                username TEXT,
                email TEXT
            )''')

# Commit changes and close the connection
conn.commit()
conn.close()
