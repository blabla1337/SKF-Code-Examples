
Debug Enabling
-------

**Example:**

    """
    Debug mode makes it a major security risk and therefore it must never be used on production machines. It may even lead to execution of arbitary code.
    """

    #In Linux machines, never export the environment variable FLASK_DEBUG to 1
    $ export FLASK_DEBUG=0
    $ flask run

    #On Windows you need to use set instead of export

    #Even with python you can enable debug mode
    app.debug = True
    app.run(debug=True)