# 4.22
import java.util.Date;
  
public class DateDemo {
 
   public static void main(String[] args) {
       // 初始化 Date 对象
       Date date = new Date();
        
       // 使用toString()显示日期和时间
       System.out.printf("%1$s %2$tB %2$td, %2$tY", 
                         "Due date:", date);
   }
}
