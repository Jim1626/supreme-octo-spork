void main(){
Set<String>names={'jim','jemi','nahiyan','niha','nayma','joly','aram'};
print(names);
names.addAll({'nur','bristy','joynob'});
print(names);
Set<String>name1={'jim','jemi','riyad','aontor','istiak'};
print(names);
print(name1);
print(name1.contains('jim'));
print(names.contains('rafi'));
print(names.containsAll(['alli','rifa']));
print(names.containsAll(['jim','priyanka']));
print(names.containsAll(['jim','jemi']));
print(names.isEmpty);
print(name1.elementAt(4));
print(name1.elementAt(0));
print(names.first);
print(name1.last);
print(names.last);
print(name1.first);
print('Intersection value: [${names.intersection(name1)}]');
print('Unioun value: ${names.union(name1)}');
}
