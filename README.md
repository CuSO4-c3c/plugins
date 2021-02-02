# Plugins for c3cbot 0.x
tải source code về rồi bỏ vào folder plugins trong file bot
# Cách cài trên Windows/macOS/Linux(máy tính)
Tải source code dưới dạng file .zip, giải nén bỏ vào folder plugins.
# Cách cài trên Termux 
Vào termux, gõ < ./start-ubuntu.sh > để vào ubuntu.
Sau đó, paste dòng lệnh sau vào:
< cd ~/c3c && mv plugins/nodemodules/ ~/nodemodules && rm -r plugins && git clone https://github.com/CuSO4-c3c/plugins && mv ~/nodemodules ~/c3c/plugins/nodemodules && cd ~/c3c > (trong gói plugins này chưa có folder nodemodules)
