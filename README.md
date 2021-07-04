## NAMA     : RIZKI ILHAMI
## KELAS    : TI.19.B.2
## NIM      : 311910424

## BACKUP DAN RESTORE

# Masuk database dan show table

![table](https://user-images.githubusercontent.com/81584642/124391701-110fc100-dd1c-11eb-995f-e94edca045f9.JPG)

# proses backup dan recovery dengan sql

![lock](https://user-images.githubusercontent.com/81584642/124391699-10772a80-dd1c-11eb-91b9-e1217cdda0a5.JPG)

![bckup](https://user-images.githubusercontent.com/81584642/124391690-0c4b0d00-dd1c-11eb-84c8-9724d6395233.JPG)

![del](https://user-images.githubusercontent.com/81584642/124391695-0ead6700-dd1c-11eb-8aad-12e6ceccf553.JPG)

![cekdel](https://user-images.githubusercontent.com/81584642/124391693-0d7c3a00-dd1c-11eb-8d79-2278a8c7ec34.JPG)

![restore](https://user-images.githubusercontent.com/81584642/124391700-110fc100-dd1c-11eb-9e4f-0cad8532e4a9.JPG)

![cekrestore](https://user-images.githubusercontent.com/81584642/124391694-0e14d080-dd1c-11eb-9389-5344fede402d.JPG)

# proses backup dan recovery menggunakan mysqldump

![dump](https://user-images.githubusercontent.com/81584642/124391696-0f45fd80-dd1c-11eb-93e8-4f306a1dfbce.JPG)

![dump2](https://user-images.githubusercontent.com/81584642/124391698-0fde9400-dd1c-11eb-99a9-8c9a5e002722.JPG)

# menulis scrift cron job untuk backup otomatis setiap jam 12 malam

# 0 0 * * 7 mysqldump -u root -p12020 rizkiilhami_311910424 > rizkiilhami_311910424_backupdatabs.sql