# pandas-zmq

Communicate Pandas DataFrame over ZeroMQ connection

## API

```
send_dataframe(socket, dataframe, flags=0)
```

```
recv_dataframe(socket, flags=0)
```

### Server

```
import pandas_zmq

# ...
pandas_zmq.send_dataframe(socket, df)
```


### Client

```
import pandas_zmq

# ...
pandas_zmq.recv_dataframe(socket, df)
```
