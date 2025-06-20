# Deque
package queue;
import java.util.*;
public class deque {
    public static void main(String[] args) {
        Deque<Integer> dq= new LinkedList<>();
        dq.addLast(1);
        dq.addLast(3 );
        dq.addLast(2);
        dq.addLast(4);
        dq.addLast(8);
        System.out.println(dq);
        dq.addFirst(5);
        System.out.println(dq);
        dq.removeLast();
        System.out.println(dq);
        dq.removeFirst();
        System.out.println(dq);
        System.out.println(dq.getFirst()); // 1
        dq.addLast(1);
        dq.addLast(3 );
        dq.addLast(2);
        dq.add(4);
        dq.addLast(8);
       dq.remove();    // remove krta hai fisrt ko
       dq.removeAll(dq); // sara clear

        System.out.println(dq);



    }
}
