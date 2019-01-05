# README

Step 1:
The only thing I did was in the directory which I named activerecord-associations-lv-lecture. 

Step 2:
I created a new rails app by the following command:

> rails new activerecord-associations-lv-lecture

Step 3:
After I ran this I basically just added the following macros(has_many and belongs_to) to the following classes: 

> class Artist < ApplicationRecord
>   has_many :songs
> end


> class Song < ApplicationRecord
>   belongs_to :artist
> end

Step 4:
in your terminal type the following to get into the rails console 

> rails console 

or 

> rails c 

Step 5: 
Have fun with your objects!!!!!!!
