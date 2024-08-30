# -first-project
Two approaches for finding maximum number in a list
#approach one: 
        def find_max(numbers):
            maximum=max(numbers)
            return maximum

#approach two
      def find_maximum(values):
        maximum=values[0]
        for number in values:
            if number > maximum:
              maximum=number
        return maximum

#To use the function any of the function
      numbers=[20,10,30,60,100,30]
      print(find_max(numbers))           #output will be 100
      print(find_maximum(numbers))       #output will be 100
