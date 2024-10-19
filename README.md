# Abinaya-k
AI fashion designer 
<section id="measure">
    <h2>Body Measurements</h2>
    <p>Enter your measurements for personalized clothing designs.</p>
    <link rel="stylesheet" href="measurement.css">
    <form action="measure.php" method="POST" id="measureForm">
        <input type="number" id="height" name="height" placeholder="Height (cm)" required>
        <input type="number" id="waist" name="waist" placeholder="Waist (cm)" required>
        <input type="number" id="chest" name="chest" placeholder="Chest (cm)" required>
        <input type="number" id="hip" name="hip" placeholder="Hip (cm)" required>
        <input type="number" id="shoulders" name="shoulders" placeholder="Shoulders (cm)" required>
        <input type="number" id="inseam" name="inseam" placeholder="Inseam (cm)" required>
        <input type="number" id="sleeveLength" name="sleeveLength" placeholder="Sleeve Length (cm)" required>
        <input type="number" id="neck" name="neck" placeholder="Neck (cm)" required>
        <input type="number" id="thigh" name="thigh" placeholder="Thigh (cm)" required>
        <button type="submit">Submit Measurements</button>
      
    </form>
    
    <script src="measure.js"></script>
</section>
