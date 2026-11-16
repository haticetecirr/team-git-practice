# Git Branch Kullanımı

## Branch Nedir?
Branch, bir projede ana kodu etkilemeden ayrı bir geliştirme alanında çalışmamızı sağlar.

## git branch
Mevcut branch'leri listeler ve yeni branch oluşturmaya yardımcı olur.

## git switch
Branch'ler arasında geçiş yapmak için kullanılır.

## git merge
Bir branch'teki değişiklikleri, üzerinde bulunulan başka bir branch ile birleştirir.

Örnek:

```bash
git switch main
git merge feature/member-two
```

Bu örnekte önce main branch'ine geçilir. Ardından feature/member-two branch'indeki değişiklikler main branch'i ile birleştirilir.

## Pull Request
Yapılan değişikliklerin incelenmesini ve ana projeye eklenmesini talep eder.