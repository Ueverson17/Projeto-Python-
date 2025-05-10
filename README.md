print(f"{'Fahrenheit':>10} | {'Celsius':>7}")
print("-" * 22)
for f in range(45, 81):
    c = 5 * (f - 32) / 9  
    print(f"{f:10.1f} ºF | {c:7.3f} ºC")
