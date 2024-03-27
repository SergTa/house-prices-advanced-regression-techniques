# house-prices-advanced-regression-techniques
MSSubClass: Identifies the type of dwelling involved in the sale. # Определяет тип жилья, участвующего в продаже	

        20	1-STORY 1946 & NEWER ALL STYLES
        30	1-STORY 1945 & OLDER
        40	1-STORY W/FINISHED ATTIC ALL AGES
        45	1-1/2 STORY - UNFINISHED ALL AGES
        50	1-1/2 STORY FINISHED ALL AGES
        60	2-STORY 1946 & NEWER
        70	2-STORY 1945 & OLDER
        75	2-1/2 STORY ALL AGES
        80	SPLIT OR MULTI-LEVEL
        85	SPLIT FOYER
        90	DUPLEX - ALL STYLES AND AGES
       120	1-STORY PUD (Planned Unit Development) - 1946 & NEWER
       150	1-1/2 STORY PUD - ALL AGES
       160	2-STORY PUD - 1946 & NEWER
       180	PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
       190	2 FAMILY CONVERSION - ALL STYLES AND AGES

MSZoning: Identifies the general zoning classification of the sale. #Определяет общую классификацию зонирования объекта продажи
		
       A	Agriculture
       C	Commercial
       FV	Floating Village Residential   Жилой комплекс "Плавучая деревня"
       I	Industrial
       RH	Residential High Density    Жилая застройка с высокой плотностью
       RL	Residential Low Density
       RP	Residential Low Density Park     Жилой парк с низкой плотностью застройки
       RM	Residential Medium Density
	
LotFrontage: Linear feet of street connected to property #Линейные футы улицы, соединенной с объектом недвижимости

LotArea: Lot size in square feet  # Размер участка в квадратных футах

Street: Type of road access to property # Улица: Тип дороги, по которой можно подъехать к объекту недвижимости

       Grvl	Gravel	
       Pave	Paved
       	
Alley: Type of alley access to property # Аллея: Тип подъездной аллеи к собственности

       Grvl	Gravel
       Pave	Paved
       NA 	No alley access
		
LotShape: General shape of property # Форма участка: Общая форма объекта недвижимости

       Reg	Regular	
       IR1	Slightly irregular
       IR2	Moderately Irregular
       IR3	Irregular
       
LandContour: Flatness of the property #Описание участка: Ровность участка

       Lvl	Near Flat/Level	
       Bnk	Banked - Quick and significant rise from street grade to building
       HLS	Hillside - Significant slope from side to side
       Low	Depression
		
Utilities: Type of utilities available # Коммунальные услуги: Тип доступных коммунальных услуг
		
       AllPub	All public Utilities (E,G,W,& S)	
       NoSewr	Electricity, Gas, and Water (Septic Tank)
       NoSeWa	Electricity and Gas Only
       ELO	Electricity only	
	
LotConfig: Lot configuration #

       Inside	Inside lot   Внутри
       Corner	Corner lot   Угловой 
       CulDSac	Cul-de-sac   Тупик
       FR2	Frontage on 2 sides of property  Фасад с 2-х сторон дома
       FR3	Frontage on 3 sides of property
	
LandSlope: Slope of property # Уклон участка
		
       Gtl	Gentle slope
       Mod	Moderate Slope	
       Sev	Severe Slope
	
Neighborhood: Physical locations within Ames city limits #Окрестности: Физические местоположения в черте города Эймс

       Blmngtn	Bloomington Heights
       Blueste	Bluestem
       BrDale	Briardale
       BrkSide	Brookside
       ClearCr	Clear Creek
       CollgCr	College Creek
       Crawfor	Crawford
       Edwards	Edwards
       Gilbert	Gilbert
       IDOTRR	Iowa DOT and Rail Road
       MeadowV	Meadow Village
       Mitchel	Mitchell
       Names	North Ames
       NoRidge	Northridge
       NPkVill	Northpark Villa
       NridgHt	Northridge Heights
       NWAmes	Northwest Ames
       OldTown	Old Town
       SWISU	South & West of Iowa State University
       Sawyer	Sawyer
       SawyerW	Sawyer West
       Somerst	Somerset
       StoneBr	Stone Brook
       Timber	Timberland
       Veenker	Veenker
			
