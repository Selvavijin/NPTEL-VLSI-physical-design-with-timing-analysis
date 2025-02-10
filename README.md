# NPTEL - VLSI Physical design with timing analysis

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

