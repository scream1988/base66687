# base66687
Monitoring Bridge Events
logs = bridge.events.DepositInitiated.createFilter(fromBlock="latest")
print(logs.get_new_entries())
