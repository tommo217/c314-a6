CPSC 314 A6  (Sept 2023)

NAME or NAMES:

Martin Lou (35042712), Tom Mo


CREATIVE COMPONENT:

Implemented ability to toggle bounce count from 1 to 3
Implemented a mirror-like plane that reflects the entire scene

COMMENTS:

Please add any comments that you wish to pass on to the graders or instructor.


Call Graph

main()
	initialize()
	rayCast()
		localShade()
		nearestT()
			sphere_intersect()
		bgColor()
			nearestT()
				sphere_intersect()

rayCast2()
	bgColor()
		nearestT()
			sphere_intersect()
