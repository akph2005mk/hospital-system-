# Hospital System (Team Project)
## Requirements
Implement a system for a hospital with the following features:

- There are 20 different specializations, each with a maximum of 5 available spots in a queue.
- When adding a patient:
  - Read the requested specialization (1-20).
  - Read the patient's name and status (0 = regular, 1 = urgent).
  - If the queue for the requested specialization is full, apologize and do not accept the patient.
  - If the patient is regular, add them to the end of the queue. If the patient is urgent, add them to the beginning of the queue.
- Print the list of patients waiting for each specialization that has waiting patients.
- When a doctor picks up a patient:
  - Read the requested specialization.
  - If there are no patients in the queue for that specialization, inform the doctor.
  - Otherwise, ask the first patient in the queue to go with the doctor and remove them from the queue.
