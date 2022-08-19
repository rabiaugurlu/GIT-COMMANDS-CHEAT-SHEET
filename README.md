# GIT COMMANDS CHEAT SHEET

* Yeni bir git repository'si başlatmak: `git init`
* Üzerinde çalışılan repository’nin durumunu ve başlangıç alanını kontrol etmek: 
`git status`
* Hazırlama alanına(staging area) bir dosya eklemek:
`git add <file>`
* Tüm dosya değişikliklerini başlangıç alanına(staging area) eklemek:
`git add .`
* Dizinden ve çalışma dizininden bir dosyayı kaldırmak: 
`git rm <file>`
* Projedeki değişikleri local repository’e kaydetmek: 
`git commit `
* Kullanıcı adı ve e-posta adresi için konfigürasyon değerlerini ayarlamak: 
`git config --global user.name <your-name>`
`git config --global user.email <your-email>`
* Sıralanmamış değişiklikleri kontrol etmek: 
`git diff `
* Bir git repository'sini kopyalamak: 
`git clone <repository-url>`
* Uzak bir repository'den bir içeriği indirmek:
`git pull <remote>`
* Üzerinde çalışılan branch ile belirtilen branch'i birleştirmek: 
`git merge <branch-name>`
* Yapılan değişiklikleri uzak bir repository'e göndermek: 
`git push <remote> <branch>`
* Başka bir branch'e geçmek: 
`git checkout <branch-name>`
* Tüm local branch'leri listelemek: 
`git branch`
* Yeni bir branch oluşturmak: 
`git branch <branch-name>`
* Var olan branch'i yeniden adlandırmak: 
`git branch -m <new-branch-name>`
* Bir branch silmek: 
`git branch -d <branch-name> `
* Uzak bir repository'de yeni bağlantı oluşturmak: 
`git remote add <name> <repository-url>`
* Commit geçmişini listelemek: 
`git log `
* Dosyada yapılan değişikliği geri almak:
`git reset `
* Commit'lerin meta verilerini ve değişikliklerini kontrol etmek:
`git show <commit-hash>`
* Uzak sunucuda bulunan branch'lerin bilgisini local'e indirmek:
`git fetch `
* Gereksiz dosyaları temizleme ve local repository'i optimize etmek: 
`git gc` 
* Bir şey yapılmamış değişiklikleri kaldırmak ve daha sonra kullanmak için kaydetmek: 
`git stash`
* Önceden kullanmak için kaydedilen değişiklikleri yeniden uygulamak: 
`git stash apply`

## Author
* **Rabia Uğurlu** - [rabiaugurlu](https://github.com/rabiaugurlu)
