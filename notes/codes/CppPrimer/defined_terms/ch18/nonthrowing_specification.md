不抛出说明（nonthrowing specification）该异常说明用于承诺某个函数不会抛出异常。如果一个做了不抛出说明的函数实际抛出了异常，将调用terminate。不抛出说明符是不含实参或者含有一个值为true的实参的noexcept。
