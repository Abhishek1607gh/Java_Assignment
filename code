class assign {
    public static void main(String[] args) {
        int[] arr = new int []{1,2,3,4,5,6,7};
        int i,t,temp=0;
        for(i=0;i<4;i++)
        {
            t=arr[i];
            arr[i]=arr[6-i];
            arr[6-i]=t;
        }
        
        Scanner obj=new Scanner(System.in);
        String inp=obj.nextLine();
        static r2n(str,len) 
        {   for(i=0;i<len();i++)
            {
                if(str.charAt(i)==I)
                {
                    temp+=1;
                }
                else if(str.charAt(i)==V)
                {
                    if(temp<5)
                        temp=5-temp;
                    else
                        temp+=5;
                }
                else if(str.charAt(i)==X)
                {
                    if(temp<10)
                        temp=10-temp;
                    else
                        temp+=10;
                }
                else if(str.charAt(i)==L)
                {
                    if(temp<50)
                        temp=50-temp;
                    else
                        temp+=50;
                }
                else if(str.charAt(i)==C)
                {
                    if(temp<100)
                        temp=100-temp;
                    else
                        temp+=100;
                }
                else if(str.charAt(i)==M)
                {
                    if(temp<1000)
                        temp=1000-temp;
                    else
                        temp+=1000;
                }
                else
                {   System.out.println("Invalid Number")
                    break;
                }
            }
            System.out.println(temp);
        }
        
        static int size = 26;
        static boolean isLetter(char ch)
        {
            if (!Character.isLetter(ch))
                return false;
            
            return true;
        }
        static boolean allLetter(String str,
                             int len)
        {
            str = str.toLowerCase();
            boolean[] present = new boolean[size];
            for (int i = 0; i < len; i++) {
                if (isLetter(str.charAt(i))) {
                    int letter = str.charAt(i) - 'a';
                    present[letter] = true;
            }
        }
            for (int i = 0; i < size; i++) {
                if (!present[i])
                    return false;
            }
            return true;
        }
        r2n(inp,inp.length());
        if (allLetter(inp, inp.length()))
            System.out.println("Input is Pangram");
        else
            System.out.println("Input is not Pangram");
    }
}
