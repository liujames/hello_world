TARGET = EigenValue
SRC =  EigenValue.cpp
INC_PATH = -I/opt/amdappsdk2/include -I/opt/amdappsdk2/include/SDKUtil -I/opt/hsa/include
LIB_PATH = -L/opt/amdappsdk2/lib/x86_64 
LIBS = -lOpenCL

$(TARGET) : $(SRC) 
	g++  $(INC_PATH) $(LIB_PATH) -o $(TARGET) $(SRC)  $(LIBS)
clean :
	rm $(TARGET)
