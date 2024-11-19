package checker;






import java.util.Scanner;
import java.util.concurrent.ThreadLocalRandom;



public class cac {


    public static String player[] = {"name", "character", "Max health", "atack", "defence", "money", "health", "rangedatack", "magicatack", "maxmana", "mana"
            , "poisonatack", "healthdrain", "agility", "manaregen", "healthregen", "stamina", "staminaregen", "healthdrainchanse", "race", "maxstamina"};


    public static String playerhelmet[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerchestarmor[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerlegarmors[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerarmarmors[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerlefthand[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerrighthand[] = {"empty","category","affecttype","affect","hand","empty"};

    public static String playerbody[][] = {playerhelmet,playerchestarmor,playerarmarmors,playerlegarmors,playerrighthand,playerlefthand};

    /*oyun ayarlari elave et,save inventory dificuty                   */
    public static String item1[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item2[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item3[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item4[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item5[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item6[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item7[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String item8[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String inventory[][]= {item1,item2,item3,item4,item5,item6,item7,item8};


    public static String slime[] = {"Slime","12","4","0","5","live","new"};

    static String element1[]= {"1","1","3","4","5","6","7"};

    static String element2[]= {"1","2","3","4","5","6","7"};

    static String element3[]= {"1","2","3","4","5","6","7"};

    static String elements[][]= {element1,element2,element3};


    public static String[] oldsword = {"Old sword","sword","atackbuff","4","onehanded"};
    public static String oldswordprice[] = {"20","10"};

    public static String ordinarysword[] = {"Ordinary sword","sword","atackbuff","5","onehanded"};
    public static String ordinaryswordprice[] = {"30","15"};//100 items add

    public static String ordinarybow[] = {"Ordinary bow","bow","rangedatackbuff","4","onehanded"};
    public static String ordinarybowprice[] = {"40","20"};

    public static String ordinaryaxe[] = {"Ordinary axe","axe","atackbuff","6","onehanded"};
    public static String ordinaryaxeprice[] = {"10","5"};

    public static String[] shieldOfValor = {"Shield of Valor", "shield", "defensebuff", "3","onehanded"};
    public static String[] shieldOfValorPrice = {"25", "15"};

    public static String[] flamebow = {"Flamebow", "bow", "rangedatackbuff", "5","onehanded"};
    public static String[] flamebowPrice = {"30", "12"};

    public static String[] mysticAmulet = {"Mystic Amulet", "amulet", "magicatackbuff", "2","onehanded"};
    public static String[] mysticAmuletPrice = {"15", "5"};

    public static String[] godhelmet = {"Demon helmet", "helmet", "defencebuff", "4", "onehanded"};
    public static String[] godhelmetprice = {"50", "25"};

    public static String[] dragonGauntlets = {"Dragon gauntlets", "armarmors", "attackbuff", "5", "onehanded"};
    public static String[] dragonGauntletsPrice = {"20", "10"};

    public static String[] phoenixBoots = {"Phoenix boots", "legarmors", "agilitybuff", "3", "onehanded"};
    public static String[] phoenixBootsPrice = {"50", "25"};

    public static String[] vampireCloak = {"Vampire cloak", "cloak", "agilitybuff", "2", "none"};
    public static String[] vampireCloakPrice = {"50", "25"};

    public static String[] mageRobe = {"Mage robe", "chestarmor", "magicbuff", "4", "twohanded"};
    public static String[] mageRobePrice = {"220", "110"};

    public static String[] rogueMask = {"Rogue mask", "helmet", "agilitybuff", "3", "onehanded"};
    public static String[] rogueMaskPrice = {"160", "80"};

    public static String[] knightPlate = {"Knight plate", "chestarmor", "defencebuff", "12", "twohanded"};
    public static String[] knightPlatePrice = {"350", "175"};

    public static String[] archerGloves = {"Archer gloves", "armarmors", "agilitybuff", "2", "onehanded"};
    public static String[] archerGlovesPrice = {"90", "45"};

    public static String[] berserkerBoots = {"Berserker boots", "legarmors", "atackbuff", "7", "onehanded"};
    public static String[] berserkerBootsPrice = {"200", "100"};

    public static String[] elementalShield = {"Elemental shield", "shield", "defencebuff", "5", "twohanded"};
    public static String[] elementalShieldPrice = {"280", "140"};

    public static String[] specterHood = {"Specter hood", "helmet", "agility", "4", "onehanded"};
    public static String[] specterHoodPrice = {"175", "87"};

    public static String[] barbarianChest = {"Barbarian chest", "chestarmor", "defencebuff", "8", "twohanded"};
    public static String[] barbarianChestPrice = {"300", "150"};

    public static String[] thiefsGloves = {"Thief's gloves", "armarmors", "healthbuff", "2", "onehanded"};
    public static String[] thiefsGlovesPrice = {"120", "60"};

    public static String[] guardianGreaves = {"Guardian greaves", "legarmors", "defencebuff", "6", "onehanded"};
    public static String[] guardianGreavesPrice = {"150", "75"};

    public static String[] wizardHat = {"Wizard hat", "helmet", "magicatackbuff", "3", "onehanded"};
    public static String[] wizardHatPrice = {"130", "65"};

    public static String[] lancerArmor = {"Lancer armor", "chestarmor", "defencebuff", "10", "twohanded"};
    public static String[] lancerArmorPrice = {"320", "160"};

    public static String[] ninjaMask = {"Ninja mask", "helmet", "agility", "4", "onehanded"};
    public static String[] ninjaMaskPrice = {"160", "80"};

    public static String[] paladinGauntlets = {"Paladin gauntlets", "armarmors", "defencebuff", "5", "onehanded"};
    public static String[] paladinGauntletsPrice = {"140", "70"};

    public static String[] cavalierBoots = {"Cavalier boots", "armarmors", "agilitybuff", "3", "onehanded"};
    public static String[] cavalierBootsPrice = {"110", "55"};

    public static String[] druidRobe = {"Druid robe", "chestarmor", "magicatackbuff", "4", "twohanded"};
    public static String[] druidRobePrice = {"210", "105"};

    public static String[] shadowCloak = {"Shadow cloak", "chestarmor", "agilitybuff", "6", "none"};
    public static String[] shadowCloakPrice = {"300", "150"};

    public static String[] frostHelm = {"Frost helmet", "helmet", "healthbuff", "5", "onehanded"};
    public static String[] frostHelmPrice = {"180", "90"};

    public static String[] infernoArmor = {"Inferno armor", "chestarmor", "defencebuff", "10", "twohanded"};
    public static String[] infernoArmorPrice = {"330", "165"};

    public static String[] mysticGloves = {"Mystic gloves", "armarmors", "magicatackbuff", "3", "onehanded"};
    public static String[] mysticGlovesPrice = {"130", "65"};

    public static String[] falconBoots = {"Falcon boots", "legarmors", "agilitybuff", "4", "onehanded"};
    public static String[] falconBootsPrice = {"160", "80"};

    public static String[] titanShield = {"Titan shield", "shield", "defencebuff", "8", "twohanded"};
    public static String[] titanShieldPrice = {"300", "150"};

    public static String[] crimsonMask = {"Crimson mask", "helmet", "atackbuff", "6", "onehanded"};
    public static String[] crimsonMaskPrice = {"180", "90"};

    public static String[] giantsBreastplate = {"Giant's breastplate", "chestarmor", "defencebuff", "12", "twohanded"};
    public static String[] giantsBreastplatePrice = {"400", "200"};

    public static String[] assassinsGloves = {"Assassin's gloves", "armarmors", "stealth", "4", "onehanded"};
    public static String[] assassinsGlovesPrice = {"150", "75"};

    public static String[] swiftfootSandals = {"Swiftfoot sandals", "legarmors", "agilitybuff", "5", "onehanded"};
    public static String[] swiftfootSandalsPrice = {"130", "65"};

    public static String[] eldritchWard = {"Eldritch ward", "shield", "magicbuff", "9", "twohanded"};
    public static String[] eldritchWardPrice = {"290", "145"};

    public static String[] beastlyHelm = {"Beastly helm", "helmet", "atackbuff", "8", "onehanded"};
    public static String[] beastlyHelmPrice = {"190", "95"};

    public static String[] titaniumChest = {"Titanium chest", "chest", "defencebuff", "14", "twohanded"};
    public static String[] titaniumChestPrice = {"450", "225"};

    public static String[] fingersOfFate = {"Fingers of Fate", "armarmors", "magicatackbuff", "10", "onehanded"};
    public static String[] fingersOfFatePrice = {"80", "40"};

    public static String[] celerityBoots = {"Celerity boots", "legarmors", "agilitybuff", "6", "onehanded"};
    public static String[] celerityBootsPrice = {"150", "75"};

    public static String[] arcaneWard = {"Arcane ward", "shield", "magicatackbuff", "9", "twohanded"};
    public static String[] arcaneWardPrice = {"300", "150"};

    public static String[] golemMask = {"Golem mask", "helmet", "defencebuff", "7", "onehanded"};
    public static String[] golemMaskPrice = {"180", "90"};

    public static String[] celestialArmor = {"Celestial armor", "chestarmor", "magicatackbuff", "11", "twohanded"};
    public static String[] celestialArmorPrice = {"360", "180"};

    public static String[] spikedGloves = {"Spiked gloves", "armarmors", "atackbuff", "5", "onehanded"};
    public static String[] spikedGlovesPrice = {"140", "70"};

    public static String[] ghostwalkerBoots = {"Ghostwalker boots", "legarmors", "agilitybuff", "5", "onehanded"};
    public static String[] ghostwalkerBootsPrice = {"120", "60"};

    public static String[] ironcladShield = {"Ironclad shield", "shield", "defencebuff", "10", "twohanded"};
    public static String[] ironcladShieldPrice = {"280", "140"};

    public static String[] eagleHelm = {"Eagle helm", "helmet", "agilitybuff", "4", "onehanded"};
    public static String[] eagleHelmPrice = {"160", "80"};//create armor sets


    public static String generalitems[][] = {oldsword,oldswordprice,ordinarysword,ordinaryswordprice,ordinarybow,ordinarybowprice,ordinaryaxe,ordinaryaxeprice};


    public static String shopitems[][] = {ordinarysword,ordinaryswordprice,ordinarybow,ordinarybowprice,ordinaryaxe,ordinaryaxeprice};


    public static String shopmenuelement1[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenuelement2[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenuelement3[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenuelement4[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenuelement5[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenuelement6[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String shopmenu[][] = {shopmenuelement1,shopmenuelement2,shopmenuelement3,shopmenuelement4,shopmenuelement5,shopmenuelement6};


    public static String shopmenupriceelement1[]= {"1","1"};

    public static String shopmenupriceelement2[]= {"1","1"};

    public static String shopmenupriceelement3[]= {"1","1"};

    public static String shopmenupriceelement4[]= {"1","1"};

    public static String shopmenupriceelement5[]= {"1","1"};

    public static String shopmenupriceelement6[]= {"1","1"};

    public static String shopmenuprice[][] = {shopmenupriceelement1,shopmenupriceelement2,shopmenupriceelement3,shopmenupriceelement4,shopmenupriceelement5,shopmenupriceelement6};



    public static String merchantitems[][] = {ironcladShield,ironcladShieldPrice,fingersOfFate,fingersOfFatePrice,knightPlate,knightPlatePrice};


    public static String merchantmenuelement1[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String merchantmenupriceelement1[]= {"1","1"};

    public static String merchantmenuelement2[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String merchantmenupriceelement2[]= {"1","1"};

    public static String merchantmenuelement3[]= {"Definition","category","affecttype","affect","hand","empty"};

    public static String merchantmenupriceelement3[]= {"1","1"};

    public static String merchantmenu[][] = {merchantmenuelement1,merchantmenupriceelement1,merchantmenuelement2,merchantmenupriceelement2,merchantmenuelement3,merchantmenupriceelement3};



    public static String gainselement[]= {"O","s","a","h","g"};

    public static String gains[][]= {gainselement,null,null};


    public static String swordsmanpassivatack[]= {"week","stamina","10","100"};

    public static String swordsmannormalatack[]= {"normal","stamina","20","85"};

    public static String swordsmanagressivatack[]= {"agressiv","stamina","40","50"};

    public static String sawordsmanallatack[][]= {swordsmanpassivatack,swordsmannormalatack,swordsmanagressivatack};


    public static String bowmanpassivatack[]= {"week","stamina","10","100"};

    public static String bowmannormalatack[]= {"normal","stamina","20","85"};

    public static String bowmanagressivatack[]= {"agressiv","stamina","40","50"};

    public static String bowmanallatack[][]= {bowmanpassivatack,bowmannormalatack,bowmanagressivatack};


    public static String axepassivatack[]= {"week atack","stamina","10","100"};

    public static String axenormalatack[]= {"normal atack","stamina","20","85"};

    public static String axeagressivatack[]= {"agressiv atack","stamina","40","50"};

    public static String axeallatack[][]= {axepassivatack,axenormalatack,axeagressivatack};


    public static String magicianpassivatack[]= {"tiny fireball","mana","10","100"};

    public static String magiciannormalatack[]= {"linghtning","mana","20","85"};

    public static String magicianagressivatack[]= {"big something","mana","40","50"};

    public static String magicianallatack[][]= {magicianpassivatack,magiciannormalatack,magicianagressivatack};


    public static String selectedpassivatack[]= {"w","s","1","1"};

    public static String selectednormalatack[]= {"w","s","1","1"};

    public static String selectedagressivatack[]= {"w","s","1","1"};

    public static String selectedallatack[][]= {selectedpassivatack,selectednormalatack,selectedagressivatack};


    public static int merchantvar=1;


    public static void selectatackstyle(String i[][]) {
        for (int j = 0; j < 3; j++) {
            for (int j2 = 0; j2 < 4; j2++) {
                selectedallatack[j][j2]=i[j][j2];
            }
        }
    }
    public static void character(int i) {

        switch(i) {
            case 1:
                player[1]="Bowman";
                player[2]="20";
                player[3]="0";
                player[4]="0";
                player[5]="25";
                player[6]="20";
                player[7]="10";
                player[8]="0";
                player[9]="50";
                player[10]="50";
                player[11]="0";
                player[12]="0";
                player[13]="10";
                player[14]="1";
                player[15]="1";
                player[16]="100";
                player[17]="5";
                player[18]="0";
                player[20]="100";
                selectatackstyle(bowmanallatack);
                break;
            case 2:
                player[1]="Swordman";
                player[2]="30";
                player[3]="4";
                player[4]="3";
                player[5]="25";
                player[6]="30";
                player[7]="0";
                player[8]="0";
                player[9]="50";
                player[10]="50";
                player[11]="0";
                player[12]="0";
                player[13]="0";
                player[14]="1";
                player[15]="1";
                player[16]="100";
                player[17]="5";
                player[18]="0";
                player[20]="100";
                selectatackstyle(sawordsmanallatack);
                break;
            case 3:
                player[1]="Axeman";
                player[2]="20";
                player[3]="15";
                player[4]="0";
                player[5]="25";
                player[6]="20";
                player[7]="0";
                player[8]="0";
                player[9]="50";
                player[10]="50";
                player[11]="0";
                player[12]="0";
                player[13]="10";
                player[14]="1";
                player[15]="1";
                player[16]="100";
                player[17]="5";
                player[18]="0";
                player[20]="100";
                selectatackstyle(axeallatack);
                break;
            case 4:
                player[1]="Magician";
                player[2]="20";
                player[3]="0";
                player[4]="0";
                player[5]="25";
                player[6]="20";
                player[7]="0";
                player[8]="10";
                player[9]="100";
                player[10]="100";
                player[11]="0";
                player[12]="0";
                player[13]="10";
                player[14]="5";
                player[15]="1";
                player[16]="50";
                player[17]="1";
                player[18]="0";
                player[20]="50";
                selectatackstyle(magicianallatack);
                break;
            default:
                System.out.println();
                System.out.println("Wrong operator");
                System.out.println();
        }


    }

    public static void equipe(int a) {
        if(inventory[a-1][5].equals("ful")) {
            if(inventory[a-1][1].equals("helmet")) {
                equipevol2("helmet",inventory[a-1],a);
            }else if(inventory[a-1][1].equals("chestarmor")) {
                equipevol2("chestarmor",inventory[a-1],a);
            }else if(inventory[a-1][1].equals("legarmors")) {
                equipevol2("legarmors",inventory[a-1],a);
            }else if (inventory[a-1][1].equals("armarmors")) {
                equipevol2("armarmors",inventory[a-1],a);
            }else if (inventory[a-1][1].equals("sword")||inventory[a-1][1].equals("bow")||inventory[a-1][1].equals("axe")||inventory[a-1][1].equals("shield")||inventory[a-1][1].equals("amulet")
                    ||inventory[a-1][1].equals("gauntlets")||inventory[a-1][1].equals("fang")||inventory[a-1][1].equals("cloak")||inventory[a-1][1].equals("scythe")
                    ||inventory[a-1][1].equals("ring")||inventory[a-1][1].equals("hammer")||inventory[a-1][1].equals("dagger")||inventory[a-1][1].equals("staff")||inventory[a-1][1].equals("orb")
                    ||inventory[a-1][1].equals("claw")||inventory[a-1][1].equals("culdran")||inventory[a-1][1].equals("club")||inventory[a-1][1].equals("wand")
                    ||inventory[a-1][1].equals("crossbow")||inventory[a-1][1].equals("scepter")||inventory[a-1][1].equals("bracers")||inventory[a-1][1].equals("chalice")
            ) {
                equipevol2(inventory[a-1][1],inventory[a-1],a);
            }
        }else {
            System.out.println("You don't have equipable element");
        }



    }
    public static void buff(String op[]) {

        String a=op[2];
        String regex = "[,\\.\\s]";

        String[] myArray = a.split(regex);

        String[] myArray1 = op[3].split(regex);

        int count=0;
        for (String string : myArray) {

            if(string.equals("atackbuff")) {
                player[3]=String.valueOf(Integer.parseInt(player[3])+Integer.parseInt(myArray1[count]));

            }else if(string.equals("defencebuff")) {
                player[4]=String.valueOf(Integer.parseInt(player[4])+Integer.parseInt(myArray1[count]));

            }else if(string.equals("healthbuff")) {
                player[2]=String.valueOf(Integer.parseInt(player[2])+Integer.parseInt(myArray1[count]));

            }else if(string.equals("rangedatackbuff")) {
                player[7]=String.valueOf(Integer.parseInt(player[7])+Integer.parseInt(myArray1[count]));

            }else if(string.equals("magicatackbuff")) {
                player[8]=String.valueOf(Integer.parseInt(player[8])+Integer.parseInt(myArray1[count]));

            }else if(string.equals("agilitybuff")) {
                player[13]=String.valueOf(Integer.parseInt(player[13])+Integer.parseInt(myArray1[count]));

            }
            count++;}
        player[6]=player[2];
        player[10]=player[9];
        player[16]=player[20];
        System.out.println(op[0]+" equiped");
    }
    public static void equipevol2(String i,String op[],int a) {
        if(i.equals("helmet")) {
            if(playerhelmet[5].equals("empty")) {
                int c=op.length;
                int b=0;
                while (b<c) {
                    playerhelmet[b]=op[b];
                    b++;
                }

                int con=0;
                while (con<inventory.length) {
                    if (con==a-1) {
                        inventory[con][5]="empty";
                    }

                    con++;}}else {
                unequipeinequipe(playerhelmet, i, a);
            }

            buff(op);


        }else if(i.equals("chestarmor")) {
            if(playerchestarmor[5].equals("empty")) {
                int c=op.length;
                int b=0;
                while (b<c) {
                    playerchestarmor[b]=op[b];
                    b++;
                }

                int con=0;
                while (con<inventory.length) {
                    if (con==a-1) {
                        inventory[con][5]="empty";
                    }

                    con++;}}else {
                unequipeinequipe(playerchestarmor, i, a);
            }

            buff(op);

        }else if(i.equals("legarmors")) {
            if(playerlegarmors[5].equals("empty")) {
                int c=op.length;
                int b=0;
                while (b<c) {
                    playerlegarmors[b]=op[b];
                    b++;
                }

                int con=0;
                while (con<inventory.length) {
                    if (con==a-1) {
                        inventory[con][5]="empty";
                    }

                    con++;}}else {
                unequipeinequipe(playerlegarmors, i, a);
            }

            buff(op);

        }else if (i.equals("armarmors")) {
            if(playerarmarmors[5].equals("empty")) {
                int c=op.length;
                int b=0;
                while (b<c) {
                    playerarmarmors[b]=op[b];
                    b++;
                }

                int con=0;
                while (con<inventory.length) {
                    if (con==a-1) {
                        inventory[con][5]="empty";
                    }

                    con++;}}else {
                unequipeinequipe(playerarmarmors, i, a);
            }

            buff(op);

        }else if (i.equals("sword")||i.equals("bow")||i.equals("axe")) {
            if(op[4].equals("onehanded")) {
                if(playerlefthand[5].equals("empty")) {
                    int c=op.length;
                    int b=0;
                    while (b<c) {
                        playerlefthand[b]=op[b];
                        b++;
                    }

                    int con=0;
                    while (con<inventory.length) {
                        if (con==a-1) {
                            inventory[con][5]="empty";
                        }

                        con++;}

                    buff(op);
                    playerlefthand[5]="ful";
                }else if(playerrighthand[5].equals("empty")){

                    int c=op.length;
                    int b=0;
                    while (b<c) {
                        playerrighthand[b]=op[b];
                        b++;
                    }

                    int con=0;
                    while (con<inventory.length) {
                        if (con==a-1) {
                            inventory[con][5]="empty";
                        }

                        con++;}
                    playerrighthand[5]="ful";
                    buff(op);
                    //unequipe yigilma var
                }else {
                    unequipeinequipe(playerlefthand,i,a);
                }

            }else if(op[4].equals("twohanded")) {
                if(playerlefthand[5].equals("empty")&&playerrighthand[5].equals("empty")) {
                    int c=op.length;
                    int b=0;
                    while (b<c) {
                        playerlefthand[b]=op[b];
                        b++;
                    }

                    int con=0;
                    while (con<inventory.length) {
                        if (con==a-1) {
                            inventory[con][5]="empty";
                        }

                        con++;}}else {
                    unequipeinequipe(playerlefthand,i,a);
                }//burada problem olacaq
                playerlefthand[5]="ful";
                playerrighthand[5]="ful";
                buff(op);
            }
        }


    }
    public static void debuffinequipe(String op[]) {
        String a=op[2];
        String regex = "[,\\.\\s]";

        String[] myArray = a.split(regex);

        String[] myArray1 = op[3].split(regex);

        int count=0;
        for (String string : myArray) {

            if(string.equals("atackbuff")) {
                player[3]=String.valueOf(Integer.parseInt(player[3])-Integer.parseInt(myArray1[count]));

            }else if(string.equals("defencebuff")) {
                player[4]=String.valueOf(Integer.parseInt(player[4])-Integer.parseInt(myArray1[count]));

            }else if(string.equals("healthbuff")) {//bura bax
                player[2]=String.valueOf(Integer.parseInt(player[2])-Integer.parseInt(myArray1[count]));

            }else if(string.equals("rangedatackbuff")) {//bura bax
                player[7]=String.valueOf(Integer.parseInt(player[7])-Integer.parseInt(myArray1[count]));

            }else if(string.equals("magicatackbuff")) {//bura bax
                player[8]=String.valueOf(Integer.parseInt(player[8])-Integer.parseInt(myArray1[count]));

            }else if(string.equals("agilitybuff")) {
                player[13]=String.valueOf(Integer.parseInt(player[13])-Integer.parseInt(myArray1[count]));

            }
            count++;}
        player[6]=player[2];
        player[10]=player[9];
        player[16]=player[20];
        System.out.println(op[0]+" equiped");
    }

    public static void unequipeinequipe(String op[],String i,int n) {
        String a[]= {"O","s","a","h","g"};
        int c=op.length-1;
        int b=0;
        while (b<c) {
            a[b]=op[b];
            b++;
        }

        playerlefthand[5]="empty";
        debuffinequipe(op);
        equipevol2(i, op, n);
        inventoryinwithoutplace(a, 1);
        home();

    }
    public static void unequipe(String op[],int n) {
        if(op[5].equals("ful")) {
            String a[]= {"O","s","a","h","g"};
            int c=op.length-1;
            int b=0;
            while (b<c) {
                a[b]=op[b];
                b++;
            }

            op[5]="empty";
            op[0]="empty";
            debuffinequipe(op);
            inventoryinwithoutplace(a, 1);
            home();}
        System.out.println("There is no element");
        System.out.println();
        home();
    }
    public static void showinventory() {
        for(int i=0;i<inventory.length;i++) {
            if(inventory[i][5].equals("ful")) {
                System.out.println(i+1+"."+inventory[i][0]);
                System.out.println();
            }
        }
        System.out.println();
        System.out.println("What do you want?");
        System.out.println("1.Equipe item"+"\n"+"2.Remove item from inventory"+"\n"+"3.Unequipe item"+"\n"+"4.Exit");
        try(Scanner scanner = new Scanner(System.in)){
            int a=scanner.nextInt();
            if(a==1) {
                System.out.println("Select item");
                int b=scanner.nextInt();
                equipe(b);
                home();
            }else if(a==2) {
                inventoryremove();
            }else if(a==3) {
                System.out.println("Select item");
                showplayerbody();//print playerbody
                int c=scanner.nextInt();
                unequipe(playerbody[c-1],c);//bura bax
            }else if(a==4) {
                home();
            }

        }

    }
    public static void showplayerbody() {
        System.out.println();
        System.out.println("1.Helmet: "+playerbody[0][0]);
        System.out.println();
        System.out.println("2.Chest armor: "+playerbody[1][0]);
        System.out.println();
        System.out.println("3.Arm armors: "+playerbody[2][0]);
        System.out.println();
        System.out.println("4.Leg armors: "+playerbody[3][0]);
        System.out.println();
        System.out.println("5.Right hand: "+playerbody[4][0]);
        System.out.println();
        System.out.println("6.Left hand: "+playerbody[5][0]);
        System.out.println();
    }
    public static void inventoryinwithoutplace(String i[],int cs) {
        int con=0;
        int count=0;
        int tfgies=0;
        while (tfgies<cs) {
            while (con<inventory.length) {
                if(inventory[con][5].equals("empty")) {
                    inventory[con][5]="ful";
                    count++;
                    int x=0;

                    while(x<5) {
                        inventory[con][x]=i[x];
                        x++;
                    }

                    break;}
                con++;
            }
            if (count==0) {
                System.out.println("Your inventory is ful");
                System.out.println("1.Throw away the item"+"\n"+"2.Remove item from inventory");
                try(Scanner scanner = new Scanner(System.in)){
                    int a=scanner.nextInt();
                    if(a==1) {
                        System.out.println(i[0] +" was thrown away");
                    }else if(a==2) {
                        itemremove(i);
                    }else {
                        System.out.print("Wrong operator");
                    }

                }}
            tfgies++;
        }

    }
    public static void inventoryin(String i[],int cs) {
        int con=0;
        int count=0;
        int tfgies=0;
        while (tfgies<cs) {
            while (con<inventory.length) {
                if(inventory[con][5].equals("empty")) {
                    inventory[con][5]="ful";
                    count++;
                    int x=0;

                    while(x<5) {
                        inventory[con][x]=i[x];
                        x++;
                    }

                    break;}
                con++;
            }
            if (count==0) {
                System.out.println("Your inventory is ful");
                System.out.println("1.Throw away the item"+"\n"+"2.Remove item from inventory");
                try(Scanner scanner = new Scanner(System.in)){
                    int a=scanner.nextInt();
                    if(a==1) {
                        System.out.println(i[0] +" was thrown away");
                    }else if(a==2) {
                        itemremove(i);
                    }else {
                        System.out.print("Wrong operator");
                    }

                }}
            tfgies++;
        }
        place();

    }
    public static void itemremove(String sa[]) {
        System.out.println("Select the item to delete");
        for(int i=0;i<inventory.length;i++) {
            System.out.println(i+1+"."+inventory[i][0]);
        }
        try(Scanner scanner = new Scanner(System.in)){
            int a=scanner.nextInt();
            int con=0;
            while (con<inventory.length) {
                if (con==a) {
                    inventory[con][5]="empty";
                }

                con++;}
        }
        inventoryin(sa,1);
    }
    public static void inventoryremove() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("Select the item to delete");
            int a=scanner.nextInt();

            int con=0;
            while (con<inventory.length) {
                if (a==con+1) {
                    inventory[con][5]="empty";
                }
                con++;
            }
            System.out.println("item deleted");
            System.out.println();

            home();}
    }

    public static void fightdeep(int i,String monster[]) {
        int hul=0;
        int x=0;
        switch(i) {
            case 1:
                while(hul<1) {
                    x=0;

                    while(x<7) {
                        elements[hul][x]=monster[x];
                        x++;
                    }
                    hul++;
                };
                break;
            case 2:
                hul=0;
                while(hul<2) {
                    x=0;

                    while(x<7) {
                        elements[hul][x]=monster[x];
                        x++;
                    }
                    hul++;
                };

                break;
            case 3:
                hul=0;
                while(hul<3) {
                    x=0;
                    while(x<7) {
                        elements[hul][x]=monster[x];
                        x++;

                    }
                    hul++;
                };
                break;

        }

        fightscreen(i);
    }
    public static void Win() {
        int countrand1 = ThreadLocalRandom.current().nextInt(1, 101);
        if (countrand1>95){
            merchantvar=1;
        }else {
           merchantvar=0;
        }
        player[10]=player[9];
        player[16]=player[20];
        int i=3;
        int count=0;
        int count1=0;
        for (int h=0;h<i;h++) {
            if(elements[h][5].equals("death")&&elements[h][6].equals("new")) {
                count++;

                int countrand = ThreadLocalRandom.current().nextInt(1, 101);
                if (countrand>50) {
                    count1++;
                }
            }}
        player[5]=String.valueOf(Integer.parseInt(player[5])+count*Integer.parseInt(elements[0][4]));
        String str="You gain "+String.valueOf(count*Integer.parseInt(elements[0][4]))+" gold";
        System.out.println();
        System.out.println(str);
        System.out.println();
        i=4;
        for (int s=0;s<i;s++) {
            if(elements[s][5].equals("death")&&elements[s][6].equals("new")) {
                elements[s][6]="old";
                i=i-1;
            }}
        String stry=count1+" "+gains[0][0];
        if (count1==1) {
            System.out.println(stry);
            System.out.println();
            inventoryin(gains[0],1);
            //inventory guncelle
        }else if(count1==2) {
            System.out.println(stry);
            System.out.println();
            inventoryin(gains[0],2);
        }
        else if(count1==3) {
            System.out.println(stry);
            System.out.println();
            inventoryin(gains[0],3);
        }else if(count1==0) {

            System.out.println(stry);
            System.out.println();}





    }
    public static void fightscreen(int i) {

        if (Integer.parseInt(player[6])>Integer.parseInt(player[2])+1) {
            player[6]=player[2];//player health problem swordman
        }
        playerstats();
        System.out.println();
        for(int h=0;h<i;h++) {
            monsterstats(elements[h]);
            System.out.println();
        }
        if(i==0) {

            System.out.println("Win");
            Win();
            playerstats();


            place();
        }else if(Integer.parseInt(player[6])<1){
            playerstats();
            gameover();
        }else {
            fight(i);}
    }
    public static void fight(int i) {// create atack Type that it has own requriemants
        int atackcount=0;
        try(Scanner scanner = new Scanner(System.in)){
            int playeratack=Integer.parseInt(player[3])+Integer.parseInt(player[7])+Integer.parseInt(player[8]);
            int playerhealth=Integer.parseInt(player[6]);//max health problem in health drain
            int monsteratack=0;
            for (int s=0;s<i;s++) {
                monsteratack=monsteratack+Integer.parseInt(elements[s][2]);}
            String avalable1="Available";
            String avalable2="Available";
            String avalable3="Available";
            if(player[1].equals("Magician")) {

                if(Integer.parseInt(player[10])<Integer.parseInt(selectedallatack[0][2])) {
                    avalable1="Not enough mana";
                    avalable2="Not enough mana";
                    avalable3="Not enough mana";
                }else if (Integer.parseInt(player[10])<Integer.parseInt(selectedallatack[1][2])) {
                    avalable2="Not enough mana";
                    avalable3="Not enough mana";
                }else if (Integer.parseInt(player[10])<Integer.parseInt(selectedallatack[2][2])) {
                    avalable3="Not enough mana";
                }
                System.out.println("Select atack method:"+"\n"+"1."+selectedallatack[0][0]+"\n"+"Hit chanse: "+selectedallatack[0][3]+"%"+avalable1
                        +"\n"+"2."+selectedallatack[1][0]+"\n"+"Hit chanse: "+selectedallatack[1][3]+"%"+avalable2+
                        "\n"+"3."+selectedallatack[2][0]+"\n"+"Hit chanse: "+selectedallatack[2][3]+"%"+avalable3+
                        "\n"+"4.Rest");
            }else {
                if(Integer.parseInt(player[16])<Integer.parseInt(selectedallatack[0][2])) {
                    avalable1="Not enough stamina";
                    avalable2="Not enough stamina";
                    avalable3="Not enough stamina";
                }else if (Integer.parseInt(player[16])<Integer.parseInt(selectedallatack[1][2])) {
                    avalable2="Not enough stamina";
                    avalable3="Not enough stamina";
                }else if (Integer.parseInt(player[16])<Integer.parseInt(selectedallatack[2][2])) {
                    avalable3="Not enough stamina";
                }
                System.out.println("Select atack method:"+"\n"+"1."+selectedallatack[0][0]+"\n"+"Hit chanse: "+selectedallatack[0][3]+"%"+avalable1
                        +"\n"+"2."+selectedallatack[1][0]+"\n"+"Hit chanse: "+selectedallatack[1][3]+"%"+avalable2+
                        "\n"+"3."+selectedallatack[2][0]+"\n"+"Hit chanse: "+selectedallatack[2][3]+"%"+avalable3+
                        "\n"+"4.Rest");}

            int a=scanner.nextInt();
            switch(a) {
                case 1:
                    if (avalable1.equals("Available")) {
                        atackcount++;
                        playeratack=playeratack/2;
                        if (selectedallatack[0][1].equals("mana")) {
                            player[10]= String.valueOf(Integer.parseInt(player[10])-Integer.parseInt(selectedallatack[0][2]));
                        }else {
                            player[16]= String.valueOf(Integer.parseInt(player[16])-Integer.parseInt(selectedallatack[0][2]));
                        }
                    }else {
                        playeratack=0;
                    }
                    break;
                case 2:
                    if (avalable2.equals("Available")) {
                        atackcount++;
                        int count = ThreadLocalRandom.current().nextInt(1, 101);
                        if(count<16) {
                            playeratack=0;
                        }
                        if (selectedallatack[0][1].equals("mana")) {
                            player[10]= String.valueOf(Integer.parseInt(player[10])-Integer.parseInt(selectedallatack[1][2]));
                        }else {
                            player[16]= String.valueOf(Integer.parseInt(player[16])-Integer.parseInt(selectedallatack[1][2]));
                        }
                    }else {
                        playeratack=0;
                    }
                    break;
                case 3:
                    if (avalable3.equals("Available")) {
                        atackcount++;
                        int coun = ThreadLocalRandom.current().nextInt(1, 101);
                        if(coun<51) {
                            playeratack=0;
                        }else {
                            playeratack=playeratack*2;//fightvol2 add
                        }
                        if (selectedallatack[0][1].equals("mana")) {
                            player[10]= String.valueOf(Integer.parseInt(player[10])-Integer.parseInt(selectedallatack[2][2]));
                        }else {
                            player[16]= String.valueOf(Integer.parseInt(player[16])-Integer.parseInt(selectedallatack[2][2]));
                        }
                    }else {
                        playeratack=0;
                    }
                    break;
                case 4:
                    player[16]=String.valueOf(Integer.parseInt(player[16])+40+40*Integer.parseInt(player[17])/10);
                    if (Integer.parseInt(player[16])>Integer.parseInt(player[20])) {
                        player[16]=player[20];
                    }
                    player[10]=String.valueOf(Integer.parseInt(player[10])+40+40*Integer.parseInt(player[14])/10);
                    if (Integer.parseInt(player[10])>Integer.parseInt(player[9])) {
                        player[10]=player[9];
                    }

                    break;

            }



            if(Integer.parseInt(player[13])!=0) {
                int count = ThreadLocalRandom.current().nextInt(1, 101);
                if(count>Integer.parseInt(player[13])+1) {
                    player[6]=String.valueOf(playerhealth-monsteratack*(1-Integer.parseInt(player[4])/100));}}

            fightvol2(avalable3, i, playeratack, playerhealth, atackcount);
            fightdeath(i);
        }}
    public static void fightvol2(String t,int i,int playeratack,int playerhealth,int  atackcount) {
        if(atackcount==1) {
            if(Integer.parseInt(player[18])!=0) {
                int cou = ThreadLocalRandom.current().nextInt(1, 101);
                if (cou<Integer.parseInt(player[18])+1) {
                    playerhealth=playerhealth+playeratack*Integer.parseInt(player[12])/100;
                }

            }
            if(Integer.parseInt(player[15])!=0) {
                player[6]=String.valueOf(Integer.parseInt(player[6])+Integer.parseInt(player[15]));
            }


            elements[i-1][1]=String.valueOf(Integer.parseInt(elements[i-1][1])-playeratack*(1-Integer.parseInt(elements[i-1][3])/100));
        }
    }
    public static void fightdeath(int i) {
        for (String[] el : elements) {
            if(Integer.parseInt(el[1])<1) {
                el[5]="death";
            }
        }
        fightremove(i);
    }
    public static void fightremove(int i) {

        for (int h=0;h<i;h++) {
            if(elements[h][5].equals("death")) {

                i=i-1;
            }
        }
        fightscreen(i);
    }

    public static void gameover() {

        System.out.println("Game over");
        System.out.println("Do you want to restart?");
        gameover1();
    }
    public static void gameover1() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("1.Yes"+"\n"+"2.No");
            int a=scanner.nextInt();
            if(a==1) {
                characterselect();
            }else if(a==2) {
                System.out.println("End");
            }else {
                System.out.print("Wrong operator");
                gameover1();
            }
        }}
    public static void place() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("Where will you go?");
            System.out.println("1.Home"+"\n"+"2.Forest"+"\n"+"3.Dungeon"+"\n"+"4.Demon's Land"+"\n"+"5.Demon's castle"+"\n"+"6.Town");//you at
            System.out.print("Write here: ");
            int b;
            b = scanner.nextInt();


            switch(b) {
                case 1:
                    System.out.println();
                    System.out.println("You reached home");
                    System.out.println();
                    home();
                    break;
                case 2:
                    System.out.println();
                    System.out.print("You reached forest");
                    System.out.println();
                    forest();
                    break;
                case 3:
                    System.out.println();
                    System.out.print("You reached dungeon");
                    System.out.println();
                    break;
                case 4:
                    System.out.println();
                    System.out.print("You reached demon,s land");
                    System.out.println();
                    break;
                case 5:
                    System.out.println();
                    System.out.print("You reached demon's castle");
                    System.out.println();
                    break;
                case 6:
                    System.out.println();
                    System.out.print("You reached Town");
                    System.out.println();
                    Town();
                    break;
                default:
                    System.out.print("Wrong operator");
            }}
    }
    public static void home() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("What do you want?"+"\n"+"1.Rest"+"\n"+"2.Show my stats"+"\n"+"3.Show my invantory"+"\n"+"4.Exit");
            System.out.print("Write here: ");
            int a;
            a = scanner.nextInt();
            System.out.println();
            switch(a) {
                case 1:
                    System.out.println("You healled");
                    System.out.println();
                    player[6]=player[2];
                    home();

                    break;
                case 2:
                    playerstatsextended();
                    home();
                    break;
                case 3:
                    showinventory();;
                    System.out.println();
                    System.out.println();


                    break;
                case 4:
                    place();
                    break;
                default:
                    System.out.println();
                    System.out.println("Wrong operator");
                    System.out.println();


            }}

    }
    public static void playerstats() {
        System.out.println("Your character stats:"+"\n"+"Character name: "+player[1]+"\n"+"Health: "+player[6]+"\n"+"Mele atack: "+player[3]
                +"\n"+"Defence: "+player[4]+"\n"+"Money: "+player[5]);
        System.out.println();

    }
    public static void playerstatsextended() {
        System.out.println("Your character stats:"+"\n"+"Character name: "+player[1]+"\n"+"Health: "+player[6]+"\n"+"Mele atack: "+player[3]
                +"\n"+"Defence: "+player[4]+"\n"+"Money: "+player[5]+"\n"+"Range atack: "+player[7]+"\n"+"Magic atack: "+player[8]
                +"\n"+"Mana: "+player[10]+"\n"+"Poison atack: "+player[11]+"\n"+"Health drain: "+player[12]+"\n"+"Agility: "+player[13]+
                "\n"+"Mana regen: "+player[14]+"\n"+"Health regen: "+player[15]+"\n"+"Stamina: "+player[16]+"\n"+"Stamina regen: "+player[17]
                +"\n"+"Health drain chanse: "+player[18]);
        System.out.println();

    }
    public static void monsterstats(String i[]) {
        System.out.println("Monster stats:"+"\n"+"Character name: "+i[0]+"\n"+"Health: "+i[1]+"\n"+"Atack: "+i[2]
                +"\n"+"Defence: "+i[3]);
    }
    public static void forest() {

        int b=0;
        while (b<5) {
            gains[0][b]=oldsword[b];
            b++;
        }
        int monstercount = ThreadLocalRandom.current().nextInt(1, 4);
        System.out.println("You met "+monstercount+" monster");
        System.out.println();
        System.out.println("What you do?"+"\n"+"1.Fight with monsters"+"\n"+"2.Run to home");
        System.out.print("Write here: ");
        try(Scanner scanner = new Scanner(System.in)){
            int a;
            a = scanner.nextInt();
            switch(a) {
                case 1:
                    System.out.println();
                    fightdeep(monstercount,slime);
                    break;
                case 2:
                    System.out.println();
                    home();
                    break;
                default:
                    System.out.println();
                    System.out.println("Wrong operator");
                    System.out.println();


            }
        }}
    public static void Town() {
        try(Scanner scanner = new Scanner(System.in)) {//silahlar haqqinda melumat ver
            //default itemlar elave et
            String plc = null;
            if (merchantvar == 1) {
                plc = "2.Go to Merchant";

            } else {
                plc = "2.merchant isn't here";
            }
            System.out.println("What do you want?" + "\n" + "1.Go to Shop" + "\n" + plc + "\n" + "3.Go to Magic shop" + "\n" + "4.Go to Tavern" + "\n" + "5.Exit");
            System.out.print("Write here: ");//town-da gez;)
            int a;//basqa mekanlarada yeni varinatlar  elavae et
            a = scanner.nextInt();
            System.out.println();
            switch (a) {
                case 1:
                    System.out.println("You reached shop");
                    System.out.println();
                    shop();
                    break;
                case 2:
                    if (merchantvar == 1) {
                    System.out.println("You reached Merchant");
                    System.out.println();
                    Merchant();}else {
                        Town();
                    }
                    break;
                case 3:
                    System.out.println("You reached Magic shop");
                    System.out.println();
                    Magicshop();shop();
                    break;
                case 4:
                    System.out.println("You reached Tavern");
                    System.out.println();
                    Tavern();
                    break;
                case 5:
                    place();
                    break;
                default:
                    System.out.println();
                    System.out.println("Wrong operator");
                    System.out.println();
            }
        }
    }
    public static void sel(int i) {
        int con=0;
        int length=inventory.length;
        while (con<length) {
            if (con==i-1) {
                int len=0;
                while(len<generalitems.length) {
                    if(inventory[con][0].equals(generalitems[len][0])) {
                        player[5]=String.valueOf(Integer.parseInt(player[5])+Integer.parseInt(generalitems[len+1][0]));
                        System.out.println();
                        System.out.println("You get "+generalitems[len+1][1]+" gold");
                        System.out.println();
                        inventory[con][5]="empty";


                    }
                    len=len+2;
                }

            }
            con++;
        }
        ;}
    public static void shopbuymenu() {//oxuyan qisalda bileceyimi bilirem
        System.out.println("Select item:");
        for (int i = 0; i < shopmenu.length; i++) {
            int count = ThreadLocalRandom.current().nextInt(1, 6);//ikinci reqemi shop menunu sayina beraber ele
            if (count%2==1) {
                count--;
            }
            for (int s = 0; s < oldsword.length; s++) {
                shopmenu[i][s]=shopitems[count][s];//i can see you

            }
            count++;
            shopmenuprice[i][0]=shopitems[count][0];
            shopmenuprice[i][1]=shopitems[count][1];

            int c=i+1;
            System.out.println(c+". "+shopmenu[i][0]+"   Price: "+shopitems[count][0]+" gold");

        }

    }

    public static void shop() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("What do you want?"+"\n"+"1.Buy"+"\n"+"2.Sel"+"\n"+"3.Exit");
            System.out.print("Write here: ");
            int a;
            a = scanner.nextInt();
            System.out.println();
            switch(a) {
                case 2:
                    System.out.println("Select item");
                    for(int i=0;i<inventory.length;i++) {
                        if(inventory[i][5].equals("ful")) {
                            System.out.println(i+1+"."+inventory[i][0]);
                            System.out.println();
                        }
                    }
                    int as=scanner.nextInt();
                    sel(as);
                    System.out.println();

                    shop();

                    break;
                case 1:

                    shopbuymenu();
                    int in=scanner.nextInt();
                    in--;
                    if(Integer.parseInt(player[5])>Integer.parseInt(shopmenuprice[in][0])) {

                        inventoryinwithoutplace(shopmenu[in], 1);
                        player[5]=String.valueOf(Integer.parseInt(player[5])-Integer.parseInt(shopmenuprice[in][0]));

                    }else {
                        System.out.print("Not enough money ");
                    }

                    shop();
                    break;
                case 3:
                    place();
                    break;
                default:
                    System.out.println();
                    System.out.println("Wrong operator");
                    System.out.println();}}

    }
    public static void merchantbuymenu(){
        System.out.println("Select item:");
        for (int i = 0; i < 6; i++) {
            int count = ThreadLocalRandom.current().nextInt(0, 6);//ikinci reqemi shop menunu sayina beraber ele
            if (count%2==1) {
                count--;
            }
            if((i % 2) == 0) {
                for (int s = 0; s < 5; s++) {
                    merchantmenu[i][s] = merchantitems[count][s];//i can see you

                }
                merchantmenu[i + 1][0] = merchantitems[count + 1][0];
                merchantmenu[i + 1][1] = merchantitems[count + 1][1];
                int c = i + 1;
                System.out.println(c + ". " + merchantmenu[i][0] + "   Price: " + merchantmenu[i + 1][0] + " gold");
            }
        }

    }


    public static void Merchant() {
        try (Scanner scanner = new Scanner(System.in)) {
            System.out.println("What do you want?" + "\n" + "1.Buy" + "\n" + "2.Sel" + "\n" + "3.Exit");
            System.out.print("Write here: ");
            int a;
            a = scanner.nextInt();
            System.out.println();
            switch (a) {
                case 2:
                    System.out.println("Select item");
                    for (int i = 0; i < inventory.length; i++) {
                        if (inventory[i][5].equals("ful")) {
                            System.out.println(i + 1 + "." + inventory[i][0]);
                            System.out.println();
                        }
                    }
                    int as = scanner.nextInt();
                    sel(as);
                    System.out.println();

                    Merchant();

                    break;
                case 1:
                    if(merchantvar==1){
                    merchantbuymenu();
                    merchantvar=0;}

                    int in = scanner.nextInt();
                    in--;
                    if (Integer.parseInt(player[5]) > Integer.parseInt(merchantmenu[in+1][0])) {

                        inventoryinwithoutplace(merchantmenu[in], 1);
                        player[5] = String.valueOf(Integer.parseInt(player[5]) - Integer.parseInt(merchantmenu[in+1][0]));

                    } else {
                        System.out.print("Not enough money ");
                    }

                    Merchant();
                    break;
                case 3:
                    place();
                    break;
                default:
                    System.out.println();
                    System.out.println("Wrong operator");
                    System.out.println();
            }
        }

    }

    public static void Magicshop() {}
    public static void Tavern() {}

    public static void raceselect(int a) {


        switch(a) {
            case 1:
                player[19]="Human";
                player[2]=String.valueOf(Integer.parseInt(player[2])+10);
                player[4]=String.valueOf(Integer.parseInt(player[4])+1);
                player[6]=String.valueOf(Integer.parseInt(player[6])+10);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+10);
                player[13]=String.valueOf(Integer.parseInt(player[13])+3);
                player[14]=String.valueOf(Integer.parseInt(player[14])+1);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+50);
                player[17]=String.valueOf(Integer.parseInt(player[17])+5);
                player[20]=String.valueOf(Integer.parseInt(player[20])+50);

                break;
            case 2:
                player[19]="Elf";
                player[2]=String.valueOf(Integer.parseInt(player[2])+10);
                player[4]=String.valueOf(Integer.parseInt(player[4])+1);
                player[6]=String.valueOf(Integer.parseInt(player[6])+10);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+10);
                player[13]=String.valueOf(Integer.parseInt(player[13])+12);
                player[14]=String.valueOf(Integer.parseInt(player[14])+1);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+10);
                player[17]=String.valueOf(Integer.parseInt(player[17])+1);
                player[20]=String.valueOf(Integer.parseInt(player[20])+10);

                break;
            case 3:
                player[19]="Dwarf";
                player[2]=String.valueOf(Integer.parseInt(player[2])+10);
                player[4]=String.valueOf(Integer.parseInt(player[4])+10);
                player[6]=String.valueOf(Integer.parseInt(player[6])+10);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+10);
                player[13]=String.valueOf(Integer.parseInt(player[13])+1);
                player[14]=String.valueOf(Integer.parseInt(player[14])+1);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+10);
                player[17]=String.valueOf(Integer.parseInt(player[17])+1);
                player[20]=String.valueOf(Integer.parseInt(player[20])+10);
                break;
            case 4:
                player[19]="Vampire";
                player[2]=String.valueOf(Integer.parseInt(player[2])+10);
                player[4]=String.valueOf(Integer.parseInt(player[4])+1);
                player[6]=String.valueOf(Integer.parseInt(player[6])+10);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+10);
                player[13]=String.valueOf(Integer.parseInt(player[13])+3);
                player[14]=String.valueOf(Integer.parseInt(player[14])+1);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+10);
                player[17]=String.valueOf(Integer.parseInt(player[17])+1);
                player[12]=String.valueOf(Integer.parseInt(player[12])+10);
                player[18]=String.valueOf(Integer.parseInt(player[18])+10);
                player[20]=String.valueOf(Integer.parseInt(player[20])+10);
                break;
            case 5:
                player[19]="Orc";
                player[2]=String.valueOf(Integer.parseInt(player[2])+25);
                player[4]=String.valueOf(Integer.parseInt(player[4])+1);
                player[6]=String.valueOf(Integer.parseInt(player[6])+25);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+10);
                player[13]=String.valueOf(Integer.parseInt(player[13])+1);
                player[14]=String.valueOf(Integer.parseInt(player[14])+1);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+10);
                player[17]=String.valueOf(Integer.parseInt(player[17])+1);
                player[20]=String.valueOf(Integer.parseInt(player[20])+10);
                break;
            case 6:
                player[19]="Demmon";
                player[2]=String.valueOf(Integer.parseInt(player[2])+10);
                player[4]=String.valueOf(Integer.parseInt(player[4])+1);
                player[6]=String.valueOf(Integer.parseInt(player[6])+10);
                player[9]=String.valueOf(Integer.parseInt(player[9])+10);
                player[10]=String.valueOf(Integer.parseInt(player[10])+50);
                player[13]=String.valueOf(Integer.parseInt(player[13])+3);
                player[14]=String.valueOf(Integer.parseInt(player[14])+5);
                player[15]=String.valueOf(Integer.parseInt(player[15])+1);
                player[16]=String.valueOf(Integer.parseInt(player[16])+10);
                player[17]=String.valueOf(Integer.parseInt(player[17])+1);
                player[20]=String.valueOf(Integer.parseInt(player[20])+10);

                break;
            default:
                System.out.println();
                System.out.println("Wrong operator");
                System.out.println();
        }

    }

    public static void characterselect() {
        try(Scanner scanner = new Scanner(System.in)){
            System.out.println("Select your character");
            System.out.println("1.A Bowman"+"\n"+"2.A Swordman"+"\n"+"3.A Axeman"+"\n"+"4.A Magician");
            System.out.print("Write here: ");
            int a;
            a = scanner.nextInt();
            character(a);
            System.out.println();
            System.out.println("Select your race");
            System.out.println("1.Human"+"\n"+"2.Elf"+"\n"+"3.Dwarf"+"\n"+"4.Vampire"+"\n"+"5.Orc"+"\n"+"6.Demon");
            System.out.print("Write here: ");
            int c;
            c = scanner.nextInt();
            raceselect(c);
            System.out.println();
            playerstatsextended();
            System.out.println();
            place();}
    }
    public static void prolog() {
        System.out.println("In the ancient realm of Eldoria, three mighty kingdoms existed" +"\n" +
                " in a delicate balance: the Realm of the Elves, the Kingdom of Humans," +"\n" +
                " and the Abyssal Lands of Demons. For centuries, their fates intertwined" +"\n" +
                " through conflict and fragile alliances, each vying for power and control " +"\n" +
                "over legendary artifacts said to be forged by the gods themselves.\n" +
                "The Elves, guardians of nature, thrived in their shimmering cities of " +"\n" +
                "silverwood and crystal, believing themselves the rightful protectors of the" +"\n" +
                " world. The Humans, ambitious and inventive, sought to expand their territories," +"\n" +
                " driven by an insatiable thirst for knowledge and power. In contrast, the Demons," +"\n" +
                " born of chaos, lurked in the shadows, envying the light of their counterparts and" +"\n" +
                " craving destruction.\n" +
                "As a fragile peace settled over the land, a young human king named Caden" +"\n" +
                " stumbled upon an ancient temple hidden within the mountains, where he" +"\n" +
                " discovered the Thunderhammer—a weapon of immense power. Fueled by dreams " +"\n" +
                "of unifying Eldoria under human rule, he ignited a chain of events that would" +"\n" +
                " shatter the peace and awaken dark forces long sealed away.\n" +
                "With each drop of blood spilled in the ensuing conflict, the demon lord Xal’thar " +"\n" +
                "felt his power growing. Sensing opportunity, he unleashed his legions upon the " +"\n" +
                "world, eager to claim the mythic weapons for himself. Thus began a war that would" +"\n" +
                " test the bonds between Elves and Humans, and awaken the shadows of the Abyss.\n" +
                "In this tale of destiny, heroes will rise, legends will be forged, and the fate " +"\n" +
                "of Eldoria hangs in the balance. The Instruments of Eternity await their wielders" +"\n" +
                ", but in the struggle for power, who will pay the ultimate price?\n");
    }

    public static void main(String[] args) {
        prolog();//settings
        System.out.print("what is your name:");
        try(Scanner scanner = new Scanner(System.in)){
            String vnString = scanner.nextLine();
            player[0]=vnString;
            System.out.println("Hello "+player[0]);
            System.out.println();
            characterselect();



        }}




}
