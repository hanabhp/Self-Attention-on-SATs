### A typo in the submitted paper
We apologize for a subtle typo in **equation 4**, where there should be only a single **T** in the denominator instead of **T square**.
`P^{'}_h` is designed to be a joint distribution, and an extra division by **T** makes the distribution sum up to **1/T** instead of **1**.
We provide the error-free version in this repository.

<img src="https://imgur.com/L9hS7tm.jpg" width="600"/>

# Self-Attention-on-SATs

## Visualization and Categorization

- Attention maps: [M3](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/HkmGR4EjU), [M6](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/ryj2SwEsU), [M9](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/Byy_qDVi8)

- Head distribution across layers according to three metrics

<img src="https://imgur.com/LUgcf15.jpg" width="600"/>

Red is for M3; Green is for M6; Blue is for M9.
The deeper color represents the layer closer to input features.
Global heads dominate especially for M6 and M9, while M3 contains the most heads with high diagonality.

## Phoneme Segmentation

Please refer to `supplementary.pdf` in  this repository.

## Phoneme Relation Map

- Phoneme relation distribtuion of a corpus (baseline distribution): `supplementary.pdf`
- Phoneme relation maps: [M3](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/HJBDZfmnI), [M6](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/ryaUQzXh8), [M9](https://hackmd.io/@QMLdEc5PRayZZIfBA3H1kA/Hk2SVzm28)

## Importance Ranking

- Global vs Weight: We mark the top 10 ranking differences by their head ID. As shown at the second row, the head ranked most differently in M3, M6, or M9 tends to neglect.

<img src="https://i.imgur.com/nbzekF0.png" width="600"/>
