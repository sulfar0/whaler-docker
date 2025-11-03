'''
sudo flatpak install --system flathub com.github.sdv43.whaler
'''


tambahkan di kedua file subuid dan subgid dibawah dengan
your_username:165536:65536

```
nvim /etc/subuid
```

```
nvim /etc/subgid
```

lalu jalankan command dibawah dalam keadaan user
```
export DOCKER_HOST=unix://$XDG_RUNTIME_DIR/docker.sock
```
