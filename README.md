---------------------------------------------
ACTIVE Version 2.2  Auto start termux 
---------------------------------------------

pkg install git -y

git clone https://github.com/creativeHHD/begin

cd begin

sh begin.sh

--------------------------------------------------------
        โปรแกรมจะเปิด login ubuntu อันโนมัติ  กด PGWN ที่มือถือเพื่อให้อยู่บรรทัดสุดท้าย แล้วแทรกคำสั่งด้านล่าง
-----------------------------------------------------

proot-distro login ubuntu

บันทัก แล้วออกจากโหมด รอขึ้น root แล้วพิมพ์คำสั่งต่อไป

apt-get update

apt-get install git -y

git clone https://github.com/creativeHHD/actives

cd actives

sh setup.sh

ในระหว่างการทำงาน โปรแกรมจะถามให้กรอก โซนประเทศ ให้เลือก 6 (Asia)  และ โซนเวลา เป็น 12 (bangkok)

------------------------------------------
      ระบบจะเปิดไฟล์ bash.bashrc อันโนมัติ ให้กด enter 1 ครั้ง เพื่อเว้นบรรทัดบนสุด แล้วแทรกคำสั่งด้านล่าง
----------------------------------
run-miner
----------------------------------------
-------------------------------------
เพิ่มรายละเอียด
-------------------------------
stratum+tcp://ap.luckpool.net:3956

RHq9fSNPPXraAVQnq3SkNqgzrnADwGbvru.HDNote51

รหัสผ่าน lockpool ให้ใส่ x 

รหัส hybrid ให้ใส่ hybrid

ระบุจำนวน CPU 1-8 core

--------------------------------------------------------
