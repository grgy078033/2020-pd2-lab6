1.  
     (1)Yes, when the derived class's contructors are called, the constructor    s of base-class will also be called, but they are not inherited by derived class.  
     (2)No, composition is a "has-a" relationship.  
     (3)No, it should be a "has-a" relationship.  
     (4)Yes.  
     (5)Yes.  
2.  
                             Students            DoctoralStudent  
                            /        \              /  
         UndergraduateStudent        GraduateStudent  
         /       |       |   \                 |    \  
   Freshman  Sophomore Junior Senior         Worker  MasterStudent  
   |       \                  /    \            | \  
 StudyHard  PlayHard  ReadyForWork  ReadyForExam|  \  
                                                |   \  
                                 ---------------|    \  
                                 |              |     \  
                             Designer    Researcher   Technician  
                            /        \               /          \  
                         Architect  Clothing      Engineer      Labor  
  
