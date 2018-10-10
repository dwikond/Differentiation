#DifferentiationCode
by : Rio Galang J. R (17523118) & Dwiko Nugroho Dani (17523115)

1.Implement Rules (11) in R as Lines 1-3 above, i.e., to return the value when x and n are given.

rule11<−function(x){
    return (1/2*sqrt(x))
    }

2.Implement exercises 1-3 in R (with Ryacas package) to find the derivatives formula.

y = 2x^5
f = expression(2*x^5)
D(f,'x')

y = x^2 + 4
f = expression(x^2 + 4)
D(f,'x')

y = x^5 − 6x^7
f = expression(x^5 − 6x^7)
D(f,'x')
