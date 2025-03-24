![image](https://github.com/user-attachments/assets/5a276a39-9b24-4458-82f0-b1ed4aec1ad0)# NPTEL - VLSI Physical design with timing analysis
 
Week 1 (lecture 1-Introduction to VLSI design)

![image](https://github.com/user-attachments/assets/6111cae5-3cad-40e6-8df1-039beab117e2)


![image](https://github.com/user-attachments/assets/63c21c0a-ace4-4d8a-bb52-4159a8ee8b95)


![image](https://github.com/user-attachments/assets/ee2b0dee-cda4-426a-baa3-5c264f368700)


![image](https://github.com/user-attachments/assets/6056f384-15bc-4ec8-a7c1-50055eb1cbcb)


![image](https://github.com/user-attachments/assets/1bfd35df-e87c-46f0-a457-9cba387f1e8d)

Time to market is the driving force to make the chip. If the chip has to be manufactured within the small amount of time, then semi-custom design is the best thing to do.

![image](https://github.com/user-attachments/assets/2b14e9cb-533d-42eb-8bb6-ed174753fed1)

Semi-custom design are the designs that are designed and manufactured by the third-party companies and sold.

![image](https://github.com/user-attachments/assets/563ee186-d19a-49ac-bfe3-7d07a8c4802c)

![image](https://github.com/user-attachments/assets/c79abe8a-cb33-4d83-a807-cbcf8b83ad5a)

![image](https://github.com/user-attachments/assets/aa3b730a-11d2-4ab7-804d-ee9c547d84e7)

The heights of the standard cells are same or multiples of each other. The heiights depends on the number of metals on track. The width of the cells are the multiple of unit tile which is present in the technology file. The characterized library provides library files, timing files and power characterization.

![image](https://github.com/user-attachments/assets/c20316e8-c1b6-4788-9061-7251eaddc531)

![image](https://github.com/user-attachments/assets/e1af8a77-9bbc-4503-bc9b-2c91c6490ce1)

The channel is prsent as shown in the diagram below. The channel is used for the routing the metals tracks. There is also a thing called feed through cells which are used to route through another channels when the number of layers of the chip is minimum.

![image](https://github.com/user-attachments/assets/ac5da6ff-bc83-4ba0-a89b-a558c2fb1f6a)

Standard cell design is faster than the full custom design flow and it is more popular.

![image](https://github.com/user-attachments/assets/c8004938-7522-4174-88cf-f624833d466c)

![image](https://github.com/user-attachments/assets/4575486a-d946-40b9-82ea-e335d6c73e76)

![image](https://github.com/user-attachments/assets/3bcc1253-59bd-4b8d-9caf-a023270fa2b6)

Macro cells can be placed anywhere in the layout, but it should be placed in such a way that the delay will be reduced.

![image](https://github.com/user-attachments/assets/87250030-6602-4c8e-b3c2-5aac0fdd89a7)

The identical cells are repeated throughout the chip in the matrix form in Array-Based design style.

![image](https://github.com/user-attachments/assets/a5c53e88-9cf5-44c2-b374-5746e8c73855)

In uncommitted gate array, the routing layers are on the top. It is expensive because, we need to get a gate array and do the required things. In committed gate array, the routing layers will be present and we need to do programming to connect them according to our need.

![image](https://github.com/user-attachments/assets/a472dfd5-46b1-4e13-87ed-7307a1de694f)

Here, we map the actual design with it and do the routing.

![image](https://github.com/user-attachments/assets/e7cd7f95-53dc-4f8c-920f-ab5c16606396)

In committed gate array, the example is shown below where there are 5 NAND gates and we route them and use it.

![image](https://github.com/user-attachments/assets/e670d291-8caa-4563-a96c-a910bac532c6)

![image](https://github.com/user-attachments/assets/2abb7281-9ed6-45d2-8932-2f94dbec4490)

In the case of FPGA we have programmable IO, interconnect and LUT.

![image](https://github.com/user-attachments/assets/2eab94db-abd3-43ac-86a8-f8b0497adf1e)

Switch box are the interconnects that are programmable in the runtime. We can implement both combinational and sequential logics using this.

![image](https://github.com/user-attachments/assets/a9e3ccd4-583f-4d96-a012-c6d80a04e3f9)

Here, the gate level circuit is mapped to the LUT.

![image](https://github.com/user-attachments/assets/114793bf-27c3-4372-8e30-d30dc7187928)

Modules are the different blocks inside the system(chip) and how they are connected to each other. If we go into one of the module,
gates are there which is called gate level. Inside that we have transistor level. Then we have device which is implemented using silicon.
We need to do optimization in all the levels to achive the three targets mentioned in the diagram below.

![image](https://github.com/user-attachments/assets/a5266c61-2287-43c7-8b6b-59a4a8acb3a3)

![image](https://github.com/user-attachments/assets/5756e19d-2223-429a-be2b-9899cfc2d1f0)

![image](https://github.com/user-attachments/assets/615bf9f0-5b44-4419-93b1-e1ced711c33b)

![image](https://github.com/user-attachments/assets/8a341196-b554-491e-903d-c4478ffeeca1)

![image](https://github.com/user-attachments/assets/ca25f5ed-10ef-462c-8f22-802da0339409)

![image](https://github.com/user-attachments/assets/42d50d7b-efc3-474c-9d47-6404590ae324)

![image](https://github.com/user-attachments/assets/e4a45e85-5909-4115-ba9b-4041821791ae)

![image](https://github.com/user-attachments/assets/9dd8b32d-1c44-4794-a080-0564882042b4)

![image](https://github.com/user-attachments/assets/7bce0597-faf9-4a27-bb3a-bd46efc192bc)

![image](https://github.com/user-attachments/assets/36289c37-6a8d-45df-a084-24e23e1ed6c9)

Week 1 (lecture 2-Introduction to VLSI physical design)

![image](https://github.com/user-attachments/assets/711cd240-8413-475c-8023-6cbed03badfa)

![image](https://github.com/user-attachments/assets/6400d451-1935-4c34-85dd-3ba514f26754)

![image](https://github.com/user-attachments/assets/e902a973-25ed-411b-8cd3-cb6a67ab0ed7)

In Architectural design, we need to specify, which arcitecture(RISC, MIPS, etc) we are going to use. Also we need to specify, how the components are interconnected with each other and what kind of communication protocols we are going to use.

![image](https://github.com/user-attachments/assets/e89341d4-1a71-4c7c-b09d-923c67e9cac5)

![image](https://github.com/user-attachments/assets/862ba09b-2472-4847-b3b1-e2061a2c8783)

![image](https://github.com/user-attachments/assets/6a96b378-17a5-4192-8056-86e9fd7183db)

![image](https://github.com/user-attachments/assets/296ba7ed-c20d-418b-8620-4a8b97a24bb2)

Technology specific means, example: size of the transistor 6nm

![image](https://github.com/user-attachments/assets/f712fdae-4347-4f73-a2b9-9f65835a0009)

![image](https://github.com/user-attachments/assets/e4d68892-a2e7-49d6-ad2a-5235316fe6dd)

![image](https://github.com/user-attachments/assets/ddc64ab0-2f1c-4ff4-bf7c-a5f33c9bc40b)

![image](https://github.com/user-attachments/assets/60e7769c-951b-4907-a248-b55256b4a37a)

![image](https://github.com/user-attachments/assets/64a259b5-6a19-4401-a09e-27389e30c3ef)

![image](https://github.com/user-attachments/assets/0d1f4ec1-a7f7-479c-b719-ccf564b6140d)

![image](https://github.com/user-attachments/assets/85e2d2d1-762c-4f07-802d-4703cd3b28d1)

![image](https://github.com/user-attachments/assets/e77c5d12-5ba5-4efc-a10e-2063064a4c67)

Packaging is done to test the functionality of the chip.

![image](https://github.com/user-attachments/assets/b4f187d6-dfc9-4f0a-a79e-ef1d53deb3f7)

![image](https://github.com/user-attachments/assets/96740154-898a-4c17-abd9-ad80d7bd77ff)

![image](https://github.com/user-attachments/assets/25c25019-095a-41ec-8ebd-4504ae0db6a7)

![image](https://github.com/user-attachments/assets/29e0e0ba-3414-4ac1-aaf5-b58d5b9b7c95)

![image](https://github.com/user-attachments/assets/1fd62bb3-7cab-4587-98b8-54ab385b9f28)

The module shapes and arrangements are fixed during floor planning.

![image](https://github.com/user-attachments/assets/6c9765b4-fc90-4f0f-8224-3628dfa300e2)

![image](https://github.com/user-attachments/assets/8aec4c84-4366-41da-ba3e-92ea21f16440)

![image](https://github.com/user-attachments/assets/37e12525-2b23-4ead-841b-cce1f1301cd3)

![image](https://github.com/user-attachments/assets/e3d21480-ccca-4c07-af8d-eb2b542c70b0)

Timing closure is the most critical step. Here, the chip should maintain the timing that was specified initially by optimizing the placement and routing.

![image](https://github.com/user-attachments/assets/9c05ba92-5814-4f07-b57e-a2fd96efb47c)

![image](https://github.com/user-attachments/assets/e5b0f81a-3d56-4600-a82e-23a9f7b34483)

![image](https://github.com/user-attachments/assets/fcd12879-c987-4878-85c8-b3ff20c0b3d0)

![image](https://github.com/user-attachments/assets/d0995bfe-0244-44c9-8fc6-78f68622fb5b)

![image](https://github.com/user-attachments/assets/818f1169-22fb-4e2b-b794-f55ca973483f)

![image](https://github.com/user-attachments/assets/497dfdaa-544c-4306-bf7f-4a99515f4165)

![image](https://github.com/user-attachments/assets/fbf660ea-6813-466b-b1ed-7dfdee519909)

![image](https://github.com/user-attachments/assets/e363c35a-b442-4b38-96a4-f034ec178e8f)

![image](https://github.com/user-attachments/assets/7a0312e1-ec4a-41b3-b786-c143302cab28)

Device mismatch - the number of transistors are not same in the schematic and layout
property errors - different sized transistors

![image](https://github.com/user-attachments/assets/6e2fe45f-a30b-4243-b60f-1d3edc686988)

Missing device terminal - let us say that the substrate is not grounded, so this is a missing device terminal

![image](https://github.com/user-attachments/assets/7db8e857-cfd9-4e2c-b03a-04d494125ddf)

Schematic should be carefully designed. so, that it will be useful to check with the layout.

![image](https://github.com/user-attachments/assets/d96e35c6-dfc6-4304-8e9e-68b74ad1150d)

![image](https://github.com/user-attachments/assets/37bf5bc7-f161-4e8e-8d36-26113fce4cf1)

![image](https://github.com/user-attachments/assets/8c0b8a10-df7a-4731-a356-44c22ea3c964)

![image](https://github.com/user-attachments/assets/dcd5c2c4-fb15-4df4-8fb8-b0723da8d083)

![image](https://github.com/user-attachments/assets/b6d46beb-bcb3-4496-9fad-d4d6b8cbaae4)

![image](https://github.com/user-attachments/assets/72908d76-6f5d-44ce-bba3-a68b8ae1d073)

When the length of the metal is large, charge accumulation occurs and the gate of transistor will gets damaged. This can be avoided by using two methods as shown below.

![image](https://github.com/user-attachments/assets/ebde1908-81fc-482e-ac32-fb1a98e8a703)

![image](https://github.com/user-attachments/assets/944f3aea-a3ce-4227-addc-bbaccfb9d2d1)

Week 1 (lecture 3-Complexity analysis for algorithms)

![image](https://github.com/user-attachments/assets/b8e7d50f-1050-43a2-8278-fb7498e4b845)

![image](https://github.com/user-attachments/assets/e20998b9-41b6-4f07-bc50-bbffbd92fdd7)

Greedy algorithm - Finds the solution in less time. But, it is locally optimum and not globally optimum.
The Divide and Conquer and Dynamic programming algorithms are similar but the difference is, in Divide and Conquer algorithms, the divided subsets are independent and does not depend on other subsets and in Dynamic programming algorithms, the subsets will overlap on each other. 
Linear/ Integer programming algorithms - They are useful during routing.

![image](https://github.com/user-attachments/assets/1ee260bd-407f-437d-9bd2-6794bfd0aee9)

![image](https://github.com/user-attachments/assets/db80b640-fe2a-4898-b57a-d71539f0e003)

The below mentioned are important for the VLSI physical design implementations.

![image](https://github.com/user-attachments/assets/d22bc385-3925-41a4-af23-6a30666c67dd)

To understand the time and space complexity, we need to analyze the performance of the algorithms and select the algorithm which takes less time. Resource management - we need to choose the algorithm which takes less memory because, higher the memory, higher the space.

![image](https://github.com/user-attachments/assets/7fd9a322-6d45-45fc-b21c-42fe38293512)

We need to find a method where we can find the runtime of the algorithm which does not depend on all the below mentioned things.

![image](https://github.com/user-attachments/assets/cfe0c93d-395f-4a1c-aa40-71d95fd8a9cd)

![image](https://github.com/user-attachments/assets/37bdc7d8-8d80-4d69-9705-ef3e6e55f732)

![image](https://github.com/user-attachments/assets/9d9d7964-65d8-4edd-ac3b-8e23af94dbb3)

So, to find the complexity of the algorithm, we first remove the lower order terms and then we remove the co-efficient.

![image](https://github.com/user-attachments/assets/0dc94e0c-0d9b-4cef-8f43-9d0e997c4f27)

There is an analysis which does not depend on the type of the input, machine speed and the programming language. That is called Asymptotic analysis.

![image](https://github.com/user-attachments/assets/f1c6d0f7-7ed4-4e2d-bf2c-aed4d0a32f7e)

We have 3 different types of Asymptotic analysis. 

1

![image](https://github.com/user-attachments/assets/a4bff228-1041-4797-a0ba-9d357754e136)

![image](https://github.com/user-attachments/assets/a56f5cc7-5ef4-48fb-8286-f9991b2efd2f)

2

![image](https://github.com/user-attachments/assets/bee76051-e74f-4aba-80d9-3b61f743af46)

![image](https://github.com/user-attachments/assets/0dedf146-6e89-4f9a-85df-ec5c2e5176b0)

3

![image](https://github.com/user-attachments/assets/b807af14-c524-4400-a0dd-b59fa5b60753)

![image](https://github.com/user-attachments/assets/56297434-00f0-45fa-9c93-2b6cd9b873a9)

![image](https://github.com/user-attachments/assets/60bbe4b1-25b4-4a57-b1c4-1db4a039de49)

![image](https://github.com/user-attachments/assets/743b0de4-80a4-4397-b5e1-72a2469f25fa)

![image](https://github.com/user-attachments/assets/e7144420-87d4-40f7-85b8-23c9747e4cf8)

![image](https://github.com/user-attachments/assets/f2079fc5-5301-45ed-ac93-71ca91a78aa1)

Let us see how an algorithm can be implemented in two different time complexity.

![image](https://github.com/user-attachments/assets/608f357d-6aff-4f1e-a2dc-3ba342042c9b)

![image](https://github.com/user-attachments/assets/b9e89028-17cd-4862-b976-2f67083e82bd)

![image](https://github.com/user-attachments/assets/743fdb88-974d-4ad5-b82d-2533ea717d7b)

Here the we can't specifically mention the time delay in linear search. Because, the element can present in anywhere. But, the worst case time delay is the last element. So, we will say the complexity as the order of 'n'

![image](https://github.com/user-attachments/assets/9d93e28e-5b43-49b4-b05a-7ec90ae04e9f)

![image](https://github.com/user-attachments/assets/d8669dfa-15a9-4e7b-a5f0-0912e36f59aa)

![image](https://github.com/user-attachments/assets/9052ae3f-e6dc-4545-88cb-6ddc8cc416f7)

The examples of 'P' type algorithms are merge sort, linear search, etc.

![image](https://github.com/user-attachments/assets/7211cbc6-68cf-44d6-b691-e9c001248f95)

![image](https://github.com/user-attachments/assets/2032d983-a357-4f2f-938a-cc2aa604da01)

![image](https://github.com/user-attachments/assets/affb399a-2cd9-4b4b-a33e-f100e2c24d28)

![image](https://github.com/user-attachments/assets/07171bd6-ccc4-4517-b6b6-c4291437d0ea)

![image](https://github.com/user-attachments/assets/9218c44d-51ed-48ed-a8f1-a86b30e7eaab)

![image](https://github.com/user-attachments/assets/b0870e2b-2e70-4360-ae04-ae32a29b2675)

![image](https://github.com/user-attachments/assets/ce800396-d3df-40ca-9626-55f8bb4ec938)

Here, since the large problem is cut down into smaller problems, it can be solved using ploynomial time method and then will be merged.

![image](https://github.com/user-attachments/assets/0fdcdcfc-df7d-4b58-87f8-a6d8f251c58a)

When k=2, we can solve it using polynomial time method.

![image](https://github.com/user-attachments/assets/aaf049fc-e8f9-4049-a6da-1f843241e103)

![image](https://github.com/user-attachments/assets/1af2b1b6-63a8-4aed-92e2-1d430474a2df)

![image](https://github.com/user-attachments/assets/086a1f10-7c52-4e27-9ead-72b1fd7bc952)

Week 1 (Lecture 4-Graphs for physical design)

![image](https://github.com/user-attachments/assets/d272d829-cf87-445a-8f27-3b24db886c4c)

![image](https://github.com/user-attachments/assets/6949c6f9-854f-4df2-a03d-543d32c78593)

![image](https://github.com/user-attachments/assets/1ce8b6f0-96b4-4359-a515-1464e4b695f1)

The small circles are called node and the connection between them is called edges.

![image](https://github.com/user-attachments/assets/4971667c-2c19-4ec8-8c44-7c971b00c641)

![image](https://github.com/user-attachments/assets/0d0e4ecf-c4f4-42ee-bdf1-42c51823746f)

Hyperedges - Subset of two or more nodes.

![image](https://github.com/user-attachments/assets/5ae53e78-ff86-4316-8776-fe7869107b30)

![image](https://github.com/user-attachments/assets/cfa6de42-3542-4c15-88d8-b079bcf593b3)

![image](https://github.com/user-attachments/assets/09226010-e3de-453e-b2d3-853c803b62c1)

![image](https://github.com/user-attachments/assets/c7489950-7fa7-40cf-a27f-cb072ad49c2f)

![image](https://github.com/user-attachments/assets/092ad4fe-6230-4756-b423-65eaa5a84514)

![image](https://github.com/user-attachments/assets/1c82a255-8792-4392-89cb-b0d4a970e055)

![image](https://github.com/user-attachments/assets/c25c0b78-b287-4421-a89a-0321bc4d41fa)

![image](https://github.com/user-attachments/assets/63f6523e-bb71-4d37-a78c-021d5b158938)

![image](https://github.com/user-attachments/assets/f107d21f-b76c-4069-9966-827c168ca96b)

![image](https://github.com/user-attachments/assets/ca29a982-8ffb-4224-a25c-f7cba1c0d4d7)

![image](https://github.com/user-attachments/assets/9f6caec3-7aad-42e0-9a1b-23e68d57f946)

![image](https://github.com/user-attachments/assets/55badd8a-be20-4aa4-b3f9-1891aaa13f8f)

![image](https://github.com/user-attachments/assets/a0722568-dd69-4610-b5eb-60398794cca6)

The last column has '/' which represents that there is no nodes further.

![image](https://github.com/user-attachments/assets/bc917203-9cd2-4f57-919a-dd10413e2971)

This graph will be useful and best when there is less number of edges.
![image](https://github.com/user-attachments/assets/fe1902a2-fcf6-447b-b2da-2e6d5a96bd40)

![image](https://github.com/user-attachments/assets/2d6c53d9-253e-473f-9cf6-76943ed362df)

This graph is useful for static timing analysis. Because, the delay parameter can be inserted inside the column that is present there.
![image](https://github.com/user-attachments/assets/dd0ead6b-c726-4004-9123-06b3751426a6)

![image](https://github.com/user-attachments/assets/5ee41957-8523-4466-9330-3b0cfa2f42e0)

![image](https://github.com/user-attachments/assets/8bd89d43-3f53-4ee5-9935-8a5322148c0c)

![image](https://github.com/user-attachments/assets/7ac9ce88-58c5-4014-80df-1c1f3950f7c1)

![image](https://github.com/user-attachments/assets/d472107b-d8cb-484b-8459-4d3c97876d16)

![image](https://github.com/user-attachments/assets/3ce7b9c8-7679-4f7a-b29e-d751872bf10e)

![image](https://github.com/user-attachments/assets/7f08b07a-ca03-4a92-80bd-172966f3d10d)

![image](https://github.com/user-attachments/assets/00eea7ef-626b-4037-bc12-c8d4bc700ab1)

![image](https://github.com/user-attachments/assets/b377d48d-144e-47b3-8c58-00e1f6ef5d0b)

![image](https://github.com/user-attachments/assets/7d97de79-57da-423e-8d98-5fa00a4e291e)

![image](https://github.com/user-attachments/assets/c245e126-e2a3-4200-9b11-e07260f28740)

Here the intervels are A,B,C,D,E,F

![image](https://github.com/user-attachments/assets/58d9f144-0db8-4607-94b2-eca65945da67)

![image](https://github.com/user-attachments/assets/204399ea-f577-47a1-8373-b9e6a2cde411)

![image](https://github.com/user-attachments/assets/caedc8f3-af39-4365-85c2-b9c8fa9a6ad5)

![image](https://github.com/user-attachments/assets/52c3908a-76cc-42fc-9242-1bd1b479c0c1)

![image](https://github.com/user-attachments/assets/38931755-92d7-42c9-8b8e-9b59756dcc9e)

![image](https://github.com/user-attachments/assets/4b66d545-100e-4093-a231-79b0aa26bcfc)

![image](https://github.com/user-attachments/assets/45eede58-e86a-4bf3-ad4a-068ca77922a3)

![image](https://github.com/user-attachments/assets/aeac28bc-0cdf-4ce0-94ac-95a871515951)

![image](https://github.com/user-attachments/assets/ea0c274c-67fb-4a92-8f02-92a75e090735)

![image](https://github.com/user-attachments/assets/07213198-4a4e-493e-96b3-bd0550c83ce8)

![image](https://github.com/user-attachments/assets/ca9b23d1-ff61-4a54-85b4-1ef3d5a3501a)

![image](https://github.com/user-attachments/assets/dd928be8-302b-494d-9514-e2164bda8125)

Week 1 (Lecture 5-Graph searching algorithms)

![image](https://github.com/user-attachments/assets/fd6cc66a-a7ac-475f-9f72-6d307ab78ab8)

![image](https://github.com/user-attachments/assets/e90837fd-e6e0-4181-97cb-12ed508dfd74)

![image](https://github.com/user-attachments/assets/b4650cc0-16f8-45ca-ba16-68b79feb7fc9)

The Pseudo code of the DFS is shown below.

![image](https://github.com/user-attachments/assets/a702b9ec-713c-49af-9661-e63ae7865378)

The main aim is to find the discovery time and finish time of each of the vertices.

![image](https://github.com/user-attachments/assets/50db4e0d-ff94-41aa-809b-cc6eea58fa67)

Here, A has two adjacent elements. They are B,D and E. Let us select any one element first and we select B so, B is added to the stack. This is done for all the elements. Once it reaches 'e', it can't go further. Because, it has only 'b' in its direction and it is also already visited. So, the finish time of 'e' is given.

![image](https://github.com/user-attachments/assets/020c23fa-53e6-4dd5-8651-7080452bfae5)

Then it will go back to 'd' and 'c' is selected.

![image](https://github.com/user-attachments/assets/c615de69-9224-4a93-b56f-f02f2e33d8ad)

![image](https://github.com/user-attachments/assets/06c523c1-be9b-444a-ba27-2a282c0b4d43)

Then the top element in the stack is 'd' and so, the finish time for 'd' is given.

![image](https://github.com/user-attachments/assets/f2e78167-4431-47da-9cd8-98c4e21f9da0)

![image](https://github.com/user-attachments/assets/ea9b99b0-1f12-405d-952a-eccf7b4ccfd3)

![image](https://github.com/user-attachments/assets/452dcf2f-641a-4902-af30-47db418dacb5)

![image](https://github.com/user-attachments/assets/a9d91600-982f-4d90-a4cf-8ca8c8edacdc)

![image](https://github.com/user-attachments/assets/2e37efcc-ae1f-4110-aec4-6f3eabc005ee)

Now we have to visit the nodes that are not visited so far. First we will see 'w'

![image](https://github.com/user-attachments/assets/fcd523fc-7e99-47fa-844c-838f9a505eaa)

![image](https://github.com/user-attachments/assets/daa3d7c6-ec0f-47f1-b4cb-99b73de82ec3)

BFS

![image](https://github.com/user-attachments/assets/0ba891a1-da0d-41a0-a568-bb1aae39714f)

![image](https://github.com/user-attachments/assets/aece994f-2802-4a57-a300-91dd4aeabdcd)

In DFS algorithm we used stack data structure which follows LIFO principle. Here in BFS we use queue data structure which follows FIFO principle. There will be a source node 's' form where we will be starting. Here, since all the three t,u,v are visited at the same time, they are denoted as 1.

![image](https://github.com/user-attachments/assets/73defd1e-21e3-436b-896a-02cabc1f597e)

Now we look into adjacent nodes of 't' and we have 'w' so it is denoted as 2. Then we see for 'u' and there is none similarly 'v'.

![image](https://github.com/user-attachments/assets/a3d55c8d-0529-4d11-abf1-fbf9c2cbe279)

![image](https://github.com/user-attachments/assets/19614b6b-f105-4dde-962f-c066ace6829a)

![image](https://github.com/user-attachments/assets/d779ea32-9cc4-4007-bece-83f6607dd9b0)

![image](https://github.com/user-attachments/assets/2f3392c3-2c68-49e3-b51a-7b596848573c)

![image](https://github.com/user-attachments/assets/6d72f60a-b68a-40b9-a514-e028bad9d004)

![image](https://github.com/user-attachments/assets/173bdd9c-013c-4ba5-b0a8-c2d6947b9bdc)

![image](https://github.com/user-attachments/assets/a771fc0a-419a-4df3-ba20-c0bd4c770934)

![image](https://github.com/user-attachments/assets/41a38567-9cb2-483e-997a-79b1bf6a87bc)

Week 1 (Lecture 6-Spanning tree and shortest path algorithms)

These algorithms are used to reduce the wire length and hence the delay of the circuit is also reduced.

![image](https://github.com/user-attachments/assets/2d67134c-46fc-4c30-ab89-30b1ee13b70b)

![image](https://github.com/user-attachments/assets/304ab880-0cb2-4c6e-9767-ad204d30e1f0)

![image](https://github.com/user-attachments/assets/298beb16-080e-481e-bf1f-c2320780b898)

![image](https://github.com/user-attachments/assets/30523f5f-43b8-4a5a-a1d8-7a626f6790eb)

![image](https://github.com/user-attachments/assets/c89cc2e1-4711-401a-97c3-2cbca25865bc)

![image](https://github.com/user-attachments/assets/ebcd1c0b-720a-449a-ac2e-18d11b38bc17)

In prim's algorithm, we look for the path with low weight and also in a order(like 1,2,3,4). Once we did connection from a to d, the final cost is 4 and so we search for 5 and it is present between g and c. So, we do connect that.

![image](https://github.com/user-attachments/assets/6ef7138c-6c61-4e2e-bb5d-b96d33eccd62)

After that 6 is not there. Also, if we select 7, a cycle will be formed which is not allowed. 8 will also create a cycle.

![image](https://github.com/user-attachments/assets/0ed47784-ba44-4c57-b54c-6a5f04ad30d2)

So, we connected all the nodes with the minimum weights and hence it is called minimum spanning tree.  

![image](https://github.com/user-attachments/assets/9f071006-8731-4acc-aabf-b8781c6c8970)

![image](https://github.com/user-attachments/assets/554153ea-b14e-42e5-a921-433e1c8e7b4c)

In Kruskal's algorithm, we first need to see, which has the least cost. b,h and h,g is selected. Then g,f is selected. Then f,d and a,b are selected.

![image](https://github.com/user-attachments/assets/f66a4613-1013-40a2-adeb-a9e642ad6e0c)

![image](https://github.com/user-attachments/assets/3a4e2dc1-f788-4580-aa3c-29fe0bd0f464)

Shortest path algorithms:

![image](https://github.com/user-attachments/assets/6cbaac5a-33c9-4f05-b5aa-1c6db5fedfc1)

We have to find the shortest path from the source node s to all other nodes. So, we assign infinity to all the other nodes.

![image](https://github.com/user-attachments/assets/bf5e6cfa-9cde-4c1b-af1c-4bb6b89af16c)

![image](https://github.com/user-attachments/assets/6fe6fa12-4b39-41e5-b57e-80e540fd5d77)

![image](https://github.com/user-attachments/assets/01a1c4f8-0702-435e-b7d4-f2c787352bc6)

![image](https://github.com/user-attachments/assets/e80fc3a2-dd02-4246-9031-edd972bc038f)

![image](https://github.com/user-attachments/assets/05cab2fc-a874-4ca3-a3c2-6a0f19d69ef6)

![image](https://github.com/user-attachments/assets/4b74f687-85c3-4409-8457-d5959c9e0a01)

![image](https://github.com/user-attachments/assets/bee785e8-8257-4171-aa53-1ae60129c73f)

![image](https://github.com/user-attachments/assets/69f4562e-523c-4170-8029-03a6908f35af)

![image](https://github.com/user-attachments/assets/ff2f0777-5a6d-4df1-961e-64ca7a80b0b7)

Week 2 (lecture 7-Overview of timing analysis)

![image](https://github.com/user-attachments/assets/dc537156-8b52-4816-8ea9-7dd7d384ab9d)

![image](https://github.com/user-attachments/assets/cf2d2467-4f7e-4893-9245-ca5797acd718)

The longest path is determined to avoid the setup violation and the shortest path is determined to avoid the hold violation.

![image](https://github.com/user-attachments/assets/c62cfac1-86e2-4890-b353-a2e6ba8fa59f)

In order to maintain the timing closure at the end, we need to do the timing analysis at each step of the physical design flow. In case if the timing is not met in any of the flow, we need to go back and check the timing.

![image](https://github.com/user-attachments/assets/45dc5134-4daa-4288-a759-e9dcb579c18f)

![image](https://github.com/user-attachments/assets/8c2ad65f-7c23-4540-90d9-bdbeb80e1bc5)

In STA, no input is applied. The analysis is done for individual paths separately so it takes more time. Let us say that we design a processor with a clock speed of 1GHz and clock time of 1ns. This time will be given as a timing constraint and the analysis is done. 

![image](https://github.com/user-attachments/assets/5db6112c-cd36-4511-aa02-0a70bcc44e85)

In DTA, the inputs are applied and the expected output is also checked.

![image](https://github.com/user-attachments/assets/7d6e6cd7-3ab3-4442-a9cd-a8c8e222a9dc)

![image](https://github.com/user-attachments/assets/8630d33d-49a2-4458-88cb-67146ebc634b)

There are multiple timing path available from the source node to the destination node in the below circuit. So, all the paths need to be analyzed by the STA tool in order to find the worst case path in the design.

![image](https://github.com/user-attachments/assets/461befc9-360b-410a-bb49-5d47394e5af2)

![image](https://github.com/user-attachments/assets/6f513013-c6b2-4f76-962c-c92992d224c4)

We need to instruct the timing analysis tools about the false path. Because, it might consider this false path as a critical path.

![image](https://github.com/user-attachments/assets/a46e0b2f-4a13-4b83-b994-66fe242326c6)

![image](https://github.com/user-attachments/assets/4c4bc095-50e0-438e-945f-599484190b3c)

![image](https://github.com/user-attachments/assets/b3cfbf92-ee9a-43cb-ac1e-89098c5e0876)

![image](https://github.com/user-attachments/assets/e4133335-a99e-4a27-b168-699579b8070e)

![image](https://github.com/user-attachments/assets/1ea7d55e-a781-4930-91a7-0066f55f5bc4)

![image](https://github.com/user-attachments/assets/79f13329-4130-4ad4-ae11-c3ef6042f9a2)

![image](https://github.com/user-attachments/assets/662cc6c5-c7a9-4261-a3d1-5e042644f7b8)

![image](https://github.com/user-attachments/assets/ce0cd98f-6749-460c-b42f-019e5290f2a3)

Week 2 (lecture 8-Timing arcs and unateness)

![image](https://github.com/user-attachments/assets/fa2a6a85-e57d-429f-8d56-96087ae63f44)

![image](https://github.com/user-attachments/assets/4dffbb30-f45a-4979-9610-066dde400302)

![image](https://github.com/user-attachments/assets/df9444b5-0486-420a-9a35-6794a3be0b6a)

Unateness is also important for the timing analysis and it is used by the STA tools. Timing sense is denoted by unateness.

![image](https://github.com/user-attachments/assets/d35188a3-1244-4599-801b-335383ebc6ab)

Let us see the timing arcs of AND gate. It has multiple timing arcs. There are 5 arcs shown for AND gate. But, the 5th arc is not used. When '0' is given to one input, the output will be of 'no change'. But it is not used because, when one input is '0', the input will not gets propagated to the output.

![image](https://github.com/user-attachments/assets/214c6d7e-c722-40ee-9600-8937d0f221ba)

Till we discussed about Positive unate, then we discuss about negative unate.

![image](https://github.com/user-attachments/assets/347878f7-3abf-43a6-86a7-144ef3aa2609)

For NAND gate, 5 arcs are shown and in the 5th graph, when one input is 0, without considering the other input, without change, the output will always be high. So, it is not a valid timing arc.

![image](https://github.com/user-attachments/assets/bf754f97-9b20-444d-a011-1eac57f2122f)

In Non Unate case, the output rise and fall transition is not directly reflected on the input rise and fall transition. It depends upon what is the condition in the other pin.

![image](https://github.com/user-attachments/assets/10d233a2-c64e-4b3a-93a2-72e2a47dab8b)

Here, the .lib file used for timing analysis is given. It is given for inverter. It can be used by the timing analysis tool.

![image](https://github.com/user-attachments/assets/37d7430d-6173-4659-a3bb-52ee9d6242c2)

Till now we did the timing arc of combinational circuits. And hereafter we will see the timing arc of sequential circuits.

![image](https://github.com/user-attachments/assets/2c1b8132-e6a3-4b03-9a81-71a0c6031e22)

The output 'q' will come after the rising edge of the clock. The time between the rising edge and the data change is called the 'clock to q delay'.

![image](https://github.com/user-attachments/assets/ef110542-823a-41ec-bdaa-608fa8fff331)

![image](https://github.com/user-attachments/assets/6112cdc8-7ebb-4466-9fcc-587f41772610)

Recovery check arc: The minimum time required between the deassertion of the reset signal and the arrival of the clock signal, such that the data can be captured by the clock's rising edge.

Removal check arc: The minimum time after the rising edge of the clock, the reset should high to make the output in '0' till the next rising edge of clock. Why is this needed?, The output 'q' is driven by two inputs reset and d. So there is a possibility of creating a metastability state.

![image](https://github.com/user-attachments/assets/eb605dde-d859-4154-bf41-4dd727053019)

![image](https://github.com/user-attachments/assets/36cf1b34-00fb-4785-95a5-33ff3cc7ce87)

Week 2 (lecture 9-Delay Parameters of a Combinational Circuit)

![image](https://github.com/user-attachments/assets/5bf8886c-0314-4a95-84fe-c69606137f2c)

Combinational circuits are the circuits where if we give any input to it, the output will gets generated after a delay. If the input changes, the output will also respond immediately. The input pulse width 'tpulse' should greater than the delay of the inverter, so that the output will come out and the delay can be measured. The below mentioned delay property(case 2) is the inertial delay property of the combinational circuit. 

![image](https://github.com/user-attachments/assets/4c69061d-3ef7-44cb-a06c-7c42cb3b913b)

How we can use this delay for the timing analysis?.

![image](https://github.com/user-attachments/assets/59f03a6a-1608-46d7-b05b-896c9728c88f)

![image](https://github.com/user-attachments/assets/e6c7d953-7164-4eb5-8269-545f3ebefd28)

![image](https://github.com/user-attachments/assets/4ef77139-2620-42b0-99c5-47b7304cd3ef)

From the previous lec_ture, we understood that the buffer is positive unate and the inverter is negative untate.

![image](https://github.com/user-attachments/assets/6f7f726a-f037-4a81-a6be-c359afd5e89c)

These rise and fall propagation delay are charcterized before the timing analysis of the path.

![image](https://github.com/user-attachments/assets/5ccc17a9-afb7-41a1-a64e-502a34201263)

![image](https://github.com/user-attachments/assets/ab77463d-440c-415b-bee0-c6c3e492932c)

Here, why does the rise and fall transition time come into picture.

![image](https://github.com/user-attachments/assets/153e47ef-597d-4655-bdeb-9e0145c70ede)

The timing diagram which explains it is shown below.

![image](https://github.com/user-attachments/assets/7134667a-192a-44db-aff4-395783592edc)

Now what we are discussing is for the inverting gate and the things will change for non-inverting gate.
We might think like, we need only the propagation delay and why we bother about the transition times?. Because, when more than one circuits are cascaded as shown below, we need those datas to calculate the delay.

![image](https://github.com/user-attachments/assets/56ab3d8b-d0a3-4c16-8d2d-f0695b75a31c)

Now, let us take a path and do the timing analysis and now let us not consider the transition times. If we look into the circuit, all the gates are inverting in nature.

![image](https://github.com/user-attachments/assets/a204d46f-d45e-4009-abdc-89da3a279113)

So, the rise propagation delay of this path is critical than the fall propagation delay.

Week 2 (lecture 10-Delay Parameters of a Sequential Circuit)

![image](https://github.com/user-attachments/assets/e395f25a-6f46-4bbb-9b65-a6f30684f3be)

In sequential circuits there will not be a delay like we seen in combinational circuits. But, the input signal will wait for the clock signal to propagate to the output.

![image](https://github.com/user-attachments/assets/fb8fd82e-4d7a-43c9-acd6-771e63c52a1c)

We have two MUX and indirectly they are latched. Because, they have feedback loop.

![image](https://github.com/user-attachments/assets/fd5de665-945d-4498-b4ba-e8efbf6eea8b)

![image](https://github.com/user-attachments/assets/be0014ee-2d5f-4d5a-9c91-bbd5e696d2eb)

Now let us go into the FF and see what are the delay available there. So, let us see the concept of Transmission gate first.

![image](https://github.com/user-attachments/assets/868de405-2eee-4a77-a75f-2c6af3eff4a5)

The input 'D' should arrive faster than the setup time. Otherwise, the data will not get in output.

![image](https://github.com/user-attachments/assets/90a7f664-daf9-40fa-89d7-fd2b66a78aeb)

During hold time, T2 and T3 are in ON state. And we need the data to be sent from 'Z' to 'Q'. At that time, if an unwanted data come form 'P1', that will also reflected in 'Q', which is not desired and this is due to HOLD VIOLATION. In case 1, the data should come after the rising edge of the clock so that it will be propagated. Because, if 'Tinitial' is smaller, then data D can go from 'P1' to 'W' faster and it can corrupt the data. In the case 2, the rising edge of clock and the data comes at the same time. So, the Transmission gate 'T1' will gets open and the data will not cross 'T1'. We are finding the hold with respect to the rising edge of the clock, so we are concluding like +ve, -ve,=. In the case 3, the data never crosses the 'T1' gate and so, the data in 'W' is not get corrupted. But, we should not add more buffer to the 'Tinitial' so that the hold will be negative. Because, it will also make the setup time longer and the speed gets affected.

![image](https://github.com/user-attachments/assets/1902da81-1409-48f7-8420-83a9e120337f)

Week 2 (lecture 11-Timing Analysis in a Sequential Circuit)

![image](https://github.com/user-attachments/assets/a30f1603-26a7-49b6-8a53-f6c5c35cc93b)

The first four delay is for the FF and the last two is for the combinational circuits. If we wish to find the maximum delay, we need to find both delays.

![image](https://github.com/user-attachments/assets/0906f31a-7f87-4f15-be6c-ff83c3d1d643)

Uses of sequential circuits is shown in the diagram below. In pipeline, if we have bigger combinational delay, we will divide the delay into smaller combinational delay and place the FF between the combinational delays. It is also used in other places like shift registers, counters etc.

![image](https://github.com/user-attachments/assets/66155a40-0fa7-4d20-a9dd-4315e0183869)

Maximum Timing Analysis:
FF1 is launching the data, so it is called launch FF. FF2 is capturing the data, so it is called capture FF. This analysis starts with one clock edge and ends in another clock edge(one cycle). Let us say  that there are 'n' number of FFs. So, we have to do the maximum timing analysis for all the FFs(ie :the worst case time) and then fix the clock signal or the frequency of operation.

![image](https://github.com/user-attachments/assets/4f4f378f-7f3f-4133-85cc-d541b4f52340)

s-slow, t-typical, f-fast. There are many corners as shown in the figure below which depends on the speed of transister. And for worst case analysis we use this. For maximum timing analysis we use 'ss' where the nmos is slow and also the pmos is slow.

![image](https://github.com/user-attachments/assets/ce4b09f1-13af-4d92-aea3-23a6193f3ac9)

Minimum timing analysis:
For this we consider the hold time. For maximum timing analysis, we used one clock cycle(ie: two edges). But, here we will use only one edge.

![image](https://github.com/user-attachments/assets/9d3ae8b0-c627-4d95-bb7d-92105733a818)

After manufacturing, if the chip has a setup violaton, it can be rectified by slowing down the clock speed. Because the clock is sent from the outside chip. But, if there is a hold violation, we can't insert a buffer after manufacturing. So, it is not easy. But, there is a technique which is adding number of isolated buffers based on the requirement. This is possible because, these are in metal layers and not in the transistor level. So, this metal modification will be quite low cost compared to the manufacturing of the chip two times.

![image](https://github.com/user-attachments/assets/524401b5-8651-4106-a264-e8347abba989)

Week 2 (lecture 12-STA in Sequential Circuit with Clock Skew – I)

![image](https://github.com/user-attachments/assets/475ed795-650a-4972-941e-78d3a3464e3e)

Ideally the clock will reach two FFs at the same time. But, practically it will not attain at the same time due to the buffer present in between them or due to the length of the interconnect which provides some delay.
Spatial variation - location of FF. Even if there are two buffers, their delay time should not be similar.
static variation - once the chip is fabricated, we can find the variation in the clock skew between two registers or FF and it will not dynamically change.
A.T: Arrival Time.

![image](https://github.com/user-attachments/assets/cb7d6553-0146-4b2b-85ad-33f8cf736ccf)

If the data and the clock is moving in the same direction, then it is positive skew.

![image](https://github.com/user-attachments/assets/e61d6742-eb1f-465c-98b7-cf27f960b48e)

![image](https://github.com/user-attachments/assets/3c533a8c-d650-4206-aef7-0fa0a4aff775)

From the below slide, it is concluded that the positive skew will increase the speed(frequency). But, there is a disadvantage which is seen in hold check.

![image](https://github.com/user-attachments/assets/96d3b729-4d16-423c-8cea-6753eafbdf3e)

For setup check, we considered edges 1,2,3,4. But, for hold check we consider only edges 1 and 2. It is important to note that, if the setup time is violated, we can adjust the clock speed. But if the hold time is violated, we have to refabricate the entire chip to add buffer or we have to add buffer using the metal layers as mentioned in the previous lecture.

![image](https://github.com/user-attachments/assets/aa4752fa-71bf-4d27-84bc-2cca82f5b514)

Week 3 (lecture 13-STA in Sequential Circuit with Clock Skew – II)

![image](https://github.com/user-attachments/assets/d30844ed-3f73-4b5e-9987-a87a0d51d658)

![image](https://github.com/user-attachments/assets/b2374547-3da0-44c8-bc52-edf472d88a50)

![image](https://github.com/user-attachments/assets/761f02a2-aa77-4e8c-912a-1fb0c9d3f737)

This delta will help to fix the hold violation easily. 

![image](https://github.com/user-attachments/assets/ee17fcfe-d72a-44e2-87d4-c9bbc33903fc)

![image](https://github.com/user-attachments/assets/cde18284-0ee8-479e-b0ab-32e652482703)

We should note that, even if we adjust the clock speed, it will not mitigate the hold violation. The only way to solve is to insert the buffer in combinational path. Initially we do the analysis without the skew and then we do the analysis with skew. And we here considered positive skew.

![image](https://github.com/user-attachments/assets/73688716-4048-4127-ab47-5184cc3de3f7)

![image](https://github.com/user-attachments/assets/12ec1cce-90df-4062-9f7a-762497f066c7)

![image](https://github.com/user-attachments/assets/958450c1-bd79-401a-bf58-fd89a935dc5b)

![image](https://github.com/user-attachments/assets/e1589bba-07b3-4c97-a3ae-ed69f5917963)

Clock generation can be done using PLL or crystals. We should know the specifications of those things. Because, that is source of jitter.

![image](https://github.com/user-attachments/assets/02f9ae80-d362-4a4f-82d4-6dfd373d81a4)

![image](https://github.com/user-attachments/assets/a2170cf1-464c-4a9f-8962-5e1922dc5817)


![image](https://github.com/user-attachments/assets/cf4c5cf6-49ad-4a49-a686-91522b820e95)

Week 3 (lecture 14-STA in Sequential Circuit with Clock Jitter)

![image](https://github.com/user-attachments/assets/0cf0e0e7-2ac7-4d1f-a1b9-f25f7378032a)

![image](https://github.com/user-attachments/assets/1f25f6b5-52c1-4b4e-bd0d-4eb89d8eebd9)

![image](https://github.com/user-attachments/assets/326c672b-9234-4eed-82cf-1f06bb700045)

![image](https://github.com/user-attachments/assets/8ae9eed4-c6f0-4636-ad7a-117cd6225d73)

![image](https://github.com/user-attachments/assets/8e0c2a26-750b-4ad1-a772-a1788ea3b077)

![image](https://github.com/user-attachments/assets/2864a68f-e91f-49c5-91c1-b0d2db6332f1)

Week 3 (lecture 15-STA considering OCV and CRPR (Setup check))

![image](https://github.com/user-attachments/assets/bd8e1e5a-d48f-49e2-a4e2-1c368b6af61c)

![image](https://github.com/user-attachments/assets/00483c77-2b1f-4ea3-9b8b-c5739ebb2fcb)

As mentioned in the diagram above, for setup time check, the data arrival time should be less than data required time for the successful capture of data at the capture FF.

![image](https://github.com/user-attachments/assets/3f3f8e01-aeb2-44dd-b3ff-eb5d673282f9)

![image](https://github.com/user-attachments/assets/df853956-12b8-4346-958b-22749fd1e9f2)

When the slack is positive, the data will arrive fast and wait for the clock to reach the FF in capture FF. Here the time is wasting and no other issues. But, if the slack is negative, it leads to setup violation.

![image](https://github.com/user-attachments/assets/7f34960f-a283-4fcf-868c-6f68a8b2df37)

![image](https://github.com/user-attachments/assets/3a8ebffc-5aad-4f26-b20c-785b02151e86)

For the worst case, The data arrival time(DAT) should be treated as maximum and data required time(DRT) should be treated as minimum. 

![image](https://github.com/user-attachments/assets/b16824f1-83f6-4784-8b88-84ad462bc6d6)

![image](https://github.com/user-attachments/assets/03aab3c8-9c0d-48ff-bb00-d1b08db8bffe)

For launch path and capture path we considered late and early respectively from the same common path itself, which is not correct. Because for the same path we considered early and late. So we introduce a term called CPP.

![image](https://github.com/user-attachments/assets/470df222-594b-4030-a46a-0819f17d458a)

We have different derating for the launch path and capture path which is not correct. So, we need to correct it with the CRPR.

![image](https://github.com/user-attachments/assets/da23260a-b9c1-47e4-b49f-2ec59d6d4501)

Week 3 (lecture 16-STA considering OCV and CRPR (Hold check))

![image](https://github.com/user-attachments/assets/a7467b24-933f-4c7e-84c1-3ea04ee2755f)

![image](https://github.com/user-attachments/assets/2e38daa3-683d-4b8e-aaa5-e6519160fca9)

The below shown is the ideal case which has no buffer.

![image](https://github.com/user-attachments/assets/23c44a7b-d784-489e-b2fd-d8fff33a981c)

![image](https://github.com/user-attachments/assets/ed5d54b6-337e-4ca5-92e3-ebfd39857483)

The derating factors are given from the foundry.

![image](https://github.com/user-attachments/assets/c7747a95-a53e-4f85-b771-f5f177e5ec7a)

Still hold violation exists but it is reduced. And it can be solved by buffer insertion.

![image](https://github.com/user-attachments/assets/b9769123-baae-41d0-b52d-9e066157df8b)

Week 3 (lecture 17-STA for Combinational Circuits – I)

![image](https://github.com/user-attachments/assets/d15f754f-e43b-4755-bca0-ecb8700049c1)

![image](https://github.com/user-attachments/assets/d013806a-65b9-45fa-ba22-0a49c2281d20)

![image](https://github.com/user-attachments/assets/cce0448c-5aa4-4895-95a4-0d287674af42)

3/4 -> 3 is the rise arrival time of a, 4 is the fall arrival time of a.
2/3 -> 2 is the rise time, 3 is the fall time.
6/8 -> 6 is the output rise arrival time, 8 is the output fall arrival time.

![image](https://github.com/user-attachments/assets/7155d1d6-5b30-477f-9c7d-9baf432481ee)

![image](https://github.com/user-attachments/assets/4373ef90-16ba-494d-8245-25754999e42e)

![image](https://github.com/user-attachments/assets/f45bb424-e67f-4b97-9d5a-adb6a6af8dff)

![image](https://github.com/user-attachments/assets/0bf6d46b-c7a6-420b-b47f-c2992bd89e2d)

![image](https://github.com/user-attachments/assets/4d0ac295-2b61-4e99-a690-d810516242fb)

![image](https://github.com/user-attachments/assets/5e1a76d3-8b90-4048-840d-7f8d068becd6)

![image](https://github.com/user-attachments/assets/ae4ef986-d7f1-4310-b470-cb0230395108)

Week 3 (lecture 18-STA for Combinational Circuits – II)

![image](https://github.com/user-attachments/assets/f466d92c-e591-4632-8766-48e49b9f3846)

![image](https://github.com/user-attachments/assets/c6f1d71d-5e2b-49fd-ba3e-69dbed63517e)

![image](https://github.com/user-attachments/assets/5500778b-c2cd-4a34-9614-5bcea3b5074d)

![image](https://github.com/user-attachments/assets/09ec48b2-c709-4f60-b426-6b2384e51d6e)

![image](https://github.com/user-attachments/assets/8e8d973d-8fd2-4ead-bde2-ea8d73de0f66)

a and b inputs have same required time. Because, a and b are the inputs for the same gate. Similarly for c and d.

![image](https://github.com/user-attachments/assets/443ceae9-e784-474f-aa67-0b68c243aec6)

Critical path is the one which have largest negative slack. So, when we are finding the critical path, we have to move from the Primary output to the primary input.

![image](https://github.com/user-attachments/assets/1e18b374-58ad-404e-a39a-84d648f09881)

Week 4 (lecture 19-Introduction to Partitioning – I)

Partitioning is the first step of any System level or Board level or Chip level design.

![image](https://github.com/user-attachments/assets/54888f88-725c-442a-9510-6fa005341e14)

Partitioning is done to increase the productivity. Eg: Dividing the processor into, ALU, control unit, etc. This method is quite similar to the Divide and Conqure Algorithm.

![image](https://github.com/user-attachments/assets/2be88d31-291f-426a-a977-70828fd76e3e)

There are 48 gates present. And we are planning it to divide into 3. So, each partition should have like 16 transistors each. But, we can adjust some gates as shown below. So, different people can work on the implementation of each partition parallely and combine it for faster process. Looking at the interconnects inbetween the partition is also important. This is one method to implement faster. 

![image](https://github.com/user-attachments/assets/66642bff-0c60-475b-abf9-3260c35101ee)

Finding the best partition.

![image](https://github.com/user-attachments/assets/c23e1caf-f46f-4631-aa74-c60b954babb0)

Also, we should not do partition blindly. The number of interconnections between partition should be as minimum as possible.

![image](https://github.com/user-attachments/assets/ef81c764-f31c-42f2-a5fc-83ed36035a70)

Cell - Eg: logic gates.

![image](https://github.com/user-attachments/assets/bb4642ed-3595-4af5-a2db-b6b8da101021)

![image](https://github.com/user-attachments/assets/b39d16c8-e03f-4729-bfd8-f5bfe45771c6)

Eg:
![image](https://github.com/user-attachments/assets/e2df127c-feae-4c62-9434-4ee6b45b2d5c)

System level partitioning - Eg: Boards in the computer like mother board, memory and other boards.
Board level partitioning - Eg: ICs in the PCB

![image](https://github.com/user-attachments/assets/884fc8d9-30ee-42b9-84ed-f65ce9d5d6f5)

![image](https://github.com/user-attachments/assets/9b0e5988-9a26-4c40-ab84-c29ce06e7d57)

![image](https://github.com/user-attachments/assets/701574b9-98a7-448a-998d-7c014ea42c47)

![image](https://github.com/user-attachments/assets/15081435-011d-40b8-a48f-5d4e305f9430)

![image](https://github.com/user-attachments/assets/adb32a85-a5fb-4089-947d-64361376a603)

![image](https://github.com/user-attachments/assets/94094b61-d4f1-4060-86ae-f052df22ae78)

We can't change the routing inside the chip. But, we can optimize the routing in PCB board. The requirements will depend on the need. Eg: let us say that we need high resolution ADC, then we can use PCB 3.

![image](https://github.com/user-attachments/assets/c50e7e3d-9275-4381-971b-208b3136af0d)

Week 4 (lecture 20-Introduction to Partitioning – II)

![image](https://github.com/user-attachments/assets/4219fc98-3afe-4bc2-a01c-e52683710daa)

![image](https://github.com/user-attachments/assets/19d1ef89-b923-41bc-a382-f9ea03fe3e97)

![image](https://github.com/user-attachments/assets/9500b4ae-8523-4ca1-8a08-c11710dd2dba)

![image](https://github.com/user-attachments/assets/a3a4fb93-16ad-4693-9078-8429495f7e2b)

![image](https://github.com/user-attachments/assets/51bfe184-cde9-4f05-be44-4918f030f6eb)

![image](https://github.com/user-attachments/assets/970a592f-14f9-4097-8b46-184a4b1e0776)

![image](https://github.com/user-attachments/assets/47d4c986-a011-4b44-ad57-13ecb339ed1c)

Now we will see some constraints.

![image](https://github.com/user-attachments/assets/edf3ae6b-d92d-4342-b4af-c0340b68998a)

![image](https://github.com/user-attachments/assets/45520314-7618-4f35-9a47-a764407c8633)

![image](https://github.com/user-attachments/assets/49a4205f-5580-4d9a-9dfd-dc6b3a0fdc43)

![image](https://github.com/user-attachments/assets/d5acaac3-5f00-4fd4-870c-61be10a8041e)

![image](https://github.com/user-attachments/assets/33b68806-033c-4f2f-92d5-8547953134ac)

![image](https://github.com/user-attachments/assets/8870ba4f-6bad-4564-a24b-0468164d0f9a)

Pitch - distance between two terminals.

![image](https://github.com/user-attachments/assets/f8ea3d61-c2fc-4537-bf4e-bdf656501f1b)

Obj1 : Minimum number of cuts between partitions. Cons1: Number of terminals. Cons2: Area

![image](https://github.com/user-attachments/assets/f1c24ac8-b7e6-4936-a27f-79bc38d52158)

![image](https://github.com/user-attachments/assets/8e7f04c6-cbaf-4c7f-94e9-60ba3f9bed74)

![image](https://github.com/user-attachments/assets/879be37e-d26c-43f8-b85d-97b28250c3bb)

Week 4 (lecture 21-Partitioning Algorithms)

![image](https://github.com/user-attachments/assets/684c4dac-bfea-4d8b-b6ba-7fae91d7c734)

![image](https://github.com/user-attachments/assets/5fd50c19-b09f-4fe3-aba9-2452d6c0a11a)

![image](https://github.com/user-attachments/assets/da6ce8e9-8723-4c08-b92e-2b148a510294)

initial partition - It means that we don't get the optimal solution but we get the partition in less time using constructive algorithms.
1.Based on the availability of initial partition
![image](https://github.com/user-attachments/assets/bb401a9c-1c13-4c69-9fb4-d37e120c8dd4)

![image](https://github.com/user-attachments/assets/ae5b10dc-d1c7-48c9-9525-68a4d14193de)

2.Based on the nature of algorithms
    In deterministic algorithm, if we give some input to the algorithm, we will get the same solution all the time.  

  ![image](https://github.com/user-attachments/assets/b0ef9fcd-fb76-496e-a2e6-5eb16bacb0b8)

In random algorithm, if we change the input, we get different outputs.

![image](https://github.com/user-attachments/assets/62e9f791-5a04-4ba8-8651-da90cac7432a)

3.Based on the process used for partitioning.
    In group Migration algorithm, the inputs will the initial partition that are generated before. In the picture, if we move G2 to the P2, the number of interconnections will be reduced.

  ![image](https://github.com/user-attachments/assets/efe61e9a-2088-4c63-a6ec-851b9aa399e1)

In deterministic algorithms, we should get only optimal solutions and it is not ready to take any bad solutions. But in this method shown in the below picture, it allows to consider even the bad solution with the hope that we will get better solutions in the future iterations.

![image](https://github.com/user-attachments/assets/383b620c-7173-41d5-a786-bf08d29c747d)

Simulated anealing is one of the algorithms used in the industry for partition. 

![image](https://github.com/user-attachments/assets/197bc44e-62be-407b-9621-2602efcebfac)

![image](https://github.com/user-attachments/assets/03049bbe-d86f-4314-b529-6aab9e6cbe47)

![image](https://github.com/user-attachments/assets/5b169c8d-665c-4602-8326-b54cb98fb15b)

![image](https://github.com/user-attachments/assets/dccc1647-aef6-4ca8-98fc-4ee750b04337)

![image](https://github.com/user-attachments/assets/b11b46ae-c75e-4d02-80f5-86b5d829815e)

![image](https://github.com/user-attachments/assets/34cb301a-3c89-4eec-8120-8cba05c6871b)

In KL algorithm, there should be equal number of nodes maintained in each partition. So, if we want to move one node from this to other partition, we also have to move one node from other to this partition. If there is a edge present between g1 and g2, we have to consider the edge weight. Otherwise it is 0.

![image](https://github.com/user-attachments/assets/11e699ab-9313-4982-9510-f4e6cc9acc98)

![image](https://github.com/user-attachments/assets/d40f65ba-190d-4202-8944-61f1a033a578)

![image](https://github.com/user-attachments/assets/9a1717f1-5ef7-4703-8a6d-8c9dd78797d3)

Here, the gain is maximum. So, we swap the two nodes.

![image](https://github.com/user-attachments/assets/4984c84b-36bb-4040-9439-5f4100f01b56)

![image](https://github.com/user-attachments/assets/8f027bae-d2dc-4fcc-9907-e839e6ccf0c1)

Week 4 (lecture 22-Kernighan – Lin (KL) Algorithm)

![image](https://github.com/user-attachments/assets/f1f91e74-b9c5-4f2c-b05b-829fe5ba4c69)

![image](https://github.com/user-attachments/assets/b75f6a0f-1d9d-434f-9c9b-60e640fe4f48)

![image](https://github.com/user-attachments/assets/22222f11-ad7c-423e-bc8b-28b09fa4176d)

This process will continue till all the nodes are fixed.

![image](https://github.com/user-attachments/assets/bf231be7-70c5-4f17-aca5-5fe4e59b04a0)

![image](https://github.com/user-attachments/assets/8b1a4348-b27c-4942-b414-3b0e7816e8e1)

![image](https://github.com/user-attachments/assets/5fabebd4-e708-4445-8349-5e2fbb25f4ca)

![image](https://github.com/user-attachments/assets/4648ea53-755d-4ad6-a142-36402a7ab9ff)

![image](https://github.com/user-attachments/assets/054b1350-f657-406c-a2b0-3895878b1933)

Now, node 2 and 9 is fixed.

![image](https://github.com/user-attachments/assets/54e96693-9aa4-4869-81a5-1ec592480e39)

![image](https://github.com/user-attachments/assets/d4b6723d-da11-4c6c-996e-301a2020cad6)

![image](https://github.com/user-attachments/assets/0e9ed2eb-17bb-4ff5-a0a6-a1d760bd7fa2)

![image](https://github.com/user-attachments/assets/efcbb0e3-7bc9-4c90-a610-8486f29e7eea)

![image](https://github.com/user-attachments/assets/664c67d2-84cc-4b43-8af1-59b2cbd0e985)

![image](https://github.com/user-attachments/assets/87f581aa-64b4-46b2-9534-639c5ea3995b)

![image](https://github.com/user-attachments/assets/b035e599-46c8-44d3-9ae8-dc10ae74bf78)

![image](https://github.com/user-attachments/assets/5fd310db-8026-4db0-8929-df535edc293d)

![image](https://github.com/user-attachments/assets/1841adea-a388-438b-9119-1aa67d555238)

![image](https://github.com/user-attachments/assets/169f71be-1dc0-4c41-a284-1c7d39a67de0)

We have to execute till the gain is negative. So, we need to execute further from the desired step.

![image](https://github.com/user-attachments/assets/78b16217-9781-4da4-9391-bedfde2863c9)

So, we go for the 2nd pass.

![image](https://github.com/user-attachments/assets/b2c8a2d7-11c1-401a-9635-edf71031912a)

![image](https://github.com/user-attachments/assets/218f41bd-4b0b-4384-8aaf-72123635a47f)

![image](https://github.com/user-attachments/assets/a961b047-37f5-4005-b672-3d774de3a65a)

So, we got all the gains negative and we can stop the algorithm here.

![image](https://github.com/user-attachments/assets/94f86c9f-d1b7-4f5a-9ffe-12ca1d907c2c)

![image](https://github.com/user-attachments/assets/40bc1033-08c2-41da-b60c-a0a44aac9933)

![image](https://github.com/user-attachments/assets/c571c716-5d34-41c6-a2a5-0ee9f523408d)

![image](https://github.com/user-attachments/assets/d2ae7044-83b0-4c7b-b53d-3214d0c9d0fa)

Week 4 (lecture 23-Fidduccia-Mattheyeses(FM) Algorithm)

![image](https://github.com/user-attachments/assets/fb2ecad4-b1f6-43cb-b1d8-b3c88b1f9cb1)

![image](https://github.com/user-attachments/assets/3060a8f8-190c-456b-a1e0-a25f83fc363f)

Here, the number of cells in each partition is not important. But the area of individual cells is considered. Also, we can move the cell from one partition to another partition without swapping.

![image](https://github.com/user-attachments/assets/beda23e3-bec2-4635-bbc7-c5059bae83b1)

Hyper graph is not possible in KL algorithm.

![image](https://github.com/user-attachments/assets/9a7170fe-0c27-4d3b-a3c8-2f6818c9e884)

'Moving force' tells that we need to move the gate from one partition to another. 'Retention graph' tells that we need to retain the gate in the same partition.

![image](https://github.com/user-attachments/assets/23c4cfbf-ec9b-4efd-9728-8f450f57ca62)

So, if we move the 2 to other partition, the number of cutcost will be increased by 1.

![image](https://github.com/user-attachments/assets/2f990ea9-23be-4892-be02-7afb676733c6)

Once we write FS and TE for all the nodes, we need to find the cells which have high gain. So, here we can choose cell 1 or 5.

![image](https://github.com/user-attachments/assets/459845c0-0e02-4fc3-ba78-e04d486e0d6f)

![image](https://github.com/user-attachments/assets/0bc1546e-4f4b-40eb-b517-cbc909182073)

![image](https://github.com/user-attachments/assets/371512e8-2664-462d-bf3d-ce2495d26a79)

![image](https://github.com/user-attachments/assets/3a47f92d-042a-49cf-9f56-0725e83ace56)

![image](https://github.com/user-attachments/assets/d64c8bee-d912-4076-b6dc-ae551c8fe66b)

![image](https://github.com/user-attachments/assets/764f4059-d05f-4044-ad50-24b2147768f9)

Free cells are the cells which are not fixed.

![image](https://github.com/user-attachments/assets/330d22d5-e143-4f79-9976-3f83f7a73e5e)

![image](https://github.com/user-attachments/assets/c060347c-716c-4e2b-8753-33c6b76791fb)

![image](https://github.com/user-attachments/assets/1e4e8cb3-af39-4272-85e6-4c811132c9eb)

Then find out the iteration where the Gm is maximum.

![image](https://github.com/user-attachments/assets/b797c91d-90b0-42f4-987c-04ab446fb028)

![image](https://github.com/user-attachments/assets/cc9467ea-0d63-4b1a-bc07-8e69cfa6f357)

Whenever we are doing all the steps, we have to make sure that the balance criteria is met.

![image](https://github.com/user-attachments/assets/e83221fb-5445-454c-9c1f-3df59224b56e)

![image](https://github.com/user-attachments/assets/0409ffab-ace3-4deb-9090-0cf1628262d3)

![image](https://github.com/user-attachments/assets/e66cf447-254a-41d0-829d-068919cbb7f1)

![image](https://github.com/user-attachments/assets/5737e3a1-3464-4a3f-a495-078871f3b54b)

![image](https://github.com/user-attachments/assets/63c3291b-b92a-49ab-895f-3fa8a48b04d0)

![image](https://github.com/user-attachments/assets/fe4e178d-4b1a-4220-87fb-968c03b47507)

![image](https://github.com/user-attachments/assets/538f7034-8ba5-44d8-b9e7-bc3198394183)

![image](https://github.com/user-attachments/assets/a20c009e-bad4-44c6-a0c0-8b2c514f6bce)

![image](https://github.com/user-attachments/assets/39789c3a-de66-4a9f-be79-4c88d1091a88)

![image](https://github.com/user-attachments/assets/1d208629-ad9d-4597-8665-6c5f9933adb1)

![image](https://github.com/user-attachments/assets/9707d051-2c86-4e8e-8515-0df4ef14da42)

![image](https://github.com/user-attachments/assets/2a00a10a-7fe9-4664-b35e-6febcede281c)

![image](https://github.com/user-attachments/assets/f11b3426-2950-4d34-83a8-05504f63b2a6)

![image](https://github.com/user-attachments/assets/975a12db-78ce-4f51-9b9b-734e3bfff6a0)

Week 5 (lecture 24-Introduction to Floorplanning)

![image](https://github.com/user-attachments/assets/4444caf4-258b-4183-b7a1-2423d9d68119)

![image](https://github.com/user-attachments/assets/04c5d2ca-02c1-411c-88e8-3d3c13111adf)

![image](https://github.com/user-attachments/assets/3668ab12-9f6b-4696-bfe7-daa84e507f40)

![image](https://github.com/user-attachments/assets/0739d98b-7aa7-47b6-9a3c-f88949ca8de2)

![image](https://github.com/user-attachments/assets/afda2ff6-7c99-449f-ba7b-35691cbd4c23)

![image](https://github.com/user-attachments/assets/e9a6e19e-64be-4be9-a45a-c54f73a7ec9c)

![image](https://github.com/user-attachments/assets/5b985ca5-6786-40b4-b277-8d3568b648d1)

![image](https://github.com/user-attachments/assets/69f6eeec-f1d9-4f26-af2f-d4d87980ef84)

Output of the floorplanning phase will go as a input to placement phase. Now we will see, how the blocks can be placed in the given chip area, so that the routing will be easier.

![image](https://github.com/user-attachments/assets/2f56b13a-742e-4e84-b0d8-f3138c1f7f0c)

![image](https://github.com/user-attachments/assets/eeb9128c-b02c-4b92-a7d8-83a8e0651ebb)

Here, the area is same but the width and height is different.

![image](https://github.com/user-attachments/assets/2f79a4c3-fd5a-4676-8400-f7c5af0fa9b2)

Now let us see how to place these a,b,c blocks in the chip layout, so that the area is minimum. The below diagram says that, even though the area of all the floorplan are same, sometimes some of the orientation is suitable for the particular design.

![image](https://github.com/user-attachments/assets/f95d5f42-b06d-4ea6-850d-2aa83aa7805d)

![image](https://github.com/user-attachments/assets/f6dfd054-8995-4b7c-b150-7341393658c1)

![image](https://github.com/user-attachments/assets/71e6d936-8cd8-485c-ae36-6e0d1e28e20d)

![image](https://github.com/user-attachments/assets/2d42fd77-9b43-43b2-84cd-6b4a3217732f)

![image](https://github.com/user-attachments/assets/fceb2767-e679-44b7-ad91-9c76d75036b0)

![image](https://github.com/user-attachments/assets/cd6315f1-f697-44a0-b4cb-0e3754ed6121)

If we have equal priority to the area and wirelength, alpha is assigned to 0.5. If more priority is given to area, then alpha will be close to 1 and 0 if the priority is given to wirelength.

![image](https://github.com/user-attachments/assets/f86887c9-ea49-46e4-8495-aa049f40b0ba)

![image](https://github.com/user-attachments/assets/0e6ae2a6-2886-4c54-b366-b5fbd375c0eb)

![image](https://github.com/user-attachments/assets/a839e68a-ddbe-452d-b5e8-37da23e0e287)

![image](https://github.com/user-attachments/assets/430fc050-c9b4-4029-a10b-ee11441460f3)

![image](https://github.com/user-attachments/assets/76555675-5fc5-45b2-82e5-cbcaaa424219)

In horizontal cut, The right node of the tree corresponds to the top block and the left side of the tree corresponds to the bottom block. For vertical cut, the left side node is the left block and the right node is the right block.

![image](https://github.com/user-attachments/assets/5d23d67a-9e5e-4622-9249-f7b225bc2621)

![image](https://github.com/user-attachments/assets/4c51d608-f6e9-4bbc-b6fa-b699a038cfe8)

![image](https://github.com/user-attachments/assets/4c35b73e-2d7b-452b-8d1f-b4f0d7feadf5)

![image](https://github.com/user-attachments/assets/68ce38d3-2055-4b27-b679-5ceae14c33e4)

In non-slicing floorplan, we will not cut the entire design area into either vertical or horizontal cuts.

![image](https://github.com/user-attachments/assets/627ce02b-33a5-4cb1-94fc-2171b4324589)

![image](https://github.com/user-attachments/assets/1ef92b05-0f8c-4ea2-95eb-67ae3641eb1d)

Here, W stands for wheel.

![image](https://github.com/user-attachments/assets/7042b910-735a-41be-be85-8717dfdacab3)

![image](https://github.com/user-attachments/assets/36f2a05e-73ec-4e96-a43d-24c097b6a843)

![image](https://github.com/user-attachments/assets/d073cdda-3b8f-4b73-af3b-9ef09ac5049e)

![image](https://github.com/user-attachments/assets/fb48475b-7eee-4867-a5ed-b24712b27635)

![image](https://github.com/user-attachments/assets/4f5bc026-e5bf-4f6d-a7d3-cd232a3a7275)

![image](https://github.com/user-attachments/assets/0de7a5ca-8a9e-43be-af65-53b8418f64da)

This sequence pair help to represent the floorplan in a compact manner, which can be given as input to the floorplanning algorithm.

![image](https://github.com/user-attachments/assets/2c8038cc-b335-4029-a840-fc3cdce7cd17)

Week 5 (lecture 25-Floorplanning Representations)

![image](https://github.com/user-attachments/assets/e8207507-4c90-45ab-99b2-40d6d50aa157)

![image](https://github.com/user-attachments/assets/f2a586d1-3b4d-4729-8f7d-eb1bb529c91a)

![image](https://github.com/user-attachments/assets/c3dca92a-6938-46c2-b542-cc71545689c4)

The second step is to add the source and sink(termination) nodes. If a node is present left to other node, then we add a directed edge.

![image](https://github.com/user-attachments/assets/89048ed8-f0a4-4019-9030-5f3ff0e7d256)

Then we can remove the redundant edges.

![image](https://github.com/user-attachments/assets/45e25272-994e-4288-8bc4-8531b88d9d17)

Then we move to the vertical constraint graph.

![image](https://github.com/user-attachments/assets/0fec4df8-4a0e-4c8e-a197-1d69ed52d561)

![image](https://github.com/user-attachments/assets/ae27701e-a66a-43c9-9168-918171cb0ac1)

![image](https://github.com/user-attachments/assets/43a92408-9374-4ead-96ab-17e579225859)

![image](https://github.com/user-attachments/assets/8d34cf75-95e4-4c9b-a70e-173fd43828ef)

![image](https://github.com/user-attachments/assets/4e094b56-59fe-41e6-8647-b2cc8f21711f)

![image](https://github.com/user-attachments/assets/eb987669-7c62-41af-a2b1-379f9f1d5346)

S+ means looking from top to bottom and S- is looking from bottom to top and using the vertical constraint graph.

![image](https://github.com/user-attachments/assets/ded582c6-24b8-4117-869d-8c4c9a7586e4)

Then we are doing it using horizontal constraint graph. For that we are using the sequence form the previous slide and check for HCG conditions. If there is any change, we can change it. Eg: In S-, 'ba' is changed to 'ab'.

![image](https://github.com/user-attachments/assets/f4cbabc8-ad52-4401-a6fd-ddb6ebcf8748)

This sequence pair represents the floorplan. Which means, if we know this sequence pair, we can create the floorplan.

![image](https://github.com/user-attachments/assets/b50ce83c-a9ea-45ef-9e9a-ec1256dd5567)

Now let us see how to create a floorplan using sequence pair.

![image](https://github.com/user-attachments/assets/e7a245f5-37a3-46a7-b57f-fb69bd2d4d87)

LCS is used to find the x and y co-ordinates. To find the x co-ordinates, the input to the LCS is S+, S- and widths of each blocks. Similarly, To find the y co-ordinates, the input to the LCS is S+ reverse, S- and widths of each blocks. 

![image](https://github.com/user-attachments/assets/cd5d5022-c99b-4072-b862-727cb252defc)

Block order - Position of block in the S2(S-) sequence. Weights - Widths and heights of each of the block.

![image](https://github.com/user-attachments/assets/28c15244-7376-4b45-a80f-bc42364c62a3)

Let us understand this with an example.

![image](https://github.com/user-attachments/assets/b3734319-8d8f-46a9-8028-d7e9238e7e6a)

Initially all the lengths are '0'

![image](https://github.com/user-attachments/assets/d25588a1-abf1-400c-9caa-f95e6060a04d)

![image](https://github.com/user-attachments/assets/871dfc76-bc80-4560-acb9-08af547eeea2)

![image](https://github.com/user-attachments/assets/e450fc75-9f8d-4ac1-926a-fc54cfae801b)

The positions of the block gives the x-coordinate. The maximum width of the block will be given by the t-span, because we are working in the x-direction.

![image](https://github.com/user-attachments/assets/b6d63469-244d-423f-9120-36592a9eb46b)

Now let us see how to find the y-coordinates.

![image](https://github.com/user-attachments/assets/5784b0ee-2e6c-4efb-bfd4-81fb64dd2d4f)

Here, the weights will be heights.

![image](https://github.com/user-attachments/assets/a9300a9b-3c06-49ae-b819-14b1610ebdae)

![image](https://github.com/user-attachments/assets/aeebed9b-28ac-475e-9a19-8daed3d4449f)

The height of the block is determined by the t-span.

![image](https://github.com/user-attachments/assets/16fefec6-5c72-4f38-912e-1606f17db75a)

Now we know the height and width of the global bounding box, x and y coordinates of all the blocks.

![image](https://github.com/user-attachments/assets/d6362405-f1cd-4ab1-b660-fa0656988548)

Week 5 (lecture 26-Floorplanning Algorithms - 1)

![image](https://github.com/user-attachments/assets/f5e53e1b-3d48-44ba-ae64-7d224a86f948)

![image](https://github.com/user-attachments/assets/296469b4-3957-48b3-9a31-51e4898bd53d)

![image](https://github.com/user-attachments/assets/3dcb2178-0456-4ed7-bdfb-0a652e86abb6)

![image](https://github.com/user-attachments/assets/72536a15-15e3-4b35-9801-5ee0a991191b)

Ideally there should not be any wastage of area in the floorplan but it is not always possible and we will see that. The equations says that there are multiple combinations of W and H are possible for the same area but it is not possible to create any shape of the block.

![image](https://github.com/user-attachments/assets/57ef2eb4-8bb2-4160-8f6c-430f6e37749f)

The graph says that, either the W changes or the H changes, but the area of the block remains same. Third quadrant is not considered because, the width and the height cannot be negative.

![image](https://github.com/user-attachments/assets/fd9e750d-98a3-48e2-a179-48083b0603b5)

All the points in the curve line satisfies the area constraint. So, everything above the curve line is a legal area.

![image](https://github.com/user-attachments/assets/4c3393ee-ccd6-4a86-b292-15770d0874c5)

As shown in the diagram below, the area below the lower bound line is not allowed.

![image](https://github.com/user-attachments/assets/08734dd1-ae19-4f8f-a90c-35565a18e43a)

![image](https://github.com/user-attachments/assets/8df4ce94-765d-4fff-949e-2f586f60b316)

Due to some technology dependent design rules we can create shape of the block in some particular points and not in the continuous manner. 

![image](https://github.com/user-attachments/assets/d3000e4a-194d-466e-99ce-7492c05d6697)

There are some hard IPs will be present like Memory blocks. For those blocks, there will be two orientations.

![image](https://github.com/user-attachments/assets/05fa2c41-8c2a-4a1a-963f-4e3d2d8aa457)

![image](https://github.com/user-attachments/assets/1c5de0c6-d4cb-4579-9c73-3293772d08b2)

![image](https://github.com/user-attachments/assets/66eafa5b-ed6c-436d-8e4d-dde0779f203a)

![image](https://github.com/user-attachments/assets/89d99865-140c-441a-9d21-135d88013d89)

![image](https://github.com/user-attachments/assets/89521152-9069-426b-bffc-170a5c0126fb)

![image](https://github.com/user-attachments/assets/d6ca66d7-548c-4922-9fbe-882d5d878edb)

![image](https://github.com/user-attachments/assets/0b168154-27a7-409a-95e1-f5263a7fc0f8)

Then consider the block B.

![image](https://github.com/user-attachments/assets/467dda64-93f2-4d89-aafc-c5f2613e5ab3)

![image](https://github.com/user-attachments/assets/abf10df9-924e-4be3-9732-417e52edf26b)

We found the shape functions of blocks A and B. Our aim is to find the minimum area of the floorplan. Block A has height of 3 and block B has height of 4, so the height of overall floorplan is 4+3=7.

![image](https://github.com/user-attachments/assets/5ad9b0b5-5109-42c3-8de8-c74fceb06e99)

![image](https://github.com/user-attachments/assets/2f644a49-7294-4976-b30b-7dad237eefab)

So, in vertical composition, the best one is shown below.

![image](https://github.com/user-attachments/assets/6c1e32cd-c797-49d5-8693-af29ffec1726)

Now let us see the horizontal composition.

![image](https://github.com/user-attachments/assets/a8a944f1-b21e-460a-9047-57166706388f)

![image](https://github.com/user-attachments/assets/55840100-8c27-45a8-b6ea-d50d9e2e36c2)

![image](https://github.com/user-attachments/assets/9923c026-a7e0-494a-993c-e8aff1f63539)

Week 5 (lecture 27-Floorplanning Algorithms – 2)

![image](https://github.com/user-attachments/assets/dfa8694c-01f4-443c-9029-3afecf34c01b)

![image](https://github.com/user-attachments/assets/b8f2b146-ea8d-4c99-8edb-822989d3a1d7)

![image](https://github.com/user-attachments/assets/29ddd52a-729e-41c8-a483-c43e916876bd)

When we place block C, then N1 and N2 are called terminating nets.

![image](https://github.com/user-attachments/assets/d2f0eacf-73ac-4167-a81a-7b1edacf4aab)

Partially constructed means, previous blocks.

![image](https://github.com/user-attachments/assets/1e7ebbd7-0448-46ef-8fb6-7fed1be2d105)

![image](https://github.com/user-attachments/assets/8d19cce5-9cac-4e90-b4f4-b6bfaa20b3b8)

We place the blocks such that the interconnect distance is minimum. It is possible using the gain formula.

![image](https://github.com/user-attachments/assets/c3337c5c-0054-4d76-9ead-8e8e62dd7370)

![image](https://github.com/user-attachments/assets/54efaf1c-e208-4fd8-9efc-00541bebfe54)

The below shown is our initial circuit. Now we have to find the placement of the blocks such the distance of the interconnects is minimum.

![image](https://github.com/user-attachments/assets/fb750cb8-69e6-4512-ae02-bf60972eb546)

![image](https://github.com/user-attachments/assets/c830b67a-b7ca-495e-86dd-946928f85e34)

We have to choose the block which gives the highest gain. In the below diagram we are checking like which block can be placed after the 'a' block.

![image](https://github.com/user-attachments/assets/fdc364a9-8932-4985-8a49-1b26f02d6cfd)

Here the gain of two blocks are equal and so we are seeing the continuing nets and choosing 'd'. Because if we choose 'c', the length of the continuing nets will the large.

![image](https://github.com/user-attachments/assets/9a209cda-05c2-43ef-9e88-2e6368788308)

Here we can choose any blocks. Because all are equal.

![image](https://github.com/user-attachments/assets/27c43727-68b0-4b4f-8910-9d864137401c)

![image](https://github.com/user-attachments/assets/399cdcaf-8f88-44a3-a7dc-eb1cc728bef5)

Lets move to the second algorithm 'Cluster growth'.

![image](https://github.com/user-attachments/assets/0a827f94-322e-440f-915e-ee472fc2686c)

The further blocks are placed in such a way that the final size of floorplan is minimum.

![image](https://github.com/user-attachments/assets/3f16aa4c-cc1e-4d09-96a9-307528269329)

![image](https://github.com/user-attachments/assets/cf986981-db5c-45a9-afdc-a2d400cae1d5)

![image](https://github.com/user-attachments/assets/29e94ed3-3e45-46f4-b624-336f3b767e53)

Cost may be area,wirelength or anything which is our target. After we run the linear ordering algorithm, we take one block at a time and order it using cluster growth algorithm.

![image](https://github.com/user-attachments/assets/2ab9c9a4-1d66-42f0-a46b-3459377ede1b)

The inputs given are blocks, linear ordering(from the previous example) and aspect ratio(different orientations with same area.)

![image](https://github.com/user-attachments/assets/982394ff-91a7-45f4-9aec-9859450abb12)

![image](https://github.com/user-attachments/assets/17b57d09-b03d-4bab-9ec2-7d59e487a150)

![image](https://github.com/user-attachments/assets/46cfe7da-f1e1-40da-bc16-375c48518dfc)

We placed 'a' and 'b' in such a way that the area is minimum and there is no area wastage. If we choose other dimensions, the are will be wasted.

![image](https://github.com/user-attachments/assets/05410c46-f6e7-468a-bb20-39e4b4f31588)

![image](https://github.com/user-attachments/assets/b72efce9-d5a1-4ddd-bccd-cc8bcdb83095)

![image](https://github.com/user-attachments/assets/4a77f0d0-c130-4cd9-907c-29bc35f0b11b)

![image](https://github.com/user-attachments/assets/9267c8e7-c834-44f3-841e-fcbe44e86daf)

Now lets move to the next algorithm 'simulated annealing'. In Greedy algorithms, we always goto local optimum value or best solution at each step.

![image](https://github.com/user-attachments/assets/1e0c9c7a-d799-4ee9-9fe1-534ca868e10b)

![image](https://github.com/user-attachments/assets/fab1307a-085c-482c-bbea-71f25e535e29)

![image](https://github.com/user-attachments/assets/13d5a90a-315d-424f-a8bf-d998fd72be32)

![image](https://github.com/user-attachments/assets/1b62b3b9-6f3e-401b-8c46-ef3b8c72f509)

In minimum energy configuration, we get the better solution.

![image](https://github.com/user-attachments/assets/02c238a3-2ec7-48bd-9453-83f5737222aa)

![image](https://github.com/user-attachments/assets/1da26577-7454-4082-9908-3197aec373e4)

![image](https://github.com/user-attachments/assets/c47aeb42-b5e4-4467-a29f-62831141366d)

If the below condition is satisfied, then we accept the solution.

![image](https://github.com/user-attachments/assets/1997e16b-1ec1-4807-9242-b9a2b84586af)

![image](https://github.com/user-attachments/assets/165b29c1-69ba-401d-93c4-4fbfefb5b73d)

![image](https://github.com/user-attachments/assets/eb8a58b5-4b05-4ca6-b8f6-f91e247f09a6)

![image](https://github.com/user-attachments/assets/99d1d6ed-c6a8-47ca-b4d5-09f269b7671f)

![image](https://github.com/user-attachments/assets/a7fa6e21-924f-49bc-95f3-62eb8686b4f3)

![image](https://github.com/user-attachments/assets/fa13b82f-c5ed-4c5c-be0f-96d882febd3c)

![image](https://github.com/user-attachments/assets/571c624b-396a-4179-9035-d5abfa991982)

![image](https://github.com/user-attachments/assets/4ba818b0-cced-4490-9048-616785ca83b1)

The below shown is the output and it says that, if we increase the time, we get the better solution. And the second thing is that we have 3 different configurations and so we have 3 different solutions. Which means, if we run it for longer time we get better solution and for different configurations we get different solutions.

![image](https://github.com/user-attachments/assets/bf5242c3-f85c-4c2a-bec1-535b40bbc555)

Week 5 (lecture 28-Pin Assignment and Power - Ground Routing)

Planar routing is for full custom design style and Mesh routing is for semi custom design style.

![image](https://github.com/user-attachments/assets/9103adde-cd11-42a8-b576-465edab79d12)

![image](https://github.com/user-attachments/assets/9375f274-7371-418b-b866-a675eafaf8c8)

![image](https://github.com/user-attachments/assets/8709fe71-c57a-4463-93f9-09241df6b183)

![image](https://github.com/user-attachments/assets/84d28df1-e6a9-443b-a503-3e733582e71b)

![image](https://github.com/user-attachments/assets/c09f0274-4cd4-4e64-8bb9-1c760bf2230f)

Functionally equivalent does not mean electrically equivalent.

![image](https://github.com/user-attachments/assets/7f333b95-a562-4e3f-b6c0-4cf88d5db4df)

![image](https://github.com/user-attachments/assets/5703629c-298c-440e-8f12-36b3514dd0e2)

![image](https://github.com/user-attachments/assets/468e336f-3a2d-47b1-9ac0-2e73671a2803)

![image](https://github.com/user-attachments/assets/4699d767-8175-43c8-b93b-22c61e32b75b)

![image](https://github.com/user-attachments/assets/aff7d71a-9a61-4ff3-bbf8-369aa87f0c2c)

![image](https://github.com/user-attachments/assets/f9fed4de-8cd9-4a3c-b001-81f78dd8f98e)

![image](https://github.com/user-attachments/assets/2255e0e5-337e-4185-b6ca-1b99606e79a6)

![image](https://github.com/user-attachments/assets/cd9a0ce9-8e57-4288-bb5d-2d658c1549f6)

The small red circles that are present on the circles are important for us.

![image](https://github.com/user-attachments/assets/6ba2be15-c739-4c86-9869-689fb1427894)

![image](https://github.com/user-attachments/assets/92a859a3-4387-4d8f-bf8d-fd3f72ef40c1)

![image](https://github.com/user-attachments/assets/3896ac2e-3109-47d4-8c15-9c2e826a38ae)

Initial mapping is the first solution but it is not the best solution.

![image](https://github.com/user-attachments/assets/4053c040-3eca-4765-b0a6-8e6ac24feff4)

![image](https://github.com/user-attachments/assets/628e5eec-5729-402c-8bfc-c635e7ce12c5)

![image](https://github.com/user-attachments/assets/a73b0aa4-00b5-42dc-80ac-379267a83446)

![image](https://github.com/user-attachments/assets/abafa593-97f3-45cc-942f-f01a985cd107)

![image](https://github.com/user-attachments/assets/25fda4ef-cce9-4841-b8f1-3d4c51e2e375)

Topological pin assignment:

![image](https://github.com/user-attachments/assets/8989f229-053f-4b15-92f8-c7a5c688a622)

![image](https://github.com/user-attachments/assets/ff55cec8-4187-40e4-8c91-3aa108682315)

Draw a line to find the farthest point from block M to external block.

![image](https://github.com/user-attachments/assets/929106d9-cb6e-4f8b-9829-d82609bd6402)

Then we draw a perpendicular line to the previous line.

![image](https://github.com/user-attachments/assets/db15396d-1853-4951-9e97-ccdb5ae5afa1)

Now we can connect them using concentric circles.

![image](https://github.com/user-attachments/assets/4fe7f77c-441e-4a09-85f0-df5f85e5ccd4)

![image](https://github.com/user-attachments/assets/774aff93-eb7d-4c0a-89ba-a17847aa9cba)

From M, we are passing two lines through the midpoint of the block a and b.

![image](https://github.com/user-attachments/assets/168a4587-b811-4e73-92a9-db6d8cc2580c)

![image](https://github.com/user-attachments/assets/84f62ad3-02eb-415e-91ed-d6b780f23a3a)

![image](https://github.com/user-attachments/assets/3f289f39-6b55-4e80-a52b-70e89adee0d9)

![image](https://github.com/user-attachments/assets/58d180a4-24e1-4243-ae07-956d62e190d1)

![image](https://github.com/user-attachments/assets/3fb0ad88-287f-44bf-89dd-5a513a6ceee5)

The chip has two rings, Vdd and GND, also the individual blocks has these rings.

![image](https://github.com/user-attachments/assets/2f9fa015-7560-4d55-a3f4-97df9e65ef4a)

![image](https://github.com/user-attachments/assets/70b40fa9-c0e2-4c28-95f3-8337e0431b75)

![image](https://github.com/user-attachments/assets/8fea5c7f-bf84-4c8c-abe3-2441987795fe)

![image](https://github.com/user-attachments/assets/848c7a3c-67be-4f7f-83c1-5d3e7528f345)

![image](https://github.com/user-attachments/assets/bb9f69d0-7783-47d3-adfd-708f5e910658)

![image](https://github.com/user-attachments/assets/9bd2b715-3cc9-4248-b7d1-4fbda7443028)

![image](https://github.com/user-attachments/assets/143c9f81-dbb9-455b-9917-4871658cef4b)

Mesh network is low resistance network compared to the ring network.

![image](https://github.com/user-attachments/assets/8f4fd6a7-2fae-4d46-bbb5-6b8db1267b29)

![image](https://github.com/user-attachments/assets/092f1dd6-c27c-432e-bbcb-2387a5653cc6)

![image](https://github.com/user-attachments/assets/dbeac31d-17ed-4428-bd9c-bb47977a78b1)

![image](https://github.com/user-attachments/assets/87857693-3d7a-442e-8fcd-45efd5868f8e)

![image](https://github.com/user-attachments/assets/42de3ede-bd16-4a7e-ba6b-9cbe4a790c18)

![image](https://github.com/user-attachments/assets/ffdba330-58b2-4fa9-98b5-c4170c451776)

Week 6 (lecture 29-Introduction to Placement)

![image](https://github.com/user-attachments/assets/181a2fc8-1c4c-4d4b-8b36-66bcf06669d3)

![image](https://github.com/user-attachments/assets/ea001e43-805c-4ea4-b96c-12081ed4cfaa)

![image](https://github.com/user-attachments/assets/2c70bbdf-a04a-4116-b6b9-d3dd795df3ce)

![image](https://github.com/user-attachments/assets/f2080841-84fe-4288-afc6-d2d40921ab57)

![image](https://github.com/user-attachments/assets/89b79f83-63cf-4354-a5a4-6ec65bfe7b88)

![image](https://github.com/user-attachments/assets/34446848-6598-40a5-8e1b-2e176672fe1a)

![image](https://github.com/user-attachments/assets/8898a19e-4af3-44bc-a072-5106d1310e1d)

![image](https://github.com/user-attachments/assets/06f1b9ac-f19c-4379-8a21-09b861259bf5)

![image](https://github.com/user-attachments/assets/a242e3a9-7b06-4eb7-b1d6-7223e0318433)

![image](https://github.com/user-attachments/assets/f192b35a-0aea-4e45-8037-8b5fd41acb2b)

![image](https://github.com/user-attachments/assets/da8d76b0-9055-4ec2-a21c-025af5286597)

![image](https://github.com/user-attachments/assets/cbe7da1f-73ff-405a-b170-f413287b7ff8)

These are the blocks given as input to the placement problem. All the 1s should be connected, and other respective numbers should also connected such that the overall area and overall wirelength is reduced.

![image](https://github.com/user-attachments/assets/5d542f6c-42ad-4f21-bc85-9d565d6efa4d)

![image](https://github.com/user-attachments/assets/ed2cd888-912b-4555-a60f-8ccf180de754)

![image](https://github.com/user-attachments/assets/5c777e6a-a0a3-408d-97ca-2aa3261935d6)

![image](https://github.com/user-attachments/assets/78660710-1281-4c79-a95c-285206108a3b)

![image](https://github.com/user-attachments/assets/cf6071c6-f6a0-43b7-9397-f0fcc3a6f24d)

![image](https://github.com/user-attachments/assets/47abd213-9906-411c-ba83-4b016d324a79)

This is similar to the packaging of books in a box. The difference is, When packaging books, overlap can be done. But, here the overlapping is not allowed.

![image](https://github.com/user-attachments/assets/70d19320-d16b-4555-aa18-b7e2f0c0ba58)

The height of the cells can be 7 or 9 or 10 track depending on the company.

![image](https://github.com/user-attachments/assets/34794279-9f41-4478-b760-e4b33b6803ff)

![image](https://github.com/user-attachments/assets/685196b2-31dd-4611-bb01-412d119bae81)

![image](https://github.com/user-attachments/assets/d18069b5-80d7-4b42-8803-2f16d8a37e8f)

![image](https://github.com/user-attachments/assets/b43da3d9-d963-4687-bde9-f706f8cc2abf)

![image](https://github.com/user-attachments/assets/e16ec53f-a46d-4ee0-9b56-7590ad4ca9e3)

![image](https://github.com/user-attachments/assets/d88dae3c-9488-40f6-91c1-b9df15498d94)

![image](https://github.com/user-attachments/assets/fff4b1b5-fd50-4046-ba83-6519fe29429a)

![image](https://github.com/user-attachments/assets/6ca65e3e-e42c-4fb5-9e98-164a0e7b6cb4)

![image](https://github.com/user-attachments/assets/32fcd291-6880-4440-b982-9bbca3806802)

![image](https://github.com/user-attachments/assets/527eca51-1d62-400e-a845-e416e0a6749a)

Week 6 (lecture 30-Wirelength estimation techniques)

![image](https://github.com/user-attachments/assets/00b61392-38dc-4c92-a8f9-213769763715)

We should not calculate the equilidian distance here which is given below of the picture. Because, it calculates the diagonal distance.

![image](https://github.com/user-attachments/assets/2e4fa8a9-c5ea-4a70-b4de-0059acdb127c)

![image](https://github.com/user-attachments/assets/69423e47-e91d-415f-8b25-15c5feeb47da)

![image](https://github.com/user-attachments/assets/74d96693-9fd2-4144-85c7-e816c3ee3df3)

![image](https://github.com/user-attachments/assets/264a0a33-8727-4c9d-b5d1-b4e73d0af32b)

![image](https://github.com/user-attachments/assets/b4df0ada-4984-4307-96c7-a5f6483c74dc)

![image](https://github.com/user-attachments/assets/08f708a9-0acd-462e-92fc-e98b70f02bf2)

![image](https://github.com/user-attachments/assets/4118fda1-a366-44a6-a48e-48d660827343)

![image](https://github.com/user-attachments/assets/326aef2c-25f4-45d7-af00-f062069d1eb7)

![image](https://github.com/user-attachments/assets/6b168960-dbd5-440b-a687-b11c2a92a5f4)

![image](https://github.com/user-attachments/assets/e622398d-a3ee-4d81-91d8-2f44a3a98dfc)

![image](https://github.com/user-attachments/assets/40715821-a596-44da-a488-3fb927cf758f)

Manhatten geometry means, either horizontal or vertical lines. It should have max of p-1 edges. Because, even if one more edge is added, it lose the property of tree and behaves as a cycle.

![image](https://github.com/user-attachments/assets/2e249997-8627-4725-a563-129051c8cca5)

![image](https://github.com/user-attachments/assets/374234d7-08e5-4487-84dc-1cc0d32f98cc)

![image](https://github.com/user-attachments/assets/f19c80af-0b23-4671-9a02-b4123f066565)

![image](https://github.com/user-attachments/assets/50f716cc-6558-4953-a70a-3a5c54f2f680)

![image](https://github.com/user-attachments/assets/095f788c-b62c-44fb-8cef-d5bae5d79d86)

![image](https://github.com/user-attachments/assets/0d09e679-a03d-453d-9038-e2a7d5556ff7)

![image](https://github.com/user-attachments/assets/ed9952b2-e535-494c-8d6a-e44ad3a91af2)

![image](https://github.com/user-attachments/assets/f6a8e499-2392-467f-a24a-bd7615fd07ee)

If we want more accuracy, we can go for RSMT. Else we can go for HPWL.

![image](https://github.com/user-attachments/assets/0d9d34d6-226c-4fda-9fa4-048893c7f091)

Here the error is close to 10%

![image](https://github.com/user-attachments/assets/fb77ceb1-04bc-4f74-a522-937ad9aaa83a)

![image](https://github.com/user-attachments/assets/95b6293b-cc3a-4723-b7a0-79279ce2298d)

![image](https://github.com/user-attachments/assets/1b7acf7e-4204-49f8-9fb1-3175f5a85011)

![image](https://github.com/user-attachments/assets/70fae6c3-0f78-4839-9678-ea77a4e44982)

![image](https://github.com/user-attachments/assets/0431d4ed-875a-4e7a-8850-b1ddbfb6b683)

![image](https://github.com/user-attachments/assets/90ffcc3e-4ed2-4ba3-bc6c-e0992ed27c29)

![image](https://github.com/user-attachments/assets/d4b2654d-a021-408a-8536-043fd629fb65)

![image](https://github.com/user-attachments/assets/fc8b4ace-7092-4cf5-8d56-6d9e6db3c7ce)

![image](https://github.com/user-attachments/assets/78e982d5-25d3-43bf-8939-44b3c80f41e8)

![image](https://github.com/user-attachments/assets/57a327a7-d1ce-4c95-8378-60dced01ee61)

![image](https://github.com/user-attachments/assets/16fbe514-c56d-4802-92bf-a7cb053fad11)

![image](https://github.com/user-attachments/assets/f4cea026-d2d5-4b67-a98f-a17acc6428a1)

![image](https://github.com/user-attachments/assets/9ddd488c-3a90-4bbe-a743-c587873f6872)

![image](https://github.com/user-attachments/assets/b80355ce-72d2-4ba9-8abf-929dccbcd00c)

Now the block b is moved vertically up. So, the h1 is cutting only one edge.

![image](https://github.com/user-attachments/assets/10897e97-df84-46d2-9356-4f1cade08342)


Week 6 (lecture 31-Min-cut placement)

![image](https://github.com/user-attachments/assets/424d59b7-92d7-4c1b-a3a4-c556fc72e6f0)

![image](https://github.com/user-attachments/assets/a1b84f65-42dc-4f92-9ce7-d1d45a589493)

![image](https://github.com/user-attachments/assets/25a5b4f0-815f-4aae-8922-bdfbd8de258e)

We try to minimize this value, so that there is no routing congestion.

![image](https://github.com/user-attachments/assets/ab36f279-728b-4a54-b2ed-8cc28827049b)

![image](https://github.com/user-attachments/assets/0f3e42d2-3854-40fe-b83e-ee0d5c9f34e0)

![image](https://github.com/user-attachments/assets/0d7b5d54-a8da-4bf7-89a4-066d3f050eb9)

![image](https://github.com/user-attachments/assets/99b0e815-9019-49e7-bb39-5ef618006546)

![image](https://github.com/user-attachments/assets/45550d58-0881-4fa0-8bea-121c86204889)

![image](https://github.com/user-attachments/assets/74717e77-10c6-4bf2-a1de-be6ac19dfd61)

![image](https://github.com/user-attachments/assets/f7abf078-dbdd-4a16-8544-12a0b60fd4d1)

![image](https://github.com/user-attachments/assets/600cf18e-4f5d-441d-bdea-e5d9f9091baf)

![image](https://github.com/user-attachments/assets/50a19623-feb1-4d17-a9b2-01a94ad9a8e8)

![image](https://github.com/user-attachments/assets/615b2919-c19c-4996-8092-7bf95feddad4)

![image](https://github.com/user-attachments/assets/a31e81ee-a4f7-421c-ad1b-b0fbdd12196c)

![image](https://github.com/user-attachments/assets/ba474ae3-c077-45b4-a598-7de8ec7be093)

![image](https://github.com/user-attachments/assets/d8b93bac-a6ab-4abf-8cc6-2d191932b268)

![image](https://github.com/user-attachments/assets/123b228d-ab5a-4064-bd3a-8843a0c3e3c1)

![image](https://github.com/user-attachments/assets/a9d27d4b-a58b-4afb-9706-b01590bd0eba)

![image](https://github.com/user-attachments/assets/a9675577-f683-46c7-b7ee-93cc66672421)

![image](https://github.com/user-attachments/assets/e51ebf02-776d-4efe-98d6-746f7c3b247c)

![image](https://github.com/user-attachments/assets/f9fdfbd8-26a5-439b-a61d-d8976114d405)

![image](https://github.com/user-attachments/assets/114061b5-7d86-4fc6-89b8-528362690f53)

![image](https://github.com/user-attachments/assets/5f0adc74-e001-49d5-be2f-ebe6d524aa79)

![image](https://github.com/user-attachments/assets/801e6490-6415-475b-bc0b-662b7ae97364)

![image](https://github.com/user-attachments/assets/11a1c9e7-a892-4c6c-92c3-7b9bc795dee5)

![image](https://github.com/user-attachments/assets/fb3f68e3-4e08-4dbb-b733-a7242fecda54)

![image](https://github.com/user-attachments/assets/1bc1476a-7b7a-4438-894f-d424c5750ecb)

![image](https://github.com/user-attachments/assets/c2ffc7a2-7366-4573-afc4-2e8531d25965)

![image](https://github.com/user-attachments/assets/4219a536-b144-4b52-a3cb-957f728bb64c)

![image](https://github.com/user-attachments/assets/9e12bf8a-c71e-4c77-978a-1e6a1a466525)

Nand and Nor has the value 2, which is the max value.

![image](https://github.com/user-attachments/assets/b993b0be-331b-4875-89ac-5b408457d98d)

![image](https://github.com/user-attachments/assets/9bbf5947-a504-4c33-ab6c-4d536256d845)

![image](https://github.com/user-attachments/assets/c2dabd20-8de8-4c91-975a-63dea60d91a7)

![image](https://github.com/user-attachments/assets/8d38f97e-088f-4f0e-8a98-f4e75946efb5)

![image](https://github.com/user-attachments/assets/1882617f-2f25-4d01-bed4-2bdfdad6e312)

![image](https://github.com/user-attachments/assets/4b16f3bd-9332-405c-8b72-26fbd7b57f86)

It has the highest gain

![image](https://github.com/user-attachments/assets/317e6baa-36f5-4083-920a-083a5f1b2e06)

![image](https://github.com/user-attachments/assets/189ca040-ea2a-4633-b23f-83418200aa30)

![image](https://github.com/user-attachments/assets/4824930b-90f8-4e3f-97f2-4d11b23dd43b)

This process is repeated. And the final placement is shown below.

![image](https://github.com/user-attachments/assets/538390d8-ff09-4ff8-b980-2bdb8a924cc1)

Week 6 (lecture 32-Placement Algorithms)

![image](https://github.com/user-attachments/assets/043eae91-ae43-4eb1-b7b6-98755daf1c6d)

![image](https://github.com/user-attachments/assets/f1388a4a-2fa1-4469-8c91-7b3b7d9e7ad0)

![image](https://github.com/user-attachments/assets/663b2652-8ec6-490f-b0dd-a2c2010ca667)

We need to find the locations of logic gates in this 2 by 2 grid.

![image](https://github.com/user-attachments/assets/2ba4d3ae-31ee-4cd0-b1bc-f2a71f759658)

But if we don't consider the external connections, there will be a long wire as shown in the figure below.

![image](https://github.com/user-attachments/assets/635d9935-396c-4b55-bf3e-223c2baf0e67)

![image](https://github.com/user-attachments/assets/ca259388-c329-4477-af78-8daed28c73de)

![image](https://github.com/user-attachments/assets/a0aec273-8148-4a30-939d-4ef65e27144e)

c(i,j) is 1, if there is a line between i and j.

![image](https://github.com/user-attachments/assets/93e888c2-d986-4a35-9021-fc8a3c33d721)

In global placement, the cells will find the any one grid and get placed but it is not the actual placement.

![image](https://github.com/user-attachments/assets/e921a240-0a46-4195-9020-c66fb943e334)

![image](https://github.com/user-attachments/assets/cce3aa3f-32c5-4dfc-9632-fdd0c26a5bb6)

![image](https://github.com/user-attachments/assets/4e58e5fc-5a1a-4be4-80a7-60e03fdc3080)

The above functions should be differentiable so that we can find the global minimum.
Convex means, local minimum becomes global minimum.

![image](https://github.com/user-attachments/assets/e155b205-1319-4556-8fbe-1f194ac5ab3a)

![image](https://github.com/user-attachments/assets/b3447d8c-0de4-453b-b897-3ce406889e1f)

![image](https://github.com/user-attachments/assets/49819516-bd3c-41aa-88fe-ff93cde9c7c5)

![image](https://github.com/user-attachments/assets/41e24ee5-6478-42d7-bd75-ca7e4a184c46)

![image](https://github.com/user-attachments/assets/d8fa5cbc-e290-458e-a818-92f55b7800d9)

![image](https://github.com/user-attachments/assets/a07fa86c-d61c-4b46-9af1-83e89b70948a)

![image](https://github.com/user-attachments/assets/96b1d714-f87e-4c55-9ef5-35d67b002eff)

![image](https://github.com/user-attachments/assets/d9c6f5c1-a9dd-4394-a030-19cfe7a0dd8a)

![image](https://github.com/user-attachments/assets/faad06b5-b923-41a1-b4ad-21e9ae63e9f9)

![image](https://github.com/user-attachments/assets/bad362d2-61b3-4e51-9b46-07e32b934c4c)

![image](https://github.com/user-attachments/assets/0c27c892-a229-43d3-a43f-46b22a5fd092)

![image](https://github.com/user-attachments/assets/28cdf731-d8c1-4341-a9d7-c084d40d84b1)

![image](https://github.com/user-attachments/assets/6de1ee6e-0fde-4379-9d4e-21b5fd4874cc)

![image](https://github.com/user-attachments/assets/31839d51-74e7-46b1-bdd1-eebcf47e3990)

![image](https://github.com/user-attachments/assets/242cdb20-6222-4ebd-9567-752a9b9ca1f4)

Week 6 (lecture 33-Placement algorithms and legalization)

![image](https://github.com/user-attachments/assets/72a9f49b-6bef-4d8b-b039-902ec63e4bdd)

![image](https://github.com/user-attachments/assets/e2eba8da-3c53-4535-9649-a1c67281a617)

![image](https://github.com/user-attachments/assets/194fd601-ea69-4417-b2fe-c057f9c59a15)

![image](https://github.com/user-attachments/assets/7fe8bf0f-5f46-47c6-94f0-37c83b437d0e)

![image](https://github.com/user-attachments/assets/3c29adc8-c5a7-41ff-9e16-6f3e46f1a1c0)

![image](https://github.com/user-attachments/assets/6ca51616-0975-4e2a-9693-905f5550824f)

![image](https://github.com/user-attachments/assets/95393267-1733-43ec-9c11-be41b2467bf7)

We have to find the xi and yi values.

![image](https://github.com/user-attachments/assets/7d121d60-c074-4ca2-a539-336a35479899)

![image](https://github.com/user-attachments/assets/b110f252-9073-45a4-9daf-1ce26ad00d91)

![image](https://github.com/user-attachments/assets/2d80e479-08ff-43f8-9708-d71a78b78f7e)

![image](https://github.com/user-attachments/assets/fe03d155-1b63-4996-bef1-da784ec3b1e2)

the 3*3 layout is shown below. And in1,2,3 and out is fixed. We have other 5 location to place the nand gate.

![image](https://github.com/user-attachments/assets/7e2fb006-f6b4-4b9a-b267-3aa3577a4a2c)

![image](https://github.com/user-attachments/assets/2eda4de5-f299-4fde-9764-ce25e11961fc)

![image](https://github.com/user-attachments/assets/2eaf2214-5d59-46f3-8951-842cb18fe64f)

![image](https://github.com/user-attachments/assets/76d30090-6853-4864-9657-fa62be7f80ea)

![image](https://github.com/user-attachments/assets/05c02e65-017b-4fcb-a0fb-cfe5b4f6a1cd)

![image](https://github.com/user-attachments/assets/837ba25b-f93c-471f-bd8c-3979e5d908c2)

![image](https://github.com/user-attachments/assets/ae7c8fe5-66a1-4b74-8723-ac0cacdce637)

Place the 'p' in q's position. So, the q is shifted to other position. The position where q needs to be shifted is occupied by 'r', so shift the r to other location and place q in that location. This is called 'chain move'.

![image](https://github.com/user-attachments/assets/de18c8ac-fecc-4000-8b54-acb5612cca68)

![image](https://github.com/user-attachments/assets/04792f5b-a65b-438c-9663-507b27624955)

![image](https://github.com/user-attachments/assets/9113efb2-b9aa-4459-b15b-3882437760ee)

Here, we are finding the x co-ordinate. Because, only this information is given to us.

![image](https://github.com/user-attachments/assets/38199827-b6f5-4158-8d0a-01adac5d686a)

The position of b3 is (0,0). Already b1 is present in that position. So, we are finding L(p) before move and after move. Before move is shown below.

![image](https://github.com/user-attachments/assets/cf3a2a2b-53e7-4249-8e28-50a05e8d1f14)

After move is shown below.

![image](https://github.com/user-attachments/assets/b04411ad-2879-46bd-8971-818cae675052)

ZFT position of b2 is (2,0). Now L(p)=3, so the wirelength is reduced by 2. So we are swapping b2 and b3.

![image](https://github.com/user-attachments/assets/22be0607-64c2-49b4-919d-3f72e1758548)

![image](https://github.com/user-attachments/assets/af76094c-1b71-4239-a03b-d379f9bcc74a)

![image](https://github.com/user-attachments/assets/afb165cd-4cbe-4690-a497-9ef75a632ef7)

![image](https://github.com/user-attachments/assets/0f0df8d0-d666-4bda-97e9-e233dcb8d0ac)

![image](https://github.com/user-attachments/assets/b1012bf4-ce4b-4275-bc7e-3ec6cc60c763)

When the temperature is high, the probability of accepting the solution is higher. When the temperature is low, the probability of accepting the solution is lower.

![image](https://github.com/user-attachments/assets/593f9625-f54e-4723-abc0-99554c3e013e)

![image](https://github.com/user-attachments/assets/32e17242-4f5a-4602-81c1-07facfb62e67)

![image](https://github.com/user-attachments/assets/fbede06d-9c71-4b9a-a5aa-d825f8fe2971)

![image](https://github.com/user-attachments/assets/9c9df176-f3e8-4bf1-8d50-f5253a0517ff)

![image](https://github.com/user-attachments/assets/68dabe86-e4bf-4a20-a16c-dba9a6a1ea3a)

![image](https://github.com/user-attachments/assets/56b3316a-960f-4f39-abed-971fc9f9b759)

![image](https://github.com/user-attachments/assets/abe2b179-02cb-483c-a8e0-e1779e14cd5c)

![image](https://github.com/user-attachments/assets/124c5e6c-e27a-420e-86b3-15b7b2f684b5)

![image](https://github.com/user-attachments/assets/10d48bc6-3926-451e-84e6-c99811dc81b5)

![image](https://github.com/user-attachments/assets/4c06c659-f6fd-4896-b6a4-4652194bd841)

![image](https://github.com/user-attachments/assets/aaa485e2-3bba-49a7-9fe4-b8a2eec16995)

![image](https://github.com/user-attachments/assets/99c09c3a-d29b-4c92-b7fc-474b6487cd26)

![image](https://github.com/user-attachments/assets/d9594a19-a383-44c4-9fab-62f58a123a77)

![image](https://github.com/user-attachments/assets/487887cd-461f-4370-adf6-e8e18c0b0b5d)

![image](https://github.com/user-attachments/assets/a10b22f3-1767-4ca1-a755-d1b0b4d3e5b4)

Week 7 (lecture 34-Introduction to Clock Tree Synthesis)

![image](https://github.com/user-attachments/assets/b45e5259-1a34-4d97-bfe4-99f994bea99c)

![image](https://github.com/user-attachments/assets/4663e906-becc-420c-99b5-f0fb7ec1cbd4)

![image](https://github.com/user-attachments/assets/78cbae4c-6a05-4576-8873-16d9f3d8f5f7)

![image](https://github.com/user-attachments/assets/57cd9e5c-062a-483c-9578-a712e2bca0d2)

![image](https://github.com/user-attachments/assets/a16d6c47-5b88-4620-ae79-fbdd2fd84078)

![image](https://github.com/user-attachments/assets/6460d026-1c65-4c6a-82b3-c0412d31a86f)

![image](https://github.com/user-attachments/assets/2117e88e-6a02-41db-af41-708b405e4cfd)

![image](https://github.com/user-attachments/assets/be021044-6069-417a-88c9-cd78f90b86cd)

![image](https://github.com/user-attachments/assets/78a1ea47-c3d9-4930-b0b0-6bd5ce89eaf8)

![image](https://github.com/user-attachments/assets/a50dbd83-d034-4dc3-b9ba-92c92b271cd2)

![image](https://github.com/user-attachments/assets/849e4796-9fca-40ef-ac32-ebb2e9fad220)

![image](https://github.com/user-attachments/assets/5e015c50-8736-46a5-9b66-87b2b0c9cb1e)

![image](https://github.com/user-attachments/assets/6c497e1a-8fbc-4f87-ba74-165c054e8253)

![image](https://github.com/user-attachments/assets/0074b8df-739a-4419-8fab-bcb092629bdc)

Distributed RC model takes more time to simulate but it is more accurate. There are equivalent T and Pi model to simulate in less time.

![image](https://github.com/user-attachments/assets/8aa98329-7667-4164-9ccc-294f8603f1d7)

Find the delay from the source node to I node.

![image](https://github.com/user-attachments/assets/772f5669-6ddb-477b-8b63-c0622775a883)

To apply Elmore delay model, the following conditions should be satisfied.

![image](https://github.com/user-attachments/assets/80fcf285-f434-410c-89ec-55429598a851)

![image](https://github.com/user-attachments/assets/4fa77821-0079-4cc4-9a6a-7d48ebc7d24f)

![image](https://github.com/user-attachments/assets/a8d67c71-c7df-4e41-a94d-d017cf9bbefb)

![image](https://github.com/user-attachments/assets/873b081b-5c11-40ae-8aa0-fe8b8c5c316b)

In unbuffered tree, all the capacitances are added, because all the capacitors are parallel.

![image](https://github.com/user-attachments/assets/a112ea99-99a4-4365-b972-822b1924e0da)

![image](https://github.com/user-attachments/assets/5921f3b1-fe03-4c23-ace4-66f4ffa7bcb4)

Buffer improves the transition time of the clock signal as shown in the diagram below.

![image](https://github.com/user-attachments/assets/f374df06-03b4-43fa-81b1-95507bd86beb)

The capacitance of the buffered node is minimum as shown in the diagram below.

![image](https://github.com/user-attachments/assets/b6f584dd-7e0f-4359-bec1-e62a8f54c421)

![image](https://github.com/user-attachments/assets/ff794216-2e47-4ab3-96fe-5390239d5814)

![image](https://github.com/user-attachments/assets/d11f229d-b7f0-4574-b248-8aa37cfccab8)

![image](https://github.com/user-attachments/assets/26ba1abe-e1cd-47db-b49e-f43f1f2074b5)

Week 7 (lecture 35-Clock Routing Algorithms – I)

![image](https://github.com/user-attachments/assets/67001c2c-4e30-4ca3-9f9f-b1846e3ab6a0)

![image](https://github.com/user-attachments/assets/cf056bd6-f98b-414b-86c4-99edbcd8e3ce)

![image](https://github.com/user-attachments/assets/1fcf6917-a1c6-49a9-8f19-c0621b4e0eb7)

![image](https://github.com/user-attachments/assets/880ffa0c-da17-4b6f-ad0f-57f8eb1bf2f3)

![image](https://github.com/user-attachments/assets/f196b154-a285-4860-8aba-57a82908defc)

![image](https://github.com/user-attachments/assets/219916d6-c75a-42c1-ad3e-7d36e5ce44bf)

Here, for doing the analysis, setup time, clock to q delay are ignored.

![image](https://github.com/user-attachments/assets/41765bbe-6f37-4cf6-a7f0-727a08be020e)

Here the time period is reduced, so the speed will be higher. This is called useful skew.

![image](https://github.com/user-attachments/assets/2cfe6b73-98ef-4c5d-adfd-9cce6e923534)

![image](https://github.com/user-attachments/assets/c748e026-e55b-4085-8e4b-0e2d2cb39902)

![image](https://github.com/user-attachments/assets/1daad693-6d6e-40d5-a9e0-aa1e7b7c0c26)

![image](https://github.com/user-attachments/assets/3aec7e83-a379-44d8-bef4-2311b42bccb8)

![image](https://github.com/user-attachments/assets/7d8a474a-a6e9-4d37-91ff-ae44910f639c)

![image](https://github.com/user-attachments/assets/a112c38b-8ac3-4046-a9fc-ff2dcfa78391)

![image](https://github.com/user-attachments/assets/a92ea4b5-81d2-45bd-9474-9b4969f52efc)

![image](https://github.com/user-attachments/assets/5de242de-3705-4fd9-9012-668249edad97)

![image](https://github.com/user-attachments/assets/296e6610-1415-4c6c-8c7f-18a944805a33)

![image](https://github.com/user-attachments/assets/8f1e7bdf-d6c5-4611-b5d9-a9672a2173d0)

![image](https://github.com/user-attachments/assets/64f43dc7-6ba1-4496-ba58-e09b087dd754)

![image](https://github.com/user-attachments/assets/398b1968-862e-4f00-94f5-7e50f53879d2)

Tapping points are used to connect.

![image](https://github.com/user-attachments/assets/b9817cd2-4b57-4675-9b8d-6b49363d366b)

![image](https://github.com/user-attachments/assets/a5acb824-3b16-4097-925b-90f4cd5bc14b)

![image](https://github.com/user-attachments/assets/7df0d74c-d12f-4876-8612-18eb4772f4c8)

We can extend this method to create more H trees. Here, 2 level H tree is shown.

![image](https://github.com/user-attachments/assets/ccabb829-0fb0-4175-9bc5-560590222466)

When the level k=2, the number of sink nodes possible are 4^2=16.

![image](https://github.com/user-attachments/assets/a405f2fd-fcfe-44f4-a609-8786cc8c9f69)

Week 7 (lecture 36-Clock Routing Algorithms – II)

![image](https://github.com/user-attachments/assets/66c4fa76-c1dd-4f86-a69c-379159be45f5)

![image](https://github.com/user-attachments/assets/6e26183c-cb36-4edf-808b-2b7b4a7c5c2c)

![image](https://github.com/user-attachments/assets/4e81f0af-2cc1-4749-a8a9-b5ba327b5536)

![image](https://github.com/user-attachments/assets/b2735992-dc13-4f1e-ab8a-16c2d91b1031)

![image](https://github.com/user-attachments/assets/7a06bbd2-df1f-4905-ac4d-df4747898b15)

![image](https://github.com/user-attachments/assets/7754fdbb-eddb-45af-a045-027fca9ee1f1)

![image](https://github.com/user-attachments/assets/8b34e804-e1e7-46c2-8ce2-52b28b68ccfc)

![image](https://github.com/user-attachments/assets/4f60e564-ff59-4c40-8b09-d1c3817e4648)

![image](https://github.com/user-attachments/assets/04f6ca69-ec06-4d27-b23e-168b1630160f)

![image](https://github.com/user-attachments/assets/30db1cd3-6d73-4035-9a38-b3eeb4b1fa7a)

![image](https://github.com/user-attachments/assets/01838a23-da7b-4a6c-9c28-0cadfa2ae881)

![image](https://github.com/user-attachments/assets/be06e77c-862a-4543-a5eb-f0870eac0049)

![image](https://github.com/user-attachments/assets/17ca2707-463e-4e32-993c-6728cc0f78c1)

![image](https://github.com/user-attachments/assets/3f1f6ad2-3ec9-434c-973d-56069bf6ba29)

![image](https://github.com/user-attachments/assets/e492c0c1-1992-4888-bfc9-81e241f67048)

Week 7 (lecture 37-Clock Routing Algorithms – III)

![image](https://github.com/user-attachments/assets/245587e3-bd33-42b5-8499-238c9fcf03de)

![image](https://github.com/user-attachments/assets/6d5dbebb-edf0-45ba-8077-c28f9dce5839)

![image](https://github.com/user-attachments/assets/cfc8df1e-c5ff-4d0d-bf79-cb95fe5b8dc1)

We should find the tapping point, so that both the branch delay is same. ie) the delay from A to T and B to T should be same, so that the skew at point T is zero.

![image](https://github.com/user-attachments/assets/9376e5eb-1ddd-4f23-b760-23bd6c53e0f4)

![image](https://github.com/user-attachments/assets/b3082203-9e70-482f-a573-99f7645034bc)

![image](https://github.com/user-attachments/assets/441744fe-bca0-497e-8734-dd6246c6ce11)

![image](https://github.com/user-attachments/assets/282ae623-f260-4dd1-a0ec-a8fde55d0504)

![image](https://github.com/user-attachments/assets/d2902d4b-f74e-4773-87fa-e06a4e3014f7)

![image](https://github.com/user-attachments/assets/c7af5649-827f-4c33-bb21-10b4dd79cfb9)

![image](https://github.com/user-attachments/assets/e8397b8b-c888-4745-b9e6-a285944c96f0)

If the sinks are aligned in a straight line, then the Manhattan arc will be a point.

![image](https://github.com/user-attachments/assets/f645457e-c07e-42eb-950f-1a6e04c7e19b)

![image](https://github.com/user-attachments/assets/b6819017-d317-4bb4-ad9f-145eaa6226f5)

![image](https://github.com/user-attachments/assets/2a6c2405-3df3-4057-88e1-82598b0f18ae)

![image](https://github.com/user-attachments/assets/9c8221f4-f096-4ced-987d-c1774e27aa19)

![image](https://github.com/user-attachments/assets/36e7eed9-5ad8-4bc7-93f1-ff7e08fd211b)

![image](https://github.com/user-attachments/assets/09d4ca65-1a96-446d-ab69-a111eccecfa9)

![image](https://github.com/user-attachments/assets/7bb7c9ab-405a-42a3-a65a-4ed0d7a7daf0)

s0 is the point where the clock is entering to the chip.

![image](https://github.com/user-attachments/assets/328f2040-af78-4e59-9cf3-95b93f89210e)

![image](https://github.com/user-attachments/assets/3d58bdde-5d30-4c18-b85d-a55f41aba790)

![image](https://github.com/user-attachments/assets/d8387202-d0f9-4a50-b788-91f5d3db1f44)

Week 8 (lecture 38-Introduction and Optimization Goals – Global Routing)

![image](https://github.com/user-attachments/assets/71eaefd7-640b-4614-bba9-b483a9dbd5ce)

![image](https://github.com/user-attachments/assets/56b44d45-8273-46e9-a06a-8870a7f0f22f)

This routing region is useful for creating routing tracks.

![image](https://github.com/user-attachments/assets/a68bcc9e-4923-44d9-a723-9c8448c3e44e)

![image](https://github.com/user-attachments/assets/7bc47583-a521-4d69-a0c4-1abf7e4dbc84)

There are two metal connections, vertical and horizontal.

![image](https://github.com/user-attachments/assets/7849a5a7-c8c5-4e1f-bdbe-cf234379dcf2)

![image](https://github.com/user-attachments/assets/bd4e3788-7a13-41eb-b289-63400b6b6c5b)

In time-driven routing, we see the critical nets and if the timing is not met, we do the operations mentioned in the below slide to improve the speed.

![image](https://github.com/user-attachments/assets/87859a07-ef0e-480f-91ad-6cb5b0b52451)

In global routing, the metals are not assigned and they are just the connections.

![image](https://github.com/user-attachments/assets/6412c47f-698b-4dd7-b0c3-f065a6121d4e)

![image](https://github.com/user-attachments/assets/4d78b7db-86d9-4a44-99dc-2529f2a3cab2)

![image](https://github.com/user-attachments/assets/84397d12-c0a9-408e-8460-8586520ce109)

In Net ordering, we will choose one of the nets that will be routed and in case of pin ordering, we will check what are the pins connecting to that net.

![image](https://github.com/user-attachments/assets/e212e171-6f33-4f80-8ac6-5de905c796e0)

![image](https://github.com/user-attachments/assets/0f74176e-841c-4b34-9c93-6031d36a75a5)

![image](https://github.com/user-attachments/assets/831fd5c0-7e70-42dc-b389-430feb94e4a5)

The routing tracks are mentioned as 1,2,3. The distance between two metal tracks are called pitch.

![image](https://github.com/user-attachments/assets/1875ca97-14a9-429e-abee-4c4177ea52d9)

This pitch will determine, how many tracks are possible in this routing region. In multilayer routing, we find the capicity for each layer and sum it up.

![image](https://github.com/user-attachments/assets/81cd952f-c40f-4341-9555-5048e375ef96)

![image](https://github.com/user-attachments/assets/12a31cba-c1ec-44b8-b6be-27487c2cb541)

![image](https://github.com/user-attachments/assets/e4164f78-f77e-4966-99bc-53cc3a20dcaa)

![image](https://github.com/user-attachments/assets/fefaa444-e609-41a3-a849-531122b25b34)

![image](https://github.com/user-attachments/assets/251bc440-11e7-4ddf-9797-ef9b3ccb4e1f)

![image](https://github.com/user-attachments/assets/5db0f32b-1d37-4ffb-9fef-547992870b37)

Feedthrough cells are extra cells in standard cell library.

![image](https://github.com/user-attachments/assets/a3489a8a-57ea-4cdb-9302-efef372fcdef)

![image](https://github.com/user-attachments/assets/790273eb-b663-47c4-8364-11aeb68f0bfa)

In the method shown below, the C pin remains unrouted. One possible solution is to modify the placement. Because, the routing region is fixed, so we can't change the routing region.

![image](https://github.com/user-attachments/assets/d7769794-b673-49b9-8e96-4bc30268bfdc)

Week 8 (lecture 39-Single net routing (Rectilinear routing))

![image](https://github.com/user-attachments/assets/b114e4a8-bacf-47c2-b690-2c7dae9955c3)

![image](https://github.com/user-attachments/assets/a12c2baf-11cd-43cf-8f78-7d6b716c49a3)

![image](https://github.com/user-attachments/assets/1c5f6162-4566-459d-b03a-2d490143c739)

![image](https://github.com/user-attachments/assets/49769b56-b7ec-4897-a50b-fe9300d02929)

![image](https://github.com/user-attachments/assets/cdf40222-01b1-4278-8933-59d06963400e)

![image](https://github.com/user-attachments/assets/178a7ec5-c363-4227-bae7-0fb8da375ae5)

![image](https://github.com/user-attachments/assets/afc1b5f5-411c-478b-9039-6df9299c9a3d)

![image](https://github.com/user-attachments/assets/dd1072e9-d637-43ad-b3b1-38f727af31b2)

![image](https://github.com/user-attachments/assets/05fdf2c3-a6d4-4f74-96b6-c662fc0d14ac)

![image](https://github.com/user-attachments/assets/ca7e4e3e-86d0-4995-8a10-0c160b94a6cc)

![image](https://github.com/user-attachments/assets/e5d85327-a396-4f54-9e3c-c9a48bed0234)

![image](https://github.com/user-attachments/assets/62e5547e-695c-4c20-9476-54ab33b1f607)

![image](https://github.com/user-attachments/assets/4eef038f-8eac-41e7-9a58-022e507b40be)

![image](https://github.com/user-attachments/assets/2787d537-e491-4ee6-bcca-4cb87b26afe7)

![image](https://github.com/user-attachments/assets/cdf1fc5a-5eb3-44bf-9943-9747c0026c3a)

![image](https://github.com/user-attachments/assets/8059c104-ddf1-4011-a1cf-8da984b19b18)

![image](https://github.com/user-attachments/assets/b563b1ba-435c-46ca-90d0-7e1d029955fb)

![image](https://github.com/user-attachments/assets/c684a46f-d701-4c30-96ef-2b9dbb2a6df9)

![image](https://github.com/user-attachments/assets/911e3e0d-a7f8-4050-ba49-5f3c0742c2f0)

![image](https://github.com/user-attachments/assets/07f5b64e-3e91-4cbb-a43d-ecccea48e95c)

![image](https://github.com/user-attachments/assets/b2cfde57-aa7f-4694-a85a-11ad5d2599df)

![image](https://github.com/user-attachments/assets/7ba67cf9-cc3d-4df1-957f-8cbb50fd4ab3)

Week 8 (lecture 40-Global Routing in the connectivity graph)

![image](https://github.com/user-attachments/assets/26fdfc20-6841-45cc-93c8-8aac9dbed4dd)

![image](https://github.com/user-attachments/assets/ce2573aa-8f98-4ad2-a4c2-7afd8e237227)

In the left side diagram, the blue blocks are the blocks of the placement and the white spaces are the channels, which represent a node.

![image](https://github.com/user-attachments/assets/f86472a1-451a-4b11-ac17-4e713c48a4ee)

When a vertical channel crosses the horizontal channel, a switchbox is formed.

![image](https://github.com/user-attachments/assets/a412f970-c20c-4818-8b47-c3164412c707)

Both the channel and switchbox connectivity graph combined to form a connectivity graph.

![image](https://github.com/user-attachments/assets/5dea853b-753e-415f-ad3c-5ab14134ea52)

![image](https://github.com/user-attachments/assets/60747693-1133-487f-8fb1-e22114eca46c)

![image](https://github.com/user-attachments/assets/80180ed6-d4f5-4aa3-a681-68e49a3c0e11)

![image](https://github.com/user-attachments/assets/f58a497d-51f6-4c57-b26c-36ae5db8b161)

![image](https://github.com/user-attachments/assets/2f84cfd2-0c5a-4f04-a7ec-f1df8e5d4e6c)

![image](https://github.com/user-attachments/assets/8b9f4d7f-8bc8-4da1-9955-c4ed3d92fd9a)

Horizontal or vertical capacity means that how many metals or wires pass through that regions.

![image](https://github.com/user-attachments/assets/38db2515-d198-4b50-af16-32562b47d55a)

![image](https://github.com/user-attachments/assets/7b0bdc82-5059-42d3-8b01-dfc2a0d577ae)

![image](https://github.com/user-attachments/assets/474c3ca5-b5bf-40d5-8f47-d5a4e743c3c2)

![image](https://github.com/user-attachments/assets/6a44f16d-3b2b-4a12-9626-585e0278236c)

If we use the horizontal metal, the horizontal capacity will be reduced by 1 and vice versa. I we use both the horizontal and vertical metal, both the capacity will be reduced by 1.

![image](https://github.com/user-attachments/assets/05b097fd-40af-4024-9819-2d535ab47878)

This is the finally routed design.

![image](https://github.com/user-attachments/assets/d94aca21-c682-43f3-bfe7-9844196727c6)

![image](https://github.com/user-attachments/assets/73bbd3fe-4b2b-4a6e-93d4-78ced30f7572)

After we do route for A, there is no space to route for B in 4 and 6. So, we can't use the shortest path. So, we use longest path.

![image](https://github.com/user-attachments/assets/49323384-bc6c-4bab-b15c-379b8b4ae674)

![image](https://github.com/user-attachments/assets/dcb49e7e-35d5-4071-980a-494d5d77b103)

![image](https://github.com/user-attachments/assets/fe77f220-b412-41e7-ab54-0c217f0af198)

Week 8 (lecture 41-Finding Shortest Paths with Dijkstra’s Algorithm)

![image](https://github.com/user-attachments/assets/d19b1b09-f2b1-4b4c-8395-031006a49d52)

![image](https://github.com/user-attachments/assets/ac220d7a-ce58-4e06-bb46-57b7b47ce389)

![image](https://github.com/user-attachments/assets/854279ab-6400-4e37-95d4-3458e03eb97d)

![image](https://github.com/user-attachments/assets/c7630ae3-fb07-40b2-ab5b-e16a2e7090aa)

![image](https://github.com/user-attachments/assets/62346880-ed17-4138-919d-eb507f1be1a7)

![image](https://github.com/user-attachments/assets/6d03be8b-a047-4d20-9600-aeb97348069d)

In the line 6, the first s is starting node and the second s is target node.

![image](https://github.com/user-attachments/assets/db7a9e74-e451-4239-99ca-480390eb945c)

![image](https://github.com/user-attachments/assets/e3f4fa4e-6f10-4f50-b0b4-ee5d166f870a)

![image](https://github.com/user-attachments/assets/f46eb13b-24ce-4a5c-baaa-947f1daa9cfc)

![image](https://github.com/user-attachments/assets/dc3a5979-a7ad-4973-8f57-8075105db471)

![image](https://github.com/user-attachments/assets/3523a10f-07a1-4247-a1ba-e3cd256f221c)

![image](https://github.com/user-attachments/assets/7e502f8b-3bf4-4afd-83cf-40f2374a4126)

![image](https://github.com/user-attachments/assets/cc5c4a38-46c9-4aa1-84e2-9037e4e4be98)

In the week 1 of the lecture also we saw this algorithm, but it uses only single weight per edge. Here we use two weights, one is horizontal capacity and the other is vertical capacity. Also previously our interconnects are not perpendicular to the x or y axis. But here the interconnect is either perpendicular to the x or y axis.

![image](https://github.com/user-attachments/assets/f4df7886-c62e-4cf5-95e5-257081e31107)

initially the source node goes to group 3, because, the distance form source node to source node is 0. Then we see the neighbours of node 1.

![image](https://github.com/user-attachments/assets/c822e061-4fca-4119-9e5e-724ff8bcb5fe)

![image](https://github.com/user-attachments/assets/e74def37-2bcc-429b-9bd7-16cfc579bdec)

Node 5 is occured 2 times so, we see which has higher cost and will remove it.

![image](https://github.com/user-attachments/assets/baa91032-9df0-49d0-8b37-580fa43b4eea)

Node 5 and Node 7 has same cost. So, we can choose any one of them.

![image](https://github.com/user-attachments/assets/b4ed6804-aa0f-4a60-80d8-07d26ee2a85c)

![image](https://github.com/user-attachments/assets/2db89686-bd12-4219-9683-cdcd2dda4f9d)

![image](https://github.com/user-attachments/assets/7a435876-9bc7-4faf-aa89-f81bef23eeb2)

![image](https://github.com/user-attachments/assets/f4a3e16e-7581-4045-bf21-a9b5a5568b35)

Week 8 (lecture 42-Full-Netlist Routing)

![image](https://github.com/user-attachments/assets/9a53471c-790e-46eb-bd7c-ec262d8f3927)

![image](https://github.com/user-attachments/assets/40e53c75-0511-491b-a350-b9f77bdb110e)

![image](https://github.com/user-attachments/assets/96f88794-9517-47ae-912f-bec417ed4a25)

![image](https://github.com/user-attachments/assets/680d2c46-e9fc-4048-8834-a5ed6451d2c9)

![image](https://github.com/user-attachments/assets/7b89ba2f-9e5b-4115-8cf2-9ccff6eb1adc)

![image](https://github.com/user-attachments/assets/11dee126-150e-4150-9a86-d3c1570edecb)

![image](https://github.com/user-attachments/assets/81492ac4-04ea-4c70-b3a5-d73735dffae3)

![image](https://github.com/user-attachments/assets/bcc55eb2-4cdf-4656-86ea-7770b697f472)

![image](https://github.com/user-attachments/assets/f54091ec-47b6-4e03-a6bb-01e5a9723b2b)

![image](https://github.com/user-attachments/assets/0341f083-39c7-49e0-9623-3ba937b038a5)

![image](https://github.com/user-attachments/assets/6f87dbdd-2927-45bb-87d5-7e5615629f4c)

![image](https://github.com/user-attachments/assets/70ac7915-e6be-46eb-b542-f18e7ed06963)

![image](https://github.com/user-attachments/assets/d3b60579-c268-4bc9-b6a3-f6f857b5e2ec)

![image](https://github.com/user-attachments/assets/39a214c9-aa26-4431-be90-fe2185ea5505)

![image](https://github.com/user-attachments/assets/e68e2d14-410e-44f4-9f9f-59dd43d7573d)

![image](https://github.com/user-attachments/assets/d5942989-5693-43fe-b5db-7c2beedbd6e0)

For L shape structure, we multiply the net with 1 and for Z shape structure, we multiply the net with 0.99. This means that the highest priority is given to the L shape net, and if no routing is possible with L shape net, we can go for Z shape net.

![image](https://github.com/user-attachments/assets/7800542c-471b-4545-a6a3-00db1a0b6980)

![image](https://github.com/user-attachments/assets/bdd776cc-f5d9-4358-8991-ec528ba744ee)

![image](https://github.com/user-attachments/assets/d5c4f09c-ca99-49c7-813e-b5814510dbde)

Week 9 (lecture 43-Introduction: Detailed Routing)

![image](https://github.com/user-attachments/assets/344d3b29-f859-480d-9595-2e0547338aef)

![image](https://github.com/user-attachments/assets/446c80c1-4db8-423f-9b78-75ef2d1a191e)

