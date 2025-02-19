<h2 align=center>PoP mining within Hemi Network</h2>

## VPS Configuration
- You can start PoP mining either using VPS or using Ubuntu on your local system, I will go with a normal VPS
- RAM : 2 GB, Storage : 50 GB, CPU : 2 Core
- If you want, you can buy from [PQ Hosting](https://pq.hosting/?from=622403&lang=en) using crypto currency

## Installation
```bash
[ -f "hemixyz.sh" ] && rm hemixyz.sh; wget -q https://raw.githubusercontent.com/dxzenith/PoP-Mining/main/hemixyz.sh && chmod +x hemixyz.sh && ./hemixyz.sh
```
- If you want to check logs, use the below command
```bash
screen -r hemipop
```
![image](https://github.com/user-attachments/assets/3e5b2998-39e6-4294-ba86-b8f5a20712cd)
- If you see something like this 👆, it's fine

![image](https://github.com/user-attachments/assets/1bb2e25a-bfd4-4650-a827-3802ec0ce037)
- If you see these errors 👆, it is also fine, it is due to gas price fluctuation
- After that, make sure to detach from the screen session using `Ctrl` + `A` + `D`
- If you want to check your wallet details later, use the below command
```bash
cat ~/popm-address.json
```
## Reward
- Hemi network team directly did not announce any reward for this but you will earn 1 tHEMI for each transactions. May be in near future, team will give reward to active PoP miners one the basis of tHEMI
- You can check how many tHEMI you have collected so far using this [block explorer](https://testnet.explorer.hemi.xyz/)

![image](https://github.com/user-attachments/assets/af5fcf19-167b-44e8-b271-dc52363cdda4)

## Issue
- If you face any issue join my channel, ask there : [Link](https://t.me/ZuNXBT)