Condition1: Proximity to various conditions # Условие 1: Близость к различным условиям
	
       Artery	Adjacent to arterial street
       Feedr	Adjacent to feeder street	
       Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
       PosN	Near positive off-site feature--park, greenbelt, etc.
       PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad
	
Condition2: Proximity to various conditions (if more than one is present) # Близость к различным условиям (если присутствует более одного)
		
       Artery	Adjacent to arterial street
       Feedr	Adjacent to feeder street	
       Norm	Normal	
       RRNn	Within 200' of North-South Railroad
       RRAn	Adjacent to North-South Railroad
       PosN	Near positive off-site feature--park, greenbelt, etc.
       PosA	Adjacent to postive off-site feature
       RRNe	Within 200' of East-West Railroad
       RRAe	Adjacent to East-West Railroad
	
BldgType: Type of dwelling # Тип жилища
		
       1Fam	Single-family Detached	
       2FmCon	Two-family Conversion; originally built as one-family dwelling
       Duplx	Duplex
       TwnhsE	Townhouse End Unit
       TwnhsI	Townhouse Inside Unit
	
HouseStyle: Style of dwelling       Стиль жилища
	
       1Story	One story
       1.5Fin	One and one-half story: 2nd level finished
       1.5Unf	One and one-half story: 2nd level unfinished
       2Story	Two story
       2.5Fin	Two and one-half story: 2nd level finished
       2.5Unf	Two and one-half story: 2nd level unfinished
       SFoyer	Split Foyer              Раздельное фойе
       SLvl	Split Level
	
OverallQual: Rates the overall material and finish of the house  Общая оценка: Оценивает общий материал и отделку дома

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average
       5	Average
       4	Below Average
       3	Fair
       2	Poor
       1	Very Poor
	
OverallCond: Rates the overall condition of the house  Общий показатель: Оценивает общее состояние дома

       10	Very Excellent
       9	Excellent
       8	Very Good
       7	Good
       6	Above Average	
       5	Average
       4	Below Average	
       3	Fair
       2	Poor
       1	Very Poor
		
YearBuilt: Original construction date   Год постройки: Первоначальная дата постройки

YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)   Год переделки: Дата переделки (совпадает с датой строительства, если никаких переделок или дополнений нет)

RoofStyle: Type of roof  Тип крыши

       Flat	Flat
       Gable	Gable
       Gambrel	Gabrel (Barn)
       Hip	Hip
       Mansard	Mansard
       Shed	Shed
		
RoofMatl: Roof material  Кровельный материал

       ClyTile	Clay or Tile
       CompShg	Standard (Composite) Shingle
       Membran	Membrane
       Metal	Metal
       Roll	Roll
       Tar&Grv	Gravel & Tar
       WdShake	Wood Shakes
       WdShngl	Wood Shingles
		
Exterior1st: Exterior covering on house  Наружное покрытие дома

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast	
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles
	
Exterior2nd: Exterior covering on house (if more than one material)   Наружное покрытие дома (если используется более одного материала)

       AsbShng	Asbestos Shingles
       AsphShn	Asphalt Shingles
       BrkComm	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       CemntBd	Cement Board
       HdBoard	Hard Board
       ImStucc	Imitation Stucco
       MetalSd	Metal Siding
       Other	Other
       Plywood	Plywood
       PreCast	PreCast
       Stone	Stone
       Stucco	Stucco
       VinylSd	Vinyl Siding
       Wd Sdng	Wood Siding
       WdShing	Wood Shingles
	
MasVnrType: Masonry veneer type  Тип облицовки каменной кладки

       BrkCmn	Brick Common
       BrkFace	Brick Face
       CBlock	Cinder Block
       None	None
       Stone	Stone
	
MasVnrArea: Masonry veneer area in square feet   Площадь облицовки каменной кладки в квадратных футах

ExterQual: Evaluates the quality of the material on the exterior   Оценивает качество материала, из которого выполнена внешняя отделка
		
       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor
		
ExterCond: Evaluates the present condition of the material on the exterior   Оценивает текущее состояние материала на внешней поверхности
		
       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor
		
Foundation: Type of foundation    Тип фундамента
		
       BrkTil	Brick & Tile
       CBlock	Cinder Block
       PConc	Poured Contrete	
       Slab	Slab
       Stone	Stone
       Wood	Wood
		
