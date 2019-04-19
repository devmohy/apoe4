<template>
    <div class="container-fluid">
        <div class="container">
            <!-- ALL COMPONENT MARKUP GOES HERE-->
						<form action="#">
							<div class="container">
								<legend style="font-size:2rem; font-weight:bold" class="text-center">Contact Us</legend>
								<p>Contact us to find out more or how we can help you better</p>
								<br><br>
								<div class="row" style=text-align:left;>
									<div class="form-group col-sm-6">
										<label class="text-left" for="name">Name</label>
										<input type="email" class="form-control" id="name" aria-describedby="nameHelp">
									</div>

									<div class="form-group col-sm-6">
										<label class="text-left" for="exampleInputEmail">Email address</label>
										<input type="email" class="form-control" id="exampleInputEmail" aria-describedby="emailHelp">
									</div>
								</div>
									<br>
								<div class="row">
									<div class="form-group col-sm-12">
										<label class="text-left" for="message">Message</label>
										<textarea class="form-control" id="message" rows="15"></textarea>
									</div>
								</div>

								<div class="row">
									<div class="form-group col-sm-12">
										<button class="btn btn-lg btn-primary">Send</button>
									</div>
								</div>

							</div>			
					</form>
				
        </div>
    </div>
</template>

<style scoped>

	form {
		padding:50px;
		width: 80%;
		text-align: center;
		box-shadow: 2px 2px 10px gray;
		margin: -150px auto auto auto;
		background:#ffffff;
		border-radius:10px;
	}
	
	p{
		font-size:1em;
		font-weight:bold;
	}
	label {
		font-size: 1.3rem;
	}

	h3{
		padding-top:50px;
		font-weight:600;
	}

	textarea,input {
		background-color:#F2F2F2;
		
	}

</style>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>
