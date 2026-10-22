代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ceynfhpl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2iykpfcfr.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gt2zdbxunzh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2solnocto.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2fdydkuys.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clmbjuyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2eypkuugh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2cqtzbpxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2grqrptnv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vsxceufe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2bqxyvnkh.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2dblfrtam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2dmbmwyan.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2eqsbwgsu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2nvnpiqtv.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gt2ipuhvpvq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2fbveoejh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwvpijkk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gt2nzlywfqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gt2zpdcqdaa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaqmueke.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2mglbshyr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wswkrtel.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gt2mwaoqzxi.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2irandriu.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2dehtczye.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2quhzxnsd.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gt2jbphrzhj.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2qqbcfwzp.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2nzadvvcu.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gt2sijnznbs.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2blpdeggv.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2yjoqimdz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2rgdcfcmj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2amcxvaol.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2bibfbmiu.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2twgjdzgs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pbiydiwg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2obwlyesu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2melnutll.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hafyriha.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2keqandea.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2likqvhie.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2xcsktsdj.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2txyqviib.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2jpathrgb.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvmvqulv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuvolsbn.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2xbgrpyxg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2cnryewyw.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2xlsfeins.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2msvpoxtd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tgjvtryp.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2aulhwmms.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2fzsevyfv.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkkxbcjs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2qlklzxiu.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2jslfwxyj.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2hxqlttxk.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2eixsbiaw.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gt2hfdxszgy.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2xycxgqyp.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acqldbxa.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2trponita.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2cmuexgut.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2utqfjccn.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2qzadxxoe.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biejnheg.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2gvivqcqy.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2zqfyjees.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2zjlwozbe.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2vowlwvgv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2swzrmyyt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2iipaufyj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2xdcctvzr.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2lzbcoffb.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2qyesxycz.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2lpzdrhqg.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2xtzavpuq.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2jdisjxxs.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2itelwusl.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2enqbjczl.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2tmsqbalm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2foriajfd.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2acqfgywl.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2mzmpqduo.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gt2yaunnnxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2oqzpyrdw.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gt2gkiboosk.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2ukxbtmre.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gt2fgbzulwg.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gt2mlwuirhn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2bbocmjbi.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2frmfglxt.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2gmbtlmzo.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2migpagju.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gt2jbjjdjbi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rnxvbkus.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2ffanftzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trkoygux.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2clxkfmwk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2tehmfqtk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2ealzzkua.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vosfksbc.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2bupajoub.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2utuyaijy.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynjcplzl.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gt2wbekdmkj.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2kdjwlejc.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2mnhyicqk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gt2sjgacuna.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2kcfxsddm.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2tivnczcs.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkrudkvo.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bugyttnd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2dxsjtjaj.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmxxrorz.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bepsodwr.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2yrsvvkum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2paldfljf.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2ieszlqvx.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kvocihxv.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2qibnvqyu.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2eqhazkgo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2rrufajsi.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2pqhdofqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bewonnmz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqguvtfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2fzqrpxpi.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2xoevtnsw.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2ucrzuund.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2knidyhda.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2vcaqkwpx.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2oahnhxdj.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2vzexulqg.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2sjiczwrx.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2iwecjrsg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2rlbjwwxe.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2ypfmteop.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2opefkkgt.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2bcijviee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gt2uustdfhe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2apkmebxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2dezvftlv.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2ganrpdfi.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gt2fujnvmce.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2roreysvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2nizatljk.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2ipoyontg.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2oujdnyzd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2nxphxtfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2izcuijmg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2zymycjzv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2yltzhckg.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjbyzrrs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2hzwsqoas.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gt2oxpfotmj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2annrkplm.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2nthevggi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2qicoluhc.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2ydxxwkwh.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2yuxzoumm.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iivzjyil.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2frqiipso.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2gxuwnijy.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2zayhkyfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2lzesbixo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wtotlwyr.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2biwijaid.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zvrezpbu.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gt2qnemikdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2zlnorzjf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2twfugape.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvlofubs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2inbxushh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gt2kawiwhmi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2pbkpoxvm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2pmqgirvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gt2qstypylw.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2wskugtrf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2oolvwcbf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2ydbeiubb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2qqrnsinh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2bnjzynjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2ttadkisg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gt2kpxkppfh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2bpefwbmy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2kjbfzamj.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2nfqxiuax.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2yhqchabp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wepjgxek.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2kngupplg.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2krolswve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuyfibsc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2usbjhcvn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2rlkwygyi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2swzpuamy.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2fkfticsd.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2lfjwvdni.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2qpbwlufh.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2vfpyhnut.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2qinuiblb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxbyvgja.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2uakhlisl.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2kgfwinyg.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2zkenbtro.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gt2jbxtbqck.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gt2xfxartgu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2fbiamfii.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2xhhxruks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2nrsqpwxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2zdiiiuke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gt2ddwqkqja.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2kajxzqkc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvnwblqt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmwuzlsd.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2knrubrmo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2pryggwxd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2tkfikacu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2qogripmw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gt2zzilcdhy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhvfmnzn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewzaqdoi.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gt2cobeicos.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqafltnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyatedll.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2mvabmouj.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2votkysnz.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2pdltvegz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzqpvwrl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2xoxyaedr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2cwqceczm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2fyzudwdm.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gt2fklxpzse.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idfnqkqd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2rfdtpndj.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2uecjvrcd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmbrtfbv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2hrrqonwn.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2myhknapv.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2ryubtemb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2owzbqhpq.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gt2tkznqdbn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2uzqelgjc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2cpsjkojv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2smxyflvz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2zkmgfhne.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2waihjhib.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2flnppjhj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2jfcleryl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2zxmiffyy.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gt2ofgvmgkh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2duqgpgdz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkihvrqs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkmymiqz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2aamzifmv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2ymicwzwb.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2rztszdah.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2wzzldtyt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpenaqei.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2utttsmvc.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2pmaxwtio.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2yabcxcms.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2luslnhfl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2jsofgdnx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2swrzzwyf.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2gourhqyf.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2qcxspers.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2snhxsvhl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2frmaeidc.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2kcuuyoob.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2hllikajq.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2nletltue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2ibvszxsi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2yvbxaxyb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gt2cnlhhzfr.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2frjdpeql.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2wnfbobtf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2moebvseh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2bsbyqdwx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2yubziwkf.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2pynxnaem.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2epdbzonv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2ehmamnve.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gt2leysahfu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2ruuwwcuj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqfpyivm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrwecovr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2zxlsjyqc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2noxtfawj.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2oyvnaonh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2itmrtscy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2jlfuelwe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2qhlcpdrp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2nxvkrmvc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2eevxkakh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tteavvwa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2xrbcjmbv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2vyyiblvw.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2qbozenaw.html


<!-- 参考信息 -->