# ase2json_py

This Python program downloads the MTA:SA server list from [https://master.multitheftauto.com/ase/mta/](https://master.multitheftauto.com/ase/mta/) and parses it, extracting the list of servers to JSON. The data provided by the master server is in a format similar to ASE ([All-Seeing Eye Protocol](https://int64.org/docs/gamestat-protocols/ase.html)).

There are no dependencies. The only requirement is Python 3+. Normal usage: `python masterlist.py`.

You can use it to quickly search for a specific server using `python masterlist.py <ip> <port>`.
