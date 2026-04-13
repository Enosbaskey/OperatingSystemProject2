# Scheduling Algorithms Implementation

##Name
Enos Baskey  done algorithm 3 and 4

---

## 📌 Description
This project implements two scheduling algorithms:
 1. Run Lottery Scheduler
 2. Run Rate Monotonic Scheduler (RMS)
 done by me 3 and 4
 3. Earliest Deadline First (EDF)
 4. Shortest Job First (SJF)

These algorithms are simulated in a multiprocessor environment.

---

## ⚙️ Algorithms Implemented

### 3. EDF (Earliest Deadline First)
- Priority based on earliest deadline
- Used for real-time systems
+++ Multiprocessor Scheduling Simulator +++
   Algorithms: Lottery, RMS, EDF, SJF
   Number of Processing Cores: 2
   Total tasks initialized: 20

Available choices:
 1. Run Lottery Scheduler
 2. Run Rate Monotonic Scheduler (RMS)
 3. EDF
 4. SJF
 5. Quit
3

--- EDF Scheduling ---
00	[T1]	[T1]	
01	[T1]	[T1]	
02	[T3]	[T3]	
03	[T3]	[T3]	
04	[T1]	[T1]	
05	[T1]	[T1]	
06	[T4]	[T4]	
07	[T4]	[T4]	
08	[T5]	[T5]	
09	[T4]	[T4]	
10	[T4]	[T4]	
11	[T4]	[T4]	
12	[T7]	[T7]	
13	[T7]	[T7]	
14	[T7]	[T7]	
15	[T8]	[T8]	
16	[T8]	[T8]	
17	[T8]	[T8]	
18	[T4]	[T4]	
19	[T2]	[T2]	
20	[T9]	[T9]	
21	[T9]	[T9]	
22	[T10]	[T10]	
23	[T10]	[T10]	
24	[T9]	[T9]	
25	[T11]	[T11]	
26	[T11]	[T11]	
27	[T11]	[T11]	
28	[T11]	[T11]	
29	[T9]	[T9]	
30	[T9]	[T9]	
31	[T9]	[T9]	
32	[T9]	[T9]	
33	[T9]	[T9]	
34	[T2]	[T2]	
35	[T13]	[T13]	
36	[T2]	[T2]	
37	[T2]	[T2]	
38	[T2]	[T2]	
39	[T2]	[T2]	
40	[T14]	[T14]	
41	[T14]	[T14]	
42	[T14]	[T14]	
43	[T14]	[T14]	
44	[T14]	[T14]	
45	[T15]	[T15]	
46	[T15]	[T15]	
47	[T2]	[T2]	
48	[T2]	[T2]	
49	[T2]	[T2]	
50	[T16]	[T16]	
51	[T16]	[T16]	
52	[T16]	[T16]	
53	[T16]	[T16]	
54	[T16]	[T16]	
55	[T17]	[T17]	
56	[T17]	[T17]	
57	[T17]	[T17]	
58	[T16]	[T16]	
59	[T16]	[T16]	
60	[T18]	[T18]	
61	[T18]	[T18]	
62	[T18]	[T18]	
63	[T18]	[T18]	
64	[T16]	[T16]	
65	[T16]	[T16]	
66	[T2]	[T2]	
67	[T2]	[T2]	
68	[T2]	[T2]	
69	[T2]	[T2]	
70	[T20]	[T20]	
71	[T20]	[T20]	
72	[T19]	[T19]	
73	[T19]	[T19]	
74	[T19]	[T19]	
75	[T19]	[T19]	
76	[T19]	[T19]	
77	[T19]	[T19]	
78	[T19]	[T19]	
79	[T19]	[T19]	
80	[T19]	[T19]	
81	[T19]	[T19]	
82	[T19]	[T19]	
83	[T6]	[T6]	
84	[T6]	[T6]	
85	[T6]	[T6]	
86	[T6]	[T6]	
87	[T6]	[T6]	
88	[T6]	[T6]	
89	[T6]	[T6]	
90	[T6]	[T6]	
91	[T6]	[T6]	
92	[T6]	[T6]	
93	[T6]	[T6]	
94	[T6]	[T6]	
95	[T6]	[T6]	
96	[T6]	[T6]	
97	[T6]	[T6]	
98	[T6]	[T6]	
99	[T6]	[T6]	
100	[T6]	[T6]	
101	[T6]	[T6]	
102	[T6]	[T6]	
103	[T12]	[T12]	
104	[T12]	[T12]	
105	[T12]	[T12]	
106	[T12]	[T12]	
107	[T12]	[T12]	
108	[T12]	[T12]	
109	[T12]	[T12]	
110	[T12]	[T12]	
111	[T12]	[T12]	
112	[T12]	[T12]	
113	[T12]	[T12]	
114	[T12]	[T12]	
115	[T12]	[T12]	
116	[T12]	[T12]	
117	[T12]	[T12]	
118	[T12]	[T12]	
119	[T12]	[T12]	
120	[T12]	[T12]	
121	[T12]	[T12]	
122	[T12]	[T12]	
123	[T12]	[T12]	
124	[T12]	[T12]	
125	[T12]	[T12]	
126	[T12]	[T12]	
127	[T12]	[T12]	

