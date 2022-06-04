# Data_Structure_Assignment_4

public final class IntegrityStatement {
    public static String signature() {
        String names = "Omer Casif and Ariel Amit"; // <- Fill in your names here!
        if (names.length() == 0) {
            throw new UnsupportedOperationException("Omer Casif and Ariel Amit");
        }
        return names;
    }
}
