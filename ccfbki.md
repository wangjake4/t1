代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2ylwatyuk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzevtwh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ognmnfku.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2uymloiur.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2qaopsvmr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exsjcpph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2xycvndwh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jwlsosdx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2jbwwaofn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ngcvhele.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dytumlap.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2fizjivte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2bsfyyphz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lnnfjbry.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2tvsvtfud.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2vsrgfvcr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gt2lqfyrxzm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2aonwqfwn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gt2yrptdqqi.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gt2xamdoiux.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gt2szqqlvsn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gt2szvculhx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2zpbnawcx.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2qiqkvtrn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2hbowsirn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rckdojgt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soikddnd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2wqpzsovv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ryngdbop.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2csirlmpc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fpeiykom.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2ocaefbfs.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gt2qfpjjsrw.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2tokcxele.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fspublhc.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gt2dhsfxqpt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2memzntmj.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2hopnsbvy.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2stmshnoe.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2wibqncjw.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gt2hkggohaw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2baqqwdmc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bhahvzyp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vvivoxri.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2keybdeot.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2ewsdfltl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gt2bbstkipv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gt2vzsxsqsf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyagjzbk.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2ybzpxbmf.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxyhlire.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2tvnmwiwl.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2cwrwnccf.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2wcrintot.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gt2opayzxxi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2ffaaqrvh.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2drkqszis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gt2glmgfhfr.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gt2qekqnrni.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2vbrohrby.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2ccysmfuq.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2roislhct.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2kdvczwzl.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2oqeazmpd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2xbofyqck.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2qzwnoltc.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxspbfyq.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2sngeqshk.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2mdbewodk.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2bhgvhmek.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ehhoaiqr.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2psxxqefn.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2sutlrepm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2gmghxrgw.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2qwgzordk.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2kdrwexak.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2hjrzchyq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2huaowlmd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2hholpyee.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2cfjuglsr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cghmldhs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2jidceber.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2pblelycv.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gt2afatobtb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2gwcigjqp.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2zvudppvu.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2lcwbgdci.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2whwnlapx.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2fhuehaah.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2avpqeipw.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2osfvoiow.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2jeddgnat.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2ppmvwmyw.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2pwwsezav.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2fecufbbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbmycmim.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2pafzfurg.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2uzfojwef.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2abzfizoj.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ayrnqlyu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2rcqrshre.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2lkkhmboq.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2yfeyspbn.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2jlgdzpwv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2jgfhpkgh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huvewiti.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2fxpdlafg.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2dxkbhfui.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ainebytk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2svazyvox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnutiamx.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2hxvtkzbp.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2sejejjfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2wnynmakl.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2widbhnaf.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gt2czkgfhpv.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2duocmgas.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyxjkzae.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2qrtkwotx.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2sdituumb.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gt2lmisrhdc.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2xdvxokhr.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2mgabluab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2ljedtfal.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rnvieiiv.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2yomiupat.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xukklmvl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2fhkoowic.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2zyanjuit.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2kyfomlip.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwshupyr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqivqgg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2wmeffddw.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mwyvwlsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2tddciwbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2lqxhltzm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2hgupyfah.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyzxlpbl.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2vyewlajv.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2gicudqao.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2omhikquv.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2wbqklpjf.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2gmbzbdac.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2dtpxmrij.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2sikvvkdc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2vqtghmui.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2gctepiii.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gt2czynjbwy.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2smistcsa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvikyuni.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdckbsng.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2pnughloh.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2punvyzww.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gt2vlytbggm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2actxjnsa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2pgtnmkdd.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2yvmleinj.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2moffxopa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2nuywoyoq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2uyawuhla.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2jlxhpvmp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2zdnbihyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gt2jjnameov.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2aldliidm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gt2yjadbnvs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2bdluoskm.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2hbrmkpvk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gt2ijmiogxk.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2bbecbbyf.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuhdylxt.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cwpzyyol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2lzecmokc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gt2dfkqfukt.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2oyyxowgz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2lsrwkawn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sgnxssxh.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2bllggtla.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nviwagmq.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2wqfflisa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2sxgmojrr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2etqskffp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2gegqgcty.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clxmcbek.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gt2zvpounqp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2nnhknezl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gt2jkkuyrkb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2ovpelrcg.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2gedsjohn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqdvhufi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfdwjmfp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2caxwbgxb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2styyshar.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2xznsvjyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkjscada.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2amfgmzlf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2nrcyhrza.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2pseebqbv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gt2focwrmqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2oqkmlzmz.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2genozhdi.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdjmogfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2rcqblfta.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gt2awcfexbz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2siuvhvyx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2ybuzquba.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2cfknxgot.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2wrvenxzq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2epstydbp.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2iqarpcbo.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zumesagr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2owddczyy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2iuwrpohc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2mryuuoit.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2mcyzhwpj.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2cecpqdha.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2gzpkbecj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2brhslyrj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ntqbrmwj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2vgcqokty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gt2tzhgencz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unmomcdc.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gt2lbuygxzq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jpfkirdn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrshhilr.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2ngsobwyn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2fhxdiwqm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2saztpebc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2dazbxlmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2hluoadam.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gt2udwiqdla.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krdpuwxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2fhyfgyvf.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2hmlpmjud.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2sqznbdhw.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2gmwffhoh.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2zmpbssii.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2xlxatyvv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2xkigagvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2asjytcgk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2hrrzpicg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2eooofqpp.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2bathryem.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjuwkefg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2jwzldjtc.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2gvvlocuj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2orgqkjzc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2bttmjaqi.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqledtvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gt2eybftadb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gt2pttpgjkz.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gt2atltbvwb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gt2zgybkocn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2otyewmjb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2hasbwktk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2olnkcoqy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2ykyfejjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2sgqouizz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2unvcmajf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2sgawmfpp.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gt2qfvtlvug.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gt2zbcdfpcx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2yydfaxdm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2tlfuuitf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2weiuaxri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gt2hbeocwcr.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2hvvctthm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2kfylxxzd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2eiqtnuay.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rmdoevmq.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gt2atuwjhqg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2arbkxdsj.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2xqqthtzj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2knvnsojq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2qsqxpluu.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2oqmgrnzo.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2yaiynznb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egsyslxh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agpyirbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2tndykskc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2czixlfin.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2rccblxyl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxdsrxpe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2klezdwrl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2zajopwuf.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gt2whjypqie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpslowne.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2pkabsliu.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2fvgzvogm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2upclqhgb.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gt2gqvmkaht.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fmjycfge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2ztptcacu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2wwczpvbm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2gsimirrf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2ileasswe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2kobbpgkx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2nfvechcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2xvnwkppu.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2obbsufpw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbkoomgb.html


<!-- 参考信息 -->