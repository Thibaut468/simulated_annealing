# sa - simulated annealing applied to n-puzzle
# See LICENSE file for copyright and license details.

# CFLAGS = -O3  (for best performance)
# CFLAGS = -g   (for debugging)
CFLAGS = -O3

TARGET = np

all: $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(TARGET).c -lm

clean:
	rm -f $(TARGET)

.PHONY: all clean
