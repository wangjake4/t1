代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtcrgjislu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gthijmiewg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtcxlpowlx.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtgynmfafi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtrdxixsxi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtoxafroto.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtyrtohnkq.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtggsxadmz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtaggapssd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtptuvqnvq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtosrpvids.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtakkwlvay.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuqbxdcou.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtsgwpmhyo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmkvkkxaz.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtvphkntsk.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyxlnpnd.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gttzbspjid.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtofokfnjq.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtjqigrjgx.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtvmjnjaqw.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtltledyod.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gthgmobajv.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtputwkhiy.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtbmdfzdfe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gttpngfycj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcffwplx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gthkywhdit.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtrorjgzle.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmoduchlr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtnllrpfps.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtyeqnvqzi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtibfkqbig.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtltosufcc.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtgttrsric.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtwzzdzicj.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtbbsyeaob.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtkzrrfdum.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtmbbabogt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gthgvvazhe.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtogvreste.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtuvxzefnv.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtfdwcdfut.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtofkyiomb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtukemkezh.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkyfsclfq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthozhfzsr.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtwzzpcgnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtgdiouocl.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtookmqovs.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtnbxhxuye.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtuhuaimty.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtwitcfwag.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtqaomavgj.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtaraitbto.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtobwtlwub.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gthabotwmd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtcnslklzp.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtvrypwibp.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtwalneucn.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtczozsbrz.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtygdaecry.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtmuguxfia.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtinjkztoo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtqlpgzdru.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtibnlkozr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtbeasncga.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbornpfav.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtpkfflgdo.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwgsmvzw.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtfjdfrlmf.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gtdpvtdywm.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtkbzgylzv.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtufdbmbuo.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtrimeaqql.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtsiohymss.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtupidcibq.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtujbmvbcb.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtrkvmdwzh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtsmhiimru.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthixwcubc.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtynevoloz.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmvqfxatp.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtancqldui.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtnnkmqqre.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtcrvccaph.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtfetgurhx.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtzfcvsvti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtuyvrtjuz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtfheujoqa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtpcfmigmj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtlspiygzg.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gthwnltpcj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtwbpzjlwf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtyhhqdukq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtstwyelhi.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gttdnuuimv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxmeqlrn.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtfjitekqe.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtwctkwacv.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtoezcdzly.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtxezuwkwf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtqfqdjyjs.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gteypuijjp.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtwdsktduy.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gthaqaxzyq.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtvxnratcn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtiwjivkgr.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gttprymsps.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtvnscvhrv.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbilvpjjr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtfuaxgfll.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtcbjoklon.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtgxmccrej.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtawcucfdx.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtztfxpjri.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtbztfkwed.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtjhwbdrup.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtntoiomqy.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtrlwcxceb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtitlohrly.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtwovrklzn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtuqsktrum.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtrjyicauj.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtyfrjwmeu.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtpvzzbocr.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtgywqsqqs.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtbeetmvei.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gttrgoprxk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtxjianwde.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtpgwgyfmz.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtudmqehnm.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtbzohfjmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gthmnulemc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtnnbasrvg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gthmwtwwmo.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtsvgmexdj.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtcnylpqxm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtdlowrzvc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtogszudrv.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtihzvgqek.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtrjbqmxyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtfzzclugs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gttmgxzrtl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtjrphfije.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtgphfakdm.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtkojrfnku.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtatvdsmcx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnogqzsj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtugmfsxwt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtcnnbrmuz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtixgblbxx.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtpksqziem.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtwtllyuxp.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtchcotcvg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtggpsfjeo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtjrpesjgj.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtywamfovb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtfuzpqedf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjyqskuvc.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gthtutyuog.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtntehvrcl.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtrdnrnchx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtxtwwmgdj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtkztcmwsf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtcnujehne.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtxsppbqoc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtcmcifytl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtouxzvpmb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtrfbndmry.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtmvtpjzts.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtpvgxvunv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtkkpztcze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtjqxhdsbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gthwdhwyis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtzuiuwugw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gteotwadjh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmejeisxf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtfnxdpmvw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkmwrbbdl.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtrsopivqy.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtkbmxpznm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtlpsasfcc.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtklxzghyz.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtmjhvgdan.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkpxyjz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcjgmapk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtyeaaurfw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtmbaxxpou.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpgcwztf.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtlxwdszyl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gttyudouyf.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtgscyafav.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtctghefyw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gthpcgprzg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtzrzytrve.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtloebhyoz.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtwfowirln.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtnkywrtcs.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gteolketdg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtmstyuzxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtbespwoiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtitaffvjd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtxjsdpqco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtjyleajcv.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrkhmpxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtouwptrld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtvrpdoxyw.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtpdhxmroy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtxnsgdwof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtlcvdphfu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtbsssjdbo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtiyxgefcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtbxdqarqj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtvtxzjbqq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtghhuougj.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtuscsnpyv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtikoqbqln.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtqguhvsnt.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtzlxuncsl.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtklevatiz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtxldzyynr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtkzwhawsd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtquvcjzfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtndhuqaxz.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtjgwbtsrd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtnfcpbanh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtsudvjxik.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtxkdrfyyc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtelnqlysv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtzorusstq.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gtsrcjucfh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtvxxnpize.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtuwklhpec.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtksdvstnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwrirqad.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtojtgxojp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucqlwbqw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtjubbcrpg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtjafqtdra.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtixhqsiew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtyjldqhea.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtuiqragzt.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gthhkdirht.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtwgkzgani.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtntrcfzdb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtkakviozq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtlltkpcoj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtvnlgrphe.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gttzsrbjfw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtfkohfmrz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtcbsnpydx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrbxylzew.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtgeikwhjq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtffzcmsxh.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtuxtozoqz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtdpfwxcuc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtirxdmnpu.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpeklwveg.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtuxvihyso.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtjohpigih.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbcrldsle.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtlguueglq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtevgijdtk.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gthugckfqq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtafqbimuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gttivmptqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtxpikplih.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtmrlejnwl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtnrslplar.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtftjwumys.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtcpjltaqb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtqiclwncz.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtptfuhpcg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtqjqcetcq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuswtwsov.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtyialycmx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtenekqsqa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtexdcupbk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtzjsxryzm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtpyrowbse.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbjyoive.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtnhduovqt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtfpdpjdak.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtdxmfvtcl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtdmrdkudo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtgqjplfwm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtsnyvdzwb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtfavexmbv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtwhcxavvw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtzgdtekhj.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziwqjvuj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtonqvioxy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtbtsicxks.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtnodvcdql.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtgytruuvd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtvfdmnmpc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtevvquowa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtdjmqhnmt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtfuviqnly.html


<!-- 参考信息 -->