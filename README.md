# folder name: local_chain
# network: pupperadmin1

## setting up a network:  --network=pupperadmin1
network chain id: 787

Running node1:
./geth --datadir node1 --unlock 0x77e25AaA89B10255e59E5aF4e2F273642CdEBD0f  --mine --rpc --allow-insecure-unlock

Running node2:
./geth --datadir node2 --unlock 0x3b49f3d4C2a2500E4af5f7AE3549615C3d10CbEb --mine --port 30304 --bootnodes " enode://d43f7af719eddcb29af12be710d1f4ee96297f31e56027a2b0fa6cbf2db55a2b61c4d8ea3a729839dd6f790e802f61336592fc8128f3a712e130f0b682a21aba@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock


