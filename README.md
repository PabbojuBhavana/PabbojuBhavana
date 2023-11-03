class BaseClass {
    protected int value;

    public void setValue(int value) {
        this.value = value;
    }
}

class SubClass extends BaseClass {
    public void doSomething() {
        // Subclass relies on the internal state of the base class
        if (value > 10) {
            // Do something
        }
    }
}


