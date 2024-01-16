def sum_column(twoD_lst, col_num):
    total_col_sum = 0
    for row in twoD_lst:
        total_col_sum = row[int(col_num)] + total_col_sum
    return total_col_sum
        
lst_1 = [[3, 5, 7], [10, 10, 10]] 
lst_2 = [[3, 5, 7], [10, 10, 10]]
lst_3 = [[3, 5], [5, 8], [0, -1]]

sum_lst1 = sum_column(lst_1, 1)
print(sum_lst1)
sum_lst2 = sum_column(lst_2, 2)
print(sum_lst2)
sum_lst3 = sum_column(lst_3, 0)
print(sum_lst3) 
        
