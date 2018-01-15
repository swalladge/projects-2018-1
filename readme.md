This is the project repository for group 1.

Before running the server, you must create the database:
  1. Open powershell in projects-2018-1
  2. cd database
  3. python setup.py
  4. cd ..
  5. python server.py

If you want support for the chatbot, you must install `apiai` on the server
computer: `pip install --user apiai`.

Warning: only compatible with Python 3. Check output of `pip --version` and
`python --version` to make sure. `pip3` or `python3` may need to be used instead
in the required commands.
