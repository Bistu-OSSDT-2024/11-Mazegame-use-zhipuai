# Mazegame
This project is a MazaGAme with allows that the players to use zhe bottom on keyboard to move the pixel block and untill it arrive at the exit. That is the main introduce of our small game . 

the main produce process is we write a basic frame and then use ChatGPT to optimize the frame and then give it to MetaGPT to generate the  body of the game. And we write a snake game to pricatice.

then we will talk about the game design. We mainly use html and css3 to write the game.
The index.html witch all we run the game on line
The main.js is all the class we use all the  port we use and all the realize.
the style.css is all the backgraound and other settings about collor and borders.

Some question we meet:
Q1:Installing build dependencies ... error
  error: subprocess-exited-with-error
  
  × pip subprocess to install build dependencies did not run successfully.
  │ exit code: 2
  ╰─> [55 lines of output]
      Collecting setuptools>=40.8.0
        Using cached setuptools-70.1.1-py3-none-any.whl.metadata (6.0 kB)
      WARNING: Retrying (Retry(total=4, connect=None, read=None, redirect=None, status=None)) after connection broken by 'ProtocolError('Connection aborted.', ConnectionResetError(10054, '远程主机强迫关闭了一个现有的连接。', None, 10054, None))': /packages/b3/7a/629889a5d76200287aa5483d753811bd247bbd1b03175186f759e0c7d3a7/setuptools-70.1.1-py3-none-any.whl
      Downloading setuptools-70.1.1-py3-none-any.whl (883 kB)
         -----------                             266.2/883.3 kB 18.5 kB/s eta 0:00:34
      ERROR: Exception:
      Traceback (most recent call last):
        File "D:\编程\Python\Lib\site-packages\pip\_vendor\urllib3\response.py", line 438, in _error_catcher
          yield
        File "D:\编程\Python\Lib\site-packages\pip\_vendor\urllib3\response.py", line 561, in read
          data = self._fp_read(amt) if not fp_closed else b""
        File "D:\编程\Python\Lib\site-packages\pip\_vendor\urllib3\response.py", line 527, in _fp_read
          return self._fp.read(amt) if amt is not None else self._fp.read()
        File "D:\编程\Python\Lib\site-packages\pip\_vendor\cachecontrol\filewrapper.py", line 98, in read
          data: bytes = self.__fp.read(amt)
        File "D:\编程\Python\lib\http\client.py", line 465, in read
          s = self.fp.read(amt)
        File "D:\编程\Python\lib\socket.py", line 705, in readinto
          return self._sock.recv_into(b)
        File "D:\编程\Python\lib\ssl.py", line 1274, in recv_into
          return self.read(nbytes, buffer)
        File "D:\编程\Python\lib\ssl.py", line 1130, in read
          return self._sslobj.read(len, buffer)
      TimeoutError: The read operation timed out

      During handling of the above exception, another exception occurred:
this problem is duto the the miss downlode of pip and other problem and we reinstalled the pip it worked
Q2 is to coreact the codes like some code like coller set or border set and so an. thers are also some problem when we run the web page some request a new operating ervironment and we need to  downlode.


here are our web page:
![image](https://github.com/Bistu-OSSDT-2024/11-project-one/assets/164650160/b039ef87-fd4d-455f-9976-a7a2f79bb432)
![image](https://github.com/Bistu-OSSDT-2024/11-project-one/assets/164650160/63351385-611b-4068-bde6-b81ce4285b1b)





