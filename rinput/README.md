#  [![](https://i.postimg.cc/wBPhM5Lv/jackal-11-24-v2-32-inverted.png)]()  CODEBABEL

## rinput: 0.0.1 💎
### description / descrição :
~~~
{EN}

💎 rinput is a simplifier of the 'chomp' method with print in one place,
making data capture easier...

{PTBR}

💎 rinput é um simplificador do método 'chomp' com impressão em um só lugar,
facilitando a captura de dados...
~~~

![](https://img.shields.io/badge/Ruby-3.2.2|%203.2-red)
![](https://img.shields.io/badge/license-MIT-blue)
![](https://img.shields.io/badge/-Linux-grey?logo=linux)
![](https://shields.io/badge/MacOS--9cf?logo=Apple&style=social)
![](https://img.shields.io/badge/Windows-10%20&%2011-blue)

[![](https://i.postimg.cc/mgzZ5W57/banner-rinput.png)]()

## 🌐 Content / Conteúdo
* [Installation](#installation)
* [How to use](#use)
* [[ EN ] How to use](#use_en)
* [[ PTBR ] Como usar](#uso_ptbr)
* [rinput(String)](#with_string)
* [rinput_i(Integer)](#with_integer)
* [rinput_f(Float)](#with_float)
* [Change log](#changelog)

### installation
## 💻 Installation / Instalação:
Ruby Gem
> `gem install rinput`

### use
## how to use / como usar :
> use go minimum sintax

### use_en
~~~bash
#{EN}:: Step By Step :: rinput

# 1) install rinput on terminal.
> gem install rinput

# 2) create a file called "Gemfile" and put code..
source 'https://rubygems.org/gems/rinput'
gem 'rinput'

# 3) in the folder where the Gemfile is, type the command in the
# terminal to install it using the bundle install command,
# generate "Gemfile.lock".
> bundle install

# 4) create your_file.rb and call the rinput lib via require

# your_file.rb
require 'rinput'

name = rinput("What's your name? > ")
puts(name)

#$> What's your name? > Carlos Oliveira
#$> Carlos Oliveira
~~~

### uso_ptbr
~~~bash
#{PTBR}:: Passo À Passo :: rinput

# 1) instale a rinput pelo terminal.
> gem install rinput

# 2) crie um arquivo chamado "Gemfile" e põe o codigo abaixo..
source 'https://rubygems.org/gems/rinput'
gem 'rinput'

# 3) na pasta onde está o Gemfile digite o comando no terminal para instalação
# pelo comando bundle install, isso gera o "Gemfile.lock".
> bundle install

# 4) crie seu_arquivo.rb e chame a lib rinput pelo require.

# seu_arquivo.rb
require 'rinput'

name = rinput("What's your name? > ")
puts(name)

#$> What's your name? > Carlos Oliveira
#$> Carlos Oliveira
~~~

### with_string
## ✅ with String: _rinput("Question? > ")_
~~~ruby
# insert question to return string: rinput
require 'rinput'

name = rinput("What's your name? > ")
puts(name.class) # -> class String
puts("your name is #{name}")
puts(name)

#$> What's your name? > Carlos Oliveira
#$> String
#$> your name is Carlos Oliveira
#$> Carlos Oliveira
~~~

### with_integer
## ✅ with integer: _rinput_i("Question? > ")_
~~~ruby
# insert question to return Integer: rinput_i
require 'rinput'

option = rinput_i("Option: 1) apply, 2) not apply > ")
puts(option.class) # -> class Integer
puts("you choose option: #{option}")
puts(option)

#$> Option: 1) apply, 2) not apply > 1
#$> Integer
#$> you choose option: 1
#$> 1
~~~

### with_float
## ✅ with float: _rinput_f("Temperature? > ")_
~~~ruby
# insert question to return Float: rinput_f
require 'rinput'

temp = rinput_f("Temperature Patient(°C)? > ")
puts(temp.class) # -> class Float
puts("Patient temperature is: #{temp}°C")
puts(temp)

#$> Temperature Patient(°C)? > 38.8
#$> Float
#$> Patient temperature is: 38.8°C
#$> 38.8
~~~

### changelog
## 🚨 Change Log
|Version| Version Name | Upgrade Latency |
|-------|--------------|-----------------|
| 0.0.1 |    rinput    |    START LIB    |

## 💜 Thank's 🧡
~~~
{EN}
Thank you for using the rinput library.
see ya!

{PTBR}
Valeu por usar a biblioteca rinput.
tmj!
~~~
© Copyright 2024, Codebabel rinput library.