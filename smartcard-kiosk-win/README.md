
1) install node js

https://nodejs.org/dist/latest-v8.x/node-v8.15.0-x64.msi

2) install bytenode and build tool

npm install -g bytenode
npm install -g --production windows-build-tools

3) install git

https://git-scm.com/download/win

4) download smartcard

cd c:\app
git clone https://github.com/monthop/deploy


5) install smartcard

deploy\smartcard-kiosk-win\build\2-install.bat

6) run smartcard

send
deploy\smartcard-kiosk-win\build\3-run.bat
to
desktop