BsmtQual: Evaluates the height of the basement   Оценивает высоту подвала

       Ex	Excellent (100+ inches)	
       Gd	Good (90-99 inches)
       TA	Typical (80-89 inches)
       Fa	Fair (70-79 inches)
       Po	Poor (<70 inches
       NA	No Basement
		
BsmtCond: Evaluates the general condition of the basement    Оценивает общее состояние подвала

       Ex	Excellent
       Gd	Good
       TA	Typical - slight dampness allowed
       Fa	Fair - dampness or some cracking or settling
       Po	Poor - Severe cracking, settling, or wetness
       NA	No Basement
	
BsmtExposure: Refers to walkout or garden level walls     Относится к стенам на уровне пешеходной дорожки или сада

       Gd	Good Exposure
       Av	Average Exposure (split levels or foyers typically score average or above)	
       Mn	Mimimum Exposure
       No	No Exposure
       NA	No Basement
	
BsmtFinType1: Rating of basement finished area    Оценка готовой площади подвала

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement
		
BsmtFinSF1: Type 1 finished square feet    Тип 1 готовые квадратные футы

BsmtFinType2: Rating of basement finished area (if multiple types)    Оценка готовой площади подвала (при наличии нескольких типов)

       GLQ	Good Living Quarters
       ALQ	Average Living Quarters
       BLQ	Below Average Living Quarters	
       Rec	Average Rec Room
       LwQ	Low Quality
       Unf	Unfinshed
       NA	No Basement

BsmtFinSF2: Type 2 finished square feet    Тип 2 готовые квадратные футы

BsmtUnfSF: Unfinished square feet of basement area    Недостроенные квадратные метры подвальной площади

TotalBsmtSF: Total square feet of basement area       Общая площадь подвала в квадратных футах
 
Heating: Type of heating                               Тип отопления
		 
       Floor	Floor Furnace
       GasA	Gas forced warm air furnace
       GasW	Gas hot water or steam heat
       Grav	Gravity furnace	
       OthW	Hot water or steam heat other than gas
       Wall	Wall furnace
		
HeatingQC: Heating quality and condition             Качество и состояние отопления

       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       Po	Poor
		
CentralAir: Central air conditioning                Центральное кондиционирование воздуха

       N	No
       Y	Yes
		
Electrical: Electrical system                       Электрическая система

       SBrkr	Standard Circuit Breakers & Romex
       FuseA	Fuse Box over 60 AMP and all Romex wiring (Average)	
       FuseF	60 AMP Fuse Box and mostly Romex wiring (Fair)
       FuseP	60 AMP Fuse Box and mostly knob & tube wiring (poor)
       Mix	Mixed
		
1stFlrSF: First Floor square feet         Площадь первого этажа в квадратных футах
 
2ndFlrSF: Second floor square feet         Площадь второго этажа в квадратных футах

LowQualFinSF: Low quality finished square feet (all floors)      Квадратные метры с отделкой низкого качества (все этажи)
 
GrLivArea: Above grade (ground) living area square feet            Жилая площадь надземной части (цокольный этаж), кв. фут

BsmtFullBath: Basement full bathrooms                             Цокольный этаж с полностью оборудованными ванными комнатами

BsmtHalfBath: Basement half bathrooms                               Половина ванных комнат на цокольном этаже

FullBath: Full bathrooms above grade                               Полностью оборудованные ванные комнаты высшего класса

HalfBath: Half baths above grade                                     Половина ванн высшего сорта

Bedroom: Bedrooms above grade (does NOT include basement bedrooms)   Спальни выше класса (не включая спальни на цокольном этаже)

Kitchen: Kitchens above grade                                       Кухни высшего класса

KitchenQual: Kitchen quality                                      Качество кухни

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       	
TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)   Общее количество номеров выше класса (без учета ванных комнат)

Functional: Home functionality (Assume typical unless deductions are warranted)   Функциональность дома (предполагается типичной, если только не требуются вычеты)

       Typ	Typical Functionality
       Min1	Minor Deductions 1
       Min2	Minor Deductions 2
       Mod	Moderate Deductions
       Maj1	Major Deductions 1
       Maj2	Major Deductions 2
       Sev	Severely Damaged
       Sal	Salvage only
		
Fireplaces: Number of fireplaces                                 Количество каминов

FireplaceQu: Fireplace quality                                      Качество камина

       Ex	Excellent - Exceptional Masonry Fireplace
       Gd	Good - Masonry Fireplace in main level
       TA	Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
       Fa	Fair - Prefabricated Fireplace in basement
       Po	Poor - Ben Franklin Stove
       NA	No Fireplace
		
