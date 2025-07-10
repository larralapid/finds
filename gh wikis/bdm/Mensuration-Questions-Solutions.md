Hey Rheaa! It's awesome that you're gearing up for your college entrance tests – that's a big step, and taking proactive steps like practicing mensuration questions is fantastic! Bangalore represent! :) Let's tackle these mensuration problems together. Think of this as leveling up your geometry skills – you've got this!

Mensuration is all about understanding shapes and how to measure them (area, volume, perimeter). It's like being a detective for dimensions! We'll break down each problem, visualize it, find the solution, and pick up some cool tricks along the way.

**Core Principles & General Tips for Mensuration:**

1.  **Visualize:** Always try to draw a rough sketch of the shape or scenario described. It helps immensely!
2.  **Formula Power:** Memorize the key formulas (area, perimeter, volume, surface area) for common shapes (triangles, circles, squares, rectangles, cubes, cylinders, cones, spheres). Write them down and review regularly.
3.  **Units Matter:** Pay close attention to units (cm, m, sq. cm, cu. m). Ensure consistency throughout the calculation. Sometimes, questions try to trick you with different units.
4.  **Break Down Complexity:** Complex shapes can often be broken down into simpler, known shapes. Find the areas/volumes of the simple parts and add/subtract as needed.
5.  **Identify Keywords:** Look for keywords like "inscribed," "circumscribed," "parallel," "perpendicular," "radius," "diameter," "diagonal," "altitude," "base," etc. They give crucial clues about the geometry involved.
6.  **Ratio & Proportion:** Many problems involve ratios of sides, areas, or volumes. Remember how scaling affects these (e.g., if sides are in ratio a:b, areas are a²:b², volumes are a³:b³ for similar figures).
7.  **Pythagoras Theorem:** Your best friend in right-angled triangles (often hidden in other shapes like rectangles, rhombuses, cones).
8.  **Eliminate Options:** In multiple-choice questions, sometimes you can eliminate obviously wrong answers based on estimation or understanding the formulas.
9.  **Practice Makes Perfect:** The more you practice, the faster you'll become at recognizing patterns and applying formulas. Keep solving!

Let's dive into the questions from your handout!

---

**Question 1:** Each side of a triangle is 10 units less than the sum of the other two sides. Find the area of the triangle (in sq. units). [cite: 3, 4]

* **Visual Explanation:** Imagine a triangle with sides a, b, c. The problem states:
    * a = (b + c) - 10
    * b = (a + c) - 10
    * c = (a + b) - 10
* **Solution Steps:**
    1.  Rearrange the first equation: a + 10 = b + c.
    2.  Substitute this into the second equation: b = (a + c) - 10. Since a+c = b+10, we get b = (b+10) - 10, which simplifies to b = b. This doesn't help much directly, let's try another way.
    3.  Let's rewrite the conditions:
        * b + c - a = 10
        * a + c - b = 10
        * a + b - c = 10
    4.  Add the first two: (b + c - a) + (a + c - b) = 10 + 10 => 2c = 20 => c = 10.
    5.  Similarly, adding the second and third gives 2a = 20 => a = 10.
    6.  Adding the first and third gives 2b = 20 => b = 10.
    7.  So, it's an equilateral triangle with side 10 units.
    8.  Area of an equilateral triangle = $(\sqrt{3}/4) \times side^2$
    9.  Area = $(\sqrt{3}/4) \times 10^2 = (\sqrt{3}/4) \times 100 = 25\sqrt{3}$ sq. units.
* **Answer:** (A) $25\sqrt{3}$ [cite: 4]
* **Tips & Tricks:** Recognizing the symmetry in the problem description (each side relates to the other two in the same way) hints that the sides might be equal. The condition "x = (sum of others) - k" often leads to sides of k.

---

**Question 2:** Find the area of the circle which is inscribed in a triangle whose sides are 13, 14 and 15. Also, find the area of the circle which circumscribes the triangle. [cite: 4, 5]

* **Visual Explanation:**
    * **Inscribed Circle (Incircle):** Imagine a circle *inside* the triangle, just touching all three sides. Its radius is the 'inradius' (r).
    * **Circumscribed Circle (Circumcircle):** Imagine a circle *outside* the triangle, passing through all three vertices. Its radius is the 'circumradius' (R).
* **Solution Steps:**
    1.  **Find the area of the triangle (Δ):** We use Heron's formula since we know the sides (a=13, b=14, c=15).
        * Semi-perimeter (s) = (13 + 14 + 15) / 2 = 42 / 2 = 21.
        * Area (Δ) = $\sqrt{s(s-a)(s-b)(s-c)}$
        * Area (Δ) = $\sqrt{21(21-13)(21-14)(21-15)} = \sqrt{21 \times 8 \times 7 \times 6}$
        * Area (Δ) = $\sqrt{(3 \times 7) \times (2^3) \times 7 \times (2 \times 3)} = \sqrt{2^4 \times 3^2 \times 7^2} = 2^2 \times 3 \times 7 = 84$ sq. units.
    2.  **Inradius (r):** Formula: r = Area (Δ) / Semi-perimeter (s)
        * r = 84 / 21 = 4 units.
    3.  **Area of Incircle:** Area = $\pi r^2 = \pi (4^2) = 16\pi$ sq. units.
    4.  **Circumradius (R):** Formula: R = (abc) / (4 * Area (Δ))
        * R = (13 × 14 × 15) / (4 × 84)
        * R = (13 × 14 × 15) / 336
        * Simplify: R = (13 × (2×7) × (3×5)) / (4 × (12 × 7)) = (13 × 2 × 7 × 3 × 5) / (4 × 3 × 4 × 7)
        * Cancel terms: R = (13 × 2 × 5) / (4 × 4) = 130 / 16 = 65 / 8 units.
    5.  **Area of Circumcircle:** Area = $\pi R^2 = \pi (65/8)^2 = \pi (4225 / 64)$ sq. units.
