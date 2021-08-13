class BinaryTree
{
    static ArrayList<Integer> preorder(Node root)
    {
        ArrayList<Integer> result=new ArrayList<Integer>();
        preorderTraversal(root,result);
        return result;
    }
    public static void preorderTraversal(Node root,ArrayList<Integer> result)
    {
        if(root==null)
        return;
        else
        {
        System.out.print(root.data+" ");
        preorderTraversal(root.left,result);
        preorderTraversal(root.right,result);
        }
    
    }

}
