# My-Codewars-Solutions-

                                                                **Challeng Num 1 in 7 Kye**
-- > descending_order 

Examples:
Input: 42145 Output: 54421

                                                                      **The solution**
def descending_order(num):
    rerrange = ""
    new = []
    for n in str(num) :
        new.append(int(n))
    for tempts in range(len(new)):
        idx = new.index(max(new))
        rerrange += str(new[idx])
        del new[idx]
    return (int(rerrange))

