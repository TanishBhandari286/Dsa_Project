# Dsa_Project
public class Delivery {
    private String packageId;
    private int source;
    private int destination;
    private int priority; // 1 = High, 2 = Medium, 3 = Low
    private int timeWindow; // Delivery time constraint in hours
     public Delivery(String packageId, int source, int destination, int priority, int timeWindow) {
        this.packageId = packageId;
        this.source = source;
        this.destination = destination;
        this.priority = priority;
        this.timeWindow = timeWindow;
    }
     public String getPackageId() {
        return packageId;
    }

   
   
