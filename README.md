# Make_your_own_coin_usind-constructor_desctructor_encapsulation
           import random  
           class Pound:     
           def __init__(self, rare=False):     #constructor  
           self.rare = rare       
           if self.rare:          
           self.value = 1.25      
           else:          
           self.value = 1.00              
           self.colour = "gold"      
           self.num_edges = 1      
           self.diameter = 2.25 #mm      
           self.thickness = 3.15 # mm      
           self.heads = True     
           def __del__(self):        #destructor
           print("Coin Spent!")     
           def rust(self):              
           self.colour = "greenish"     
           def clean(self):       
           self.colour = "gold"            
           def flip(self):        
           heads_options = [True, False]        
           choice = random.choice(heads_options)        
           self.heads = choice        
