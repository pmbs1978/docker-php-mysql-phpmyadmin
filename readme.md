1) clone the repository
2) adjust the defenitions according the needs, if necessary create data directory to mysql volume
3) run docker compose build
4) run docker compose up or docker compose up -d
5) run docker compose down or docker compose -v to delete volumes

6) to backup data directory run sudo chown -R ${USER}:${USER} data *** to change the owner of data folder