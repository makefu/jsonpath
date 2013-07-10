# JSONPATH
A simple command line (posix shell) wrapper for 
jsonpath\_rw for python. 

And Suddenly JSON is fun (again)!

# Usage

    curl http://data.mtgox.com/api/2/BTCUSD/money/ticker_fast | ./jsonpath 'data.last.display'
    curl http://api.openweathermap.org/data/2.5/weather\?q\=London,uk | jsonpath "main.temp_max|temp_min"

for all the other cool syntax things, see [https://github.com/kennknowles/python-jsonpath-rw]
    
# Install

    pip install jsonpath_rw
    ./jsonpath
