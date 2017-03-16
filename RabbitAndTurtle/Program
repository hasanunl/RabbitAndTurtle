class Rabbit_Turtle
  attr_accessor :range,:range2
  def initialize(range,range2)
    @range = range
    @range2 = range2
  end

  def Calculations
    range_array=Array.new(70,"_" )
    while(@range<70 and @range2<70)
      puts range_array.join("")
      range_array[@range-1] = "_"
      range_array[@range2-1] = "_"
      percent=rand(0...100)
      percent2=rand(0...100)
      if(percent>0 and percent<=30)
        @range=@range+1
      end
      if(percent>30 and percent<=50)
        @range=@range+0
      end
      if(percent>50 and percent<=70)
        @range=@range+9
      end
      if(percent>70 and percent<=90)
        @range=@range-2
      end
      if(percent>90 and percent<=100)
        @range=@range-12
      end
      if(percent2>0 and percent2<=50)
        @range2=@range2+3
      end
      if(percent2>50 and percent2<=80)
        @range2=@range2+1
        end
      if(percent2>80 and percent2<=100)
        @range2=@range2-6
      end
      if(@range<1)
        @range=1
      end
      if(@range2<1)
        @range2=1
      end
      range_array[@range-1] = "T"
      range_array[@range2-1] = "K"
      if(@range == @range2)
        range_array[@range-1] = "Ouch"
      end
      #puts " #{@range} #{@range2} "
    end
    #p range_array
    puts range_array.join("")
    if(@range>@range2)
      puts "Tavsan kazandi."
    end
    if(@range<@range2)
      puts "Kaplumbaga kazandi."
    end
    if(@range==@range2)
      puts "Berabere."
    end
  end
end

rabbit=Rabbit_Turtle.new(1,1)
puts rabbit.Calculations



