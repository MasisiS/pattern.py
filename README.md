# Declaring an outer loop to handle number of rows 
row_count = 4
# Declaring the stars to increment fron 1
start = 1
# A formula to increment the stars
end = (2 * row_count) + 2
# We are declaring an outer for loop to handle number of rows 
for row_number in range(start, end):
    star_count = row_number if row_number <= row_count else end - row_number
    # We are printing the full Triangle pyramid using stars 
    print("*" * star_count)
