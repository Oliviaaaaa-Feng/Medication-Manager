# Patient Manager

This project aim to manage patient information and medications, with unit tests.

## Features
- Medication: represents a medication prescribed to a patient, including datePrescribed, name, dose, route, frequency, duration.
- BloodType: represents all blood types - A+, A-, B+, B-, O+, O-, AB+, AB-.
- Patient: represents a patient and their medical data, including their full name, date of birth, height, weight, blood type, and medications.

## Methods
- nameAndAge(): Returns the patient's full name and age.
- currentMedications(): Returns the list of medications the patient is currently taking and sorted by date prescribed.
- prescribeNewMedication(_ newMedication: Medication): Prescribes a new medication for the patient.
- donorBloodTypes(): Returns the list of blood types the patient can receive a transfusion from.
- medicationHistory(): Returns a list of all medications the patient has taken with their statuses (Active/Completed)
- hasMedication(named name: String): Checks if the patient is taking a specific medication and returns a message.
- ageGroup(): Categorizes the patient into the "Child", "Teenager", "Adult", "Senior" age groups based on their age.

## Running the Tests
The unit test is in MedicationManagerTests.swift using the Swift Testing framework, which include one example Patient and test all above methods under Patient type.
