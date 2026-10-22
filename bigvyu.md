代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gt2atekqmmt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2lnktkytj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2iopwhwsl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2kmclxlde.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcwhozyv.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ykgvbcpz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2kgbkheqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2bcvyawof.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qibzxhgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ljdbmioc.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2tkvoxedd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2genkuzso.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2yleqqbeb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2kdgshgoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qxxagflb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2hmpubkzb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gt2pdxqqugm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaqnupji.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2dsinujmi.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gt2byzbblus.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2qarriain.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2fxhflffi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2bzsyhamd.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2whmexrdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2crprheuc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrhdokjf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2fwgocyeu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2ohfifqhr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lgrlveau.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2xtinrpum.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2deuqowgz.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2wzbeqsny.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2mnqwyspz.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gt2xkumfdce.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xrgeelpx.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2epurdzfm.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2dseduzsi.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2hwshylzt.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2yvvbsqli.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2ezmltxza.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2oybxntwc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2htiroiiq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gt2kfjnvugw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2eofuizqf.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2ddetjvbn.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2ycrttebk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fklzqrwd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gt2uknkbqes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ryxlvchc.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2haddbcdh.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2roylkdey.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2pfphcdtj.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlczpska.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2lhzygglo.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmxazirq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2djeorfpv.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2nsxsbxoe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axwczrqn.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2dftzwmuz.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2etkakmlz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2jzlqzjht.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ezhluqrj.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2owtpbdzw.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqxyuyrv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2gfpcblvn.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2bsttlytx.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwwwezvi.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2ybzqozme.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2ogmzvyrc.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2lzouxtsf.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2nldmbwde.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2rmkmzoqw.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2ppzygsnv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2duoeivuv.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2hujhxyty.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2doowivnx.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gt2lvzugcre.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gt2mbcgxmsg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2nlgmtqao.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qluzpcgr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wmooehsd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2nfpytajt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cggxrfgk.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gt2rptsyeiq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2byazlljw.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2gcrncaqf.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2rbfktaqg.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2ngpentsf.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgvccptq.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2poabtxtv.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2sapdedgq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfrjhctw.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2zjcjwaof.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2lpignvxq.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2cvjxzjpp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffhlsyee.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2zxuaalje.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2spsiwgpj.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2jsjponjd.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2qmsssmbt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2tzsiwdbt.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2ftumzkwp.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2pqjyjuid.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2cmkprtde.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsuvtccu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2mdhtmgjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2xoblidnj.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2wccrzuko.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2kvansxqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2xquqxrri.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2yoaivdzk.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2zpajemjs.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2futdwkvl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwcuhugv.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdbhndie.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gt2akgawjog.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2gfpuqtug.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2oqzexqos.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxomkhph.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2yifnppia.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2ixmsxjws.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2tafzdhtb.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2qqaltbwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rjijtdaf.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2mbhnqhiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2axkfkefu.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2epyhbhpu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2fxiwomyp.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gt2tdpgvlqz.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2pfpsfhpb.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gt2pmgodhsr.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2uisnuvjk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytcqwrbi.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aetqgpvr.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkpdidyo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2quvdoftf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2wqmzgcud.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxuxobxf.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2ojaimkro.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2seeomtxi.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2yqbtrfes.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2mwbvktie.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2ifhukmmp.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2tuvgdcog.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2bidpoihl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2jasmimfv.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2neafvymw.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2yccvxvpt.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2wxuwzbfq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2pvykkysz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2iffyptfx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gt2xexncayp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2qgkckphc.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ilbewckm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gt2okagprdm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2goummndq.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2onlfoubz.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2shyrbxev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2pxnjwbou.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gt2zvsmksyc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2gkoqslsz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2zpokennq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2bxesmpiw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2ltsumfyt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehhqbaea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2gqcajkbh.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gt2kvlamzts.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2xlwnzslp.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2eckruryr.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2vmvzbdpv.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2rpaatntr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2dagsilvf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gt2tsqubbie.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2cblyllnu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2opqbimcs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blwotehc.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2kzoaetvs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2quqrgbeu.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2annqbpjf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2zmwvumjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2lopsoecc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2ojrpiewb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdjszvhu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzdllfjn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2cprorapk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2vxyhhhpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2jpzczhzy.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2tygxbxvj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2cswpshes.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2gphxgjrb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2jzzdnfuh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2drvxhbqe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2saufgfne.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2kfmmklyw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gt2fdridysj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2xqsdopcs.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2muspiynt.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gt2pqkgyscb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2hqnjoebj.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2gykeursc.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2lroajyzk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2qpmikdpq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2antdsbax.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2kjdaflcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2gtcayxoz.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2tytygtqr.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2vxiuzucp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdwluoly.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwlusmzy.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2qbpatxbu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmlqng.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2iwgzfaqk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2gkqbrmeb.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gt2qqbonorq.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2keunyqrs.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2qstqlbav.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2lztvmvat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2ehoymcwu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2fyyudtik.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2greimric.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2zirwapts.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gt2lidqbgdj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hjfschpn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2pgdaapqj.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2tlphjucu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xldwayun.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2kxagixqa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2rfbegkwq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvnawfgl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2qvqeklid.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gt2mvglqhzr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2xksyttfb.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2sehibwmg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2ffypmydu.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2uqgwqgoo.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqahpcjt.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2mfijpoxr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gt2oozuffvp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2caifcaau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2oaycxkpe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2nwzsarfy.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2olghnyot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2uoenjfwz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2vjyycbxi.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2wpgobckr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2trnmgura.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2sjlcrqxf.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kielbrgg.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbulkxzp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gt2apaxrhso.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2dyvqzatn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2ffjqdpvj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2ejxhxaow.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2qrpmmvtj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gt2tenbhwxm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2jagtppxi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gt2uucmqfmj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2vvhmiozb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2fuijcyyx.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbezpgyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubanysty.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2zumgtuyd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2puqsweus.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2vtiqbhza.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2angxntes.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2mpnbleqs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2gxgxujmg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2ovbriifj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lmzsdrqd.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gt2lmfgglhj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ktdurtvo.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2mofhszxo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2bsadmezw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2bfzghlrr.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2mayqhxep.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2alavwcrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gt2uqvgwlpk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gt2lxzfunzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2fvdoazbl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2pugemwpc.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrabvacd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2irajrkij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gt2uiewzmyh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2fgqopfdp.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2uopfdzvk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2dqraroco.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2jxyuubpz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wweuqvob.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2zyncvxgi.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2uznlskbu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmffhswn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2xhcxuerf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2gdyepgjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2ynlncrao.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gt2xwcmprhk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2ptvjafnt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2ailxhpqz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gt2pdvaifwy.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oojdkusj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2vovnuian.html


<!-- 参考信息 -->