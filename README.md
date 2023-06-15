#include<iostream>
#include<string>
using namespace std;

int main()
{
	int commands;
	string isAuthorized;
	string isAuthorized_0 = "aliisrome";
	string isAuthorized_1 = "heilCaesar" ;
	string isAuthorized_2 = "constantineXI" ;
	
	cout << "Please enter the first PIN to pass through: ";
	cin >> isAuthorized;
	
	if (isAuthorized==isAuthorized_0)
	{
		cout << "\nYou need to clear the second Security Check: ";
		cin >> isAuthorized;
		
		if (isAuthorized==isAuthorized_1)
		{
			cout << "\nPass the last check to access data: ";
			cin >> isAuthorized;
			
			if (isAuthorized==isAuthorized_2)
			{
				cout << "\nTHESE WERE THE LABOURS OF HERCULES\n" << endl
					<< "1) Slay the Nemean lion." << endl
					<< "2) Slay the nine-headed Lernaean Hydra." << endl
					<< "3) Capture the Ceryneian Hind." << endl
					<< "4) Capture the Erymanthian Boar." << endl
					<< "5) Clean the Augean stables in a single day." << endl
					<< "6) Slay the Stymphalian birds." << endl
					<< "7) Capture the Cretan Bull." << endl
					<< "8) Steal the Mares of Diomedes." << endl
					<< "9) Obtain the girdle of Hippolyta, queen of the Amazon." << endl
					<< "10) Obtain the cattle of the three-bodied giant Geryon." << endl
					<< "11) Steal three of the golden apples of the Hesperides." << endl
					<< "12) Capture and bring back Cerberus." << endl
					<< "\nWhich one would you like to read? ";
				cin >> commands;
				
				switch (commands)
				{
					case 1:
						
						cout<<"\nThe Nemean lion was a vicious monster in Greek mythology that lived at Nemea. Eventually, it was killed by Hercules. Because its golden fur was impervious to attack, it could not be killed with mortals' weapons. Its claws were sharper than mortals' swords and could destroy any strong armour. In Bibliotheca, Photius wrote that the Dragon Ladon, who guarded the golden apples, was his brother. Hercules picked up his club and went after the lion. Following it to a cave which had two entrances, Hercules blocked one of the doorways, then approached the fierce lion through the other. Grasping the lion in his mighty arms, and ignoring its powerful claws, he held it tightly until he'd choked it to death."<<endl;
					
					break;
					
					case 2:
						
						cout<<"\nThe Lernaean Hydra or Hydra of Lerna, is a serpentine water monster in Greek and Roman mythology. Its lair was the lake of Lerna in the Argolid, which was also the site of the myth of the Danaïdes. Lerna was reputed to be an entrance to the Underworld, and archaeology has established it as a sacred site older than Mycenaean Argos. In the canonical Hydra myth, the monster is killed by Hercules as the second of his Twelve Labors. According to Hesiod, the Hydra was the offspring of Typhon and Echidna. It had poisonous breath and blood so virulent that even its scent was deadly. The Hydra possessed many heads, the exact number of which varies according to the source. Later versions of the Hydra story add a regeneration feature to the monster: for every head chopped off, the Hydra would regrow two heads. Heracles required the assistance of his nephew Iolaus and then each time Hercules bashed one of the hydra's heads, Iolaus held a torch to the headless tendons of the neck. The flames prevented the growth of replacement heads, and finally, Hercules had the better of the beast. Once he had removed and destroyed the eight mortal heads, Hercules chopped off the ninth, immortal head."<<endl;
						
					break;
					
					case 3:
						
						cout<<"\nIn Greek mythology, The Ceryneian Hind was a creature that lived in Ceryneia, Greece and took the form of an enormous female deer, larger than a bull, with golden antlers like a stag, hooves of bronze or brass, and a 'dappled hide', that 'excelled in swiftness of foot', and snorted fire. To bring it back alive to Eurystheus in Mycenae was the third labour of Hercules. One tradition says that Artemis found a mighty herd of five Ceryneian hinds playing on the base of Parrhasian hill far away from the banks of the 'black-pebbled Anaurus' where they always herded. Artemis was so impressed by the hinds that she yoked four of them to her golden chariot with golden bridles, but purposely let one escape to the Ceryneian hill to be a future labour for Heracles. Whilst in Ceryneia, the hind chased farmers from vineyards. The Ceryneian hind was sacred to Artemis. The hind is said to have borne the inscription 'Taygete dedicated (me) to Artemis'. Because of its sacredness, Heracles did not want to harm the hind and so hunted it for more than a year, from Oenoe to Hyperborea, to a mountain called Artemisius, (a range which divides Argolis from the plain of Mantinea) before finally capturing the hind near the river Ladon. Euripides says Heracles slew the hind and brought it to Artemis for propitiation. Another tradition says he captured it with nets while it was sleeping or that he ran it down, while another says he shot and maimed it with an arrow just before it crossed the river Ladon. Once Heracles captured the hind, and only after explaining to Artemis and Apollo (who would have wrested the hind from him) that he had only hurt the sacred hind out of necessity, was he allowed to take it alive to Eurystheus in Mycenae, thus completing his third labour."<<endl;
						
					break;
					
					case 4:
						
						cout<<"\nIn Greek mythology, The Erymanthian Boar was a mythical creature that took the form of a shaggy and wild tameless boar of vast weight and foaming jaws. It was a Tegeaean, Maenalusian or Erymanthian boar that lived in the glens of Lampeia beside the vast marsh of Erymanthus. It would sally from the thick-wooded, cypress-bearing heights of Erymanthus to harry the groves of Arcady and abuse the land of Psophis. The fourth labour of Heracles was to bring the Erymanthian boar alive to Eurystheus in Mycenae. To capture the boar, Heracles first chased the boar with shouts and thereby routed it from a certain thicket and then drove the exhausted animal into deep snow. He then trapped it, bound it in chains, and lifted it, still breathing from the dust, and returning with the boar on his left shoulder, staining his back with blood from the stricken wound, he cast it down in the entrance to the assembly of the Mycenaeans, thus completing his fourth labour. When the king [Eurystheus] saw him carrying the boar on his shoulders, he was terrified and hid himself in a bronze vessel. The inhabitants of Cumae, in the land of the Opici, profess that the boar's tusks which are preserved in the sanctuary of Apollo at Cumae are the tusks of The Erymanthian Boar, but the assertion is without a shred of probability. "<<endl;
						
					break;
					
					case 5:
						
						cout<<"\nIn Greek mythology, Augeas (whose name means bright) was king of Elis and father of Epicaste. Some say that Augeas was one of the Argonauts. He is best known for his stables, which housed the single greatest number of cattle in the country and had never been cleaned, until the time of the great hero Heracles. The fifth Labour of Hercules was to clean the Augean stables. Eurystheus intended this assignment both as humiliating (rather than impressive, like the previous labours) and as impossible, since the livestock were divinely healthy (immortal) and therefore produced an enormous quantity of dung. These stables had not been cleaned in over thirty years, and 3,000 cattle lived there. However, Heracles succeeded by rerouting the rivers Alpheus and Peneus to wash out the filth. Augeas reacted angrily because he had promised Heracles one tenth of his cattle if the job was finished in one day. He refused to honor the agreement, and Heracles killed him after completing the tasks. Heracles gave his kingdom to Phyleus, Augeas's son, who had been exiled for supporting Heracles against his father."<<endl;
						
					break;
					
					case 6:
						
						cout<<"\nThe Stymphalian Birds were defeated by Hercules in his sixth labour for Eurystheus. Heracles could not go into the marsh to reach the nests of the birds, as the ground would not support his weight. Athena, noticing the hero's plight, gave Heracles a rattle called krotala, which Hephaestus had made especially for the occasion. Heracles shook the krotala (similar to castanets) on a certain mountain that overhung the lake and thus frightening the birds into the air. Heracles then shot many of them with feathered arrows tipped with poisonous blood from the slain Hydra. In some versions of this story this labour was discounted because of the help of Athena. The rest flew far away, never to plague Arcadia again. Heracles brought some of the slain birds to Eurystheus as proof of his success. The surviving birds made a new home on the island of Aretias in the Euxine Sea. The Argonauts later encountered them there. According to Mnaseas, they were not birds, but women and daughters of Stymphalus and Ornis, and were killed by Heracles because they did not receive him hospitably. In the temple of the Stymphalian Artemis, however, they were represented as birds, and behind the temple, there were white marble statues of maidens with birds feet."<<endl;
						
					break;
					
					case 7:
						
						cout<<"\nHeracles was sent to capture the bull by Eurystheus as his seventh task. He sailed to Crete, whereupon Minos gave Heracles permission to take the bull away as he had been wreaking havoc on Crete by uprooting crops and leveling orchard walls. Heracles captured the bull, and then shipped him to Eurystheus in Tiryns. The bull later broke loose and wandered into Marathon, becoming known as the Marathonian Bull. Eurystheus then sent Heracles to bring back the man-eating Mares of Diomedes (the next task)."<<endl;
						
					break;
					
					case 8:
						
						cout<<"\nAs the eighth of his Twelve Labours Heracles was sent by King Eurystheus to steal the Mares from Diomedes. The mares’ madness was attributed to their unnatural diet which consisted of the flesh of unsuspecting guests or strangers to the island. Some versions of the myth say that the mares also expelled fire when they breathed. The Mares, which were the terror of Thrace, were kept tethered by iron chains to a bronze manger in the now vanished city of Tirida and were named Podargos (the swift), Lampon (the shining), Xanthos (the yellow) and Deinos (the terrible). Although very similar, there are slight variances in the exact details regarding the mares’ capture. In one version, Heracles brought a number of volunteers to help him capture the giant horses. After overpowering Diomedes’ men, Heracles broke the chains that tethered the horses and drove the mares down to sea. Unaware that the mares were man-eating and uncontrollable, Heracles left them in the charge of his favored companion, Abderus, while he left to fight Diomedes. Upon his return, Heracles found that the boy was eaten. As revenge, Heracles fed Diomedes to his own horses and then founded Abdera next to the boy's tomb. In another version, Heracles, who was visiting the island, stayed awake so that he didn't have his throat cut by Diomedes in the night, and cut the chains binding the horses once everyone was asleep. Having scared the horses onto the high ground of a knoll, Heracles quickly dug a trench through the peninsula, filling it with water and thus flooding the low-lying plain. When Diomedes and his men turned to flee, Heracles killed them with an axe (or a club), and fed Diomedes’ body to the horses to calm them. In yet another version, Heracles first captured Diomedes and fed him to the mares before releasing them. Only after realizing that their King was dead did his men, the Bistonians, attack Heracles. Upon seeing the mares charging at them, led in a chariot by Abderus, the Bistonians turned and fled. In all versions the horses are calmed by eating human flesh, giving Heracles the opportunity to bind their mouths shut and easily take them back to King Eurystheus, who dedicated the horses to Hera. In some versions, they were allowed to roam freely around Argos, having become permanently calm, but in others, Eurystheus ordered the horses taken to Olympus to be sacrificed to Zeus, but Zeus refused them, and sent wolves, lions, and bears to kill them. Roger Lancelyn Green states in his Tales of the Greek Heroes that the mares’ descendants were used in the Trojan War, and survived even to the time of Alexander Greek. After the incident, Eurystheus sent Heracles to bring back Hippolyta's Girdle."<<endl;
						
					break;
					
					case 9:
						
						cout<<"\nEurystheus' daughter Admete wanted the Belt of Hippolyta, queen of the Amazons, a gift from her father Ares. To please his daughter, Eurystheus ordered Heracles to retrieve the belt as his ninth labour. Taking a band of friends with him, Heracles set sail, stopping at the island of Paros, which was inhabited by some sons of Minos. The sons killed two of Heracles' companions, an act which set Heracles on a rampage. He killed two of the sons of Minos and threatened the other inhabitants until he was offered two men to replace his fallen companions. Heracles agreed and took two of Minos' grandsons, Alcaeus and Sthenelus. They continued their voyage and landed at the court of Lycus, whom Heracles defended in a battle against King Mygdon of Bebryces. After killing King Mygdon, Heracles gave much of the land to his friend Lycus. Lycus called the land Heraclea. The crew then set off for Themiscyra, where Hippolyta lived. All would have gone well for Heracles had it not been for Hera. Hippolyta, impressed with Heracles and his exploits, agreed to give him the belt and would have done so had Hera not disguised herself and walked among the Amazons sowing seeds of distrust. She claimed the strangers were plotting to carry off the queen of the Amazons. Alarmed, the women set off on horseback to confront Heracles. When Heracles saw them, he thought Hippolyta had been plotting such treachery all along and had never meant to hand over the belt, so he killed her, took the belt and returned to Eurystheus."<<endl;
						
					break;
					
					case 10:
						
						cout<<"\nThe tenth labour was to obtain the Cattle of the three-bodied giant Geryon. In the fullest account in the Bibliotheca of Pseudo-Apollodorus, Heracles had to go to the island of Erytheia in the far west (The Hesperides or The island which forms the city of Cádiz) to get the cattle. On the way there, he crossed the Libyan desert and became so frustrated at the heat that he shot an arrow at the Sun. The sun-god Helios in admiration of his courage gave Heracles the golden cup Helios used to sail across the sea from west to east each night. Heracles rode the cup to Erytheia, Heracles in the cup was a favorite motif on black-figure pottery. Such a magical conveyance undercuts any literal geography for Erytheia, the red island of the sunset. When Heracles landed at Erytheia, he was confronted by the two-headed dog Orthrus. With one blow from his olive-wood club, Heracles killed Orthrus. Eurytion the herdsman came to assist Orthrus, but Heracles dealt with him the same way. On hearing the commotion, Geryon sprang into action, carrying three shields and three spears, and wearing three helmets. He attacked Heracles at the River Anthemus, but was slain by one of Heracles' poisoned arrows. Heracles shot so forcefully that the arrow pierced Geryon's forehead, and Geryon bent his neck over to one side, like a poppy that spoils its delicate shapes, shedding its petals all at once. Heracles then had to herd the cattle back to Eurystheus. In Roman versions of the narrative, Heracles drove the cattle over the Aventine Hill on the future site of Rome. The giant Cacus, who lived there, stole some of the cattle as Heracles slept, making the cattle walk backwards so that they left no trail, a repetition of the trick of the young Hermes. According to some versions, Heracles drove his remaining cattle past the cave, where Cacus had hidden the stolen animals, and they began calling out to each other. In other versions, Cacus' sister Caca told Heracles where he was. Heracles then killed Cacus, and set up an altar on the spot, later the site of Rome's Forum Boarium (the cattle market). To annoy Heracles, Hera sent a gadfly to bite the cattle, irritate them, and scatter them. Within a year, Heracles retrieved them. Hera then sent a flood which raised the level of a river so much that Heracles could not cross with the cattle. He piled stones into the river to make the water shallower. When he finally reached the court of Eurystheus, the cattle were sacrificed to Hera."<<endl;
						
					break;
					
					case 11:
						
						cout<<"\nAfter Heracles completed the first ten labours, Eurystheus gave him two more, claiming that slaying the Hydra did not count (because Iolaus helped Heracles), neither did cleaning the Augean Stables (either because he was paid for the job or because the rivers did the work). The first additional labour was to steal three of the golden apples from the garden of the Hesperides. Heracles first caught the Old Man of the Sea, the shapeshifting sea god, to learn where the Garden of the Hesperides was located. In some variations, Heracles, either at the start or at the end of this task, meets Antaeus, who was invincible as long as he touched his mother, Gaia, the Earth. Heracles killed Antaeus by holding him aloft and crushing him in a bear hug. Herodotus claims that Heracles stopped in Egypt, where King Busiris decided to make him the yearly sacrifice, but Heracles burst out of his chains. Heracles finally made his way to the garden of the Hesperides, where he encountered Atlas holding up the heavens on his shoulders. Heracles persuaded Atlas to get the three Golden Apples for him by offering to hold up the heavens in his place for a little while. Atlas could get the apples because, in this version, he was the father or otherwise related to the Hesperides. When Atlas returned, he decided that he did not want to take the heavens back, and instead offered to deliver the apples himself, but Heracles tricked him by agreeing to remain in place of Atlas on the condition that Atlas relieve him temporarily while Heracles adjusted his cloak. Atlas agreed, but Heracles reneged and walked away with the apples. According to an alternative version, Heracles slew Ladon, the dragon who guarded the apples, instead. Eurystheus was furious that Heracles had accomplished something that Eurystheus thought could not possibly be done."<<endl;
						
					break;
					
					case 12:
						
						cout<<"The twelfth and final labour was the capture of Cerberus, the three-headed, dragon-tailed dog that was the guardian of the gates of the Underworld. To prepare for his descent into the Underworld, Heracles went to Eleusis (or Athens) to be initiated in the Eleusinian Mysteries. He entered the Underworld, and Hermes and Athena were his guides. While in the Underworld, Heracles met Theseus and Pirithous. The two companions had been imprisoned by Hades for attempting to kidnap Persephone. One tradition tells of snakes coiling around their legs, then turning into stone, another that Hades feigned hospitality and prepared a feast inviting them to sit. They unknowingly sat in chairs of forgetfulness and were permanently ensnared. When Heracles had pulled Theseus first from his chair, some of his thigh stuck to it (this explains the supposedly lean thighs of Athenians), but the Earth shook at the attempt to liberate Pirithous, whose desire to have the goddess for himself was so insulting he was doomed to stay behind. Heracles found Hades and asked permission to bring Cerberus to the surface, which Hades agreed to if Heracles could subdue the beast without using weapons. Heracles overpowered Cerberus with his bare hands and slung the beast over his back. He carried Cerberus out of the Underworld through a cavern entrance in the Peloponnese and brought it to Eurystheus, who again fled into his pithos. Eurystheus begged Heracles to return Cerberus to the Underworld, offering in return to release him from any further labours when Cerberus disappeared back to his master."<<endl;
						
					break;
					
					default:
						
						cout << "You don't have any other data from The Book of Old." << endl;
				}
			}
			else
			{
				cout << "\nYou can't break my Enigma that easily!" << endl;
			}
		}
		else
		{
			cout << "\nYou can't break my Enigma that easily!" << endl;
		}
	}
	else
	{
		cout << "\nYou can't break my Enigma that easily!" << endl;
	}
} 
