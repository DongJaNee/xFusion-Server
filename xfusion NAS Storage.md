## 초기 세팅
- UTP 케이블을 SAN 스토리지에 연결, 네트워크 연결에 접속하여 IP대역을 192.168.128.x대역으로 설정하고 내 컴퓨터 이더넷 대역도 동일하게 맞춘다.
- URL 주소에 192.168.128.101:8088 / 192.168.128.102:8088 접속 

## File Service 

<img width="1894" height="955" alt="image" src="https://github.com/user-attachments/assets/05d38720-0b16-4f89-8dcb-9465f6e6a795" />

## Storage Pool

<img width="1002" height="610" alt="image" src="https://github.com/user-attachments/assets/131b82b3-f9b9-44b2-8b5d-44d3827aaba6" />

## File Systems

<img width="1000" height="610" alt="image" src="https://github.com/user-attachments/assets/d75e278a-32ac-4e84-99ae-87b79c6efb30" />

### 순서 
1. 스토리지 풀 생성
2. 파일 시스템 생성
2-1. Share 생성 (no root squash)
3. logical port 생성
