# odev2
Q: In your drawer you have 10 pairs of socks, 6 of which are white, and 7 tee shirts, 3 of which are white. If you randomly reach in and pull out a pair of socks and a tee shirt, what is the probability both are white?
Solution: 
The probability of choosing a white pair of socks is 6/10 .
The probability of choosing a white tee shirt is 3/7 .
The probability of both being white is 6/10.3/7=9/35  
Python solution:
# Define the number of white socks and white t-shirts
white_socks = 6
total_socks = 10
white_tshirts = 3
total_tshirts = 7

# Calculate the probability of selecting a white pair of socks
prob_white_socks = white_socks / total_socks

# Calculate the probability of selecting a white t-shirt
prob_white_tshirt = white_tshirts / total_tshirts

# Calculate the probability of selecting both a white pair of socks and a white t-shirt
prob_both_white = prob_white_socks * prob_white_tshirt

# Print the probability of selecting both a white pair of socks and a white t-shirt
print("The probability of selecting both a white pair of socks and a white t-shirt is: " + str(prob_both_white))


OUTPUT:
The probability of selecting both a white pair of socks and a white t-shirt is: 0.2571428571428571