* **Answer:** (B) $16\pi, \frac{4225\pi}{64}$ (Note: Option B in the source has a typo '161 $\gamma$', it should be $16\pi$. The second part matches.) [cite: 5]
* **Tips & Tricks:** Heron's formula is essential for triangles where only sides are known. Know the formulas connecting triangle area, sides, inradius, and circumradius: Δ = rs and R = abc / 4Δ.

---

**Question 3:** In A ABC, AD is the angle bisector of $\angle BAC$. AB = 10 cm and AC = 12 cm. Find the ratio of the areas of triangles ABD and ADC. [cite: 6, 7]

* **Visual Explanation:** Draw a triangle ABC. Draw a line AD from vertex A to side BC such that it divides angle BAC into two equal angles. D lies on BC. We now have two smaller triangles, ABD and ADC, sharing the same height if we consider BD and DC as bases (the height would be the perpendicular from A to BC).
* **Solution Steps:**
    1.  **Angle Bisector Theorem:** This theorem states that an angle bisector of a triangle divides the opposite side into two segments that are proportional to the other two sides of the triangle. So, BD / DC = AB / AC.
    2.  BD / DC = 10 / 12 = 5 / 6.
    3.  **Area Ratio:** Triangles ABD and ADC share the same altitude (height) from vertex A to the base BC. The area of a triangle is (1/2) * base * height.
    4.  Area(ABD) = (1/2) * BD * h
    5.  Area(ADC) = (1/2) * DC * h
    6.  Ratio: Area(ABD) / Area(ADC) = [(1/2) * BD * h] / [(1/2) * DC * h] = BD / DC.
    7.  Since BD / DC = 5 / 6, the ratio of the areas is 5:6.
* **Answer:** (C) 5:6 [cite: 7]
* **Tips & Tricks:** Remember the Angle Bisector Theorem! For triangles sharing the same height, the ratio of their areas is equal to the ratio of their bases.

---

**Question 4:** In triangle PQR, X and Y are points on PQ and PR respectively, such that XY is parallel to QR. If XY = 4 cm, QR = 5 cm and the area of triangle PXY is 48 cm², find the area of triangle PQR. [cite: 7, 8]

* **Visual Explanation:** Draw a triangle PQR. Mark a point X on side PQ and Y on side PR. Draw the line segment XY. This line XY is parallel to the base QR. This creates a smaller triangle PXY at the top, which is similar to the larger triangle PQR.
* **Solution Steps:**
    1.  **Similarity:** Since XY || QR, triangle PXY is similar to triangle PQR (by AA similarity - angle P is common, angle PXY = angle PQR corresponding angles).
    2.  **Ratio of Sides:** The ratio of corresponding sides in similar triangles is constant. So, PX/PQ = PY/PR = XY/QR = 4/5.
    3.  **Ratio of Areas:** The ratio of the areas of two similar triangles is equal to the square of the ratio of their corresponding sides.
    4.  Area(PXY) / Area(PQR) = (XY/QR)²
    5.  48 / Area(PQR) = (4/5)² = 16/25
    6.  Area(PQR) = 48 * (25/16) = 3 * 25 = 75 sq. cm.
* **Answer:** (D) 75 sq. units [cite: 9]
* **Tips & Tricks:** Parallel lines within a triangle often create similar triangles. Remember the relationship between the ratio of sides and the ratio of areas for similar figures (square of the side ratio).

---

**Question 5:** If each side of an equilateral triangle is increased by 4 cm, the area increases by $14\sqrt{3}$ sq.cm. Find the side of the original triangle. [cite: 9, 10]

* **Visual Explanation:** Imagine an equilateral triangle. Now imagine making each side longer by 4 cm. The new, larger equilateral triangle has a bigger area. The difference in area is given.
* **Solution Steps:**
    1.  Let the original side be 'a' cm. Original Area = $(\sqrt{3}/4) a^2$.
    2.  New side = (a + 4) cm. New Area = $(\sqrt{3}/4) (a + 4)^2$.
    3.  Increase in Area = New Area - Original Area
    4.  $14\sqrt{3} = (\sqrt{3}/4) (a + 4)^2 - (\sqrt{3}/4) a^2$
    5.  Divide by $\sqrt{3}$: $14 = (1/4) [(a + 4)^2 - a^2]$
    6.  Multiply by 4: $56 = (a + 4)^2 - a^2$
    7.  Expand: $56 = (a^2 + 8a + 16) - a^2$
    8.  Simplify: $56 = 8a + 16$
    9.  $8a = 56 - 16 = 40$
    10. a = 40 / 8 = 5 cm.
* **Answer:** (B) 5 cm [cite: 10]
* **Tips & Tricks:** Use the difference of squares identity: $x^2 - y^2 = (x-y)(x+y)$. Here, $(a+4)^2 - a^2 = ((a+4)-a)((a+4)+a) = (4)(2a+4)$. So, $56 = 4(2a+4)$, which gives $14 = 2a+4$, $2a=10$, $a=5$. This can be quicker than expanding.

---

