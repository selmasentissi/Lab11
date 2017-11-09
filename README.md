# Lab11
import java.nio.file.*;

public class FileTest 
{
public void getPathMatcher( String str)
{
	String pattern = "SPEED_20171102_";
	PathMatcher matcher = FileSystems.getDefault().getPathMatcher("glob" + pattern);
}
public void deteleIfExists (Path pa)
{
	String pattern = "APOLLO_20171102_";
	PathMatcher matcher = FileSystems.getDefault().getPathMatcher( pattern);
	
}

public boolean exists( Path path  )
{
	Path p1 = Paths.get(args[0]); Path p1 = Paths.get("C:\\Backup\\SPEED\\SPEED_20171102_1of10.txt");
	Boolean isRegularExecutableFile = File.isRegularFile(file)&File.isReadable(file)&Files.isExecutable(file);
	
	return false;
	
}
}
