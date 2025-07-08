# Object Types / Data Types

- Number : 1234, 3.1415, 3+4j, 0b111, Decimal(), Fraction()
- String : 'spam', "Bob's", b'a\x01c', u'sp\xc4m'
- List : [1, [2, 'three'], 4.5], list(range(10))
- Tuple : (1, 'spam', 4, 'U'), tuple('spam'), namedtuple
- Dictionary : {'food': 'spam', 'taste': 'yum'}, dict(hours=10)

- Set : set('abc'), {'a', 'b', 'c'}

- File : open('eggs.txt'), open(r'C:\ham.bin', 'wb')

- Boolean : True, False
- None : None
- Funtions, modules, classes

- Advance: Decorators, Generators, Iterators, MetaProgramming



Python has the following data types built-in by default, in these categories:

    Text Type      :	str
    Numeric Types  :	int, float, complex
    Sequence Types :	list, tuple, range
    Mapping Type   :	dict
    Set Types      :	set, frozenset
    Boolean Type   :	bool
    Binary Types   :	bytes, bytearray, memoryview
    None Type      :	NoneType



x = str("Hello World")                           : 	str	
x = int(20)	                                     :  int	
x = float(20.5)	                                 :  float	
x = complex(1j)	                                 :  complex	
x = list(("apple", "banana", "cherry"))	         :  list	
x = tuple(("apple", "banana", "cherry"))	     :  tuple	
x = range(6)	                                 :  range	
x = dict(name="John", age=36)	                 :  dict	
x = set(("apple", "banana", "cherry"))           :	set	
x = frozenset(("apple", "banana", "cherry"))	 :  frozenset	
x = bool(5)	                                     :  bool	
x = bytes(5)	                                 :  bytes	
x = bytearray(5)	                             :  bytearray	
x = memoryview(bytes(5))                         :  memoryview 