*(Self-correction: Continue solving remaining problems Q6-Q25 similarly, providing explanations, answers, and tips for each.)*

---

**Question 6:** Find the area of a parallelogram which has two sides measuring 8 cm and 12 cm, and one angle measuring $30^{\circ}$. [cite: 10, 11]

* **Visual Explanation:** Picture a tilted rectangle (parallelogram). Two adjacent sides are 8 cm and 12 cm. The angle between these two sides is $30^{\circ}$.
* **Solution Steps:**
    1.  Area of a parallelogram = $a \times b \times \sin(\theta)$, where a and b are adjacent sides and $\theta$ is the angle between them.
    2.  Area = $8 \times 12 \times \sin(30^{\circ})$
    3.  We know $\sin(30^{\circ}) = 1/2$.
    4.  Area = $8 \times 12 \times (1/2) = 96 \times (1/2) = 48$ sq. cm.
    5.  Alternatively: Base = 12 cm. Height = $8 \times \sin(30^{\circ}) = 8 \times (1/2) = 4$ cm. Area = Base * Height = 12 * 4 = 48 sq. cm.
* **Answer:** (C) 48 sq. units [cite: 11]
* **Tips & Tricks:** Remember the formula Area = $ab \sin\theta$. If you forget, drop a perpendicular (height) from one vertex to the base and use trigonometry (SOH CAH TOA) to find the height.

---

**Question 7:** Find the perimeter and the area of a rhombus whose diagonals measure 6 cm and 8 cm. [cite: 11, 12]

