# X-Cart
ssh-keygen -t ed25519 -C «justshmv@gmail.com"

pbcopy < ~/.ssh/id_ed25519.pub

git clone git@github.com:Maksishake/X-Cart.git

cd X-Cart

git branch branch1

git branch branch2

git checkout branch1

echo "Создание файла для будущего конфликта" > file.txt

git add file.txt

git commit -m "Комментриуем вносимые изменения"

git push origin branch1

git checkout branch2

echo "Полное изменение содержимого файла из первой ветки" > file.txt

git add file.txt

git commit -m "Пушим файл с внесенными изменениями"

git push origin branch2
