unique flower library for independent study project.

server: `source ./venv/bin/activate `
Don't forget to run 
`pip3 install git+https://github.com/akirato0223/flower.git -U`
before 
`python3 server.py --server_address 10.197.152.62.6000 --rounds 3 --min_num_clients 1 --min_sample_size 1 --model Net`



Clients: Install flower(this repo) from dockerfile

Jetson: `./run_jetson.sh --server_address=10.197.152.62:6000 --cid=0 --model=Net`

Raspberry Pi: `./run_pi.sh --server_address=10.197.152.62:6000 --cid=0 --model=Net`


