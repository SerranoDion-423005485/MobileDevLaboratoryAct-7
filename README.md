# MobileDevLaboratoryAct-7
void main() {
  int quantity = 3;
  double unitPrice = 45.50;
  String productName = "Notebook";
  bool isMember = true;

  double total = quantity * unitPrice;
  bool isOver100 = total > 100;
  int remainingItems = quantity % 2;

  print("The product purchased is $productName.");
  print("The quantity purchased is $quantity.");
  print("The unit price is ₱$unitPrice.");
  print("The customer is a member: $isMember.");
  print("The total purchase amount is ₱$total.");
  print("The total is over ₱100: $isOver100.");
  print("The remainder when the quantity is divided by 2 is $remainingItems.");
}
