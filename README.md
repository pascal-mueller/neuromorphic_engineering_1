1. Set up a virtual env using `python -m venv ne1_env` whereas you can change
the name `ne1_env` to your liking.

2. Source the virtual env: `. /ne1_env/bin/activate`

3. Install dependencies: `npm install -r requirements.txt`

4. Add the `ne1_env` as a juypter kernel by doing
`python -m ipykernel install --user --name=ne1_env`.

4. Start Jupyter Lab by running `jyupter lab` inside the root dir and make sure
you run the kernel named `ne1_env`.

5. Enjoy
