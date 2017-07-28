package Model;

public class ProjectList
{
    private static String projectList[][];
    
    public void setProjectList(String projectList[][])
    {
        ProjectList.projectList = projectList;
    }
    
    public String[][] getProjectList()
    {
        return ProjectList.projectList;
    }
    
}