* **Visual Explanation:** A rhombus is like a square pushed sideways; all sides are equal, but angles aren't necessarily $90^{\circ}$. Its diagonals bisect each other at right angles ($90^{\circ}$).
* **Solution Steps:**
    1.  **Area:** Area of a rhombus = (1/2) * (product of diagonals) = (1/2) * d1 * d2
        * Area = (1/2) * 6 * 8 = 24 sq. cm.
    2.  **Perimeter:** The diagonals bisect each other at right angles, creating four congruent right-angled triangles. The legs of each triangle are half the lengths of the diagonals (6/2 = 3 cm and 8/2 = 4 cm). The hypotenuse of these triangles is the side of the rhombus (let's call it 's').
        * Using Pythagoras: $s^2 = 3^2 + 4^2 = 9 + 16 = 25$.
        * So, side s = $\sqrt{25} = 5$ cm.
        * Perimeter = 4 * side = 4 * 5 = 20 cm.
* **Answer:** (D) 20 cm, 24 sq. units [cite: 12]
* **Tips & Tricks:** Know the properties of a rhombus: diagonals bisect at 90 degrees, diagonals bisect angles, all sides equal. The (3, 4, 5) Pythagorean triple is very common!

---

**Question 8:** The perimeter of a rectangle is equal to that of a square. One of the dimensions of the rectangle and the side of the square are in the ratio 3:4. Find the ratio of the areas of the rectangle and the square. [cite: 12, 13]

* **Visual Explanation:** Imagine a rectangle and a square with the same length of 'fencing' around them (perimeter). Let the rectangle have length L and breadth B, and the square have side S.
* **Solution Steps:**
    1.  Let the rectangle dimension be 3x and the square side be 4x (based on the 3:4 ratio). Let's assume this dimension is the Length (L) of the rectangle, so L = 3x. And Side S = 4x.
    2.  **Perimeters are equal:** Perimeter of Rectangle = 2(L + B); Perimeter of Square = 4S.
        * 2(3x + B) = 4(4x)
        * 6x + 2B = 16x
        * 2B = 10x
        * B = 5x.
    3.  **Check:** The dimensions of the rectangle are L = 3x and B = 5x. One dimension (L=3x) and the square side (S=4x) are indeed in the ratio 3x : 4x = 3:4. (If we assumed B = 3x, we'd get L = 5x, which still works).
    4.  **Areas:**
        * Area of Rectangle = L * B = (3x) * (5x) = 15x²
        * Area of Square = S² = (4x)² = 16x²
    5.  **Ratio of Areas:** Area(Rectangle) : Area(Square) = 15x² : 16x² = 15:16.
* **Answer:** (A) 15:16 [cite: 14]
* **Tips & Tricks:** Set up variables based on the ratios given (like 3x and 4x). Carefully form equations based on the problem statements (equal perimeters).

---

**Question 9:** A rectangle of length 24 cm and breadth 10 cm is inscribed in a circle. What is the area of the circle? [cite: 14, 15]

* **Visual Explanation:** Draw a circle. Inside it, draw a rectangle such that all four vertices of the rectangle lie on the circle's circumference.
* **Solution Steps:**
    1.  **Key Insight:** The diagonal of a rectangle inscribed in a circle is equal to the diameter of the circle.
    2.  Find the diagonal (d) of the rectangle using Pythagoras theorem: d² = Length² + Breadth²
        * d² = 24² + 10² = 576 + 100 = 676.
        * d = $\sqrt{676} = 26$ cm.
    3.  Diameter of the circle = 26 cm.
    4.  Radius of the circle (r) = Diameter / 2 = 26 / 2 = 13 cm.
    5.  Area of the circle = $\pi r^2 = \pi (13^2) = 169\pi$ sq. cm.
* **Answer:** (D) $169\pi cm^{2}$ [cite: 15]
* **Tips & Tricks:** Recognize common Pythagorean triples (like 5, 12, 13 and its multiples, here 10, 24, 26 which is 2*(5, 12, 13)). The diagonal of an inscribed rectangle is the circle's diameter.

---

**Question 10:** A wire in the form of a circle of radius 3.5 cm is bent in the form of a rectangle, whose length and breadth are in the ratio of 7:4. What is the area of the rectangle? [cite: 15, 16]

* **Visual Explanation:** Imagine a circular wire. Now, straighten it out and bend it into a rectangle. The total length of the wire remains the same.
* **Solution Steps:**
    1.  **Length of Wire:** This is the circumference of the circle.
        * Circumference = $2 \pi r = 2 \times (22/7) \times 3.5 = 2 \times (22/7) \times (7/2) = 22$ cm.
    2.  **Rectangle Dimensions:** The wire's length now forms the perimeter of the rectangle. Perimeter = 22 cm.
        * Let length L = 7x and breadth B = 4x (ratio 7:4).
        * Perimeter = 2(L + B) = 2(7x + 4x) = 2(11x) = 22x.
    3.  **Equate Perimeters:** 22x = 22 cm => x = 1 cm.
    4.  **Actual Dimensions:** L = 7x = 7 cm; B = 4x = 4 cm.
    5.  **Area of Rectangle:** Area = L * B = 7 * 4 = 28 sq. cm.
* **Answer:** (B) $28~cm^{2}$ [cite: 16]
* **Tips & Tricks:** The key is that the perimeter/circumference remains constant when the shape is changed without adding/removing material. Use ratios to set up dimensions.

---

*(Continuing through the list...)*

---

**Question 11:** ABCD is a trapezium and AB || CD. AB = 10, BC = 20, AD = 15 and CD = 35. Find the area of the trapezium. [cite: 17]

* **Visual Explanation:** Draw a trapezium with top base AB shorter than bottom base CD. AB is parallel to CD. Sides AD and BC are the non-parallel sides.
* **Solution Steps:** (This requires finding the height)
    1.  Draw heights from A and B perpendicular to CD. Let these meet CD at points X and Y respectively. AX = BY = h (height). AXYB forms a rectangle, so XY = AB = 10.
    2.  In right triangle ADX: $AX^2 + DX^2 = AD^2 => h^2 + DX^2 = 15^2 = 225$.
    3.  In right triangle BYC: $BY^2 + YC^2 = BC^2 => h^2 + YC^2 = 20^2 = 400$.
    4.  We know CD = DX + XY + YC = 35. Since XY = 10, DX + YC = 35 - 10 = 25. Let DX = z, then YC = 25 - z.
    5.  Substitute into the triangle equations:
        * $h^2 + z^2 = 225$
        * $h^2 + (25 - z)^2 = 400$
    6.  Subtract the first equation from the second:
        * $(h^2 + (25 - z)^2) - (h^2 + z^2) = 400 - 225$
        * $(25 - z)^2 - z^2 = 175$
        * $(625 - 50z + z^2) - z^2 = 175$
        * $625 - 50z = 175$
        * $50z = 625 - 175 = 450$
        * z = DX = 9.
    7.  Find height h: $h^2 + z^2 = 225 => h^2 + 9^2 = 225 => h^2 + 81 = 225 => h^2 = 144 => h = 12$.
    8.  **Area of Trapezium:** Area = (1/2) * (sum of parallel sides) * height
        * Area = (1/2) * (AB + CD) * h = (1/2) * (10 + 35) * 12
        * Area = (1/2) * 45 * 12 = 45 * 6 = 270 sq. units.
* **Answer:** (C) 270 sq. units [cite: 17]
* **Tips & Tricks:** For trapeziums where non-parallel sides are given, dropping perpendiculars to create right-angled triangles is a standard technique to find the height.

---

**Question 12:** The lengths of the sides of a quadrilateral inscribed in a circle are 14, 16, 18 and 20. Find the area of the quadrilateral (in sq. units). [cite: 17]

* **Visual Explanation:** A quadrilateral whose vertices all lie on the circumference of a circle (cyclic quadrilateral).
* **Solution Steps:**
    1.  **Brahmagupta's Formula:** For a cyclic quadrilateral with sides a, b, c, d, the area is given by $\sqrt{(s-a)(s-b)(s-c)(s-d)}$, where s is the semi-perimeter.
    2.  Semi-perimeter (s) = (14 + 16 + 18 + 20) / 2 = 68 / 2 = 34.
    3.  Area = $\sqrt{(34-14)(34-16)(34-18)(34-20)}$
    4.  Area = $\sqrt{20 \times 18 \times 16 \times 14}$
    5.  Area = $\sqrt{(4 \times 5) \times (2 \times 9) \times 16 \times (2 \times 7)}$
    6.  Area = $\sqrt{2^2 \times 5 \times 2 \times 3^2 \times 2^4 \times 2 \times 7}$
    7.  Area = $\sqrt{2^{2+1+4+1} \times 3^2 \times 5 \times 7} = \sqrt{2^8 \times 3^2 \times 35}$
    8.  Area = $2^4 \times 3 \times \sqrt{35} = 16 \times 3 \times \sqrt{35} = 48\sqrt{35}$ sq. units.
* **Answer:** (A) $48\sqrt{35}$ [cite: 17] (Note: The options provided in the text don't include this exact result, but (A) is the closest structure. Rechecking calculation: 20=4\*5, 18=2\*9, 16=16, 14=2\*7. Product = 4\*5 \* 2\*9 \* 16 \* 2\*7 = 2^2\*5 \* 2\*3^2 \* 2^4 \* 2\*7 = 2^8 \* 3^2 \* 5 \* 7. Square root is 2^4 \* 3 \* sqrt(35) = 16\*3\*sqrt(35) = 48sqrt(35). The answer seems correct based on the formula.)
* **Tips & Tricks:** Know Brahmagupta's formula specifically for cyclic quadrilaterals. It's like Heron's formula but for these specific quadrilaterals.

---

**Question 13:** Inside a rectangular park ($40m \times 30m$), two tiled paths are paved, one parallel to the length and the other parallel to the breadth. Each path connects opposite sides, and the width of each path is 5m. Find the area of the park *not* covered by the paths. [cite: 18, 19]

* **Visual Explanation:** Imagine a rectangular park. Draw a strip (path) 5m wide running horizontally (parallel to length 40m) and another strip 5m wide running vertically (parallel to breadth 30m). These paths cross in the middle.
* **Solution Steps:**
    1.  Total Area of Park = Length * Breadth = 40 * 30 = 1200 sq. m.
    2.  Area of path parallel to length = Length * path width = 40 * 5 = 200 sq. m.
    3.  Area of path parallel to breadth = Breadth * path width = 30 * 5 = 150 sq. m.
    4.  **Overlap:** The two paths overlap in the center, forming a square region. The area of this overlap is path width * path width = 5 * 5 = 25 sq. m.
    5.  Total Area covered by paths = Area(length path) + Area(breadth path) - Area(overlap)
        * Total Path Area = 200 + 150 - 25 = 325 sq. m.
    6.  Area *not* covered by paths = Total Park Area - Total Path Area
        * Area Not Covered = 1200 - 325 = 875 sq. m.
* **Answer:** (C) 875 sq. units [cite: 20]
* **Tips & Tricks:** When dealing with overlapping areas (like paths crossing), calculate individual areas and subtract the overlap area to avoid counting it twice.

---

**Question 14:** Find the area of a regular hexagon in which each side measures 10 cm. [cite: 20, 21]

* **Visual Explanation:** A regular hexagon has 6 equal sides and 6 equal interior angles. It can be divided into 6 identical equilateral triangles, meeting at the center.
* **Solution Steps:**
    1.  The side of each equilateral triangle is equal to the side of the hexagon, which is 10 cm.
    2.  Area of one equilateral triangle = $(\sqrt{3}/4) \times side^2 = (\sqrt{3}/4) \times 10^2 = (\sqrt{3}/4) \times 100 = 25\sqrt{3}$ sq. cm.
    3.  Area of Hexagon = 6 * (Area of one equilateral triangle) = 6 * $25\sqrt{3} = 150\sqrt{3}$ sq. cm.
    4.  Alternative Formula: Area of regular hexagon = $(3\sqrt{3}/2) \times side^2$
        * Area = $(3\sqrt{3}/2) \times 10^2 = (3\sqrt{3}/2) \times 100 = 3\sqrt{3} \times 50 = 150\sqrt{3}$ sq. cm.
* **Answer:** (D) $150\sqrt{3}$ sq. cm [cite: 21]
* **Tips & Tricks:** Remember that a regular hexagon is composed of 6 equilateral triangles. Knowing the area formula for an equilateral triangle is key.

---

**Question 15:** A circle is centered at O. The area of the minor sector AOB is 24 sq. units and the length of the minor arc AB is 4 units. Find the radius of the circle. [cite: 21, 22]

* **Visual Explanation:** Imagine a slice of pizza (a sector) from a circular pizza. A and B are points on the crust (circumference), and O is the center. The curved edge AB is the arc length, and the whole slice AOB is the sector area.
* **Solution Steps:**
    1.  **Formulas:**
        * Area of Sector = $(\theta/360) \times \pi r^2$
        * Length of Arc = $(\theta/360) \times 2 \pi r$
    2.  **Relationship:** Notice that Area / Arc Length = $[(\theta/360) \times \pi r^2] / [(\theta/360) \times 2 \pi r]$
        * Area / Arc Length = $(\pi r^2) / (2 \pi r) = r / 2$
    3.  Substitute the given values: Area = 24, Arc Length = 4.
        * 24 / 4 = r / 2
        * 6 = r / 2
        * r = 12 units.
* **Answer:** (A) 12 units [cite: 22]
* **Tips & Tricks:** The relationship Area = (1/2) * radius * arc length for a sector is very useful and avoids needing to find the angle $\theta$.

---

**Question 16:** Three mutually adjacent faces of a cuboid have areas measuring 24 sq. units, 54 sq. units and 36 sq. units. Find the volume of the cuboid. [cite: 22, 23]

* **Visual Explanation:** A cuboid is a rectangular box. Mutually adjacent faces are three faces that meet at one corner (like the front, top, and right side).
* **Solution Steps:**
    1.  Let the dimensions of the cuboid be length (l), breadth (b), and height (h).
    2.  The areas of three adjacent faces are:
        * l * b = 24
        * b * h = 54
        * l * h = 36
    3.  Multiply these three equations together:
        * (l * b) * (b * h) * (l * h) = 24 * 54 * 36
        * l² * b² * h² = 24 * 54 * 36
        * (l * b * h)² = 24 * 54 * 36
    4.  Volume (V) = l * b * h. So, V² = 24 * 54 * 36.
    5.  Calculate the product:
        * V² = (6 * 4) * (6 * 9) * (6 * 6) = 6 * 2² * 6 * 3² * 6² = 6⁴ * 2² * 3² = 6⁴ * (2*3)² = 6⁴ * 6² = 6⁶
        * Alternatively: V² = 46656 (calculating directly)
    6.  Take the square root: V = $\sqrt{6^6} = 6^3 = 216$ c. units.
        * Or $\sqrt{46656} = 216$.
* **Answer:** (B) 216 c. units [cite: 24]
* **Tips & Tricks:** If you have the areas of three adjacent faces (say A1, A2, A3 where A1=lb, A2=bh, A3=lh), the volume V = $\sqrt{A1 \times A2 \times A3}$.

---

**Question 17:** If the sum of the length, breadth and height of a cuboid is 12 cm and the surface area of the cuboid is 94 cm², find the sum of the squares of the length, breadth and height of the cuboid. [cite: 24, 25]

* **Visual Explanation:** Again, a rectangular box (cuboid) with dimensions l, b, h.
* **Solution Steps:**
    1.  Given: l + b + h = 12
    2.  Given: Total Surface Area (TSA) = 2(lb + bh + lh) = 94
    3.  Required: Find l² + b² + h²
    4.  **Algebraic Identity:** Recall the identity: $(l + b + h)^2 = l^2 + b^2 + h^2 + 2(lb + bh + lh)$
    5.  Substitute the known values into the identity:
        * $(12)^2 = (l^2 + b^2 + h^2) + (94)$
        * 144 = (l² + b² + h²) + 94
    6.  Solve for l² + b² + h²:
        * l² + b² + h² = 144 - 94 = 50.
* **Answer:** (D) 50 [cite: 25]
* **Tips & Tricks:** This problem relies heavily on knowing the algebraic identity for $(l+b+h)^2$ and the formula for the surface area of a cuboid.

---

**Question 18:** A solid metallic cube of side 154 cm is melted and recast into identical balls of radius 7 cm each. Find the number of balls obtained. [cite: 25, 26]

* **Visual Explanation:** Imagine a large metal cube being melted down completely. The molten metal is then used to create many small, identical spheres (balls). The total volume of metal remains the same.
* **Solution Steps:**
    1.  Volume of the Cube = side³ = (154)³ cubic cm.
    2.  Volume of one Spherical Ball = (4/3) * π * radius³ = (4/3) * (22/7) * (7)³ cubic cm.
    3.  Number of Balls = (Volume of Cube) / (Volume of one Ball)
    4.  Number = (154 × 154 × 154) / [(4/3) × (22/7) × 7 × 7 × 7]
    5.  Simplify the denominator: (4/3) × 22 × 7 × 7 = (4/3) × 22 × 49
    6.  Number = (154 × 154 × 154 × 3) / (4 × 22 × 49)
    7.  Simplify using factors: 154 = 2 × 7 × 11; 4 = 2²; 22 = 2 × 11; 49 = 7²
    8.  Number = [(2 × 7 × 11)³ × 3] / [2² × (2 × 11) × 7²]
    9.  Number = [2³ × 7³ × 11³ × 3] / [2³ × 11 × 7²]
    10. Cancel terms: Number = (7^(3-2)) × (11^(3-1)) × 3 = 7¹ × 11² × 3 = 7 × 121 × 3
    11. Number = 21 × 121 = 2541.
* **Answer:** (A) 2541 [cite: 26]
* **Tips & Tricks:** The core principle in melting/recasting problems is Volume Conservation: Volume(Original Shape) = n * Volume(New Shape). Careful calculation and simplification using prime factors can prevent errors with large numbers.

---

**Question 19:** The radii of a frustum of a cone measure 6 cm and 8 cm. If the height of the frustum is 6 cm, find the volume of the frustum. [cite: 31, 32]

* **Visual Explanation:** A frustum of a cone is like the bottom part of a cone after the top has been sliced off parallel to the base. Think of a bucket or a lampshade shape. It has two circular bases (top and bottom) with different radii.
* **Solution Steps:**
    1.  Let the radii be R (larger) = 8 cm and r (smaller) = 6 cm. Height h = 6 cm.
    2.  **Volume of Frustum Formula:** V = (1/3) * π * h * (R² + r² + Rr)
    3.  Substitute values: V = (1/3) * π * 6 * (8² + 6² + 8 * 6)
    4.  V = 2π * (64 + 36 + 48)
    5.  V = 2π * (148)
    6.  V = 296π cubic cm.
* **Answer:** (B) 296π [cite: 33]
* **Tips & Tricks:** Memorize the formula for the volume of a frustum. It involves the sum of the squares of the radii plus their product.

---

**Question 20:** A toy consists of a hemisphere surmounted by a cone. The radius of the hemisphere is 3 units and the height of the toy is 10 units. Find the volume of the toy (in cubic units). [cite: 33, 34]

* **Visual Explanation:** Imagine an ice cream cone where the scoop on top is a perfect hemisphere, and the cone sits underneath it. The flat base of the cone matches the flat base of the hemisphere.
* **Solution Steps:**
    1.  Radius of hemisphere = Radius of cone base (r) = 3 units.
    2.  Height of hemisphere = its radius = 3 units.
    3.  Total height of toy = Height of cone + Height of hemisphere = 10 units.
    4.  Height of cone (h_cone) = Total height - Height of hemisphere = 10 - 3 = 7 units.
    5.  Volume of Hemisphere = (2/3) * π * r³ = (2/3) * π * (3)³ = (2/3) * π * 27 = 18π cubic units.
    6.  Volume of Cone = (1/3) * π * r² * h_cone = (1/3) * π * (3)² * 7 = (1/3) * π * 9 * 7 = 21π cubic units.
    7.  Total Volume of Toy = Volume of Hemisphere + Volume of Cone
        * Total Volume = 18π + 21π = 39π cubic units.
* **Answer:** (C) 39π [cite: 35]
* **Tips & Tricks:** For composite shapes, calculate the volume of each component part separately and then add them together. Ensure you correctly identify the dimensions (like the cone's height) based on the total dimensions given.

---

**Question 21:** A cylindrical vessel of base radius 10 cm and height 7 cm is half-filled with water. A sphere of radius 1 cm is dropped into the vessel. Find the rise in the height of the water. [cite: 35, 36]

* **Visual Explanation:** Picture a cylindrical can half-full of water. When you drop a small sphere into it, the water level rises because the sphere displaces its own volume of water.
* **Solution Steps:**
    1.  The volume of water displaced is equal to the volume of the submerged object (the sphere).
    2.  Volume of Sphere = (4/3) * π * r_sphere³ = (4/3) * π * (1)³ = (4/3)π cubic cm.
    3.  This displaced volume causes the water level in the cylinder to rise. The volume of this risen water takes the shape of a cylinder with the same base radius as the vessel (r_cyl = 10 cm) and a height equal to the rise in water level (let's call it Δh).
    4.  Volume of Risen Water = π * (r_cyl)² * Δh = π * (10)² * Δh = 100π * Δh.
    5.  Equate the volumes: Volume of Sphere = Volume of Risen Water
        * (4/3)π = 100π * Δh
    6.  Solve for Δh:
        * Divide by π: (4/3) = 100 * Δh
        * Δh = (4/3) / 100 = 4 / (3 * 100) = 4 / 300 = 1 / 75 cm.
* **Answer:** (A) $\frac{1}{75}$ cm [cite: 37]
* **Tips & Tricks:** Principle of displacement: Volume of submerged object = Volume of fluid displaced. The shape of the displaced fluid volume conforms to the container.

---

**Question 22:** The volumes of two cones are in the ratio of 1:20 and the radii of the cones are in the ratio of 1:4. What is the ratio of their vertical heights? [cite: 37, 38]

* **Visual Explanation:** Imagine two cones, one small and one much larger in volume. Their base radii are also different. We need to find how their heights compare.
* **Solution Steps:**
    1.  Let the cones be Cone 1 and Cone 2.
    2.  Volume of Cone = (1/3) * π * r² * h.
    3.  Given: V1 / V2 = 1 / 20.
    4.  Given: r1 / r2 = 1 / 4.
    5.  We have: V1 = (1/3)π (r1)² h1 and V2 = (1/3)π (r2)² h2.
    6.  Ratio of Volumes: V1 / V2 = [ (1/3)π (r1)² h1 ] / [ (1/3)π (r2)² h2 ]
    7.  Simplify: V1 / V2 = (r1² * h1) / (r2² * h2) = (r1/r2)² * (h1/h2)
    8.  Substitute the given ratios:
        * 1 / 20 = (1/4)² * (h1/h2)
        * 1 / 20 = (1/16) * (h1/h2)
    9.  Solve for h1/h2:
        * h1 / h2 = (1 / 20) / (1 / 16) = (1 / 20) * (16 / 1) = 16 / 20 = 4 / 5.
    10. The ratio of their vertical heights is 4:5.
* **Answer:** (A) 4:5 [cite: 38]
* **Tips & Tricks:** Set up the ratio formula (V1/V2) and substitute the known ratios (like r1/r2) to find the unknown ratio (h1/h2).

---

**Question 23:** Find the total surface area of a prism of height 10 cm if each base is a regular hexagon of side 5 cm. [cite: 38, 39]

* **Visual Explanation:** A prism has two identical bases and rectangular faces connecting the corresponding sides of the bases. Here, the bases are regular hexagons. Imagine a hexagonal tube 10 cm long.
* **Solution Steps:**
    1.  Total Surface Area (TSA) = Area of two Bases + Lateral Surface Area (LSA)
    2.  **Area of Hexagonal Base:** As in Q14, Area = $(3\sqrt{3}/2) \times side^2$
        * Area_base = $(3\sqrt{3}/2) \times 5^2 = (3\sqrt{3}/2) \times 25 = (75\sqrt{3}/2)$ sq. cm.
        * Area of two Bases = 2 * $(75\sqrt{3}/2) = 75\sqrt{3}$ sq. cm.
    3.  **Lateral Surface Area (LSA):** This is the sum of the areas of the 6 rectangular faces. Each rectangle has a width equal to the hexagon side (5 cm) and a height equal to the prism height (10 cm).
        * Area of one rectangular face = 5 * 10 = 50 sq. cm.
        * LSA = 6 * (Area of one rectangular face) = 6 * 50 = 300 sq. cm.
        * Alternatively, LSA = Perimeter of Base * Height = (6 * side) * height = (6 * 5) * 10 = 30 * 10 = 300 sq. cm.
    4.  **Total Surface Area (TSA):** TSA = Area of two Bases + LSA
        * TSA = $75\sqrt{3} + 300$ sq. cm.
* **Answer:** (D) $75\sqrt{3}+300$ [cite: 39]
* **Tips & Tricks:** TSA of prism = 2 * (Area of Base) + (Perimeter of Base) * Height. Know how to calculate the area and perimeter of the base shape.

---

**Question 24:** An equilateral triangle whose side is 12 cm is rotated about the altitude. Find the volume of the solid thus generated. [cite: 39, 40]

* **Visual Explanation:** Draw an equilateral triangle. Pick one altitude (the line from a vertex perpendicular to the opposite side). Imagine spinning the triangle around this altitude line. It will trace out a cone.
* **Solution Steps:**
    1.  When rotated about the altitude, the solid formed is a cone.
    2.  **Dimensions of the Cone:**
        * The height (h) of the cone is the altitude of the equilateral triangle. Altitude = $(\sqrt{3}/2) \times side = (\sqrt{3}/2) \times 12 = 6\sqrt{3}$ cm.
        * The radius (r) of the cone's base is half the base of the equilateral triangle (since the altitude bisects the base). Radius = 12 / 2 = 6 cm.
    3.  **Volume of Cone:** V = (1/3) * π * r² * h
        * V = (1/3) * π * (6)² * (6\sqrt{3})
        * V = (1/3) * π * 36 * 6\sqrt{3}
        * V = π * 12 * 6\sqrt{3} = 72\sqrt{3}π$ cubic cm. (Note: The unit should be cubic units or cm³)
* **Answer:** (C) $72\sqrt{3}\pi$ cu. Units [cite: 41]
* **Tips & Tricks:** Visualizing the solid formed by rotation is crucial. Identify how the dimensions of the original 2D shape relate to the dimensions (radius, height, slant height) of the resulting 3D solid.

---

**Question 25:** In the figure, A and B are the centres of unit circles intersecting each other. Find the area of the region common to both the circles. [cite: 41, 42]

* **Visual Explanation:** Imagine two identical circles (radius = 1) that overlap. Their centers (A and B) are positioned such that each circle passes through the center of the other (this is implied by the standard diagram for this problem, though not explicitly stated - usually, A and B are distance 1 apart). The common region looks like a lens or vesica piscis.
* **Solution Steps:** (Assuming distance AB = radius = 1)
    1.  The common area can be found by taking the area of the sector formed in one circle and subtracting the triangle formed by the radii and the chord, then doubling the result (due to symmetry).
    2.  Consider circle A. The intersection points (let's call them P and Q) and the center B form an equilateral triangle APB (since AP=AB=radius=1). Similarly, AQB is equilateral. Thus, angle PAQ in circle A is formed by two equilateral triangles sharing side AB, making angle PAB = 60 degrees and angle QAB = 60 degrees. So, angle PAQ = 120 degrees.
    3.  **Area of Sector PAQ in Circle A:** Area = $(\theta/360) \times \pi r^2 = (120/360) \times \pi (1)^2 = (1/3)\pi$.
    4.  **Area of Triangle PAQ:** This triangle can be split by AB into two triangles, PAB and QAB. Alternatively, use Area = (1/2) * r² * sin(θ) = (1/2) * 1² * sin(120°). Sin(120°) = Sin(60°) = $\sqrt{3}/2$. So, Area(Triangle PAQ) = (1/2) * 1 * ($\sqrt{3}/2$) = $\sqrt{3}/4$. (Wait, check this triangle area - maybe it's simpler using the equilateral triangles. Triangle APB area = $(\sqrt{3}/4) \times 1^2 = \sqrt{3}/4$. Triangle AQB area = $\sqrt{3}/4$. Total area of rhombus APBQ = $2 * (\sqrt{3}/4) = \sqrt{3}/2$. Let's rethink the segment approach).
    5.  **Area of Segment:** (Area of Sector PAQ) - (Area of Triangle PAQ calculated differently: base PQ, height needed). Let's try Area of Segment = Area of Sector - Area(Triangle APQ). We need Area(Triangle APQ). This triangle has sides AP=1, AQ=1. Angle PAQ=120°. Area = (1/2)ab*sinC = (1/2)*1*1*sin(120°) = (1/2)*($\sqrt{3}/2$) = $\sqrt{3}/4$.
    6.  Area of the segment in circle A (the part bounded by arc PQ and chord PQ) = Area(Sector PAQ) - Area(Triangle PAQ) = $(\pi/3) - (\sqrt{3}/4)$.
    7.  The total common area is made of *two* such segments (one from circle A, one from circle B).
    8.  Total Common Area = 2 * [Area of Segment] = 2 * [ $(\pi/3) - (\sqrt{3}/4)$ ] = $(2\pi/3) - (\sqrt{3}/2)$.
* **Answer:** (B) $\frac{2\pi}{3}-\frac{\sqrt{3}}{2}$ [cite: 43]
* **Tips & Tricks:** Overlapping circles problems often involve finding the area of segments. Area of Segment = Area of Sector - Area of Triangle formed by radii and chord. Symmetry is key. Recognizing equilateral triangles (if centers are distance 'r' apart for radius 'r' circles) simplifies finding the sector angle (120°).

---

**Motivation Boost!**

Wow, Rheaa, you've worked through a solid set of mensuration problems! Look at how many different shapes and concepts you've tackled – triangles, circles, parallelograms, rhombuses, rectangles, trapeziums, hexagons, cuboids, cubes, spheres, cones, cylinders, frustums, prisms, and even combinations! That's seriously impressive.

Remember, every problem you solve, even the tricky ones, builds your understanding and speed. Don't get discouraged if some take longer than others – that's part of the learning process. The key is persistence and understanding the 'why' behind each step.

Keep visualizing those shapes, practice those formulas, and trust your logic. You're building a strong foundation for your entrance tests. Keep up the amazing work, stay focused, and you'll definitely rock it! Good luck with your preparation in Bangalore!