GarageType: Garage location                       Расположение гаража
		
       2Types	More than one type of garage
       Attchd	Attached to home
       Basment	Basement Garage
       BuiltIn	Built-In (Garage part of house - typically has room above garage)
       CarPort	Car Port
       Detchd	Detached from home
       NA	No Garage
		
GarageYrBlt: Year garage was built
		
GarageFinish: Interior finish of the garage

       Fin	Finished
       RFn	Rough Finished	
       Unf	Unfinished
       NA	No Garage
		
GarageCars: Size of garage in car capacity          Размер гаража в пересчете на вместимость автомобиля

GarageArea: Size of garage in square feet          Размер гаража в квадратных футах

GarageQual: Garage quality                         Качество гаража

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       NA	No Garage
		
GarageCond: Garage condition                      Состояние гаража

       Ex	Excellent
       Gd	Good
       TA	Typical/Average
       Fa	Fair
       Po	Poor
       NA	No Garage
		
PavedDrive: Paved driveway                        Мощеная подъездная дорожка

       Y	Paved 
       P	Partial Pavement
       N	Dirt/Gravel
		
WoodDeckSF: Wood deck area in square feet   Деревянная веранда SF: Площадь деревянной веранды в квадратных футах
   
OpenPorchSF: Open porch area in square feet   Открытая веранда: Площадь открытой веранды в квадратных футах

EnclosedPorch: Enclosed porch area in square feet   Закрытая веранда: Площадь закрытой веранды в квадратных футах

3SsnPorch: Three season porch area in square feet    3SsnPorch: Площадь трехсезонной веранды в квадратных футах

ScreenPorch: Screen porch area in square feet     Сетчатая веранда: Площадь сетчатой веранды в квадратных футах

PoolArea: Pool area in square feet          Площадь бассейна: Площадь бассейна в квадратных футах

PoolQC: Pool quality                    Контроль качества бассейна: Качество бассейна
		
       Ex	Excellent
       Gd	Good
       TA	Average/Typical
       Fa	Fair
       NA	No Pool
		
Fence: Fence quality            Качество ограждения
		
       GdPrv	Good Privacy
       MnPrv	Minimum Privacy
       GdWo	Good Wood
       MnWw	Minimum Wood/Wire
       NA	No Fence
	
MiscFeature: Miscellaneous feature not covered in other categories  Разное функция, не включенная в другие категории
		
       Elev	Elevator
       Gar2	2nd Garage (if not described in garage section)
       Othr	Other
       Shed	Shed (over 100 SF)
       TenC	Tennis Court
       NA	None
		
MiscVal: $Value of miscellaneous feature                 Значение другой функции

MoSold: Month Sold (MM)                       Проданный месяц

YrSold: Year Sold (YYYY)
 
SaleType: Type of sale                            Тип продажи
		
       WD 	Warranty Deed - Conventional                  Обычный Гарантийный талон
       CWD	Warranty Deed - Cash                       Наличными Гарантийный талон
       VWD	Warranty Deed - VA Loan                      Кредит VA
       New	Home just constructed and sold                Только что построенный и проданный новый дом
       COD	Court Officer Deed/Estate                       Акт судебного исполнителя / Недвижимость
       Con	Contract 15% Down payment regular terms          Первоначальный взнос по контракту 15% обычные условия
       ConLw	Contract Low Down payment and low interest      Первоначальный взнос по контракту Низкий
       ConLI	Contract Low Interest                          Низкий первоначальный взнос и низкие проценты По контракту
       ConLD	Contract Low Down                                Низкие проценты
       Oth	Other
  
SaleCondition: Condition of sale                                 Условие продажи

       Normal	Normal Sale               Нормальная продажа
       Abnorml	Abnormal Sale -  trade, foreclosure, short sale   Ненормальная продажа - обмен, обращение взыскания, короткая продажа
       AdjLand	Adjoining Land Purchase                           Покупка прилегающего земельного участка
       Alloca	Allocation - two linked properties with separate deeds, typically condo with a garage unitРаспределение - два связанных объекта недвижимости с отдельными документами, как правило, кондоминиум с гаражом
       Family	Sale between family members
       Partial	Home was not completed when last assessed (associated with New Homes)         Дом не был достроен на момент последней оценки (связан с новыми домами)
