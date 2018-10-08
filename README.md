# MultiMiner-Config

Configuration for MultiMiner

#### Go to settings

#### Add Coin

Script: Cryptonight

Coin: Lonero (LNR)

#### Use the getting started wizard or pool config

#### Add a pool that has Lonero or the seed node

stratum+tcp://142.93.171.115:34414

#### Workername: LNR Address

#### Password: x

```
//setup a pool
        MiningPool pool = new MiningPool()
        {
            Host = "142.93.171.115, // This is just a sample, please use an actual host for your own pool
            Port = 34414,
            Username = "WorkerAddress",
            Password = "x"
        };
```
