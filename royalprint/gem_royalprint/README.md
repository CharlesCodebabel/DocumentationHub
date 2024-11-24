#  [![jackal-11-24-v2-32-inverted.png](https://i.postimg.cc/wBPhM5Lv/jackal-11-24-v2-32-inverted.png)]()  CODEBABEL

## royalprint: 0.0.2 💎
### description / descrição :
~~~
{EN}

royalprint is perfect for simplifying the information that needs to go to the console, similar to printing in C++ command cout, PHP echo, log("Hi"), go("Hello ..."), cout("whoami?"), display("She Knows")... and more.

{PTBR}

royalprint é perfeita para simplificar as informações que precisam ir para o console, com similaridade de impressão em C++ comando cout, PHP echo, log("Oi"), go("Olá ..."), cout("whoami?"), display("She Knows")... e mais.
~~~

![](https://img.shields.io/badge/Ruby-3.2.2|%203.2-red)
![](https://img.shields.io/badge/license-MIT-blue)
![](https://img.shields.io/badge/-Linux-grey?logo=linux)
![](https://shields.io/badge/MacOS--9cf?logo=Apple&style=social)
![](https://img.shields.io/badge/Windows-10%20&%2011-blue)

[![royalprint.png](https://i.postimg.cc/HLxCjz9S/royalprint.png)]()

## 🌐 Content / Conteúdo
* [Installation](#installation)
* [All print formats](#formats)
* [Basic use](#basic)
* [Complete use](#complete)
* [Change log](#changelog)

### installation
## 💻 Installation / Instalação:
Ruby Gem
> `gem install royalprint`

### how to use / como usar :
> use go minimum sintax

~~~bash
#{EN}:: Step By Step :: royalprint

# 1) install royalprint on terminal.
> gem install royalprint

# 2) create a file called "Gemfile" and put code..
source 'https://rubygems.org/gems/royalprint'
gem 'royalprint'

# 3) in the folder where the Gemfile is, type the command in the terminal to install it using the bundle install command, generate "Gemfile.lock".
> bundle install

# 4) create your_file.rb and call the royalprint lib via require

# your_file.rb
require 'royalprint'

say_my_name = "SayMyName."
go(say_my_name)
~~~

~~~bash
#{PTBR}:: Passo À Passo :: royalprint

# 1) instale a royalprint pelo terminal.
> gem install royalprint

# 2) crie um arquivo chamado "Gemfile" e põe o codigo abaixo..
source 'https://rubygems.org/gems/royalprint'
gem 'royalprint'

# 3) na pasta onde está o Gemfile digite o comando no terminal para instalação pelo comando bundle install, isso gera o "Gemfile.lock".
> bundle install

# 4) crie seu_arquivo.rb e chame a lib royalprint pelo require.

# seu_arquivo.rb
require 'royalprint'

say_my_name = "SayMyName."
go(say_my_name)`
~~~

> codebabel go
~~~ruby
# codebabel go
require 'royalprint'

say_my_name = "SayMyName."
go(say_my_name)

#> SayMyName.
~~~

> codebabel show
~~~ruby
# codebabel show
require 'royalprint'

se_eu_largar_o_freio = "Vai dar mais valor pra mim."
show(se_eu_largar_o_freio)

#> Vai dar mais valor pra mim.
~~~

> use PHP echo
~~~ruby
# PHP echo
require 'royalprint'

my_name_is = "What?"
echo(my_name_is)

#> What?
~~~

> Rails xRails
~~~ruby
# Rails xPrint
require 'royalprint'

show_this = "Do your jumps!"
xRails(show_this)

#> Do your jumps!
~~~
### formats
### all print formats / todos os formatos
~~~
go
log
show
echo
display
put_line
cout
printf
printin
println
xRails
~~~
### basic
> basic use
~~~ruby
# easy pease fela / uso básico fela
require 'royalprint'

msg_box = "I am tea pot!"
log(msg_box); # simple console message > ...
go("nengue");  # simple console message > ...
~~~
### complete
> complete use
~~~ruby
# easy pease use/ uso básico fela
require 'royalprint'

msg_box = "I am tea pot!";

# basic...
log(msg_box); # [scm] simple console message > ...

# Aesthetic Print...
go(msg_box);       # codebabel go
show(msg_box);     # codebabel show
echo(msg_box);     # php echo
display(msg_box);  # cobol display
put_line(msg_box); # ada putline
cout(msg_box);     # c++ cout <
printf(msg_box);   # c printf
printin(msg_box);  # scala printin
println(msg_box);  # java println

# Aesthetic xPrint Thematic
xRails(msg_box);     # Rails xPrint
~~~
### changelog
## 🚨 Change Log
|Version| Version Name | Upgrade Latency |
|-------|--------------|-----------------|
| 0.0.1 |  royalprint  |    START LIB    |
| 0.0.2 |  royalprint  | * Fix:lib file  |

## 💜 Thank's 🧡
~~~
{EN}
Thank you for using the royalprint library.
see ya!

{PTBR}
Valeu por usar a biblioteca royalprint.
tmj!
~~~
© Copyright 2024, Codebabel royalprint cross-language library.