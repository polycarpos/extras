## VISTAKEY: A Keyboard Without A Keyboard –A Type Of Virtual Keyboard ##
Input data to computer devices is the A B C in human-computer  interaction. 
People  use  both  the  computing devices   (desktops   orlaptops)   and
non-traditional computing  devices  (mobiledevices)  to  speed  up  their work  in  homes  and  offices. 
Therefore  to  cope  with today’s fast moving business world they try to increase the  portability  and 
mobility  by  reducing  the  size  of these  devices.  Because  the  data  input  unit  of  these devices
get smaller and smaller they lack flexibility for some  users  who  find  difficulties  to  see  the  letters 
printed on each tiny key of the tiny keypads.However, when  they  carry  an additional  keyboard,  similar to  
the traditional  keyboard  with  a  mobile  unit,  the  mobility and the  portability  will no  longer  be  there. 
Apart  from this,  users  who  work  with  Personal Computers  (PC) face  problems  such  as  functional  problems  
due  to technical  faults,  misplacement  of  units,as  well  as  the usage   of   physical   keyboards   can   depend
on   the working  environment,  for  example  clean rooms  where keyboards are not allowed.To  overcome  the  above  problems,
one  approach  is  to have Virtual Keyboards, which dynamically change the key arrangement for different users, situations,
or even from  keystroke  to  keystroke  [1,  2]such  as  Visual Panel,  FingeRing  and  Touch  Stream  to  name  a  few. But these have their own drawbacks, 
such as high cost, the  same  key  location  has  to  be  pressed  repeatedly  to enter  data,  slow  typing  speed,  user  has  to  wear  gloves or  data  processing  units,  possibility  of  damaging  the keys, etc.
However,  the  virtual input  devices  open  the  path  for  a novel  scheme  called  vision  based  human-computerinteraction   in   which   traditional   input   and   output devices  are  replaced  with  augmented 
reality  displays [3],projection  systems  [8]  and  cameras.  This  concept gives  birth  to  a  new  technology  allowing  the  use  of light  made  full  size  keyboards  on  mobile  devices  like PDAs, palmtops and 
other portable computing devices. This   new   technology   enables   a   keyboard   to   be projected  onto  a  flat  surface  using  a  beam  of  light, which  can  then  be  typed  on.  The  existing  projection keyboards 
in the world are discussed at length in [1,3],which    are    the    most    competitive    products    for “VistaKey”.  Some  examples  of  such  keyboards  are Senseboard,  VKB  Projection,  Light  key  [3,10]and Vkey. 
However,  except  the  Senseboard  keyboard,  all the  others  lack  giving  touch-typing  feedback  to  the user,  especially  for  the  touch  typists.  Furthermore  the users  of  Vkey,  LightKey, 
and  VKB  projection  cannot rest their hands  on the  keyboard image  by  keeping  the ingers  on  it.All  of  them  are  difficult  to  be  used  by people with paralysis or muscular disorder, because the typing  style 
is  a  bit  similar  to  the  normal  typing  style.  These  things  can  be  considered  as  some  of  the  major drawbacks  of  existing  products,  which  then,  can  be considered as some of the main features of “VistaKey”.
The   approaches   used   for   the   current   projection keyboards  such as  for  the  Senseboard  are  discussed  in [1,3,7].  Senseboard  uses  artificial  intelligence  together with  laser  technology.VKey  uses  laser  
technology with   visual   sensors   (cameras)   [1,3]to   detect   the movements  of  all  ten  fingers.  LightKey  uses  laser technology    with   electronic   perception   technology [3,9,10]   and   VKB   Projection   uses  
laser   sensors (infrared  cameras)  to  detect  thekeystrokes  of  all  ten fingers [1,3]. The   “VistaKey”   virtual   keyboard   proposed   in  this paper  uses  a  novel  approach  [6]  to  identify  the  letters according to
the touching movements of the user. That is,   Digital   image   capturing   and   image   processing techniques  [4,5]  together  with  the  normal  projection techniques. A  small  slide  projector  projects  a  virtual image   of   
the   full   size   QWERTY   keyboard.   The selection  of  characters  is  carried  out  by  a  LED  based light  pen.  When  the  user  selects  a  character  from  the virtual  keyboard  by  pressing  the  light  pen  against  the desired 
virtual character, the blue LED bulb in the light pen  is  illuminated  thus  giving  the  quick  touch-typing feedback to the user.Image capturing module captures these   touching   events   of   the   pen   and   the   virtual keyboard  using  a  web  camera,
and  sends  it  to  the character identification module. This module identifies the letters according to the touching events of the pen. Then  the device  emulation module  sends a  signal  with the   identified,   typed   characters   to   the   particular electronic   device, 
which   will   be   displayed   on   the device screen.  The following sections describe the techniques used to design  the  modules  in  order  to  achieve  the  keystroke identification.  Section  2.0  describes  the  designing  of the modules.  Section  3.0  describes  the  implementation and 
the  results  obtained.  Section  4.0  provides  the concluding remarks and possible future developments.
