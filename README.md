First-Project
=============
structures <- function(){
greeting <- "Do you know what you're doing?"

vector <- c("no idea","some idea","a great idea")
paste(vector, "what I'm doing")

frame <- data.frame(vector=c("no idea", "some idea", "a great idea"))

closing <- "You're Lost"

return(list(greeting,vector,frame,closing))
}
