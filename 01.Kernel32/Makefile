# 기본적으로 빌드를 수행할 목록
all: Kernel32.bin

# 커널 엔트리 포인트 빌드
Kernel32.bin: Source/EntryPoint.s
	nasm -o Kernel32.bin $<

# 소스 파일을 제외한 나머지 파일 정리	
clean:
	rm -f Kernel32.bin