# poll
poll and remove functions of priority queue
import java.util.LinkedList;
import java.util.Queue;

public class poll {

    public static void main(String[] args) {

        Queue<Integer> qi = new LinkedList<>();
        qi.add(50);
        qi.add(100);
        qi.add(25);

        boolean x1 = qi.remove(100);
        System.out.println(x1);

    int    x = qi.poll();
        System.out.println(x);

        System.out.println(qi);
    }
}
