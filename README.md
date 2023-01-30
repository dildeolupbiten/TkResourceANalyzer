# TkResourceAnalyzer

**TkResourceAnalyzer** is a Python program that calculates alternative shift systems that have 7/24 full coverages which are required for call center like businesses.

## Availability

Windows, Linux

## Usage

**1.** After a short while we run the **TkResourceAnalyzer.exe** file, we should see the following main screen:

![img01](https://user-images.githubusercontent.com/29302909/215339232-b18d5e50-c1e1-48b9-95c6-5d708f7764a5.png)

**2.** Determine the required parameters using inputs:

![img02](https://user-images.githubusercontent.com/29302909/213919920-575b3a9d-d69c-45bd-a51e-c7dc6859842e.png)

- The **Volume** parameter, which is the number of tasks in a day that the task provider committed to send.

- The **AHT** parameter, which indicates how many seconds on average employees solve the tasks.

- The **Shrinkage** parameter, which is the ratio of the number of employees that will attend to shifts to the number of all employees,

- The **Work Hour** parameter which is about how many hours an employee is working in a day.

- Like the **Utilization Rate** parameter, the **HC** (HeadCount) and the **Daily HC** parameters are calculated automatically when user presses any numeric keys on any available input fields.

**2.** By default, for every hour, trend values are same (=1/24). Under this situation, the **Analysis** tab looks like:

![img03](https://user-images.githubusercontent.com/29302909/215339366-61a7e7ed-240f-4ee7-ac0f-4e5f544abfea.png)

You can determine and save the trend of your project.

![img04](https://user-images.githubusercontent.com/29302909/215339736-de16ad17-73d1-4b88-9974-50761d53368d.png)

After saving the trend, we should see the **Analysis** tab like this:

![img05](https://user-images.githubusercontent.com/29302909/215339675-75ba45c6-2ec3-4f20-8746-cb8593b6f19b.png)

**3.** Determine the offline activities of the workers of the project.

![img06](https://user-images.githubusercontent.com/29302909/215339776-6db275ff-e6eb-4e78-bc66-6a067af0fa8d.png)

Defined offline activities affect a parameter called Utilization Rate which is found by subtracting the sum of all offline activity times from working hours. By default, the work hour is defined as 9 hours and can be changed.

![img07](https://user-images.githubusercontent.com/29302909/215339877-2c3431b7-ca12-4a9f-b017-b569e86f7789.png)

In the example above, after defined the offline activities, the value of utilization rate has changed to 0.78.

**4.** After filling all necessary inputs, the **Analysis** tab should change like this:

![img08](https://user-images.githubusercontent.com/29302909/215339948-a71d1a7e-5f90-4de4-902c-f2486004ef39.png)

**5.** Now, we can pass searching for whether there are appropriate shift systems according to the parameters we determined.

Within seconds, the program will try to find all shift combinations with full coverage for all hours, which are ranging from 3-shift system to 5-shift system, and which are visible only to premium users.

The shift systems are shown in the **N Shifts** tile while the shift combinations are shown in the **Shifts** tile. Whenever any of the values of these comboboxes change, the values of the **Actual**, the **Coverage**, the **Occupancy** and the **Waiting Time** parameters, the coverage graph and the hc distribution schemas do change too.

![img09](https://user-images.githubusercontent.com/29302909/215340066-e46927b1-c21b-460e-b632-d8c990e3e2cd.png)

**6.** Premium users can upgrade their program using the **Upgrade** tab.

![img10](https://user-images.githubusercontent.com/29302909/215344367-6b3cf001-2112-4822-a712-84bfa02f5234.png)

**Request Credentials** button sends a safe login request email that contains the credentials of the premium user and a unique token that expires in 60 seconds, to the address that is written into the input field. If the address belongs to a premium account, the frame changes as below:

![img11](https://user-images.githubusercontent.com/29302909/215345501-74152e67-5e21-4260-ae28-2b5f787f2ce8.png)

If the credentials and the token are entered correctly within 60 seconds, the **Upgrade** tab is removed until the premium user tries to upgrade the program on another operating system. 

![img12](https://user-images.githubusercontent.com/29302909/215349634-5bc6d8ea-c699-48b4-a0ec-32983e4244f4.png)

The premium user will be able to use the program on different machines but each time he/she will try to upgrade any copy of the program the versions of rest of the copies which are found on different machines will be downgraded. In other words, the premium user can only upgrade one of his/her copies.

To become a premium user, please contact the [developer](mailto://tckutlu@gmail.com).
