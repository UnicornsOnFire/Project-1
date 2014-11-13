import java.awt.EventQueue;

import javax.swing.JFrame;

import java.awt.GridBagLayout;
import java.awt.BorderLayout;

import javax.swing.BoxLayout;

import java.awt.CardLayout;

import javax.swing.JButton;
import javax.swing.JPanel;
import javax.swing.JPasswordField;

import java.awt.GridBagConstraints;
import java.awt.Insets;

import javax.swing.JTextField;
import javax.swing.JLabel;

import java.awt.Font;
import javax.swing.JPopupMenu;
import java.awt.Button;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import javax.swing.Box;
import javax.swing.border.LineBorder;
import java.awt.Color;
import javax.swing.JSeparator;
import javax.swing.JInternalFrame;


public class MainPage {

	private JFrame frame;
	private JTextField txtsearch;
	private JTextField txtusernameregister;
	private JTextField txtpasswordregister;
	private JTextField txtrepeatpassword;
	private JTextField txtemail;
	private JTextField txtusername;
	private JPasswordField passwordField;
	private JTextField textField;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					MainPage window = new MainPage();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public MainPage() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(new CardLayout(0, 0));
		
		JPanel MainPage = new JPanel();
		MainPage.setBorder(new LineBorder(new Color(0, 0, 0)));
		frame.getContentPane().add(MainPage, "name_14378214456714");
		MainPage.setLayout(null);
		
		JButton btnYourFeed = new JButton("Your Feed");
		btnYourFeed.setBounds(12, 73, 97, 25);
		MainPage.add(btnYourFeed);
		
		JButton btnPickTopic = new JButton("Pick Topic");
		btnPickTopic.setBounds(12, 347, 97, 25);
		MainPage.add(btnPickTopic);
		
		JButton btnSearch = new JButton("Search");
		btnSearch.setBounds(190, 400, 97, 25);
		MainPage.add(btnSearch);
		
		txtsearch = new JTextField();
		txtsearch.setBounds(299, 401, 301, 22);
		MainPage.add(txtsearch);
		txtsearch.setColumns(10);
		
		JLabel label = new JLabel("|");
		label.setBounds(620, 23, 16, 16);
		MainPage.add(label);
		
