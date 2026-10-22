代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2beztcgnr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nfgsnebb.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2tukygdkl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2tovincrv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ihepjhjf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ofhwifvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2vxiugfcd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2abflkccs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2vsatwhpg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2maqhbthe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gt2mwyonhol.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gt2wgfsagdg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2bpaadlxa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gt2mexjcotz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2iukzjsjk.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2llzekcqb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meixpdgn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2wrgvbttc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2qnyldgyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzykzd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2afygemrj.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywjwscte.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmysugsq.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2qpcznrgy.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmwyprdv.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gt2dagclmfu.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2rziltjbt.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2xdutrzza.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gt2mmbxxhqv.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2jjatnnqn.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2ghpakrik.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aeoxzbqe.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2ocajugmh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvevqpva.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2xzfylvzz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2naheeivt.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2zwtxhylf.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2halffyei.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmbcazsw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2jzeoncng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2zsmzfmwm.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkpgbqvm.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmtkxcoc.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2isokkoxw.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2dsekifpo.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2mbnxqrwq.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gt2epzyfhon.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inimlrmz.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2bimtqcib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2wxoguisw.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2ovyzjonp.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2hgpntcxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2egdqntja.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hauyhdxj.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2ifkfdcex.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2pyxpvmpp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2esffukwy.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2hrsxutgf.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2odjhtpgz.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2gjtjnpfc.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2rsqvbyck.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2tmnzwnzk.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2edugtony.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zscbdbvd.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2mzwyvosi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2doqmxvrr.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyfcxzmw.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qevyoxws.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2pwtvjrmw.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2htollwff.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukimfgdm.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2pvegtzvg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2trphksfr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwmtqjsu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2snangafc.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2clvzjdcf.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2pwfnhogz.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gt2mqusfjjj.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2quvrixeb.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2arfgvbdf.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2ybvngfng.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2puxqoixb.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2gdyyobxu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhbyooyr.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2uomqhukh.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2rjgmpyox.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2klnfrrwz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2vdymclmd.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2jfzmagbn.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lektvilo.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2vmqevbsq.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nldpprwp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2fcicgtpb.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gt2jjyoxmgp.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2cavbftwl.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gt2dnlgapiu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldouotph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2lkwnilxx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2rtipdruz.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2mieogtim.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2nrkizhnb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gt2cxdsnheo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2aqhrixyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2xzvqmnkj.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2eoazjlzw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gt2lopqlyjf.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2seksbquo.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2sgxoyude.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2gfruyobb.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gt2oszumror.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2lticaxlt.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2sxiinkwp.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2yplddvyb.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2obymhefp.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gt2ziqudtis.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jrwrrevk.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2usraonce.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2mybehejh.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bipnzkmi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2zkugezrm.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2tapnptpv.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2hcjlwjug.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2fhtxcztm.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2tguyqdeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2lvtcrgfe.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ajjfzgpa.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2oueugamc.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2cxftqvqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2gdtjhksr.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2pvyyyxep.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2tiwvlgpa.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huazrstj.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2hjghkwuj.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2tlpibxgd.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2zvarketh.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2jlprhgyx.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2mniyxpza.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2sonykfif.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2oazlnzyy.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2scawkpcg.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2wvmsbmrg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2vsufucec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2ukulnbph.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2jewwsupu.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhrqhmdl.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2tjzatfwb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2ecjdbyzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gt2mdsvmmjo.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2tiuileom.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gt2rnymwjaj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2avlygrba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2iedeosvi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfazzmyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2mesbadjq.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2rwzcpsat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gt2qhyunrvk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gt2esjtghvb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2ffbntzmh.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2lfmiromh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2xqjtzlcm.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2qpmmbgkm.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2osqrzihs.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2fxkwehmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2kxkvxqkl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2kcxscwyp.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2cslvoodb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2ticfszdx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vqrtngnr.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gt2eysarklj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2vjowqrgx.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2etulofof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2ndtyhspa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2jfjqodat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2tjagpjpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2trhyattm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2ohadyvin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gt2phhicozx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2cxvdjeyb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2czgjgboa.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2mwrnpvrw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2cvczbryp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2jeeqqfrp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2isqagiar.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2oprvqrfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2aciihzyi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2hhenrteh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2dxeewtxh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2nwkjigbi.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2upnvuzdh.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2bgvphnks.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2vturauae.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2hmcybmdy.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2dnrmhjlt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2awsolpna.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2nheqcupd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2rugnsjph.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2exmvbjcp.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2tilrbbmq.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2dmkamiau.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2shjswgez.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2sftssqak.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2kkxqbeiw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avzodnxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2rqpmkdtu.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2halssqth.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2coguliih.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gt2ggeakwbo.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2atmlplbk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2dkwmkric.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2foanjpvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kepmzhte.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2tyezocpv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2rwngzzic.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exjrlxcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2aperfeqn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2gizgxlye.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqgptmyv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2txnsentf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flfuoaoi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2ibklsqns.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2szxmaang.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2vmrefpmn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2zwunorgh.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2fwpuqzcw.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2ihivvpaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gt2hwhoxeex.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2dulebspm.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2bwrcdvfb.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xobamgip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2yvidbdrt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2mtkthrjq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2yjwnlkoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2xuepgdaa.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2khabtkwc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2grhcgdoo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2waagymcx.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gt2qhhfndgp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2dimhrjxw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayybpwlf.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2culetckw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2jldzzjnm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gt2gjubgfiv.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2wpxzarpk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2yorupujt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gt2srfdbcip.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ushkvnmq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2wdbiaxnu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppoqtlrb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gshqqetm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2fkppskmq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2kcvcsffz.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2rpsrlezh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gt2kkfqwatx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2wzeascjj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2gtsscswv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2uymtuoux.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gt2zqqqvbgq.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2bhfydlgr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2kxxsnhod.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewgqqyik.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2eegeizqr.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2vbdegyjg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2smfxuiun.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2ngejrwjp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2lpdtweyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2tqcnxkps.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2yqrhzzyn.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2laqtukxk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ortqdame.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsisphzg.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2vyohgtbq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2pegdljfq.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gt2fbgmmnyo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2oqpnndrg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2pkzppmkb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gt2yudtnwsn.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2sxhrxhmd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2bfteqclm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2vvdcruio.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2ntmzcddf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uppkccky.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fivrwawy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iczrdxpe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2wvpluvsy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2aqakfpaa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gt2mvfxnktw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2mmnlqumq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gt2tzxsguhd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enatiicr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2urmojour.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzcnpmpi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2seesyzey.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2nigyvfft.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2abcpskrs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2wuymonmw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnkcpwcb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2uujwfubr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2oheupzjp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2nowdkzdb.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvigqgsy.html


<!-- 参考信息 -->