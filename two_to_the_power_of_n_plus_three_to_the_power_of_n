import matplotlib.pyplot as plt

def two_to_the_power_of_n_plus_three_to_the_power_of_n():
  """
  https://oeis.org/A007689/b007689.txt
  https://oeis.org/search?q=5%2c13%2c35%2c97%2c275%20id:A007689
  
  This series makes up the differences for this sequence:
    1, 6, 19, 54, 151, 426
  """
  
  n = [x for x in range(0, 10)]
  values = []

  for i in n:
    values.append((2 ** i) + (3 ** i))
     
  print(values)

  plt.figure(figsize=(10, 6))
  plt.plot(n, values)
  plt.title('Sequence A007689: a(n) = 2^n + 3^n')
  plt.xlabel('n')
  plt.ylabel('a(n)')
  plt.grid(True)

  # 4. Optionally: use logarithmic scale if values grow too fast
  plt.yscale('log')
  plt.show()

two_to_the_power_of_n_plus_three_to_the_power_of_n()
