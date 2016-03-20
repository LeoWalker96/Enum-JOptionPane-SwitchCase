# Enum-JOptionPane-SwitchCase
import javax.swing.JOptionPane;
public class Months {
    public enum MonthsType {January, February, March, April, May, June, July, August, September, October, November, December}
    public static void main(String[] args) {
          MonthsType[] choices = {MonthsType.January, MonthsType.February, MonthsType.March, MonthsType.April, MonthsType.May, MonthsType.June, MonthsType.July, MonthsType.August, MonthsType.September, MonthsType.October, MonthsType.November, MonthsType.December};
          MonthsType select = (MonthsType) JOptionPane.showInputDialog(null, "Select a month.", "Months", JOptionPane.INFORMATION_MESSAGE, null, choices, choices[0]);
          while (select!=null) {
               switch (select) {
               case January: JOptionPane.showMessageDialog(null, "Do you want to build a snow man?");
               break;
               case February:JOptionPane.showMessageDialog(null, "Do you want to build a snow man?");
               case March:JOptionPane.showMessageDialog(null, "Happy Spring days!");
               break;
               case April:JOptionPane.showMessageDialog(null, "Happy Spring days!");
               break;
               case May:JOptionPane.showMessageDialog(null, "Happy Spring days!");
               break;
               case June:JOptionPane.showMessageDialog(null, "It's summer time.");
               break;
               case July:JOptionPane.showMessageDialog(null, "It's summer time.");
               break;
               case August:JOptionPane.showMessageDialog(null, "It's summer time.");
               break;
               case September:JOptionPane.showMessageDialog(null, "Welcome to the foliage season!");
               break;
               case October:JOptionPane.showMessageDialog(null, "Welcome to the foliage season!");
               break;
               case November:JOptionPane.showMessageDialog(null, "Welcome to the foliage season!");
               break;
               case December:JOptionPane.showMessageDialog(null, "Do you want to build a snow man?");
               break;
             }
               
               select = (MonthsType) JOptionPane.showInputDialog(null, "Select a month.", "Months", JOptionPane.INFORMATION_MESSAGE, null, choices, choices[0]);
}
               JOptionPane.showMessageDialog(null, "Good bye!");
}
}   
