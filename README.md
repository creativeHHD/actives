# AUTO RUN CCMINER IN TERMUX

pkg install git -y

git clone https://github.com/creativeHHD/begin

cd begin

sh begin.sh

PGDN ไป บรรทัดท้ายสุด พิมพ์

proot-distro login ubuntu

แล้วเซฟ ออกจาก termux แล้วเข้าใหม่ จะเข้าโหมด ปฏิบัติการของ termux แล้วพิมพ์

---------------------------------------------------

apt-get update

apt-get install giy -y

git clone https://github.com/creativeHHD/actives

cd actives

sh setup.sh

หากเข้ากระบวนการเลือก ประเทศ ให้เลือก 6 (asia) และ 12 (bangkok)

เมื่อเด้งให้กรอกข้อมูล ในหน้า bash.bashrc ให้เว้นช่องข้างบน 1 ช่องแล้วกรอก

run-miner

ระบุ pool waller password cpu 
