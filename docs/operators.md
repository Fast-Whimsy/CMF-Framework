# CMF Operators

This document defines the operator classes used within the Coherence Mapping Framework (CMF). Operators describe how CMF objects transform, combine, or evolve.

---

## **1. Structural Operators**
Operators that modify the internal structure of a CMF object.

### **1.1 Add Node**
Introduces a new node into the structure.

### **1.2 Remove Node**
Eliminates an existing node while preserving coherence where possible.

### **1.3 Add Mapping**
Creates a new directed relationship between elements.

### **1.4 Remove Mapping**
Removes an existing relationship.

---

## **2. Transformational Operators**
Operators that change the state or configuration of a CMF object.

### **2.1 Reframe**
Shifts the interpretive field or context of a structure.

### **2.2 Merge**
Combines two structures into a unified representation.

### **2.3 Split**
Divides a structure into two or more coherent substructures.

---

## **3. Analytical Operators**
Operators that extract information or evaluate coherence.

### **3.1 Trace**
Follows mappings through a structure to reveal dependencies.

### **3.2 Evaluate Coherence**
Assesses relational stability within the object.

### **3.3 Summarize**
Produces a reduced representation of the structure.

---

## **4. Metadata Operators**
Operators that modify descriptive information without altering structure.

### **4.1 Rename**
Changes the human-readable name of an element.

### **4.2 Version Bump**
Updates the version metadata to reflect changes.

---

## **5. Composite Operators**
Operators composed of multiple primitive operators.

### **5.1 Normalize**
Applies a sequence of structural and transformational operators to bring an object into canonical form.

### **5.2 Resolve**
Applies a series of transformations to eliminate contradictions or incoherence.

---

These operator classes provide the functional vocabulary for transforming CMF objects in a structured and predictable way.

