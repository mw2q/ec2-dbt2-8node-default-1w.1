Tue Aug 25 12:20:32 EDT 2015

Linux pgxl 3.10.0-229.el7.x86_64 #1 SMP Thu Jan 29 18:37:38 EST 2015 x86_64 x86_64 x86_64 GNU/Linux
Command line: /usr/local/bin/dbt2-run-workload -a pgsql -c 10 -w 1 -d 900 -n -p -c shared_buffers=8GB -c effective_cache_size=20GB -c work_mem=1GB -c default_statistics_target=1000 -c log_checkpoints=on -c log_line_prefix='%t [%p]: [%l-1] user=%u,db=%d,app=%a,client=%h ' -c log_lock_waits=on -c log_temp_files=0 -c max_prepared_transactions=100 -c shared_queue_size=8192 -c max_wal_size=128GB -c checkpoint_timeout=900 -c max_connections=100 -o /home/mark/results/ec2-dbt2-8node-default-1w.1
RDBMS: pgsql
Database Name: dbt2
Database Scale Factor: 1 warehouses
Test Duration: 900 seconds
Database Connections: 10
