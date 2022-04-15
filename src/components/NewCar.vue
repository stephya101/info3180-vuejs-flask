<template>
<form @submit.prevent="uploadPhoto" id="newCar">
    <div class ="container">
        <div class ="row">
            <div class = "form-group col-md-3">
             <label for="make">Make</label>
             <input class = "form-control" type="text" id="make" name="make">
             </div>
             <div class = "form-group col-md-3">
             <label for="model">Model</label>
             <input class = "form-control" type="text" id="model" name="model">
             </div>
        <div class ="row">
            <div class = "form-group col-md-3">
             <label for="colour">Colour</label>
             <input class = "form-control" type="text" id="colour" name="colour">
             </div>
             <div class = "form-group col-md-3">
             <label for="year">Year</label>
             <input class = "form-control" type="text" id="year" name="year">
             </div>
        <div class ="row">
            <div class = "form-group col-md-3">
            <label for="price">Price</label>
            <input class = "form-control" type="text" id="price" name="price">
            </div>
            <div class = "form-group col-md-3">
            <label for="car_type">Car Type</label>
            <select class="form-control" id="car_type">
                <option>SUV</option>
                <option>Sedan</option>
                </select>
            </div>
    <div class ="form-group">  
        <div class = "form-group col-md-3">
            <label for="transmission">Transmission</label>
            <select class="form-control" id="car_type">
                <option>Automatic</option>
                <option>Manual</option>
            </select>
        </div>
    <div class ="form-group">  
        <div class = "form-group col-md-2">              
        <label for="description">Description</label>
        <textarea id="description" name="description" rows="4" cols="65"></textarea>
        </div>
    <div class ="form-group">  
        <div class = "form-group col-md-2">              
        <label for="photo">Upload Photo</label>
        <input type="file" id="photo" name="photo">
        </div>
        <br>
        <button type = "submit" name = "submit" class="btn btn-success col-md-2">Save</button>
        </div>
        </div>
             </div>
            </div>
            </div>
        </div>
    </div>

</form>
</template>

<script>
export default {
    data() {
      return {
          
      }        
    }
}
</script>

<style>
/* Add any component specific styles here */
</style>