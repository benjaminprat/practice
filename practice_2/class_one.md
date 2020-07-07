class  : FitnessStudio

attributes:
+ Open (boolean)
+ currentCapacity (integer)
+ classSchedule (hash)
+ managerOnDuty (string)

methods:
+ isOpen (will yield yes or no)
+ checkInMember (will add one person per check in, changes currentCapacity)
+ changeManager 
+ addClass (will add to roster specified day)
