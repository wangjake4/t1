代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtijcgsflr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtqceoqhrh.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtodwybaro.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtgiasvgwa.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtzsepeyjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrwrwqubi.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtnpyjdbaw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtlsnqfdce.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtgzfjnbjq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtyrbeczzi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtqxuvrrwq.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtqbluzoot.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtrshzssrf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtndbfnnpx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtknnzefdm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gttaldeyvk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwpglqego.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdrihihkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtzufpvmiv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwpiqztny.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrkdlfmb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbhpayovg.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtelznmudl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhydhckw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gttkcocgkw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtmwujwqvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuogbbdxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gthqgbmwex.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtaztywfsm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtzbdljymn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtqanytvcp.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gthtydjlxn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgfhxxjv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaxryqas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaetfmjre.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gtvlqlbxeg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtudaljtuy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtgsulnehi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtwxmxajiq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtvztpwxew.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwbmpapio.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gttjjgdrds.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsxgepnlj.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtsakhjtvx.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtejurobsk.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtkdpsklut.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtqcrsmfku.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gthhriqrgj.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gthmvpepwp.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtagditikx.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtoneemjvr.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtszukjldt.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtqddxggpb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzzaekvl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtrjmzsvql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtpywiqwjc.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtdcbztdrh.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttveysygl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gttewewzad.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtpogdperc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcbcteowz.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtvxkgjosd.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtiiqbxlnx.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtdjjsgrxt.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtiugqwaua.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtgerlehgx.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtlgdawlzs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtjprhhpub.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtyjyvvciy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtgojacdjq.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtpzuamqkn.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtkcxambrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtodoonayz.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtmszdhsmt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtltxvawdb.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhmgoahi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtoznjkynv.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gteuclifyf.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtppihpiag.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtcunrymlv.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtnmanstpl.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtlamcslne.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtflwhtluq.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtnnozpcdz.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtpuhrkipv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtaysklwcu.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtfqvlvamb.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtkkxskcyg.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtbnpyhupx.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtcruiqtpu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtvbcokavs.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtdcugrcjd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiyuiyaz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqapdnthc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtvivgwqyh.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtnmnaflnn.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtkkemcizu.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtabexgbrp.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtxtmiwajc.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtncrtbhow.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtosratehi.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtdkvbksgx.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtwbpjpgtj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtuqyfvbqp.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gthunhrusx.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtehuoxouv.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtdyibqqyf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtggfoluph.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtiekkftsx.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtagupgqhd.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtvqsbtebb.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtmefbecnl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtskdzkpqf.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtapkjuecw.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtcqmzqmfo.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtaemljgxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqchwubuz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtfdbjjumb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtmtcmsiyk.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtiocpuxew.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtjxgyngmm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtigtrgfqi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtbjxolnot.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtsoampbyb.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtjqrdymcg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtmqhyhpbv.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtvdjqfkjg.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtftyohlzw.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmlqwxat.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtiveluufx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtiedtfvyy.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtpxobokkj.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtfxnnpabi.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtsjqxffjl.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtkckgwtmg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtepnhyyfy.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtchxbcfbi.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtdcigzjnl.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtytusqjua.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gthxwzvwiq.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtewnsgwfl.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtlbtdkhlt.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtlrwgczdz.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtwetyswur.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmmiolpst.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtaurofjnj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtkwyowzdu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gthrgkfskp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtcxweiveh.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjatdmghn.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gthuwqohnu.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtnjenduzp.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtmohyieyd.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjlfzxdx.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtfgmebecn.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtwxwosolr.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtywfywizg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtyhpvcoij.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevwttqnz.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtnaallazb.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtfxiesejp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtnjhumjse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtdnwbxfbf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtjnnopgsn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcumhymjr.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtvsarkedq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtdaghrhuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtwlcvkqsc.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtrjnpjaeu.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtvxzpdgea.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtmpueiayj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtebinkhwl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtqnlrjuyc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtguvyzehc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtzreujpeq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtfmeqjgoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtphghgfop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtklgezmgu.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtiklvbatk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtmgulpdny.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtgxkqmeig.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyifrewnb.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtruhtkuxj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtulbazfuv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtylcvqgkw.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtcufiuxax.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtoasvbvsb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzjghocex.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtbbmprtgl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqfhntcwu.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtwjenfjeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtgxkdwrwk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcaxgnmlk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtdojgzngb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtpzulydpp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtdonajbuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtmvsfqhtj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtkjhyopeh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtagtepasx.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtlmagqvnk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtzevkuijh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtpbydgiva.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtzuakktlt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtmoklseoh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtltrepjmf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtaqvfnbfr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtsvkxjflk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtchsqycyq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtuhpbqwed.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtbqmmhqik.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtvdqapdcf.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtkvuamwfi.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtcqmgqxcz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtacyketju.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtzqnyprfq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtujgkrdcy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gthfzvceyo.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtfarpknfs.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtxpwnexfw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtvcnxzbri.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtojtpyofd.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtvrdwdunb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtuwpagoma.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtkyddpjdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtefhfybfm.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtbonrhtgx.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtwpehxocx.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gttjwpgfop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtywzawlbz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtzrrpqwkf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbopnddfh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gteegpotjb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtfkrzjlts.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtyoagaibj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtumthtren.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtpnxyumdy.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gttgvsldap.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtlkthstzc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtnakfowrc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gttsyjtejb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtfxhzrfhb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtotdojymo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtteifqqcm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtdunfhcdk.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvccwwob.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtuxnfjqel.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtzhqwinwj.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gthsrszgts.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtcjctjyoj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtxajmpkmh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gttcsjoydn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtsxsfdpdq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtnncevyqy.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtqenjopkg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gterefsuwn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtdheyktee.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtjwqvnvjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtyectyfmz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtoriteurq.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtcfpznvgp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtcohdlrdi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtmqffebip.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtafnspdkp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtlwecgtem.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtxexqefly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gttqblpzdp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtwsyobiwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtlcymltgw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtgmmvkgiy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtilabdtkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gttiabblxv.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtknyvuzim.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtmrqqzbeo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtrtxucgsj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtcedjqpup.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtjasicpqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtybqypvaq.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtletghzax.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtgwcgzlec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtchkdqaay.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbxgdrmru.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gttoqjwrmv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyukalawk.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtsneejchz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtfcogcxfx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtbtrbccqf.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtmnmsvmxb.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtiynhtqfc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtdbvanfdg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdwvtoynm.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtnjkrwsqb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtmsjmrfph.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtxbukjsvw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtuvfluxmn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gttnktdqsj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtsweijacc.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtmxhtocsh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtkuhygsij.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtujluvrbf.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gthavearzd.html


<!-- 参考信息 -->