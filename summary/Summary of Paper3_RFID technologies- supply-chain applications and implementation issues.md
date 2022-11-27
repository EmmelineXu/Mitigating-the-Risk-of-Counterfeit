# Summary of Paper3

**Paper title:** RFID technologies: supply-chain applications and implementation issues  
**Author(s):** Angeles, R.  
**Abstract:** RFID technologies hold the promise of closing some of the information gaps in the supply chain, especially in retailing and logistics. As a mobile technology, RFID can enable "process freedoms" and real-time visibility into supply chains. This article provides an introduction to the technology, several case examples, and implementation guidelines for managers based on published reports.

## I. Method

- The article concludes with a set of managerial guidelines for RFID deployment, based on published literature.


## II. Benefits

- Many tags can be read at the same time, even if they are located in the same small contiguous area.

- This research paper lists seven specific cases of applying RFID, which includes   
&nbsp; &nbsp; 1) move, handle, and track its consumer products in its warehouses;   
&nbsp; &nbsp;2) uses an RFID system to process the legal documents used to support shipments of goods for crates that go in and out of this warehouse;   
&nbsp; &nbsp;3) United Biscuits uses RFID technology to control raw materials movement;   
&nbsp; &nbsp;4) Fluoroware, Inc., developed a patented turnkey system using RFID technology for firms in the semiconductor industry, which oversees a series of steps in the chip manufacturing processes;   
&nbsp; &nbsp;5) The Port of Singapore has used RFID technology in conjunction with its Electronic Data Interchange (EDI) system in tracking cargo containers and managing the comings and goings of ships;   
&nbsp; &nbsp;6) Ford is using RFID for accurate and efficient routing and identification of vehicles through an automated production process;   
&nbsp; &nbsp;7) Toyota  replaced  its  old job card system with an RFID-enhanced automatic tracking system in its manufacturing facility. 


## III. Drawbacks

### 3.1 High Cost

- Problem: A major issue with the RFID tag is keeping costs down to encourage wider scale adoption. 

- Solution: The solution and the goal are to bring down the cost to about 5 cents per tag or lower using different methods such as shrinking the size of the chip itself and cutting the costs of the antenna.

### 3.2 Two Types of Collisions

- Type1- interfering signals: There are two types of collisions. The first type of collision involves signals from one reader that can interfere with signals from another reader when their physical coverage overlaps.

- Solution: The Time Division Multiple Access (TDMA) developed by the Auto-ID Center at MIT has used the anticollision scheme to help deal with this problem. Using this scheme, readers are programmed to read tags at different times rather than simultaneously. An ancillary system for deleting duplicating codes has also been devised to support the anticollision scheme.

- Type2- Reading many chips in the same field: The second collisions problem occurs when readers are reading many chips in the same field.

- Solution: The Auto-ID Center has addressed this problem by making readers ask tags to respond only if their first digits match the digits communicated by the reader. The reader keeps querying the tags until such time when one and only one tag responds, which is the desired condition.

### 3.3 The Frequency of Communicating with Tags

- Problem: Radio waves are used when readers communicate with tags. Radio waves are part of the electromagnetic spectrum whose use is regulated by governments around the world. A problem with RFIDs is that governments have assigned different uses for the various parts of this spectrum. Therefore, a tag operating at a certain frequency in one country may not be readable in another country where the same spectrum is used for a different purpose.

- Solution: To solve this problem, the Auto-ID Center at MIT has designed reference specifications for “agile readers” that can read chips of different frequencies, which allows firms to use only one reader in situations where multiple frequencies are involved and save them the costs of having separate readers for each frequency. However, the cost of “agile readers” is also high, which is expected to go down as newer technologies are developed for its use.

### 3.4 Disturbing Radio Waves

- One of the challenges is that of false reads as a result of radio waves being easily distorted, deflected, absorbed, and interfered with. Radio frequency portal readers can still be “distracted” by metallic objects within their field of detection. 

### 3.5 Repeated Recordings

- There is also a question about whether a reader can distinguish one shelf tag from another. If a forklift driver, for example, passes by a shelf tag about three times to fix the placement of a pallet, it is not certain if the reader system will record three separate pallets or recognize that one pallet information as one and the same.

### 3.6 Data Management Concerns

- The use of RFID technology presents a number of data collection and usage issues. Firms that have tracked pallets and cases with RFID tags report at least a 30 percent increase in data that needed to be processed. The level of granularity for data collection also needs to be determined. For example, goods that may need to be recalled such as fresh perishable produce or meat or high-value items such as expensive electronic gadgets or luxury designer goods may require a more detailed record of their movements through the purchase experience.




