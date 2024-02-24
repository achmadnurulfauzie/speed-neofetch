
curl -LO https://raw.githubusercontent.com/achmadnurulfauzie/speed-neofetch/main/neofetch-speedtest.sh

sudo chmod +x neofetch-speedtest.sh

./neofetch-speedtest.sh

neofetch --cpu_brand on --cpu_cores logical --cpu_speed on --cpu_temp C --gpu_brand on  --gpu_type all --disk_show '/' --memory_percent on
