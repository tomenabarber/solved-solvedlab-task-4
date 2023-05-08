Download Link: https://assignmentchef.com/product/solved-solvedlab-task-4
<br>
Kangaroos, native animals of Australia, are not known for their intelligence. In fact they’re pretty stupid.Only slightly smarter than sheep, and that’s not saying much. In the outback kangaroos regularly jump onto the road just when a car is coming along (especially at night, because the car headlights scare them).This makes a serious mess of your car, unless you have a “roo-bar” on the front. Sadly, many ‘roos get killed in these collisions. The Royal Automobile Club of Australia needs a computer program to calculatethe expected number of kills each year. This will be done for square parcels of land, each of which has roads of known length running through.

The program needs to get the following information from the user:The length of the side of the square of land (in kilometers).The length of roads running through the square (in kilometers).The number of kangaroos living in that square.

The calulation of the expected number of kills has two phases. First, the kangaroo density has to be calculated – this is the number of kangaroos per square kilometer. Second, the road surface area has to be calculated, using the average Australian road width which is 10 meters. These are multiplied with the wellknown roadkill probablility constant, which is 1.47.

Here’s what a sample run should look like, with the keyboard input in italics …

Enter side of square in km : 3.5Enter roads length in km : 10Enter number of ‘roos : 150Expected number of kills is : 1.8

The program can be a single main function, or if you’re feeling confident, use extra functions appropriately. (3%)

Scuba divers on shallow dives (up to about 90’) put normal air in their tanks. For deeper dives divers use Nitrox (also known as EANx). Air has about 21% oxygen and 79% nitrogen, while Nitrox varies from 21% oxygen and 79% nitrogenthrough to 40% oxygen and 60% nitrogen. Using Nitrox allows you to stay down deeper for longer. However, when using Nitrox you have to take care not to use a mixture that is too strong, i.e., with a too high percentage of oxygen.This check is done using some simple mathematics:

Find out how deep the dive will be, in feet.Decide on a mixture, i.e., the percentage of oxygen in the gas.Compute the ambient pressure for the dive. To do this you need to know the “feet per atmosphere” constant, which for ocean diving is 33. The ambient pressure is then the depth divided by the “feet per atmosphere” constant, plus 1.Compute the partial pressure of oxygen for the dive, equal to the fraction of oxygen (percentage divided by 100) in the gas multiplied by the ambient pressure. The recommended maximal partial pressure of oxygen is 1.4, and thecontingency maximal partial pressure of oxygen is 1.6. If the computed partial pressure of oxygen for the dive exceeds these, I know the mixture is too strong.

Additionally, compute an “oxygen pressure group”. The oxygen pressure group is an uppercase letter representing the partial pressure of oxygen for the dive:

‘A’ represents a partial pressure of oxygen from 0.0 to less than 0.1,‘B’ represents a partial pressure of oxygen from 0.1 to less than 0.2,‘C’ represents a partial pressure of oxygen from 0.2 to less than 0.3, etc.

If the oxygen pressure group is ‘N’ the diver is close to the oxygen pressure limit of 1.4, and if it’s a letter after ‘N’ the diver knows that the mixture is too strong.

I’d like you to write a computer program to do these calculations:You’ll have to get the depth and percentage oxygen in the gas as keyboard input – both will be integers.The output must provide the ambient pressure for the dive, the partial pressure of oxygen for the dive, and the oxygen pressure group.Additionally, it must output true/false status values indicating whether or not the dive will exceed the recommended maximal and contingency maximal values for partial pressure of oxygen.Here is what a sample run should look like (with the keyboard input shown in italics):

Enter depth and percentage O2 : 99 36

Ambient pressure : 4.0O2 pressure : 1.44O2 group : O

Exceeds maximal O2 pressure : trueExceeds contingency O2 pressure : false

The program should use extra functions appropriately. (3%)

HINT: In some cases you may need variable type conversions (that we haven’t yet really covered). Such conversions can be forced by (&lt;type) by (float) t or a character by (char) t.