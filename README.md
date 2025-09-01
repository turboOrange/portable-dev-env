# portable-dev-env
A portable environement with everything I usually use to develop. The idea is that I can pop up on a random computer and start developing. 
docker run -it -p 2222:22 \
  -v $HOME/.ssh:/home/dev/.ssh \
  -v /path/to/code:/home/dev/work \
  dev-env
ssh dev@localhost -p 2222
