import java.util.*;
class ContactSearch {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number of contacts: ");
        int n = sc.nextInt();
        sc.nextLine();
        String name[] = new String[n];
        String phone[] = new String[n];
        for(int i=0;i<n;i++) {
            System.out.print("Enter name: ");
            name[i] = sc.nextLine();
            System.out.print("Enter phone number: ");
            phone[i] = sc.nextLine();
        }
        System.out.print("Enter name to search: ");
        String search = sc.nextLine();
        boolean found = false;
        for(int i=0;i<n;i++) {
            if(name[i].equalsIgnoreCase(search)) {
                System.out.println("Contact Found");
                System.out.println("Name: "+name[i]);
                System.out.println("Phone: "+phone[i]);
                found = true;
                break;
            }
        }
        if(!found) {
            System.out.println("Contact not found");
        }
    }
} 
