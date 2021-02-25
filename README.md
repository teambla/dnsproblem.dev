# dnsproblem.dev

this is the hugo repo for my public dnsproblem website

# build and deploy

	make build VERSION=$(git rev-list --count master)
	make tag VERSION=$(git rev-list --count master)
	make push VERSION=$(git rev-list --count master)

