# Machine Learning Specialization

**Personal learning archive · Md. Zubayer Ahmad Shibly**

A structured record of my work through the **Machine Learning Specialization**, offered by **DeepLearning.AI** in collaboration with **Stanford Online**. This repository brings together the course folders, Jupyter notebooks, lab resources, supporting material, and my completion credentials.

<!-- COURSE_BANNER: optional screenshot added from the locally provided image assets -->

## Completion credentials

All four certificates shown below are dated **September 9, 2026**. Open the verification links to view the issuer's official certificate pages.

| Credential | Official verification |
| --- | --- |
| Machine Learning Specialization | [Verify certificate](https://www.deeplearning.ai/certificates/c71eb09e-ce38-4ba7-9404-253847333526) |
| Supervised Machine Learning: Regression and Classification | [Verify certificate](https://www.deeplearning.ai/certificates/3f710077-fe32-4cf2-ad7d-0e9f6fe73c78) |
| Advanced Learning Algorithms | [Verify certificate](https://www.deeplearning.ai/certificates/f5f7ea2d-83cc-410a-b14b-393320f0d698) |
| Unsupervised Learning, Recommenders, Reinforcement Learning | [Verify certificate](https://www.deeplearning.ai/certificates/bfef3db2-c1c6-448f-88ee-2d97e923187a) |

<!-- CERTIFICATE_GALLERY: screenshots can be added here from the supplied certificate assets -->

The specialization credential represents completion of all three courses. Visit the [Certificates](Certificates/README.md) directory for the certificate IDs and official verification links; the updated screenshot gallery can also be added there.

## Learning path

| Course | Coverage | Study material |
| --- | --- | --- |
| **C1** — Supervised Machine Learning: Regression and Classification | 3 weeks | [Browse course](C1%20-%20Supervised%20Machine%20Learning%20Regression%20and%20Classification/README.md) |
| **C2** — Advanced Learning Algorithms | 4 weeks | [Browse course](C2%20-%20Advanced%20Learning%20Algorithms/README.md) |
| **C3** — Unsupervised Learning, Recommenders, Reinforcement Learning | 3 weeks | [Browse course](C3%20-%20Unsupervised%20Learning%20Recommenders%20Reinforcement%20Learning/README.md) |

## Course-by-course overview

### C1. Supervised Machine Learning: Regression and Classification

Understand how supervised models learn from data, how regression differs from classification, and how optimization and regularization shape model performance.

- **[Introduction to Machine Learning](C1%20-%20Supervised%20Machine%20Learning%20Regression%20and%20Classification/Week%201%20Introduction%20to%20Machine%20Learning/README.md)** — Supervised and unsupervised learning, including common application scenarios.
- **[Regression with Multiple Input Variables](C1%20-%20Supervised%20Machine%20Learning%20Regression%20and%20Classification/Week%202%20Regression%20with%20Multiple%20Input%20Variables/README.md)** — Multivariable linear regression with vectorized NumPy operations.
- **[Classification](C1%20-%20Supervised%20Machine%20Learning%20Regression%20and%20Classification/Week%203%20Classification/README.md)** — Sigmoid predictions and the decision boundary for logistic regression.

### C2. Advanced Learning Algorithms

Move beyond linear models to neural networks, training strategies, model diagnostics, decision trees, and ensemble learning.

- **[Neural Networks](C2%20-%20Advanced%20Learning%20Algorithms/Week%201%20Neural%20Networks/README.md)** — Neurons, dense layers, activation functions, and inference.
- **[Neural Networks Training](C2%20-%20Advanced%20Learning%20Algorithms/Week%202%20Neural%20Networks%20Training/README.md)** — Training neural networks for multiclass classification.
- **[Advice for Applying Machine Learning](C2%20-%20Advanced%20Learning%20Algorithms/Week%203%20Advice%20for%20Applying%20Machine%20Learning/README.md)** — Bias, variance, underfitting, and overfitting.
- **[Decision Trees](C2%20-%20Advanced%20Learning%20Algorithms/Week%204%20Decision%20Trees/README.md)** — Decision-tree splits and information gain.

### C3. Unsupervised Learning, Recommenders, Reinforcement Learning

Explore learning without target labels, recommendation techniques, and decision-making through reinforcement learning.

- **[Unsupervised Learning](C3%20-%20Unsupervised%20Learning%20Recommenders%20Reinforcement%20Learning/Week%201%20Unsupervised%20Learning/README.md)** — K-means clustering and centroid updates.
- **[Recommender Systems](C3%20-%20Unsupervised%20Learning%20Recommenders%20Reinforcement%20Learning/Week%202%20Recommender%20Systems/README.md)** — Collaborative filtering using user–item interaction patterns.
- **[Reinforcement Learning](C3%20-%20Unsupervised%20Learning%20Recommenders%20Reinforcement%20Learning/Week%203%20Reinforcement%20Learning/README.md)** — States, actions, rewards, policies, and value functions.

## Where to find the materials

- Each course has its own overview and week-by-week navigation.
- The weekly folders contain the original collection of **optional labs**, **graded-lab notebooks** and **practice-quiz resources**, depending on the week.
- The notebooks generally require Python, Jupyter and common scientific-computing packages; TensorFlow or other libraries may be needed for specific advanced exercises.
- The source notebooks and associated media have been left intact rather than rewritten solely to change appearance or metadata.

### Running a notebook

1. Clone this repository and open the relevant course/week folder.
2. Create a Python environment and install the dependencies required by the notebook. Several labs depend on local helper modules, datasets and image folders; keep those next to the notebook.
3. Launch JupyterLab or Jupyter Notebook in the appropriate lab folder and open the `.ipynb` file.
4. Run cells in order, checking the notebook's own instructions for version-specific requirements.

```bash
git clone https://github.com/iamshibly/Machine-Learning-Specialization.git
cd Machine-Learning-Specialization
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyterlab numpy pandas matplotlib scikit-learn
jupyter lab
```

> **Environment note:** This is a starting point, not a guaranteed single environment for every lab. Deep-learning and reinforcement-learning notebooks may require extra or version-specific dependencies.

## Repository stewardship and attribution

**Repository owner and certificate recipient:** Md. Zubayer Ahmad Shibly.

The Machine Learning Specialization is taught by **Andrew Ng** and provided by **DeepLearning.AI** and **Stanford Online**. Educational notebooks, illustrations, datasets, and other supplied course materials retain their original context and any applicable attribution. Keeping these materials here does not imply that I created the underlying course.

For proof of completion, rely on the [official certificate verification pages](Certificates/README.md), not on Git commit timestamps or file modification dates.
