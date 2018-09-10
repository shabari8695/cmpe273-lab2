# cmpe273-lab2
Lab 2 for CMPE 273

#### To generate the proto file output use the following :
python3 -m grpc_tools.protoc -I . --python_out=. --grpc_pythoout=. calculator.proto

#### How it works :
client sends two numbers as arguments to the server
server returns back the sum of the two numbers entered
