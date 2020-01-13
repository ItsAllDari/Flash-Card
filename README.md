# Flash-Card
import javax.swing.*;

/**
 * Created by ItsAllDari on 6/9/17.
 */
public class FlashCard {
    public static void main(String[] args) {
        WidgetView wv = new WidgetView();

        JTextField jtf1 = new JTextField(10);
        jtf1.setText("Generate two numbers");
        wv.add(jtf1);
        JLabel jlInstructions = new JLabel("What is 6 times 3?");
        JTextField num 1 = new JTextField(6);
        JTextField num 2 = new JTextField(3);

        wv.add(jlInstructions);

        JButton execute = new JButton("Click after entering an answer");
        wv.addAndWait (execute);

        int n1 = Integer.parseInt(num1.getText());
        int n2 = Integer.parseInt(num2.getText());


    }
}
