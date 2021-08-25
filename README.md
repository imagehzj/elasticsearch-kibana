# beats
## usage
### metricbeat
#### run
```bash
docker run --network=host --volume="/var/run/docker.sock:/var/run/docker.sock:ro" --volume="/sys/fs/cgroup:/hostfs/sys/fs/cgroup:ro" --volume="/proc:/hostfs/proc:ro" --volume="/:/hostfs:ro" -it ttbb/metricbeat:nake
```