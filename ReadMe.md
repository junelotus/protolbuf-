## protolbuffer 例子和编译条件
example1:https://www.ibm.com/developerworks/cn/linux/l-cn-gpb/
exampe2:https://www.cnblogs.com/dkblog/archive/2012/03/27/2419010.html
protoc  -I=./  --cpp_out=./     ./lm.helloword.proto //命令中间没有空格

g++ -o w.out writeProto.cpp addressbook.pb.cc `pkg-config --cflags --libs protobuf`
