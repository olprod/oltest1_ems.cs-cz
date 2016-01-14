---
description: na
keywords: na
title: FastTrack Center Benefit Process for Azure Active Directory Premium 
search: na
ms.date: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: f1e8d94d-ce42-4d4c-a25b-0f28b93a9e10
---
# Proces z&#237;sk&#225;n&#237; benefitu Centra FastTrack pro Azure Active Directory Premium 
Pokud má vaše organizace nárok na benefit Centra FastTrack pro Microsoft Azure AD Premium, můžete vzdáleně pracovat se specialisty Microsoftu a připravit prostředí Microsoft Azure AD Premium k použití. Informace o tom, jestli má vaše organizace na získání benefitu nárok, najdete v článku [Benefit Centra FastTrack pro Azure Active Directory Premium](../Topic/FastTrack_Center_Benefit_for_Azure_Active_Directory_Premium.md).

Tento článek obsahuje následující informace:

-   [Overview of the onboarding process](#overview)

-   [Expectations for your source environment](#expectations_src_environ)

-   [Phases of the onboarding process](#phases_onboarding_process)

-   [Microsoft responsibilities](#microsoft_responsibilities) pro každou fázi

-   [Your responsibilities](#your_responsibilities) pro každou fázi

Po dokončení registrace můžete očekávat:

-   Vytvoří se váš klient Microsoft Azure AD Premium.

-   Licencovaní uživatelé mají přístup ke službám Microsoft Azure AD Premium pomocí jedné z následujících možností identity:

    -   Cloudové identity (jedinečné účty Microsoft Azure AD Premium)

    -   Synchronizované identity: Účty Microsoft Azure AD Premium synchronizované z vašeho místního adresáře Active Directory pomocí nástroje Azure Active Directory Connect (Azure AD Connect) pro zákazníky s jednou nebo více doménovými strukturami Active Directory

    -   Federované identity – s účty Microsoft Azure AD Premium, které jsou:

        -   Synchronizované z Active Directory pomocí nástroje Microsoft Azure AD Connect pro zákazníky s konfigurací jedné doménové struktury Active Directory

        -   Federované se službou AD FS (Active Directory Federation Services) 2.0 nebo novější z vašeho místního adresáře Active Directory

## <a name="overview"></a>Přehled procesu registrace
Registraci tvoří dvě hlavní součásti:

-   **Základní možnosti** – úkoly vyžadované pro konfiguraci klienta a integraci s Azure AD (v případě potřeby). Základní možnosti poskytují i směrný plán pro registraci jiných oprávněných služeb Microsoft Online.

-   **Registrace služeb** – úkoly vyžadované ke konfiguraci Microsoft Azure AD Premium samostatně nebo se synchronizací adresářů Azure AD Connect nebo s AD FS

Následující diagram popisuje časovou osu pro používání benefitu Centra FastTrack.

![](../Image/1-rms_onboarding_process.png)

Základní proces je tento:

-   Společnost Microsoft se pokusí vás kontaktovat do 30 dní od data, kdy jste si koupili oprávněný plán. Pokud jste připravení tyto služby ve své organizaci nasadit, můžete [Centrum FastTrack](http://fasttrack.microsoft.com/) požádat o pomoc. Pokud chcete požádat o pomoc, přihlaste se k Centru FastTrack (http://fasttrack.microsoft.com), přejděte na řídicí panel, vyberte název společnosti, klikněte na kartu Nabídky a klikněte na tlačítko pro žádost o pomoc k oprávněné službě. Po zahájení registrační podpory vytvoříme harmonogram online schůzek.

-   Tým Microsoftu vám pomůže se základními možnostmi a potom taky s jednou registrací u každé oprávněné služby.

Veškerou podporu registrace budou vzdáleně poskytovat zaměstnanci Microsoftu:

-   Microsoft vám bude vzdáleně pomáhat s různými aktivitami při registraci prostřednictvím nástrojů, dokumentace a pokynů. Pokud chcete, aby Microsoft dělal určité konfigurační úkony za vás, můžete se rozhodnout společnosti Microsoft udělit příslušná oprávnění a přístupová práva k jejich provádění.

-   Podporu registrace poskytuje Centrum FastTrack, které je dostupné v běžné pracovní době pro příslušnou oblast.

-   Podpora registrace je dostupná v angličtině, tradiční čínštině, francouzštině, italštině, japonštině, němčina, portugalštině (Brazílie) nebo španělštině.

-   Tým Microsoftu může spolupracovat přímo s vámi nebo vaším zástupcem.

## <a name="expectations_src_environ"></a>Očekávání pro vaše zdrojové prostředí
Ve svém místním zdrojovém prostředí už můžete mít adresář Microsoft Active Directory, který chcete integrovat s Microsoft Azure AD Premium a využívat tak bohaté možnosti správy identit z jediné konzoly. Součástí benefitu Centra FastTrack je taky to, že vám pomůžeme integrovat Microsoft Azure AD Premium s vaší stávající místní implementací. Pokud se integrace požaduje, musí vaše zdrojové prostředí splňovat určitou minimální úroveň stanovenou pro příslušnou aplikaci.

Následující tabulka ukazuje, jaké se pro registraci očekávají minimální úrovně zdrojového prostředí.

|Aktivita|Očekávané zdrojové prostředí|
|------------|--------------------------------|
|Základní možnosti|Doménové struktury služby Active Directory s úrovní funkčnosti doménové struktury nastavenou na Windows Server 2008 nebo vyšší, s následující konfigurací doménovou struktury:<br /><br />-   Jedna doménová struktura služby Active Directory<br />-   Více doménových struktur služby Active Directory **Note:** U všech konfigurací s více doménovými strukturami se benefit Centra FastTrack nevztahuje na nasazení služby AD FS.|
|Registrace služby<br /><br />-   Microsoft Azure AD Premium|Místní adresář Active Directory a prostředí jsou připravené na Azure AD Premium, ve kterém už jsou vyřešené zjištěné problémy, které by jinak znemožňovaly integraci s funkcemi Azure AD a Azure AD Premium.|

## <a name="phases_onboarding_process"></a>Fáze procesu registrace
Registrace Microsoft Azure AD Premium má pět primárních fází, jak je vidět na následujícím obrázku:

-   Inicializace

-   Hodnocení

-   Opravy

-   Povolení

-   Zavřít

![](../Image/2-aadp_onboarding_phases-v3.png)

Podrobný popis úkolů jednotlivých fází najdete v částech [Microsoft responsibilities](#microsoft_responsibilities) a [Your responsibilities](#your_responsibilities).

### Fáze inicializace
Po nákupu příslušného počtu licencí přiřaďte licence ke stávajícímu nebo novému klientovi podle pokynů uvedených v e-mailu s potvrzením nákupu. Microsoft ověří, jestli splňujete podmínky pro benefit Centra FastTrack. Společnost Microsoft se pokusí vás kontaktovat do 30 dní od data, kdy jste si koupili oprávněný plán. Pokud jste připravení tyto služby ve své organizaci nasadit, můžete [Centrum FastTrack](http://fasttrack.microsoft.com/) požádat o pomoc. Pokud chcete požádat o pomoc, přihlaste se k Centru FastTrack (http://fasttrack.microsoft.com), přejděte na řídicí panel, vyberte název společnosti, klikněte na kartu Nabídky a klikněte na tlačítko pro žádost o pomoc k oprávněné službě. Po zahájení registrační podpory vytvoříme harmonogram online schůzek.

V průběhu této fáze se budeme zabývat procesem registrace, ověřovat data a nastavíme zahajovací schůzku.

![](../Image/Microsoft_Azure_AD_Premium_initiate_phase_1.png)

### Fáze hodnocení
Po zahájení procesu registrace s vámi bude Microsoft spolupracovat na vyhodnocení vašeho zdrojového prostředí a odpovídajících požadavků. Spustí se nástroje vyhodnocující vaše prostředí a Microsoft vás provede hodnocením vašich internetových prohlížečů, adresáře Active Directory, klientských operačních systémů v zařízeních, DNS, sítě, infrastruktury a systému identit, podle kterého určí, jestli je pro registraci potřeba udělat nějaké změny. Na základě vašeho aktuálního nastavení vám nabídneme plán oprav, kterými zajistíte splnění minimálních požadavků na zdrojové prostředí pro úspěšnou registraci Microsoft Azure AD Premium. Pro fázi oprav taky nastavíme vhodná volání kontrolních bodů.

![](../Image/Microsoft_Azure_AD_Premium_assess_phase_v6.png)

### Fáze oprav
V případě potřeby uděláte ve svém zdrojovém prostředí úkoly určené v plánu oprav, tak aby se splnily požadavky pro registraci jednotlivých služeb.

![](../Image/Microsoft_Azure_AD_Premium_remediate_phase_1.png)

Před zahájením fáze povolení společně ověříme výstupy opravných aktivit a ujistíme se, že můžete pokračovat.

### Fáze povolení
Po dokončení všech opravných aktivit se projekt posune ke konfiguraci základní infrastruktury pro používání služby a zřízení Microsoft Azure AD Premium.

**Fáze povolení – základní možnosti**

Povolení základních možností zahrnuje zřízení služby a integraci klienta a identit. Její součástí jsou i kroky pro zajištění základních podmínek registrace Microsoft Azure AD Premium.

Registrace pro Azure AD Premium může začít až po dokončení základní registrace.

**Fáze povolení – Microsoft Azure AD Premium**

Prostředí Microsoft Azure AD Premium se dá podle potřeby nastavit se synchronizací adresářů Azure AD Connect a službou Active Directory Federation Services (AD FS).

Pro scénáře Microsoft Azure AD Premium, které zahrnují synchronizaci místních identit do cloudu, vám pomůžeme přidáním IT správců a uživatelů do vašeho předplatného, konfigurací požadavků na správu, nastavením Microsoft Azure AD Premium, nastavením synchronizace adresářů přes Azure AD Connect a služby Active Directory Federation Services přes Azure AD Connect, přičemž nakonfigurujeme testovací uživatele a ověříme vaše základní případy používání pro službu.

Instalace Microsoft Azure AD Premium zahrnuje povolení následujících funkcí:

-   Samoobslužné resetování hesla (SSPR)

-   Vícefaktorové ověřování (MFA)

-   Aplikace Software jako služba (SaaS) – nastavení jedné SaaS aplikace

-   Samoobslužná správa skupin (SSGM)

-   Sestavy pro správu

![](../Image/Microsoft_Azure_AD_Premium_enable_phase_2.png)

## <a name="microsoft_responsibilities"></a>Odpovědnosti Microsoftu

### Obecné

-   Poskytovat vám vzdálenou podporu při požadovaných konfiguračních aktivitách popsaných u jednotlivých fází

-   Poskytovat dostupnou dokumentaci a softwarové nástroje, konzoly pro správu a skripty, které vám pomůžou omezit nebo odstranit úkoly konfigurace.

Poskytování oprávnění a přístupových práv Microsoftu není k využití benefitu Centra FastTrack nutné. V některých případech se můžete rozhodnout dát společnosti Microsoft odpovídající oprávnění a přístupová práva, aby mohla vaším jménem provádět konkrétní aktivity.

### Fáze inicializace

-   Kontaktovat vás do 30 dnů od zakoupení opravňujících licencí pro nového klienta

-   Spolupracovat s vámi na zahájení registrace do 90 dnů od zakoupení opravňujících licencí

-   Definovat opravňující služby, které se budou registrovat

### Fáze hodnocení

-   Poskytovat přehled pro správu

-   Poskytovat pokyny k:

    -   Řešení požadavků na DNS, síť a infrastrukturu

    -   Řešení požadavků na klienta (internetový prohlížeč, klientské operační systémy a služby)

    -   Identitě a zřizování uživatelů

    -   Identifikaci požadavků na  synchronizaci adresářů

    -   Určení, jestli synchronizace hodnot hash hesel splňuje cíle zákazníků nebo jestli se vyžaduje služba AD FS

    -   Povolení oprávněných služeb, které jste zakoupili a určili jako součást registrace

    -   Identifikaci požadavků na pilotní a testovací prostředí, například testovací účty, testovací instance SaaS aplikace (například SalesForce)

-   Stanovit časovou osu pro opravné aktivity

-   Poskytovat kontrolní seznam oprav

### Fáze oprav

-   Zařídit konferenční hovory podle odsouhlaseného plánu, při kterých s vámi bude probírat postup opravných aktivit

-   Pomáhat se spouštěním nástrojů k ručení a opravám problémů a s interpretací výsledků

### Fáze povolení
Poskytovat pokyny k:

-   Aktivaci vašeho klienta Microsoft Azure AD Premium

-   Konfiguraci portů brány firewall

-   Konfiguraci DNS pro oprávněné služby

-   Ověření připojení ke službám Microsoft Azure AD Premium

-   Pro prostředí s jednou doménovou strukturou:

    -   Instalaci synchronizace adresářů mezi službami Active Directory Domain Services (AD DS) a Azure AD Connect (v případě potřeby)

    -   Konfiguraci synchronizace hesel pomocí nástroje Microsoft Azure AD Connect

-   Pro prostředí s více doménovými strukturami:

    -   Instalaci synchronizace Azure AD Connect, nastavení pro více scénářů doménové struktury. Poznámka: Funkce synchronizace hodnot hash hesel a zpětný zápis hesel podporují více doménových struktur.  Scénáře zpětného zápisu ale podporované nejsou.

    -   Konfiguraci synchronizace mezi místními doménovými strukturami Active Directory a adresářem Microsoft Azure AD Premium (Azure Active Directory)

        > [!NOTE]
        > K vývoji a implementaci rozšíření vlastních pravidel se pokyny neposkytují.

-   U jedné doménové struktury, pokud jsou cílem federované identity: Instalaci a konfiguraci služby AD FS (Active Directory Federation Services) pro ověřování v místní doméně s Microsoft Azure AD Premium v konfiguraci s jednou lokalitou odolné proti chybám (v případě potřeby).

    > [!NOTE]
    > U všech konfigurací s více doménovými strukturami se k nasazení služby AD FS pokyny neposkytují.

-   Testování funkce jednotného přihlašování, pokud je nasazená

#### Fáze povolení – Azure AD Premium – pomocí nástroje Azure AD Connect a služby AD FS
Poskytovat pokyny k nastavení:

-   Zřizování uživatelů včetně licencí

-   Synchronizace adresářů Azure AD Connect (se zpětným zápisem hesel a synchronizací hodnot hash hesel)

-   Active Directory Federation Services (AD FS)

-   Samoobslužné resetování hesla (SSPR)

-   Vícefaktorové ověřování (MFA)

-   Jedna integrovaná aplikace, včetně jednotného přihlašování pro SaaS aplikace

-   Sestavy využití a zabezpečení pro správce

-   Samoobslužná správa skupin (SSGM)

-   Proxy soubory aplikace

-   Správcovská oznámení

-   Přizpůsobená přihlašovací obrazovka, včetně loga, textu a obrázků

## <a name="your_responsibilities"></a>Vaše odpovědnosti
Tato část popisuje některé vaše odpovědnosti během procesu registrace.

### Obecné

-   Vylepšení a integrace v rámci klienta Microsoft Azure AD Premium nad rámec konfigurovatelných možností, které jsou uvedené v tomto článku

-   Celkový program a řízení projektů vašich prostředků

-   Komunikace s koncovými uživateli, dokumentace, školení a správa změn

-   Dokumentace technické podpory a školení

-   Vytváření všech sestav, prezentací nebo zápisů ze schůzek, které jsou specifické pro vaši organizaci

-   Vytváření dokumentace architektury a technické dokumentace specifické pro vaši organizaci

-   Návrh, nákup, instalace a konfigurace hardwaru a sítě

-   Nákup, instalace a konfigurace softwaru

-   Správa, konfigurace a aplikování zásad zabezpečení nad rámec těch, které se vytvořily pro testování  vašich standardních funkcí a konfigurace služeb Microsoft Azure AD Premium

-   Registrace uživatelských účtů nad rámec těch, které se použily k testování vašich standardních funkcí a konfigurace služeb Microsoft Azure AD Premium

-   Konfigurace sítě, analýza ověření šířky pásma, testování a monitorování

-   Správa procesu schválení řízení technických změn a vytváření podpůrné dokumentace

-   Úprava provozního modelu a provozní příručky

-   Nastavení místního vícefaktorového ověřování

-   Vyřazení zdrojových prostředí a služeb dříve využívaných zákazníkem z provozu a jejich odebrání

-   Vytváření a údržba testovacího prostředí

-   Instalace aktualizací Service Pack a dalších požadovaných aktualizací serverů infrastruktury

-   Poskytování a konfigurace všech veřejných certifikátů protokolu SSL

-   Vytvoření Podmínek použití organizace příkazů pro konfiguraci a zobrazení na zařízeních vlastněných koncovými uživateli

### Fáze inicializace

-   Spolupráce s týmem Microsoftu na zahájení registrace oprávněných služeb

-   Účastnit se zahajovací schůzky, řídit a vést účastníky z vaší organizace a potvrdit časové plány oprav

### Fáze hodnocení

-   Určit příslušné účastníky (včetně vedoucího projektu) pro zajištění nutných aktivit hodnocení

-   Pokud si zvolíte takovou možnost, sdílet svou obrazovku s Microsoftem v případě potřeby pokynů pro spuštění nástrojů vyhodnocujících vaše prostředí nebo předplatné Microsoft Azure AD Premium.

-   Účastnit se schůzek, na kterých se vytvoří kontrolní seznam oprav, a přispívat k celkovému plánu, včetně infrastruktury, sítě, správy, přípravě synchronizace adresáře, zabezpečení sítě a témat federovaných identit.

-   Účastnit se schůzek, na kterých se vymezí přístup k zřizování uživatelů

-   Účastnit se schůzek plánujících konfiguraci online služeb

-   Vytvořit plán podpory pro přípravu migrace

### Fáze oprav

-   Provést požadované kroky k dokončení aktivit oprav stanovených ve fázi hodnocení

-   Účastnit schůzek kontrolního bodů

### Fáze povolení

-   Sdílet svou obrazovku s Microsoftem (pokud se tak rozhodnete) v případě, že se potřebují pokyny pro provádění změn prostředí nebo předplatného Microsoft Azure AD Premium

-   Spravovat prostředky podle potřeby

-   Konfigurovat síťové položky podle pokynů od Microsoftu

-   Provádět synchronizaci připravenosti adresářů a konfigurace adresářů podle pokynů od Microsoftu

-   Konfigurovat infrastrukturu zabezpečení (třeba portů brány firewall) podle pokynů od Microsoftu

-   Implementovat infrastrukturu příslušného klienta

-   Implementovat přístup k zřizování uživatelů podle pokynů od Microsoftu

-   Povolovat různé služby podle pokynů od Microsoftu

## Chcete se dozvědět víc?
Další informace najdete v článku věnovaném [Microsoft Azure Active Directory](http://azure.microsoft.com/en-us/documentation/services/active-directory/) a sadě [Enterprise Mobility](http://www.microsoft.com/en-us/server-cloud/products/enterprise-mobility-suite/default.aspx).

