# XxJustKiddingKubexX
Each directory is the home for a different cube. The [low_power](low_power/README.md), [medium_power](medium_power/README.md) and [high_power](high_power/README.md) directories are all examples of how a cube would look in this repo.

Each cube has its own: 
- `README.md` An internal description of the cube and any info needed.
- `cube.csv` The cube saved in the [Cube Cobra](https://cubecobra.com/dashboard) format (includes Status, Notes etc.)
- `*.xml` These xml files are exported from [MPC Fill](https://mpcfill.com/). Each of these are used to create proxy orders with [mpc-autofill](github.com/chilli-axe/mpc-autofill)

## Keeping Track of Cards
Every card in a cube has a status on [Cube Cobra](https://cubecobra.com/dashboard). This is a good place to mark if the card is:
- Not Owned
- Ordered
- Owned

We will considered an in hand proxy "Owned" and not use the "Proxied" status.

If a card is being donated by someone, that can be made note of in the "Notes" field on [Cube Cobra](https://cubecobra.com/dashboard).

## Additions and Changes
If you'd like to make a cube or suggest a change to an existing cube, submit a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request)

To create a cube, copy and rename the [blank_cube](blank_cube) directory. If the cube has been added to [Cube Cobra](https://cubecobra.com/dashboard), please add the link to the cube's `README.md` 

## Basic Workflow
I will layout the steps for making a new cube and the steps for making a suggestion/updating an existing cube.

### New Cube
#### I do not want to do any nerd shit
Here is how to go from not knowing what jacob is talking about to submitting a new cube:

- Make an account on [Cube Cobra](https://cubecobra.com/user/register)
- Under `Your Cubes`, select `Create a New Cube` or clone an exisiting cube
- Build/modify your cube
- Under the `List` tab for your cube, click `Import/Export` and under `Export` click `Comma-Separated (.csv)`
- Make an account on [GitHub](https://github.com/signup)
- Navigate to [the repo](https://github.com/jaayjee/XxJustKiddingKubexX)
- Click `Add File` and then `Create new file`
- In the `Name your file` filed write `your_cube_name/cube.csv`
- Paste the contents of your exported cube (`.csv` file)
- Click `Commit Changes`
- Select `Create a new branch for this commit and start a pull request` and click `Propose changes` 
- Click `Create pull request`
- Wait for Approval.

#### Learning git could be cool
- Make an account on [Cube Cobra](https://cubecobra.com/user/register)
- Under `Your Cubes`, select `Create a New Cube` or clone an exisiting cube
- Build/modify your cube
- Under the `List` tab for your cube, click `Import/Export` and under `Export` click `Comma-Separated (.csv)`
- Make an account on [GitHub](https://github.com/signup)
- Install [git](https://git-scm.com/downloads/win) (guide for this step and the next few found under steps 1-3 [here](https://courses.cs.washington.edu/courses/cse154/21sp/resources/assets/vscode-git-tutorial/windows/index.html#installandsetupvscode))
- Install [Visual Studio Code](https://code.visualstudio.com/)
- Click the Source Control button on the left, click `Clone Repository` and input `https://github.com/jaayjee/XxJustKiddingKubexX`
- Right click the Explorer, click `Add Folder to Workspace`, and select where you ran the command in the step above
- Duplicate the `blank_cube` directory and name it what you would like
- Replace the contents of the `cube.csv` with the contents of your downloaded `.csv`
- Update the `README.md` in your new directory 
- Click the Source Control button and click the refresh button beside the top `Changes`
- Click the `Stage All Changes` beside the lower `Changes`
- Click the `...` to the right of the top `Changes` and click `Branch > Create Branch...` and write a name
- Click the `Commit` button
- Navigate to the [Pull Request page](https://github.com/jaayjee/XxJustKiddingKubexX/pulls) and click `New pull request`
- Select your new branch as the `Compare` and click `Create pull request`
- Wait for Approval.

#### Advanced
yktv

### Updating a Cube
TODO