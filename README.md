# Intelligent Optimization of Steel Structures
![GA_2DTRUSS_Literature_2024-03-28_04-14-55](https://github.com/ugurfeyzullah/Structural-optimization-with-VP/assets/149387821/d431ece5-21c5-4f71-8fc4-bc887d315710)

**Quick Links:** [Documentation](#features) / [Installation](#installation) / [Usage](#usage) / [Paper](https://www.preprints.org/manuscript/202404.0060/v1) /  [Citation](#citation) / [Contact](#contact)

This repository hosts the implementation of an innovative methodology for the intelligent optimization of steel structures using a BIM-based visual programming platform and tools. The methodology leverages Genetic Algorithms (GA), Visual Programming (VP) with Dynamo, and FEA with RSA to minimize structural weight while satisfying stress and displacement constraints.

This project was conceptualized and performed during the research stay at the research group of Jun.-Prof. Dr. Reza Maalek, the GOLDBECK endowed chair in Digital Engineering and Construction (DEC) at the Institute of Technology and Management in Construction (TMB) of the Karlsruhe Institute of Technology (KIT). The findings and experimental details were presented in the M.Sc. thesis for the partial fulfillment of the degree of Master of Science in Civil Engineering at the Kardeniz Technical University (KTU) under the joint supervision of Jun.-Prof. Dr. Reza Maalek and Prof. Dr. Vedat Togan. The author contributions (based on MDPI’s categorization) are as follows:

Conceptualization, R.M. and F.Y.; methodology, R.M., F.Y., and V.T.; software, F.Y.; validation, F.Y.; formal analysis, F.Y.; investigation, R.M. and F.Y.; resources, R.M.; data curation, F.Y.; writing—original draft preparation, F.Y.; writing—review and editing, R.M. and V.T.; visualization, F.Y.; supervision, R.M. and V.T.; project administration, R.M. and V.T.; funding acquisition, R.M.






https://github.com/ugurfeyzullah/Intelligent-Optimization-of-Steel-Structures-Through-Bim-Based-Visual-Programming-Platform-and-Tools/assets/149387821/1261d706-0fb2-452e-8fc2-2f25243358e3





## Features

- **Integration with BIM Tools**: Utilizes Dynamo for visual programming and Revit for BIM to streamline the structural design and optimization process.
- **Genetic Algorithm Optimization**: Employs genetic algorithms for efficient search and optimization of structural parameters.
- **Finite Element Analysis**: Uses Robot Structural Analysis (RSA) for accurate stress, weight and displacement calculations.
- **Visual Programming**: Leverages the power of Dynamo to facilitate the parametric modeling and optimization process.
- **Life Cycle Assessment and Cost Analysis**: Incorporates LCA and cost analysis via Revit and Tally to evaluate the environmental and economic impact of optimized designs.




https://github.com/ugurfeyzullah/Intelligent-Optimization-of-Steel-Structures-Through-Bim-Based-Visual-Programming-Platform-and-Tools/assets/149387821/f16c190f-1e9f-4d1b-a5bc-2ce4900322ce




## Getting Started

### Prerequisites

- Autodesk Revit
- Dynamo for Revit
- Structural analysis for Dynamo package
- Robot Structural Analysis Professional
- Basic knowledge of structural engineering and optimization

### Installation

1. Clone this repository to your local machine.
2. Ensure you have the required software installed (Revit, Dynamo, RSA).
3. Open the provided Dynamo scripts within Revit using the Dynamo plugin.

## Usage

1. **Model Preparation**: Start by preparing your parametric structural model in Dynamo.
2. **Core node creation**: Create a core node from your parametric model by turning it into a custom node.
3. **Optimization with Dynamo**: Open the provided Dynamo script to perform optimization. Adjust input parameters as needed for your specific structural design requirements and change the provided core node if needed.
4. **Analysis in RSA**: Provided script will use RSA for detailed FEA as part of the optimization loop.
5. **Evaluation**: Evaluate the optimization results, including stress, displacement, and weight.
6. **Next generation creation**: Generate next generation by using metaheuristic algorithms. Python libraries or own generated python codes can be employed for this step. A sample code has been provided along with shared scripts.[Example Document](Optimization)
7. **Revit interaction**: Optimized design can be imported Revit for further analyses by using provided optimization script. [Example Document](<Optimization with Revit integration>)
8. **LCA and Cost Analysis**: Utilize Revit and Tally for environmental and economic assessment as presented in upcoming video.



https://github.com/ugurfeyzullah/Intelligent-Optimization-of-Steel-Structures-Through-Bim-Based-Visual-Programming-Platform-and-Tools/assets/149387821/809b5812-1147-4b17-a448-58cc2236c4cc




## Contributing

Contributions are welcome! If you have improvements or bug fixes, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -am 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Citation

If you have used our framework for research purposes, you can cite our publication by following reference:

MDPI and ACS Style
Yavan, F.; Maalek, R.; Toğan, V. Structural Optimization in Building Information Modeling (BIM) Projects Using Visual Programming, Evolutionary Algorithms, and Sustainability Assessment Tools. Preprints 2024, 2024040060. https://doi.org/10.20944/preprints202404.0060.v1

APA Style
Yavan, F., Maalek, R., & Toğan, V. (2024). Structural Optimization in Building Information Modeling (BIM) Projects Using Visual Programming, Evolutionary Algorithms, and Sustainability Assessment Tools. Preprints. https://doi.org/10.20944/preprints202404.0060.v1

Chicago/Turabian Style
Yavan, F., Reza Maalek and Vedat Toğan. 2024 "Structural Optimization in Building Information Modeling (BIM) Projects Using Visual Programming, Evolutionary Algorithms, and Sustainability Assessment Tools" Preprints. https://doi.org/10.20944/preprints202404.0060.v

BibTex:

@article{202404.0060,
	doi = {10.20944/preprints202404.0060.v1},
	url = {https://doi.org/10.20944/preprints202404.0060.v1},
	year = 2024,
	month = {April},
	publisher = {Preprints},
	author = {Feyzullah Yavan and Reza Maalek and Vedat Toğan},
	title = {Structural Optimization in Building Information Modeling (BIM) Projects Using Visual Programming, Evolutionary Algorithms, and Sustainability Assessment Tools},
	journal = {Preprints}
}

## Contact

- Feyzullah YAVAN - www.linkedin.com/in/ugurfey - feyzullah.yavan@kit.edu


## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE.md) file for details.

