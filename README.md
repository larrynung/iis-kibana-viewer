# IIS log parser

This is a quick hack to parse IIS logs, since there isn't any decent standalone tool to do it.

Simply drop your logfiles to /logs directory and make sure that the modified timestamp is within one day (I was lazy to fix this in config :D)

Simply start the environment with:

    docker-compose up

And browse to the kibana interface at: http://localhost:5601
