# Leak report

_The memory was not being freed, which is why the memory errors happen. The function free() needs to be called somewhere in the code which will only be used once by the memory. From its name, the free() call, from its name frees the memory from leaks._
