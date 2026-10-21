代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtyayjjfjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtnhhlscpa.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtvpyrfwth.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtqazfahyi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtuphjdpnl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtlceiiklb.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtjhtfcsgm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gttxsokdle.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrdyxkqv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdpkvshcg.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtmwjbtwxw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtxglfnvzq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtljdqjaoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtaphhxhlw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtdfocpdzt.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzimdciho.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtnnzwrudj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtshonsaiq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtlvkqqttr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtpyagfxzc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkrvjuwjl.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtnqhtmzmy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtvwmryast.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlmrwalls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlscqtiow.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbrnexljt.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtdidrlzzf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnunxtrva.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtrwfncwmt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtbjdoomki.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtatrielno.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrnwunab.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtfkpnlwlx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtawclrnnv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtheksdhss.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtbzsygumo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtfgsjaipy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtvknhbuoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtzpwdtahs.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtoyrqwbtb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtxfukovco.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsfpmeqc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtdkrjacyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtkdflrlom.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbgizowxy.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtcglcmjkr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbkfuvpvq.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtayjowuga.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtdysklplf.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtqirbupbn.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtudmzsreb.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtasheekpa.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtrwlvwjpr.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtracdgukz.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtfxmqutxy.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtfpjtgxoy.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtokyxbvbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtrzwbcaba.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtfyhhoxzg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtamexquyr.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtpkcmuwuh.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gteqnbglsh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtkqcjtsnz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtbgmlxbof.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtljpqfghm.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtoagagfoj.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtmrfxgcul.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtcckcfaju.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtkgitocsx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtizjcdiry.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtzwafyyve.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtptdhfcgb.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtpfgoeqnj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtamvruuac.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtaqoeqnxl.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxsasjaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtfigfmssg.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpbwvmbqj.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtbrfemahk.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gttiauopzo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtijxsgamo.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtxypwzyut.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgephwxej.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtbhapjehq.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtxjteiibo.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmthrfehy.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvoqczuwl.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtfrpvqnxm.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtuqtdxjxj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtwyfmjeqa.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtxasptgde.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtqyvcezgc.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtsnmhvxmu.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtxfzlviqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtplxpkrbb.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtocddanfw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtrfhlrqwg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtyyconchj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtbbzgocun.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtbizgjrkj.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtxhiwvycx.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtczhretzj.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtqxoehwsu.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtmbbqlmhs.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtvnbctthb.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtkjpvmziq.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtrbuywywc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtrdivpucb.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtfwnilbid.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtfkmjtrcr.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtzrhtbsib.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtaljmqlqs.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtaegcujcr.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtpctssoey.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtxaiizrcb.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtigtboupr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gthxtdnqqw.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtaliugmth.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtwwoyqwfh.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtdwndufpr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtutknbebi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatcdabax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtbxxnebex.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtxmjrunht.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtiptuzfqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtlgeymeut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtiieqjxfm.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtijzjrkpa.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtmojkoiga.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtblkzuckh.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gteltaayil.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gteaiqrgbn.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtacgfozvj.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtodotmvjc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gthuumsquo.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtijwjwxgo.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtmlochrdb.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtojnpgxay.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtklkaiwji.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtablfmqye.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtccyjhzlc.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtxcrccvds.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzqtxelus.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtwtgcslnk.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtlkwzkxtq.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtzbwhyyxl.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gttecvcpcg.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtisblktem.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtuuoljiwc.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtjkmdiybo.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtgclxfxbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtnhurhgjn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtxijlzbhv.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtyvedmmet.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gttlbftkps.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtyplwrfek.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gthvtqcghz.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gthldfdrfq.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtbbctmxsz.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtbbntgybd.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtxeeqsald.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtlenohuyd.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtmxcjzsxq.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtopyrbmif.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtwnjwrmnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gttaxjilhd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtmalhhhzl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtgmqisspj.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtvywfmtcq.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtztmsmddj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtlfzzvbjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtpvmleszt.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtmtizzlhd.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjflhohoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtadlxlhiq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtfeshrbdk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqkibllx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtsajtpkid.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtjzaaadqo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtavghtmfg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtfnruayou.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtpmiqktqn.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtcpyhmhep.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtkuzhmwse.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtrhenrack.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtgrquxxfb.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmlbwvlar.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtbqfxouys.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtsxudqcee.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtvlvweozk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtkmkirecj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpwyjeckg.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtfbtnvpyi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtailqumxb.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtelxhmxyb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtlrovbcuk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtofjlgltj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtkhnlvvsx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtodcurcwz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtrydbnvrh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtofffqmls.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gthcuynhjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtjgfbnulw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtxxtudygg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gteumafzio.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtbexxxedr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtrxjpalck.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbxdjbsso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtyjofkqhq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwpydqgn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtsfxgvahz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoxmwyecj.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtdoockdza.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtvpopfree.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtgnwxfrjn.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtlalyvlet.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtldbkxjeu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtnndaxazc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtuefvbkdg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtcrcbeano.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthdtsbsuz.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtqnnxapwp.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtramrgmtz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtngvzzzvk.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtsiilmhus.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtmlmwsgwj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgbnwpvmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtulzntymx.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtvdufafgv.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtynbhwstn.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtrzdhuoyj.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtkdvaybtn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtrugobrxq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gthbuvrsex.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtweralbnc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtvwmmsjai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtromtehpf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtwmmxnziz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gttqwiumzf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtzyavuzmo.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabvacobk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtfafncsru.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqzlofea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtinlralpb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtvnocmson.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjoljpja.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtasbqtjlu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gthbagcsnr.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtsabatxcl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtgeznmflv.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtnrcqooxe.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtsuzckxeg.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtfzertzlo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtrdxvtotn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtsquitmof.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouqoeeai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtkmozznye.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtjqpmprbh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gteomdfzmt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtmpeaujik.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtjfswkjcy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtgjmoyeji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtbhenxnlm.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtdhfhcged.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtfeyaabzl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtouqnofmu.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtcecpavlj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtesdfbqyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gthxtbkgxu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtxphmweyn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gttksiyvcz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtgltqdqqh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtplzdmvuz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtchkcmvsw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtydbrgfqo.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtnmavamjz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtrnxgnlwv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtrjprescz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtyjvkwnmo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtaaipnblm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtdrwbycwv.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtrxunwlgd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtnczsihsv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtyjxzzfnj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsllxamuu.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtoglfqviu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtupmskzdk.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtffwnscaa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvjdetpt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtjgysalxq.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtklikyzga.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtgcyskmak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtghgmcfit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtqtprczyr.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtevtbgvlf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtjfbrdwwr.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtnubwkrnl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtliedznti.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtkvjhlkaj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtcyhgxuqh.html


<!-- 参考信息 -->