# active-directory-lab

Bu repo, Windows Server üzerinde kurduğum kişisel lab ortamında Active Directory (AD DS) kurulumunu ve temel yönetim işlemlerini göstermektedir.

## Ortam
- Hypervisor: VMware
- İşletim Sistemi: Windows Server 2019
- Domain: dnc.com

## Kurulum Adımları
1. Windows Server kurulumu
2. AD DS rolünün eklenmesi
3. Sunucunun Domain Controller'a yükseltilmesi
4. Yeni forest oluşturulması (dnc.com)

## Yapılan Çalışmalar
- Kullanıcı oluşturma (örnek: 10 kullanıcı)
- Grup oluşturma (IT, Satış)
- OU (Organizational Unit) yapısı kurma
- Kullanıcıları gruplara atama
- Temel GPO ayarları:
  - Şifre politikası
  - Desktop kısıtlaması

## Ekran Görüntüleri
![Active Directory](İmages/ad-1.png)
![Active Directory](İmages/ad-2.png)
![Active Directory](İmages/ad-3.png)
![Users](İmages/users.png)
![GPO](İmages/gpo-1.png)
![GPO](İmages/gpo-2.png)
![GPO](İmages/gpo-3.png)

## Öğrendiklerim
- Domain yapısının mantığı
- Kullanıcı ve yetki yönetimi
- GPO ile merkezi kontrol

## Not
Bu çalışma gerçek ortam değil, kişisel lab ortamında yapılmıştır.
