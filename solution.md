# Two Envelope Problem

## Solution

Call the two envelopes A and B. There are four scenarios possible:

Choose A first, then switch to B;

Choose A first, then stay with A;

Choose B first, then switch to A; 

Choose B first, then stay with B.

For each scenario, it's equally likely that A contains the larger value or B does. Let's list these out in a table.

| Scenario          | Value of A | Value of B | Value if you stay | Value if you switch |
|-------------------|------------|------------|-------------------|---------------------|
| A first, B second | A          | 2A         | A                 | 2A                  |
| A first, B second | A          | A/2        | A                 | A/2                 |
| B first, A second | A          | 2A         | 2A                | A                   |
| B first, A second | A          | A/2        | A/2               | A                   |

Since each of these scenarios are equally likely, the expected value if you stay is (A+A+2A+A/2)/4, and the expected value if you switch is (2A+A/2+A+A)/2. Those are equal! 