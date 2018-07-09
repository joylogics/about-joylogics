# about-joylogics

## Introductions from Shinichi Urano (@9horses)

I'm writing this note to introduce you to myself, what I'm trying to do, why, and how I'm planning to work with you.

I have 30+ years of experience as a programmer. I discovered PDP-11 and BASIC in high school, and it wasn't long before I was hand-writing 6502 assembler code to simulate Millikan's experiment on an Apple II+ computer. That means I've been around programming for a long time, and I like to think I know a few things when it comes to the art of programming. (Having said that, while I understand most programming languages, I am hardly an expert in any these days.)

My first interest, though, was in physics. You might have guessed that from my reference to Millikan's experiment. I actually have a Ph.D. in theoretical particle physics, having specialized in grand unification theories. (SO(10) supergravity flavor, if you're curious.)

You may not know this, but as it turns out, theoretical particle physics has been "stuck" (IMO) for some time now. The goal of theoretical particle physics is to explain (through new theories) anomalous physical phenomena that are detected in nature (through experiments.) Unfortunately, there has actually not been any unexplained physical phenomena in particle physics for decades now! (We were hoping LHC will see something - no luck as yet.) So, somewhat disappointed, I left physics shortly after my Ph.D. and a brief stint as a professor.

Since that time, I have been working as a software engineer, then as a manager, and then as an entrepreneur. I am the curious (nosy) type, and so I've learned a lot of different things over the years. (And I've tried a lot of things. I know a lot of things _not_ to do!)

Of late, I have been consulting, primarily start-up companies. Due to my background, I have a ton of relevant experience to draw from (useful for start-ups), from technology to sales and marketing. My typical role is that of a technology advisor (CTO-as-a-service), though I have been asked to fill other roles such as business development manager or product manager. 

Thanks to my technical lean, though, I am often asked to help build software. I have been reluctant to do this, primarily because I am reluctant to build a team of full-time programmers. (You can imagine why - it's quite a burden to make sure your team has enough projects that are of the right type. This is one of the reasons why software development companies have to charge a lot of money for the projects.)

Today, however, thanks to the rise of 'gig economy', cloud technologies, and open source workflows, I believe there's a new way to build quality software, through a 'virtual' team of professional programmers looking for side gigs. This is how I'm interested in working with you!

So, here's the process I'd like to follow, at a high level (and this will likely evolve over time):
 * "Project" is the unit of my engagement with you.
 * The scope of each project will typically be bound by a service (or a microservice.) This means that I'm expecting you to work on creating or modifying some web service. Each service will have its own GitHub repo which you will be given access to.
 * The detailed requirements of each project will be produced collaboratively. This is because I believe I have a reasonable degree of clarity of the context by the time I approach you, but you are probably better at producing the specific requirements. Most likely, we will iterate a few times on the details and this is actually a good way to make sure we are communicating.
 * Once we agree on the details, you should provide an implementation plan and an estimate of time. We will use the estimate to bound the cost of each project. It's completely expected that sometimes estimates fail. We can adjust when that happens.
 * I expect you to use 'feature branches' (a la 'git flow' - see http://nvie.com/posts/a-successful-git-branching-model/ if you are not familiar with this) for each project. When you are ready for someone to review the project, you should submit a pull request (a la 'GitHub flow' - see https://guides.github.com/introduction/flow/).
 * I expect you to have "good" unit test coverage. What is "good"? I hope you're most like the 2nd programmer in this story: https://www.artima.com/forums/flat.jsp?forum=106&thread=204677
 * Your pull request will receive constructive feedback. It's expected that you will respond quickly so we can come to a good pull request that will be merged into a parent branch.
 * If you're creating a new service, it's expected that you will also work on creating a CI/CD (continuous integration/continuous delivery) automation. We use Travis-CI for build/package automation. We also use Codecov for code coverage analytics.
 * Most of the time, there will be dependencies for the service you're working on. It'll be my responsibility to provide packages (e.g. docker images) that you can use to serve these dependencies.
 * If you need a dev/test environment, I will provide one for you (most likely in AWS).

Ultimately, I am looking for a long-term relationship. To that end, I look for and I value the following (both in myself and in you):
 * Honest, transparent, communication.
 * Timeliness, and respect for other people's time.
 * Quality code.
 * Humility, Patience, and Open-Mindedness.
 * Resourcefulness. (Ability not to get blocked/stuck.)
