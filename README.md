# README

This repository shows a problem with select boxes and turbolinks 5.

Steps to reproduce:

1) git clone https://github.com/pierre-pretorius/turbolinks_test.git

2) cd turbolinks_test

3) bin/rake db:migrate

4) rails s

5) Go to http://localhost:3000/items/new

6) Enter name "any name" and select "Type two".

7) Click "Go to items".

8) Press browser back button.

9) Note that "any name" is still filled in as the name but "Type two" isn't selected.