--- Performance Stats ---
TID	Arrival	Burst	Start	Finish	Turnaround	Waiting
---	-------	-----	-----	------	----------	-------
T1	0	8	0	6	6		-2
T2	1	25	19	70	69		44
T3	2	3	2	4	2		-1
T4	5	12	6	19	14		2
T5	8	2	8	9	1		-1
T6	10	40	83	103	93		53
T7	12	5	12	15	3		-2
T8	15	6	15	18	3		-3
T9	20	15	20	34	14		-1
T10	22	4	22	24	2		-2
T11	25	8	25	29	4		-4
T12	30	50	103	128	98		48
T13	35	2	35	36	1		-1
T14	40	9	40	45	5		-4
T15	45	3	45	47	2		-1
T16	50	18	50	66	16		-2
T17	55	5	55	58	3		-2
T18	60	7	60	64	4		-3
T19	65	22	72	83	18		-4
T20	70	4	70	72	2		-2

Mean Turnaround Time : 18.00
Mean Waiting Time    : 5.60
Available choices:
 1. Run Lottery Scheduler
 2. Run Rate Monotonic Scheduler (RMS)
 3. EDF
 4. SJF
 5. Quit

### 4. SJF (Shortest Job First)
- Selects process with smallest burst time
- Minimizes waiting time
Available choices:
 1. Run Lottery Scheduler
 2. Run Rate Monotonic Scheduler (RMS)
 3. EDF
 4. SJF
 5. Quit
4

