Согласно теореме CAP:
1) DragonFly использует shared-nothing architecture и обеспечивает атомарность всех операций. Поэтому мы можем ее отнести к базам данных CP типа. 
2) ScyllaDB относится к системам AP. Как пишут сами разработчики:
    >ScyllaDB chooses availability and partition tolerance over consistency, such that:
  
    >It’s impossible to be both consistent and highly available during a network partition;
  
    >If we sacrifice consistency, we can be highly available.
3) ArenadataDB относится к системам CP, так как это распределенная транзакционная СУБД.
