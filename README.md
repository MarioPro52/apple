# appleclass Apple:
    def __init__(self, color, variety, weight):
        self.color = color
        self.variety = variety
        self.weight = weight

    def get_details(self):
        return f"Apple details: Color: {self.color}, Variety: {self.variety}, Weight: {self.weight} grams"

# Create an instance of the Apple class
my_apple = Apple(color="Red", variety="Fuji", weight=150)

# Print the details of the apple
print(my_apple.get_details())
