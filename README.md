// Request Class
public class Request {
    private int id;
    private String name;
    private List<Item> itemsOrdered;
    private double total;

    // Constructor, getters, and setters
    // ...
}

// RequestFulfillment Class
public class RequestFulfillment {
    // Methods for handling request fulfillment
    // ...
}

// Inventory Class
public class Inventory {
    private int productID;
    private String productName;
    private int quantityAvailable;

    // Constructor, getters, and setters
    // ...
}

// Item Class
public class Item {
    private int productID;
    private String productName;
    private double cost;

    // Constructor, getters, and setters
    // ...
}

// Client Class
public class Client {
    private int customerID;
    private String name;
    private String address;
    private String contactInfo;

    // Constructor, getters, and setters
    // ...
}
