# Git

**Gitda 3 ta qisim bor**: Working area -- Staging area -- Committed

- Working area
  
  git init   

git status    #faqat Working va Staging area larni ko'radi
git add .   (path)   #Staging area
git rm --cashed file-name or .

git config --global user.name "Your name"
git config --global user.email "your_email@gamil.com"
check
git config --global user.name
git config --global user.email

git commit -m "message_name"  Committed area

git log
git log --oneline

git restore file-name # bu kodega o'zgartitish kiritilgandan so'ng 1 ta oldingi commitga qaytarish uchun ishlatiladi.

git commit -am "message_name"  # bu komanda 1 vaqtda ham add qiladi va commit qiladi



Git branches

git branch # branchlar ro'yhatini ko'rsatadi. Qaysi branchda turganini * bilan ko'rsatadi 
git branch branch_name # qandaydur nom bilan branch yaratish
git branch -a  # barcha branchlarni ko'rsatadi
git branch -D branch_name  # branchni o'chirish
git checkout branch_name  # branchga o'tish
git checkout -b branch_name  # bu agar yo'q branch bo'lsa ham uni yaratib keyin unga o'tadi, agar bor bo'lsa xatolik beradi

"HEAD" da commit bo'yicha qaysi branchga qarab turgani ko'rinadi


Branchlarni birlashtirish

git marge branch_name

Misol feature branchni main branchga birlashtirishmoqchi bo'lsam,
main branchga o'taman va marge qilib feature branchni birlashtirvolaman.
