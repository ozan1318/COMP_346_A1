# COMP_346_A1

## Students:
- Kadir Altinay
- Ozan Alptekin 40162877

## Thread Running Times
Changing the buffer size from 10 to 20 did not result in a significant difference in running times for our threads. When testing with a high
performance PC, the threads terminated within 10-12ms, with no difference observed between buffer sizes 10 and 20. When testing with a
slower laptop, the times varied between 18ms to 30ms but no consistent trend was observed with the change in buffer size. This may be
because the amount of data put into the buffer is not sufficient to create a difference, and that the number of threads running is not sufficient
to saturate a modern multicore processor.
