go list -m -verions [Module] = ใช้เพื่อ list version ของ Module ที่สามารถใช้ได้

go get [Module] = เป็นคำสั่งเพื่อ Download dependency สัมพันธ์กับ version ของ Semver

go get -u [Module] = เป็นคำสั่งเพื่อ Update dependency

go mod init [project name] = สร้าง Module go

go mod tidy = ดิดตั้ง Package

go get -u [Module] = update pageage **ถ้าไม่ใส่ Module pageage ก็จะอัปเดตทั้งหมด