# Technical Writer Task

Recommendations for current [Getting Started](https://support.qredo.com/docs/Getting%20Started) page
 

## 1. External references
First sentence directs user to external page but without URL. This page should contain 
all required instructions for Getting Started and no other information (e.g. video links, 
FAQs, external instructions). User should not have to leave the page until they have Got Started. 
This page  
- should preemptively answer any relevant FAQs commonly encountered from users at this stage
- must be self-explanatory and be as close as possible to a guarantee of Getting Started.

**Suggest** the page should comprise only step instructions and brief *Notes*, *Cautions* or *Warnings* (as defined in the Standard)
e.g.
### 1. Obtain the Oredo Web App here
### 2. Prepare and install Oredo Web App
2.1
2.2
2.3 etc
### 3. Obtain the Oredo Signing App here
### 4. Authenticate Oredo Signing App 
4.1
4.2
4.3 etc

## 2.
>There are 3 sets of steps as follows:
>1.	Web app steps       #wallet-app-steps anchor missing
>2.	Signing app steps
>3.	Login steps
        

## 3. The text presented as a **Note** should be **step instructions**.
>1 Write down your seed recovery phrase clearly.
>2 Note down each word in the seed recovery phrase.
>3 Ensure that you note down the email address you used to register on Qredo. 
>   You will need this email address for recovering your master seed.
>4 Keep the email address in a separate place to the word list.
>5 Ensure that the order of the words in the seed phrase is correct by numbering each word in the phrase.
>6 Store the seed recovery phrase in a safe place.
>7 Do not store the seed recovery phrase on a device that is connected to the internet.
>8 To test master seed recovery, you should perform the steps in the Recovery section. 
>Once familiar, you can return to these steps for the setup process.

**Suggest** brevity and consistency of wording for easier reading:
>1   "Write down or store your seed recovery phrase on a device that does not connect to the internet
>2   Save the email address used to register on Qredo
>3   Store seed recovery phrase and email address used in separate devices
>4   Follow steps in Recovery section [add link] to test master seed recovery

Integrate these steps to appropriate section of instruction sequence.

## 4. Suggest ensuring all steps are a linear sequence to avoid necessity of return or external reference.
This includes number all level two and level three headings as e.g. 1.1 and 1.1.1, 1.1.2, to ensure 
a clear and simple sequence to follow in a multi-dependency configuration process.

>1. Web App Steps
>1.1 Start Registration
>1.1.1 Establish Qredo Identity
>(sub steps)
>1.1.2 Set Password
>(sub steps)
>1.1.3 Accept Terms and Conditions
>(sub steps)
>1.1.4 Validate Email Address
>(sub steps)

2. Create a new branch

2. Add your markdown file to the new branch

3. Create a Pull Request with ddocs as a reviewer


