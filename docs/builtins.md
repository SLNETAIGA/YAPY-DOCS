# Builtins in yapy

* {string}.format(*args) - Format string like as C(%s,%i)
* {string}.ljust(val,num) - Append val num-s to left
* {string}.rjust(val,num) - Append val num-s to right
* {string}.center(val,num) - Append val num-s to center
* {string}.join(list) - Join string
* {list}.join(del) - Joins list
* {list}.map(fn) - Map list
* {list}.filter(fn) - Filter list
* gettype(obj) - Type of obj
* str(obj) - obj -> str
* int(obj) - obj -> number
* float(obj) - obj -> float
* system(cmd) - execute shell command
* random() - random number
* add_builtin(name,fn) - Registers new builtin
* uncode16(a,b) - Uncode 16-data
* getattr(obj,name) - Get name from obj
* setattr(obj,name,val) - Set obj.name to val
* input() - input from console
* print(data) - output to console
* exit() - exit from here
* chr(a)/ord(a) - chr/ord
* mmatch(str,start,dst) - is str == dst from position start?
* len(obj) - length of obj
* hasattr(obj,name) - Is name in obj?
* copy(list) or {list}.copy(list)- Copy
* mtime(file) - Modification date of file
* escape(text) - Escape special chars
* quote(text) - Escape special chars(not raise exception when gived not string)
* execfile(path,chdir=True) - Loads module.
* assert(data) - Assert
* require(path,name=None) - for modules which can not import by import statement

## Library `math`
* math.abs(a) - ABS
* math.acos(a) - ACOS
* math.asin(a) - ASIN
* math.sin(a) - SIN
* math.tan(a) - TAN
* math.atan(a) - ATAN
* math.atan2(x,y) - ATAN2
* math.ceil(a) - CEIL
* math.cos(a) - COS
* math.cosh(a) - COSH
* PI = 3.141592653589793
* E = 2.718281828459045

## Library `os`
* os.getcwd() - Get current directory
* os.chdir(dir) - Change current directory
* os.listdir(dir) - Lists directory
* os.stat(file) - List of file stats
* os.exists(path) - Is file exists?

## Library `sys`
* sys.argv - Command line arguments
* sys.exit(code) - Exit from procces
* sys.modules() - Modules loaded into memory

## Library `time`
* time.time() - Time now
* time.clock() - Time now formated by clocks per second
* time.sleep(n) - Sleep n seconds
* time.ctime() - Raw time and date
* time.asctime() - Raw time and date
