# Git Komutları

## git add
Değişiklikleri staging area'ya ekler.

## git commit
Hazırlanan değişiklikleri Git geçmişine kaydeder.

## git push
Yerel commit'leri uzak repository'ye gönderir.

## git commit ve git push arasındaki fark

git commit, değişiklikleri bilgisayarımızdaki yerel
Git geçmişine kaydeder.

git push ise yerel commit'leri GitHub'daki
uzak repository'ye gönderir.

### Örnek

Bir README dosyasını güncellediğimizi düşünelim.

git add README.md
git commit -m "docs: update README"

Bu aşamada değişiklik yalnızca yerel Git geçmişindedir.

git push

Bu komuttan sonra commit GitHub'a gönderilir
ve takım arkadaşlarımız değişikliği görebilir.