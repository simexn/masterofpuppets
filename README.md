

import numpy

A = numpy.array([-1, 2, 0])

B = numpy.array([-3, 1, 4])

C = numpy.array([1, 0, -1])

combined_matrix = numpy.array([A, B, C])

combined_product = numpy.linalg.det(combined_matrix).round()

print(combined_product)

