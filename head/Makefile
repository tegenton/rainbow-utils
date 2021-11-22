
build: head

clean:
	rm -f head

install: build
	cp head /usr/bin/head
	chmod 775 /usr/bin/head

uninstall:
	rm /usr/bin/head

head: head.sed
	cp head.sed head

.PHONY: build clean install uninstall
