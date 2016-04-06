CC = g++
NAVIO = ../../Navio
INCLUDES = -I ../..

all:
	$(CC) $(INCLUDES) ADC.cpp $(NAVIO)/ADS1115.cpp $(NAVIO)/I2Cdev.cpp $(NAVIO)/Util.cpp -o ADC

clean:
	rm ADC
