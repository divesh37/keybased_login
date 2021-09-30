# keybased_login

#**Client machine**

create public key in your machine useing ssh-keygen command
![image](https://user-images.githubusercontent.com/59916238/135462600-fea1fd23-3203-4f64-9b04-3e7a48178b31.png)

cat .ssh/id_rsa.pub

Example output:
ssh-rsa dAAAB3NzaC1yc2EAAAADAQABAAABAQDCV4rtp0gTMXMiTJxiPzgnSr/bl6OJRn4FasdfrY33t1mevO4E+HdeSnIz+B97q6nxwCx5T09kzg0H/ypjDx29hsYK/VbcVS9cmnxaV3CIMaNSjPpbdEWVlan3J/win7l/RMCPLEjldKOr1lXi0vg+dyuhc3BJ1/dzPGkskVsZcYUrlRvk6Gn0SuztESG1trwSw2K/AkXhdswe7Vz4cgShdElHqRcyWfHGXcJwl7LvYrtJvD0mal56Orxu11l0dDgT9EcTpbw2LdtwHZQD4sFxq7fImV/0sMmTSSi6oT2n4gJM+weuPydWvckaU9IrLVq55WmPtw5HDGoUSHETUo14kd example

copy the public key.

![Uploading image.png…]()

#**Remote server:**

Adduser username
su username

Copy Below Run Commands
cd  ~
mkdir -p ~/.ssh 
touch ~/.ssh/authorized_keys
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys

![image](https://user-images.githubusercontent.com/59916238/135463202-5c873f03-f65b-48f1-a840-2a831acd9248.png)