--- SJF Scheduling ---
00	[T1]	[--]	
01	[T1]	[T2]	
02	[T1]	[T2]	
03	[T1]	[T2]	
04	[T1]	[T2]	
05	[T1]	[T2]	
06	[T1]	[T2]	
07	[T1]	[T2]	
08	[T5]	[T2]	
09	[T5]	[T2]	
10	[T3]	[T2]	
11	[T3]	[T2]	
12	[T3]	[T2]	
13	[T7]	[T2]	
14	[T7]	[T2]	
15	[T7]	[T2]	
16	[T7]	[T2]	
17	[T7]	[T2]	
18	[T8]	[T2]	
19	[T8]	[T2]	
20	[T8]	[T2]	
21	[T8]	[T2]	
22	[T8]	[T2]	
23	[T8]	[T2]	
24	[T10]	[T2]	
25	[T10]	[T2]	
26	[T10]	[T11]	
27	[T10]	[T11]	
28	[T4]	[T11]	
29	[T4]	[T11]	
30	[T4]	[T11]	
31	[T4]	[T11]	
32	[T4]	[T11]	
33	[T4]	[T11]	
34	[T4]	[T9]	
35	[T4]	[T9]	
36	[T4]	[T9]	
37	[T4]	[T9]	
38	[T4]	[T9]	
39	[T4]	[T9]	
40	[T13]	[T9]	
41	[T13]	[T9]	
42	[T14]	[T9]	
43	[T14]	[T9]	
44	[T14]	[T9]	
45	[T14]	[T9]	
46	[T14]	[T9]	
47	[T14]	[T9]	
48	[T14]	[T9]	
49	[T14]	[T15]	
50	[T14]	[T15]	
51	[T16]	[T15]	
52	[T16]	[T6]	
53	[T16]	[T6]	
54	[T16]	[T6]	
55	[T16]	[T6]	
56	[T16]	[T6]	
57	[T16]	[T6]	
58	[T16]	[T6]	
59	[T16]	[T6]	
60	[T16]	[T6]	
61	[T16]	[T6]	
62	[T16]	[T6]	
63	[T16]	[T6]	
64	[T16]	[T6]	
65	[T16]	[T6]	
66	[T16]	[T6]	
67	[T16]	[T6]	
68	[T16]	[T6]	
69	[T17]	[T6]	
70	[T17]	[T6]	
71	[T17]	[T6]	
72	[T17]	[T6]	
73	[T17]	[T6]	
74	[T20]	[T6]	
75	[T20]	[T6]	
76	[T20]	[T6]	
77	[T20]	[T6]	
78	[T18]	[T6]	
79	[T18]	[T6]	
80	[T18]	[T6]	
81	[T18]	[T6]	
82	[T18]	[T6]	
83	[T18]	[T6]	
84	[T18]	[T6]	
85	[T19]	[T6]	
86	[T19]	[T6]	
87	[T19]	[T6]	
88	[T19]	[T6]	
89	[T19]	[T6]	
90	[T19]	[T6]	
91	[T19]	[T6]	
92	[T19]	[T12]	
93	[T19]	[T12]	
94	[T19]	[T12]	
95	[T19]	[T12]	
96	[T19]	[T12]	
97	[T19]	[T12]	
98	[T19]	[T12]	
99	[T19]	[T12]	
100	[T19]	[T12]	
101	[T19]	[T12]	
102	[T19]	[T12]	
103	[T19]	[T12]	
104	[T19]	[T12]	
105	[T19]	[T12]	
106	[T19]	[T12]	
107	[--]	[T12]	
108	[--]	[T12]	
109	[--]	[T12]	
110	[--]	[T12]	
111	[--]	[T12]	
112	[--]	[T12]	
113	[--]	[T12]	
114	[--]	[T12]	
115	[--]	[T12]	
116	[--]	[T12]	
117	[--]	[T12]	
118	[--]	[T12]	
119	[--]	[T12]	
120	[--]	[T12]	
121	[--]	[T12]	
122	[--]	[T12]	
123	[--]	[T12]	
124	[--]	[T12]	
125	[--]	[T12]	
126	[--]	[T12]	
127	[--]	[T12]	
128	[--]	[T12]	
129	[--]	[T12]	
130	[--]	[T12]	
131	[--]	[T12]	
132	[--]	[T12]	
133	[--]	[T12]	
134	[--]	[T12]	
135	[--]	[T12]	
136	[--]	[T12]	
137	[--]	[T12]	
138	[--]	[T12]	
139	[--]	[T12]	
140	[--]	[T12]	
141	[--]	[T12]	

--- Performance Stats ---
TID	Arrival	Burst	Start	Finish	Turnaround	Waiting
---	-------	-----	-----	------	----------	-------
T1	0	8	0	8	8		0
T2	1	25	1	26	25		0
T3	2	3	10	13	11		8
T4	5	12	28	40	35		23
T5	8	2	8	10	2		0
T6	10	40	52	92	82		42
T7	12	5	13	18	6		1
T8	15	6	18	24	9		3
T9	20	15	34	49	29		14
T10	22	4	24	28	6		2
T11	25	8	26	34	9		1
T12	30	50	92	142	112		62
T13	35	2	40	42	7		5
T14	40	9	42	51	11		2
T15	45	3	49	52	7		4
T16	50	18	51	69	19		1
T17	55	5	69	74	19		14
T18	60	7	78	85	25		18
T19	65	22	85	107	42		20
T20	70	4	74	78	8		4

Mean Turnaround Time : 23.60
Mean Waiting Time    : 11.20
Available choices:
 1. Run Lottery Scheduler
 2. Run Rate Monotonic Scheduler (RMS)
 3. EDF
 4. SJF
 5. Quit

---

## ▶️ How to Run

```bash
gcc main.c algorithms.c -o sim
./sim
