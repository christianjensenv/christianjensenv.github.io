---
layout: essay
type: essay
title: Being efficient with asking questions
# All dates must be YYYY-MM-DD format!
date: 2020-01-29
labels:
  - Smart questions
  - Dumb questions
  - How to ask
---

## An example of a bad question

- Gives an infinite loop
    I am using a List in Java and I am iterating through the collection to work with the created list
    of integer values. Why is this resulting in an infinite loop?
```
int i = 0;
int j = 0;
List<Integer> li = new ArrayList<Integer>();
for (i = 0; i < 10; i++) {
    li.add(i);
}
do {
    System.out.println(li.get(j));
} while(j < li.size());
```

A question such as this one is very low effort and seems rushed. Eric Raymond tells us that to be a nice question-asker you must do 
your research before putting a question out on the web. The user’s actual question is located at the end of his description, by doing
this his header says "Hey fix my issue!". It’s never good to throw out a problem on the internet without even showing that you exhaust
every option you have. This question can be easily solved with some tracing or starting from scratch. With only eight lines of code, 
this user should have dissected each line by itself to find the problem. By printing out the variables it would give the problem away 
very easily. The "j" integer doesn't increment, therefore the while loop is always true. It’s not helpful that the question asker 
doesn’t say how he got to this point or what he’s making the code for, it almost seems like an example of someone posting a homework
question on StackOverflow. With all the information you’d wish for, at your fingertips, a simple question like this doesn’t need to be
on StackOverflow

## Negative outcomes

The negative outcomes that come from a question like this are all the backlash that it generates. The community will answer a question
like this with passive-aggressiveness, or people treating you as if you are stupid. If you look at some of the responses you would see
“Does j++ ring any bells?“ Having a horde of programmers answer your question with the same answer and no variation, that is a
punishment in itself. 

## An example of a good question

- How to pass “Null” (a real surname!) to a SOAP web service in ActionScript 3
    We have an employee whose surname is Null. Our employee lookup application is killed when that last name is used as the search term 
    (which happens to be quite often now). The error received (thanks Fiddler!) is
    
```
<soapenv:Fault>
   <faultcode>soapenv:Server.userException</faultcode>
   <faultstring>coldfusion.xml.rpc.CFCInvocationException: [coldfusion.runtime.MissingArgumentException : The SEARCHSTRING parameter to the getFacultyNames function is required but was not passed in.]</faultstring>
```
The parameter type is string.
I am using
- WSDL (SOAP)
- Flex 3.5
- ActionScript 3
- ColdFusion 8
Note that the error does not occur when calling the webservice as an object from a ColdFusion page.
   
This is a question that has more weight and importance behind it than a normal question. This is a great way to ask and structure a 
problem that you’ve run into. The user has a perplexing question that sparked the interest of many respondents. The user demonstrates 
that they are willing to give extra information about what they are using and what the parameter that the application takes in. This 
question proved that it was a difficult problem to solve as the solution using a unique method to encode the names with hex to prevent 
running into a bug. This user shows that they know what they are doing, yet they ran into a confusing problem that isn’t easy to solve,
and that’s a proper use of StackOverflow.

## Positive outcomes
The positive outcomes that come from this kind of question are that you help out a lot of people by asking it alone. Some people may 
have gotten stuck with a similar problem but didn’t know how to ask. It’s similar to a classroom, your question might be what others 
are thinking but just don’t know how to structure the question in the first place. Just based on the votes of the question shows that 
my point isn’t far from the truth. On the other side of the question, it helps respondents exercise their skills, you get much more 
meaningful answers this way.

## In conclusion

There is no such thing as a stupid question but knowing when to post it up or to do your own research is two different things. Having 
the necessary steps to solving a problem is a must before putting a question on the web, especially on StackOverflow. Being called out
for being lazy would be the worst thing possible.

StackOverflow links
[Bad Question](https://stackoverflow.com/questions/19314079/gives-an-infinite-loop/)
, 
[Good Question](https://stackoverflow.com/questions/4456438/how-to-pass-null-a-real-surname-to-a-soap-web-service-in-actionscript-3/)

