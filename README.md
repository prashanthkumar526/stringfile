# stringfile
import java.util.*;
import java.util.stream.Collectors;
class stringproblem
{
public static void main(String[] args)
{
List<String> list=new ArrayList<String>();
list.add("add");
list.add("pppp");
list.add("apple");
list.add("ant");
list.add("any");
List<String> b=list.stream().filter(s -> s.startsWith("a")).filter(s -> s.length() == 3).collect(Collectors.toList());
System.out.print(b);
}
}
