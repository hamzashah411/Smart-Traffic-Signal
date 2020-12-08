# Smart-Traffic-Signal

As the human population grow ,the cities physical infrastructure is also expanding samultaniously .We build new roads connecting cities and homes on natural habitats.These locations contain rich wildlife ,and if not taken care of would decrease their populations inturn destroying the natural habitats.Each years their are thousands of accidents at traffic intersactions involving animals crossing when the lights are green.We as humans have a collective responsibility to keep them safe and secure while building new infrastructures.

I propose a solution that would help preventing such accidents by cautioning humans. Most of  the intersections already have installed cctv cameras for regulation purposes.We can use its feed and pass it to a machiene learning model to tell us weather there is an animal or not at the intersection it is filming.If yes we can then command the all traffic lights to turn red until the the animal has crossed the road.Moreover I have added a feature of live whatsapp status alert of that particular intersaction. We can also take a photo and send it to the whatsapp as proof.


I will be using jetson nano as the compute module for this project.We will also utilize its GPIO pins to turn a set of 2 relays on and off for the traffic light red and green.

## Setting up GPIO pins

We have to setup upto 2 GPIO pins for basic demonstration of this project. Go to this link:https://www.youtube.com/watch?v=kVUNpyaHCc4 on how to initially setup your Jetson Nano GPIO pins.One key aspect to keep in mind is that Jetson Nano follows the same standered of GPIO pins as it is on the Respberry pi.The only differance is that its GPIO pins do output the same power the pi GPIO  pins do.

## Setting up Relay module
Once you are all done and familiar with your GPIO pins it now time to make physical connestions.
![relay](https://user-images.githubusercontent.com/45399315/101406710-df03c100-38ea-11eb-91cb-0f9157cffcb9.jpg)
The above image shoes the relay board which is going to be used in our project.
Connections are explained is the vedio below.




## Setting up Whatsapp Twillo account
Once you are all done and familiar with your GPIO pins and relay module ,We now will setup our whatsapp twillo account.Go to their website(follow this link:https://www.youtube.com/watch?v=O2PB6o2E8aA) and make a free account on twillo.You will get 15$ free cradit which is more then enough for implementation of our project.

## Algorithm
The algorithm is fairly compact simple and easy to understand 








