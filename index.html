<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>US History Final Exam Quiz (Ch 23-29)</title>
<style>
  body { font-family: Arial, sans-serif; max-width: 700px; margin: 20px auto; text-align: center; }
  #quiz, #score-container, #next-btn, #submit-btn { display: none; }
  button { font-size: 1.3rem; padding: 10px 20px; margin: 20px; cursor: pointer; }
  label { display: block; margin: 10px 0; cursor: pointer; text-align: left; }
  h1, h2 { color: #333; }
  .correct { color: green; }
  .wrong { color: red; }
  .unanswered { color: blue; }
  .review-question { margin-bottom: 15px; text-align: left; border-bottom: 1px solid #ccc; padding-bottom: 10px; }
</style>
</head>
<body>

<h1>US History Final Exam Quiz (Chapters 23-29)</h1>
<button id="start-btn">Start Quiz</button>

<div id="quiz"></div>
<button id="next-btn" disabled>Next</button>
  <button id="submit-btn">Submit Quiz</button>
  <button id="restart-btn">Restart Quiz</button>

<div id="score-container"></div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const quizData = [
  // Chapter 23
  {question: "What percent of Americans were investing in the stock market prior to the crash?", options: ["2.5%", "10%", "33%", "66%"], answer: 0},
  {question: "Which group of Americans benefitted the least from the economic changes of the 1920s?", options: ["Unionized manufacturing laborers", "Southern farmers", "Northern bankers", "Female educators"], answer: 1},
  {question: "What was the consequence of the Smoot-Hawley Tariff of 1930?", options: ["Lowered prices on international goods", "Increased American exports", "Loosened banking regulation to increase financial liquidity", "International trade collapsed"], answer: 3},
  {question: "How did the Federal Reserve respond to the financial collapse?", options: ["Overcorrected by raising interest rates and tightening credit", "Flooded the market with low interest rates, increasing inflation", "The Federal Reserve did not take any consequential action", "Raised interest rates but increased subsidies for lenders"], answer: 0},
  {question: "What is the definition of Herbert Hoover’s “Associationalism?”", options: ["A belief that self-interest and greed are the surest routes to innovation and economic growth", "An adaption of European socialism designed to redistribute wealth", "A system where businesses would voluntarily limit harmful business practices for the greater economic good", "The use of Progressive Era regulation to protect workers and consumers"], answer: 2},
  {question: "What was the Bonus Army?", options: ["Bankers who were criticized in the press after receiving massive bonuses during the Great Depression", "The men under the command of General Douglas MacArthur who forcibly cleared the Hooverville that had formed in Washington D.C.", "Hoover’s team of financial advisers who designed the Reconstruction Finance Corporation", "A group of World War I veterans who petitioned the government to make an early payment on bonuses scheduled to be released in 1945"], answer: 3},
  {question: "The environmental catastrophe of the Great Depression was partly the result of agricultural mismanagement. Which of the following was the most consequential example of this mismanagement?", options: ["Farmers plowed up natural ground cover to grow more crops, cover that had taken ages to form in the relatively dry sates of the Plains", "Creating excessive windbreaks which ironically enhanced windstorms", "Insufficient irrigation", "Excessive fertilization that poisoned groundwater"], answer: 0},
  {question: "Which of the following statements regarding immigration during the Great Depression is true?", options: ["More people left the United States than entered it during the Great Depression", "Herbert Hoover created a federal program to attract Mexican laborers willing to work in low paying agricultural jobs", "The Mexican-born population living in Texas more than doubled during the Great Depression", "The number of European visas remained constant while Mexican visas dropped"], answer: 0},
  {question: "Upon assuming office, how did Roosevelt respond to the collapsing bank system?", options: ["Waited for the Glass-Steagall Banking Act to take effect in June and then enforced new regulation", "Declared a bank holiday and then pushed through the Emergency Banking Act", "Closed all banks until the economy recovered from the Great Depression", "Invested major public funds on the day after his inauguration to stabilize the banking systems"], answer: 1},
  {question: "Roosevelt tried to create relief for American farmers through the Agricultural Adjustment Act (AAA). What did the AAA do?", options: ["Aimed to raise the prices of agricultural commodities by offering cash incentives to voluntarily limit farm production, thereby increasing prices", "Banned the development of certain kinds of low yield, high intensity crops that contributed to the ecological catastrophe of the Dust Bowl", "Dropped dozens of tariffs on low cost foreign agricultural products in an attempt to lower the price of food for American consumers", "Subsidized agricultural colleges to conduct research on improved agricultural techniques"], answer: 0},
  {question: "What did the Works Progress Administration do?", options: ["Gave grants to private corporations to build new manufacturing plants, thereby creating new manufacturing jobs", "Put unemployed men and women to work on projects designed and proposed by local governments", "Coordinated employment through a new bureaucracy in attempt to discourage racial discrimination in hiring", "Dismantled the first public housing program in favor of privatizing low income housing"], answer: 1},
  {question: "What was the most dramatic result of the 1938 Fair Labor Standards Act?", options: ["The suspension of a minimum wage in attempt to encourage hiring", "Created a vast physical infrastructure of roads, highways, and rail lines to fuel economic development in the South", "Suspended collective bargaining rights for unions in industries deemed essential for national security", "The creation of a national minimum wage"], answer: 3},
  {question: "Louisiana Senator Huey long criticized Roosevelt’s New Deal programs for _____________", options: ["Expanding the power of the presidency over the control of Congress", "Failing to redistribute wealth", "Damaging American business through high taxes", "Falling into a Jewish plot to destroy the United States"], answer: 1},
  {question: "Which of the following actions did FDR take to advance civil rights for African Americans?", options: ["Abolished the poll tax", "Ensured that African American farm workers had access to Social Security", "Created a federal sentencing law to prosecute perpetrators of lynching", "None of these occurred"], answer: 3},
  {question: "What was FDR’s “court-packing scheme”", options: ["An attempt to unseat justices who ruled that the NRA was unconstitutional", "The use of legal language in legislation to nullify the ability of the Supreme Court to overrule new proposed programs", "An attempt to appoint up to six new justices who would be friendly to his interests", "An economic agenda that created the “Roosevelt Recession”"], answer: 2},

  // Chapter 24
  {question: "Before turning to military expansionism, Japanese leaders were also considering which of the following strategies?", options: ["Pacifist isolationism", "Communism", "Pan-Asian anti-colonialism", "Pro-western trade alliances"], answer: 2},
  {question: "Which of the following statements are true regarding Soong May-ling, known to the public as Madame Chiang?", options: ["She was the daughter of Chiang Kai-shek", "Her American education made her an effective diplomat in Chinese-American relations", "She was able to spur American military action in China", "All of the above"], answer: 1},
  {question: "Hitler and Mussolini helped to topple which government in Spain?", options: ["Communists", "Fascists", "Nationalists", "Christian Democrats"], answer: 0},
  {question: "Britain and France declared war on Germany after which invasion?", options: ["Annexation of Austria", "Seizure of the Sudetenland", "Seizure of the remaining territory in Czechoslovakia", "Invasion of Poland"], answer: 3},
  {question: "Which of the following best characterized German military tactics?", options: ["Small detachments of marching troops", "Emphasis on fortifications", "Speed and maneuverability", "Guerrilla warfare"], answer: 2},
  {question: "Why did Hitler stop the Blitz in June 1941?", options: ["Germany was planning a land invasion of Britain", "Germany needed the resources of the Luftwaffe to invade the Soviet Union", "American efforts in southern Europe preoccupied Hitler", "Defeats in Africa forced a redeployment"], answer: 1},
  {question: "Roughly ____ of all German casualties in World War II came in the battle against the Soviet Union.", options: ["25%", "50%", "66%", "80%"], answer: 3},
  {question: "The United States responded to Japanese aggression in the Pacific with the 1940 American Neutrality Act. What did this Act attempt to do?", options: ["Maintain American diplomatic relations with both the Chinese and Japanese", "Encourage greater economic cooperation with Japan in the hopes of deterring further aggression", "Applying economic pressure to Japan to deter military expansion", "Enable American arms build up under the deceiving title of neutrality"], answer: 2},
  {question: "Which Allied nation was the first to reach Berlin?", options: ["United States", "Soviet Union", "Great Britain", "A coordinated attack from all three nations took the capital city"], answer: 1},
  {question: "After the Victory in Europe, the United States suffered a setback in the Pacific. What was that setback?", options: ["The surrender of American forces in the Philippines", "Defeat at the Battle of Midway", "Sinking of eight American battleships off the coast of the Solomon Islands", "Defeat at Guadalcanal"], answer: 0},
  {question: "Approximately how many civilians were killed by the atomic bombs dropped on Hiroshima and Nagasaki?", options: ["80,000", "180,000", "500,000", "Nearly one million"], answer: 1},
  {question: "What was the top tax rate during World War II?", options: ["33%", "50%", "60%", "94%"], answer: 3},
  {question: "Approximately how many women served in the military during WWII?", options: ["15,000", "50,000", "200,000", "350,000"], answer: 3},
  {question: "What prompted President Roosevelt to pass Executive Order 8802?", options: ["The planned march on Washington led by A. Philip Randolph", "The desperate need to fill wartime jobs", "FDR supported integration early in his campaign, and the war gave him the opportunity to pursue that agenda", "The lynching of three black naval officers"], answer: 0},
  {question: "Of the over 110,000 Japanese-descended Americans who were detained in internment camps, approximately how many were American citizens?", options: ["Zero", "25,000", "50,000", "70,000"], answer: 3},

  // Chapter 25
  {question: "What was the first military action taken by the United States against international communism?", options: ["American soldiers fought against the Red Army during the Russian civil war", "American soldiers fought isolated battles against the Soviet Union during World War II", "The Berlin Airlift", "The Korean War"], answer: 0},
  {question: "Greece and Turkey were early flashpoints in the Cold War. How did the United States respond to unrest in Greece and Turkey in 1947?", options: ["The United States established long range missiles in these nations, capable of reaching Moscow", "The United States sent military advisers to train anti-communist forces in both countries", "The United States actively intervened in Greece but not in Turkey", "The United States sent $400 million to both nations to be used in resisting communism"], answer: 3},
  {question: "What was the purpose of the Marshall Plan?", options: ["Rebuild Western Europe", "Create new markets for American goods", "Generate support for Capitalist democracies", "All of the above"], answer: 3},
  {question: "When was the Atlantic Charter issued?", options: ["After World War I", "Before the United States entered World War II", "After World War II", "When the Soviet Union invaded Korea"], answer: 1},
  {question: "What was the message of NSC-68?", options: ["A warning that the idea of the domino theory may represent a slippery slope commitment that would result in dozens of new wars", "An economic argument for isolationism", "A call for a tripling of the annual defense budget for the purpose of stopping communism", "All of the above"], answer: 2},
  {question: "Who first advocated the policy of containment?", options: ["George Kennan", "Winston Churchill", "Harry Truman", "George Marshall"], answer: 0},
  {question: "Why was Douglas MacArthur removed from command?", options: ["His defensive tactics frustrated an impatient President Truman", "He refused to attack Chinese forces because of a fear of starting World War II", "He was publicly insubordinate to the Commander in Chief", "He refused to recognize the cease-fire"], answer: 2},
  {question: "How did President Eisenhower attempt to prevent a Soviet Attack on the United States?", options: ["By creating a satellite-based missile shield", "Issuing a policy of détente to increase diplomatic cooperation", "By promising “massive retaliation” and appealing to the logic of “mutually-assured destruction”", "All of the above"], answer: 2},
  {question: "Which of the following nations were not a part of the North Atlantic Treaty Organization (NATO)?", options: ["Sweden", "Italy", "England", "France"], answer: 0},
  {question: "Which of the following advantages did the Soviet Union achieve during the Cold War?", options: ["Launched the first orbiting satellite", "Create the first intercontinental ballistic missile", "Sending the first human into orbit", "All of the above"], answer: 3},
  {question: "Joseph McCarthy first achieved national prominence in February 1950 by waving a piece of paper that he claimed included 205 communists currently working in what capacity?", options: ["Hollywood executives", "New York bankers", "Military officers", "Members of the Department of State"], answer: 3},
  {question: "Which of the following most accurately describes religious commitment during the early Cold War years?", options: ["Americans attended church at higher rates than in any time in American history", "The Pledge of Allegiance was modified in 1954", "Anti-Catholicism and Anti-Semitism declined in the United States", "All of the above"], answer: 3},
  {question: "Why did the United States fail to help more of the decolonization independence movements during the 1940s – 1970s?", options: ["The United States did serve as the most active supporter of decolonization independence movements", "The United States was preoccupied with the arms race against the Soviet Union and therefore did not act one way or another during he decolonization struggle", "The Cold War alliance with Western Europe led the United States to support many colonial powers", "The United States was war-weary and an isolationist foreign policy prohibited active intervention for these decades"], answer: 2},
  {question: "Why was the “loss” of China to communism so upsetting to Americans?", options: ["China was the most populous country in the world", "It came just after a successful Soviet atomic bomb test", "Mao overthrew a western-backed government", "All of the above"], answer: 3},
  {question: "All of the following events related to the Korean War are true EXCEPT", options: ["Communist forces took Seoul", "The United Nations established the 38th Parallel as the boundary between North and South Korea", "China sent nearly one million soldiers to repulse the UN-backed attack", "An armistice was never officially signed"], answer: 1},

  // Chapter 26
  {question: "What was the relationship between the federal government and economic growth in the aftermath of World War II?", options: ["Federal spending created more economic growth", "Federal spending slowed economic growth", "Economic growth resulted from less federal spending", "Economic stagnation resulted from less federal spending"], answer: 0},
  {question: "Which of the following enabled the rising purchase of consumer goods?", options: ["Increased production that lowered prices", "Use of installment plans", "Mass-distribution of credit cards", "All of the above"], answer: 3},
  {question: "How did federal housing programs discriminate against Americans of color?", options: ["Redlining neighborhoods that included Americans of color", "Claiming that Americans of color were at a greater risk of defaulting on FHA loans", "Creating self-fulfilling prophecies that racially integrated neighborhoods would have depreciating home values", "All of the above"], answer: 3},
  {question: "What was the result of Brown v. Board of Education?", options: ["Ruled against segregated public schools", "Overturned the legal logic of Plessy v. Ferguson", "Extended the reach of the Fourteenth Amendment", "All of the above"], answer: 3},
  {question: "Who first challenged segregation on buses?", options: ["Mary-Louise Smith", "Rosa Parks", "Sarah Keys", "Emmett Till"], answer: 2},
  {question: "Why was Emmett Till murdered?", options: ["Allegedly whistling at a white woman", "Refusing to give up a bus seat to a white woman", "Sneaking into a movie theater with a white girlfriend", "Protesting segregation in Mississippi public schools"], answer: 0},
  {question: "What did the Civil Rights Act of 1957 accomplish?", options: ["Created a Civil Rights Commission in the Department of Justice to investigate claims of racial discrimination", "Legalized interracial marriage", "Demanded the integration of all public colleges and universities", "All of the above"], answer: 0},
  {question: "Which of the following best describes the marketing techniques of early television executives?", options: ["Finding programming that would appeal to the widest possible audience", "Using targeted regional programming that created different shows for different regions of the country", "Creating new channels to market directly to smaller groups whose attention was particularly desired by advertisers", "Designing programming that appealed primarily to children"], answer: 0},
  {question: "What groups experienced the increased fertility rates associated with the baby boom?", options: ["Wealthy Americans from all racial backgrounds", "White Americans from all economic levels", "Americans of color from all economic levels", "Americans from all racial, social, and class lines"], answer: 3},
  {question: "What was the name of the 1950s counterculture that rejected the values of conformity and domesticity?", options: ["Hippies", "Beats", "Toughs", "Zoot Suiters"], answer: 1},
  {question: "The churches most common in suburban America tended most frequently celebrated which of the following cultural values?", options: ["Social justice", "Economic individualism", "Nonviolence and peacemaking", "Communal unity"], answer: 1},
  {question: "Who were the “Brass Hats?”", options: ["Union leaders who encouraged a new wave of strikes in the 1950s", "Reformers in the Catholic church who tried to highlight American principles already present in ancient church teachings", "The leadership of the National Association of Manufacturers who created advertising campaigns supporting free enterprise.", "Young Americans who grew disenchanted with consumerism and instead embraced artistic creativity as he ultimate end of life"], answer: 2},
  {question: "Which of the following right wing think tanks were created in the first decade following WWII?", options: ["Foundation for Economic Education", "Mont Pelerin Society", "Both of these", "Neither of these"], answer: 2},
  {question: "What is the name of the University of Chicago economist who helped to develop the intellectual position of libertarian economics?", options: ["Leonard Reed", "Jasper Crane", "John Maynard Keynes", "Milton Friedman"], answer: 3},
  {question: "Congressional opposition from which faction plagued Dwight D. Eisenhower’s administration?", options: ["Liberal Democrats", "Conservative Republicans", "Both", "Neither"], answer: 2},

  // Chapter 27
  {question: "Who organized the first sit-ins?", options: ["Churches", "NAACP", "Students", "Members of the Communist Party"], answer: 2},
  {question: "How did the first freedom ride end?", options: ["Angry mobs composed of KKK members attacked the riders in Birmingham, Alabama and burned one of the buses and beat the activists who escaped", "The riders were arrested in Mongomery, Alabama", "The ride was peaceful and ignored by both southerners and northern media", "The ride drew protests and media attention, but there was no violence"], answer: 0},
  {question: "The Albany Movement, centered in Albany, Georgia, drew on Christian commitments to social justice and united all of the following Civil Rights groups EXCEPT", options: ["Student Nonviolent Coordinating Committee", "Southern Christian Leadership Conference", "National Association for the Advancement of Colored People", "The Southern Baptist Convention"], answer: 3},
  {question: "President Johnson proposed the Voting Rights Act of 1965 partially in response to what event in Selma, Alabama", options: ["Bombing of an African American church", "“Bloody Sunday,” the beating of peaceful marchers by police officers", "The jailing of Martin Luther King, Jr.", "The assassination of Malcolm X"], answer: 1},
  {question: "In the mid-1960s, the Student Nonviolent Coordinating Committee (SNCC) experienced a transformation. This transformation included all of the following EXCEPT", options: ["The growing influence of radical leaders like Stokely Carmichael", "The expulsion of all white members", "Merging with the Black Panther Party", "Focus on racial injustice in northern cities"], answer: 2},
  {question: "The Civil Rights Act of 1968 focused on what primary issue", options: ["Desegregating schools", "Protecting voting rights", "Racially integrating the armed forces", "Outlawing discrimination in housing"], answer: 3},
  {question: "The 1968 Democratic National Convention included massive protests and violent reprisals by police. Where did this convention meet?", options: ["Chicago", "Washington D.C.", "Memphis", "Atlanta"], answer: 0},
  {question: "Advertisers in the 1960s innovated by beginning to emphasize which of the following traits as a means of selling products?", options: ["Beauty and sexual attractiveness", "Rebellion and individuality", "Worldliness and intelligence", "All of the above"], answer: 3},
  {question: "Which group first promoted the idea that drug use could remedy feelings of alienation?", options: ["Scientists", "Musicians", "Civil rights activists", "Feminists"], answer: 1},
  {question: "The National Indian Youth Council (NIYC) differed from the National Congress of American Indians (NCAI) because the NIYC", options: ["Emphasized the legal importance of treaty rights", "Employed direct action tactics and more combative rhetoric", "Were more interested in cultural preservation than legal strategies of resistance", "Showed less interest in issues of sovereignty and self-determination"], answer: 1},
  {question: "Betty Friedan’s Feminine Mystique focused on what primary issue", options: ["Employment discrimination based on gender", "Rising incidents of rape and sexual violence", "The problems facing women in poverty", "Feelings of dissatisfaction with life as a housewife"], answer: 3},
  {question: "What was the subject of Rachel Carson’s book Silent Spring?", options: ["Environmental dangers of pesticides", "Threats of nuclear war", "Persistence of sexism in the 1960s", "The role of religion in the Civil Rights movement"], answer: 0},
  {question: "What did Lyndon Johnson call his domestic program?", options: ["Square Deal", "New Frontier", "Great Society", "Fair Deal"], answer: 2},
  {question: "The cornerstone of Lyndon Johnson’s War on Poverty was which program?", options: ["Peace Corp", "Teach for America", "Community Action", "Head Start"], answer: 2},
  {question: "What caused the Cuban Missile Crisis?", options: ["Castro’s invitation to the Soviet Union to install missiles", "Retaliation for the American nuclear arsenal housed in Turkey", "Hostile relations between the United States and Cuba", "All of the above"], answer: 3},

  // Chapter 28
  {question: "How did the United States respond to the independence movement in Vietnam?", options: ["Encouraged independence with the aid of military advisers", "Sent troops to support Vietnamese independence", "Opposed Vietnamese independence and supported French attempts to retain its colonial control", "Avoided the issue because of the spread of isolationism"], answer: 2},
  {question: "All of the following are true about the Gulf of Tonkin incident and the ensuing resolution EXCEPT", options: ["Served as justification for the assassination of Ngo Diem", "Resulted from a minor naval conflict", "The Johnson administration distorted the incident to provide a pretext for escalating American involvement in Vietnam", "The resolution authorized the president to send bombs and troops into Vietnam"], answer: 0},
  {question: "What happened at My Lai?", options: ["The Vietnamese launched the Tet Offensive", "U.S. troops massacred hundreds of civilians", "An American ship was fired upon, leading to the Gulf of Tonkin Resolution", "An American journalist was killed increasing opposition to the war"], answer: 1},
  {question: "What was the intention of the War Powers Resolution?", options: ["Reform the selective service process to prevent draft dodging", "Reduce the president’s ability to wage war without congressional consent", "Fund military expenditures through raising taxes as a means of preventing deficit spending", "Creating regulation to monitor the Military Industrial Complex, heeding the warnings of President Eisenhower"], answer: 1},
  {question: "Roe v. Wade, the court case that legalized abortion hinged on what legal idea?", options: ["Community good", "Sexual liberation", "Feminist equality", "Right of privacy"], answer: 3},
  {question: "The Stonewall incident that catalyzed the gay rights movement occurred when __________", options: ["A prominent gay politician was murdered in San Francisco", "A gay teenager was tortured and murdered in the Midwest", "Bar patrons in New York City protested a police raid", "Media leaders began to focus on the experience of gay and lesbian Americans"], answer: 2},
  {question: "Who was the leader of the movement to stop the Equal Rights Amendment?", options: ["Phylis Schlafly", "Jerry Fallwell", "Betty Friedan", "Richard Nixon"], answer: 0},
  {question: "The Kerner Commission explained urban riots as the result of which of the following", options: ["Poor parenting by African Americans", "The provocation of racist urban police departments", "Black frustration with the hopelessness of urban poverty", "Anger over the failures of the Civil Rights Movement"], answer: 2},
  {question: "How did American liberals change their views of poverty during the 1960s?", options: ["More and more saw poverty from the failure of individuals to take full advantage of the American system", "Economists demonstrated how structural flaws in the national economy limited opportunities in the private sector", "Johnson’s Great Society and its imitators cut government-sponsored job training", "The War on Poverty created over a million new jobs under the oversight of the federal government"], answer: 1},
  {question: "All of the following led to the economic development of the Sun Belt EXCEPT", options: ["Cheap, nonunionized labor, low wages, and lax regulations stole northern industries away from the Rust Belt", "A resurgence in southern agriculture", "Massive federal subsidies, including military spending created new jobs", "The development of modern air conditioning made the climate more tolerable"], answer: 1},
  {question: "What was the “Nixon Doctrine?”", options: ["The use of militarized police forces to end urban riots", "A renewed commitment to send American forces to military conflicts", "A military policy of détente", "Commitment to the domino theory"], answer: 2},
  {question: "What initially sparked the 1973 energy crisis?", options: ["OPEC’s embargo of oil exports to the United States in retaliation for American intervention in the Middle East", "Price manipulation by American oil companies", "Environmental legislation that eliminated old coal-fired power plants", "Public panic over the Watergate scandal"], answer: 0},
  {question: "What was the primary political issue that Carter used in his presidential campaign?", options: ["The reduction of regulation in hopes of kick-starting the economy", "Continuing the progress of the Civil Rights Movement", "Solving the problems of American poverty with a major new federal program", "Carter’s campaign focused less on issues than on his background as a hardworking, honest, Southern Baptist southerner"], answer: 3},
  {question: "Which of the following resulted from American commitments to free trade?", options: ["Rising prices on international goods", "Increased diplomatic conflict with other wealthy nations", "Increased dominance of American exports", "The relocation of American manufacturing overseas"], answer: 3},
  {question: "What was the primary guiding principle of Carter’s foreign policy during his early years in office?", options: ["Realpolitik", "Human rights", "Domino Theory", "Isolationism"], answer: 1},

  // Chapter 29
  {question: "Which of the following phrases best describes “Reagan Democrats?”", options: ["Blue-collar voters who lost faith in the liberal creed", "Southerners who resisted the Civil Rights Act", "A new brand of Democrats who advocated increasingly liberal programs in attempt to oppose Ronald Reagan", "Corporate leaders in the Northeast who traditionally supported Democrats but believed in Reagan’s national security agenda"], answer: 0},
  {question: "How did racism influence the growth of the modern Republican Party?", options: ["Republicans defended white supremacy in their official party platforms", "Democrats took the lead in passing civil rights legislation, pushing many white Americans toward the Republican Party", "Members of the Ku Klux Klan were embraced by the Democratic Party, pushing moderates toward the Republicans", "Richard Nixon’s administration actively recruited black political appointees, creating a backlash against the Republican Party"], answer: 1},
  {question: "The Religious Right built a powerful coalition that united conservative evangelicals with what other influential voting group?", options: ["Jewish Americans", "Conservative Catholics", "Mainline Protestants", "All of the above"], answer: 1},
  {question: "How did Jimmy Carter respond to the economic crises of the late 1970s?", options: ["Proposing a new New Deal in attempt to revitalize American liberalism", "Using approaches championed by conservatives including deregulation, spending cuts, and tax cuts", "Actively encouraging Americans to participate in the consumer economy, believing that Americans needed more encouragement to reignite the consumer economy", "Carter took very little action on economic issues, believing that they would resolve themselves"], answer: 1},
  {question: "How did Ronald Reagan win over the Religious Right?", options: ["Emphasizing his background as a church-goer and Sunday school teacher", "Denouncing abortion and prayer in schools", "Distancing himself from the nation’s racist past by opposing Bob Jones University", "All of the above"], answer: 1},
  {question: "How did Reagan’s first budget immediately impact the national debt?", options: ["The national debt decreased slightly", "The national debt decreased dramatically", "The national debt increased dramatically", "There was little change in the national debt"], answer: 2},
  {question: "The presidential election of 1984 convinced the Democratic Party that its future lied with what group?", options: ["African Americans", "Union members", "Rural voters", "Upwardly mobile professionals and suburbanites"], answer: 3},
  {question: "All of the following aspects of the Tax Reform Act of 1986 are true EXCEPT:", options: ["Increased federal revenues", "Lowered top corporate tax rate from 46% to 34%", "Reduced the highest marginal rate from 50% to 28%", "Simplified the tax code"], answer: 0},
  {question: "Thirty-seven year old white engineer, Bernard Goetz shot and seriously wounded four black teenagers on a subway car because he suspected the young men–armed with screwdrivers–planned to rob him. What percentage of white New Yorkers sympathized with Goetz?", options: ["15%", "33%", "50%", "90%"], answer: 3},
  {question: "Which of the following industries experienced the most economic growth under Reagan?", options: ["Agriculture", "Financial Services", "Manufacturing", "Organized Laborers"], answer: 1},
  {question: "Why was the federal government slow to respond to the AIDS crisis?", options: ["Concerns about the deficit discouraged new research spending", "The disease was portrayed as an international problem, not an American problem", "The issue disproportionately affected gay Americans, a marginalized group", "The surgeon general opposed allocating research funding, believing that it would be better used to fight cancer"], answer: 2},
  {question: "Which of the following best describes the “Reagan Doctrine?”", options: ["The United States committed to supplying aid to anti-communist forces everywhere in the world", "The importance of triangulation to play communist nations off of one another", "A commitment to détente", "Avoiding international engagement in favor of domestic economic investment"], answer: 0},
  {question: "Which of the following statements regarding the Iran Contra Affair are true?", options: ["The project was authorized by the 1984 Boland Amendment", "The goal was the raise money to support the anti-Sandinista government in Nicaragua", "Reagan escaped prosecution despite proof that he authorized the operation", "All of the above"], answer: 1},
  {question: "Which leader of the Soviet Union advocated the projects of glasnost and perestroika?", options: ["Leonid Brezhnev", "Yuri Andropov", "Konstantin Chernenko", "Mikhail Gorbachev"], answer: 3},
  {question: "The Dow Jones Industrial Average–which stood at 950 in 1981–reached _______ by the end of Reagan’s second term.", options: ["1,893", "2,239", "2,947", "3,927"], answer: 1}
];
 
  const startBtn = document.getElementById('start-btn');
  const quizDiv = document.getElementById('quiz');
  const nextBtn = document.getElementById('next-btn');
  const submitBtn = document.getElementById('submit-btn');
  const restartBtn = document.getElementById('restart-btn');
  const scoreDiv = document.getElementById('score-container');

  let currentQuestion = 0;
  let answersGiven = new Array(quizData.length).fill(null); // store user answers

  function loadQuestion() {
    nextBtn.disabled = true;
    submitBtn.disabled = false;
    scoreDiv.style.display = 'none';
    quizDiv.style.display = 'block';
    nextBtn.style.display = 'inline-block';
    submitBtn.style.display = 'inline-block';
    restartBtn.style.display = 'none';
   
    const q = quizData[currentQuestion];
    let html = `<h2>Q${currentQuestion + 1}. ${q.question}</h2>`;
    q.options.forEach((opt, i) => {
      // If user already answered this question, pre-select it
      const checked = answersGiven[currentQuestion] === i ? 'checked' : '';
      html += `<label><input type="radio" name="answer" value="${i}" ${checked}> ${opt}</label>`;
    });
    quizDiv.innerHTML = html;

    document.querySelectorAll('input[name="answer"]').forEach(input => {
      input.addEventListener('change', () => {
        nextBtn.disabled = false;
        // Save answer for this question
        answersGiven[currentQuestion] = parseInt(input.value);
      });
    });
      nextBtn.disabled = answersGiven[currentQuestion] === null;
  }

  function showReview() {
    quizDiv.style.display = 'none';
    nextBtn.style.display = 'none';
    submitBtn.style.display = 'none';
     restartBtn.style.display = 'inline-block';
    scoreDiv.style.display = 'block';

    let score = 0;
    let reviewHTML = `<h2>Quiz Review</h2>`;

    quizData.forEach((q, index) => {
      const userAnswer = answersGiven[index];
      const correctAnswer = q.answer;
      const questionNumber = index + 1;

      reviewHTML += `<div class="review-question"><strong>Q${questionNumber}. ${q.question}</strong><br>`;

       if (userAnswer === null) {
        reviewHTML += `<p class="unanswered">You did not answer this question.</p>`;
        reviewHTML += `<p class="correct">Correct answer: ${q.options[correctAnswer]}</p>`;
      } else if (userAnswer === correctAnswer) {
        score++;
        reviewHTML += `<p class="correct">Your answer: ${q.options[userAnswer]} (Correct)</p>`;
      } else {
        reviewHTML += `<p class="wrong">Your answer: ${q.options[userAnswer]} (Incorrect)</p>`;
        reviewHTML += `<p class="correct">Correct answer: ${q.options[correctAnswer]}</p>`;
      }

      reviewHTML += `</div>`;
    });

    reviewHTML = `<p>You scored ${score} out of ${quizData.length} (${Math.round(score / quizData.length * 100)}%)</p>` + reviewHTML;
    scoreDiv.innerHTML = reviewHTML;
  }

   function resetQuiz() {
    currentQuestion = 0;
    answersGiven = new Array(quizData.length).fill(null);
    scoreDiv.style.display = 'none';
    quizDiv.style.display = 'none';
    nextBtn.style.display = 'none';
    submitBtn.style.display = 'none';
    restartBtn.style.display = 'none';
    startBtn.style.display = 'inline-block';
   }
 
 startBtn.onclick = () => {
    startBtn.style.display = 'none';
    loadQuestion();
  };

  nextBtn.onclick = () => {
    if (answersGiven[currentQuestion] === null) return; // no answer selected

    currentQuestion++;
    if (currentQuestion < quizData.length) {
      loadQuestion();
      // Disable next button if question not answered yet (or enable if answer saved)
      nextBtn.disabled = answersGiven[currentQuestion] === null;
    } else {
      showReview();
    }
  };

  submitBtn.onclick = () => {
    // Just show review with whatever answers user has so far
    showReview();
    };

  restartBtn.onclick = () => {
    resetQuiz();
  };
});
</script>

</body>
</html>
