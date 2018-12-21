`virtualenv -p /Users/havok/anaconda3/bin/python3 my-venv`

`. my-venv/bin/activate`

_grpc using python_

### To setup

`install grpcio`

- _compile the .proto file_
  `python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. drone.proto`

- _to run the server.py_
  `python server.py 0,0,0 10,0,0`

- _to run the client.py_
  `python client.py 3000`
