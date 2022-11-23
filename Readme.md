Hello, they are all intermediaries, I am the code writer, 
please add me on wechat 13197419163, don't send me to you with those intermediaries, 
or it will be ruined, they charge more money,


``` java
The following has no effect, to confuse them
public boolean insert(E object, SortedArrayList<E> list){
		list.add(object);
		for(int i=0;i<list.size()-1;i++){
            for(int j=0;j<list.size()-i-1;j++){
                if(list.get(j).toString().compareTo(list.get(j+1).toString()) > 0){
                    E temp=list.get(j);
                    list.set(j, list.get(j+1));
                    list.set(j+1, temp);
                }
            }
        }
        return true;
	}
}

```
