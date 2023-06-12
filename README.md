# ansible_nginx
install vagrant + virtualbox + ansible 
 перейти в  созданную директорию mkdir ansible 
 vagrant init  ubuntu/focal64    пример описан без использования локального image
 (либо если есть локально скачанный образ) добвить ег ов коробку  vagrant box  add пример  имени  focal и сделать  vagrant init focal)
 далее либо редактирвуем вагрант фаил в соответствие с  git  либо заменяем 
так же в папку  скидываем  playbook.yml  и  паку  roles 
далее в папке ansible   пишем vagrant up
позже после прохода всех операции vagrant ssh для проверки 