		Button btnlogin = new Button("Login");
		btnlogin.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {
			}
		});
		btnlogin.setBounds(545, 23, 62, 16);
		MainPage.add(btnlogin);
		
		Button btnregister = new Button("Register");
		btnregister.setBounds(642, 23, 62, 16);
		MainPage.add(btnregister);
		
		JLabel lblClickbait = new JLabel("ClickBait");
		lblClickbait.setFont(new Font("Tahoma", Font.BOLD, 18));
		lblClickbait.setBounds(12, 14, 97, 30);
		MainPage.add(lblClickbait);
		
		JSeparator separator = new JSeparator();
		separator.setBounds(-24, 52, 767, 8);
		MainPage.add(separator);
		
		JInternalFrame Login = new JInternalFrame("Login");
		Login.setDefaultCloseOperation(JFrame.HIDE_ON_CLOSE);
		Login.setClosed(true);
		Login.setClosable(true);
		Login.setBounds(173, 177, 333, 210);
		MainPage.add(Login);
		Login.getContentPane().setLayout(null);
		
		txtusername = new JTextField();
		txtusername.setBounds(104, 44, 166, 22);
		Login.getContentPane().add(txtusername);
		txtusername.setColumns(10);
		
		passwordField = new JPasswordField();
		passwordField.setBounds(104, 89, 166, 22);
		Login.getContentPane().add(passwordField);
		
		JLabel lblUsername = new JLabel("Username:");
		lblUsername.setBounds(30, 50, 69, 16);
		Login.getContentPane().add(lblUsername);
		
		JLabel lblPassword = new JLabel("Password:");
		lblPassword.setBounds(31, 92, 72, 16);
		Login.getContentPane().add(lblPassword);
		
		JButton btnLogin = new JButton("Login");
		btnLogin.setBounds(114, 124, 97, 25);
		Login.getContentPane().add(btnLogin);
		Login.setVisible(true);
		
		JPanel Feed = new JPanel();
		frame.getContentPane().add(Feed, "name_14410937859923");
		Feed.setLayout(null);
		
		JSeparator separator_3 = new JSeparator();
		separator_3.setBounds(-24, 52, 767, 8);
		Feed.add(separator_3);
		
		textField = new JTextField();
		textField.setBounds(299, 401, 301, 22);
		textField.setColumns(10);
		Feed.add(textField);
		
		JButton btnExplore = new JButton("Explore");
		btnExplore.setBounds(12, 73, 97, 25);
		Feed.add(btnExplore);
		
		JButton btnPickTopic2 = new JButton("Pick Topic");
		btnPickTopic2.setBounds(12, 347, 97, 25);
		Feed.add(btnPickTopic2);
		
		JButton btnSearch2 = new JButton("Search");
		btnSearch2.setBounds(211, 400, 73, 25);
		Feed.add(btnSearch2);
		
		Button btnlogout = new Button("Logout");
		btnlogout.setBounds(639, 24, 62, 16);
		Feed.add(btnlogout);
		
		JLabel label_3 = new JLabel("ClickBait");
		label_3.setBounds(12, 14, 97, 30);
		label_3.setFont(new Font("Tahoma", Font.BOLD, 18));
		Feed.add(label_3);
		
		JSeparator separator_2 = new JSeparator();
		separator_2.setBounds(671, 16, 0, 2);
		Feed.add(separator_2);
		
		JPanel RegisterForm = new JPanel();
		frame.getContentPane().add(RegisterForm, "name_14429475392007");
		RegisterForm.setLayout(null);
		
		txtusernameregister = new JTextField();
		txtusernameregister.setBounds(267, 104, 217, 22);
		RegisterForm.add(txtusernameregister);
		txtusernameregister.setColumns(10);
		
		txtpasswordregister = new JTextField();
		txtpasswordregister.setBounds(267, 155, 217, 22);
		RegisterForm.add(txtpasswordregister);
		txtpasswordregister.setColumns(10);
		
		txtrepeatpassword = new JTextField();
		txtrepeatpassword.setBounds(267, 208, 217, 22);
		RegisterForm.add(txtrepeatpassword);
		txtrepeatpassword.setColumns(10);
		
		txtemail = new JTextField();
		txtemail.setBounds(267, 259, 217, 19);
		RegisterForm.add(txtemail);
		txtemail.setColumns(10);
		
		JLabel lblUsername_1 = new JLabel("Username");
		lblUsername_1.setBounds(197, 107, 58, 16);
		RegisterForm.add(lblUsername_1);
		
		JLabel lblPassword_1 = new JLabel("Password");
		lblPassword_1.setBounds(199, 158, 56, 16);
		RegisterForm.add(lblPassword_1);
		
		JLabel lblRepeatPassword = new JLabel("Repeat Password");
		lblRepeatPassword.setBounds(156, 211, 99, 16);
		RegisterForm.add(lblRepeatPassword);
		
		JLabel lblEmail = new JLabel("E-mail");
		lblEmail.setBounds(219, 261, 36, 16);
		RegisterForm.add(lblEmail);
		
		JButton btnRegister = new JButton("Register");
		btnRegister.setBounds(287, 326, 97, 25);
		RegisterForm.add(btnRegister);
		
		JLabel label_2 = new JLabel("ClickBait");
		label_2.setFont(new Font("Tahoma", Font.BOLD, 18));
		label_2.setBounds(12, 13, 97, 30);
		RegisterForm.add(label_2);
		
		JButton registerButton = new JButton("register");
		registerButton.setBounds(180, 80, 80, 25);
		panel.add(registerButton);
		
		
	}
}
