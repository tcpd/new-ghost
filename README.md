# new-ghost

Repository for the ghost website
  
## Installation
Via Docker

```bash
docker-compose -f stack.yml up
```

## Usage
If all goes well, you'll be able to access the new site on http://localhost:3001 and http://localhost:3001/ghost to access Ghost Admin. One has to sign-up using their email id while accessing Ghost Admin.
 
## References
1) For `docker-installation` : [Docs](https://hub.docker.com/_/ghost/)
2) For `env` variables in the `dockerfile`: [Docs](https://ghost.org/docs/concepts/config/#section-running-ghost-with-config-env-variables)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
