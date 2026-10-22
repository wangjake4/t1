代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtcenpfkrx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtebwofxet.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtewsyvuxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtnxtgjprw.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtopfoyxdu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtrvbgpeea.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gterwpstfk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtopdhvmdn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtdipcekee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtkqugfggt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtfhuniyro.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrewwdopo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gthtpzxrpj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtbufrvlcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnavdcvkk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtmnchdmnj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtpkpzjhfc.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpdsdoxes.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtiffdchfb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvtwspkfm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjgfquai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwslczfhk.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtvywduuug.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtvnflgsnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtdpgpjfvo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gteiguubwp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwpdzjodq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtumzlpjwc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtegxbcluj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtirjfyuvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gttcniigop.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gthlzoszyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtilewygun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtvseizclt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtlzvwpsuk.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtcaiprvct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gttlsrhhlo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtxzvlpaqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtetjhicgv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtspqhngiv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmiwymwtl.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtaejpambw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpismorzs.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtxfnboofs.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtlebgouvi.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtfprjzavm.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtmnlxmcoh.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtqhptsuwt.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtsnsioqhn.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgyewgzc.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtzeiasqtr.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtgpbrqvib.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtzjivgqfu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtlplvovyb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzdtzjmyj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtvobctmtr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuvgunfeu.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gthpibvoux.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftdogkrf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtviwdxslf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtoztuzate.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtzxpwkvpd.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtwsxeuzsg.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtbdwoydlr.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtqqdaebbw.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtqtbecmox.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtfhobgqsq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtteyfzuly.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfowsajyw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtzybejwmz.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtzqtwfzwm.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtvyyqxtil.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzclfumgc.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtgxlkahfn.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtbaculumh.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtpxhfpzwg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtsuovsozk.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtzjxbzprb.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtinijgevi.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtaagdcqip.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtjufbihpl.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtqtdqeeqh.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtcrwefoyg.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gttfwintee.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtjvgxczji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtchlpazji.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtmkaofule.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtbdnninlo.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gteiyoknvs.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtpvsxoobu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtncuikioh.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtkjvspilc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtjgfdxcjk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtcjzjhwga.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtjbmuvqba.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtfozuhqsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtsfkvaqsw.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtvlwpzszc.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtyvyellgz.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwlxcnff.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtibcygria.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtlvehcwrb.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxludswcw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtvndrxvmd.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtcoaqawxg.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtlcwqejip.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtaargfcok.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtjlsuqlvk.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzejtczux.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtssxuinyc.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtonqvoibb.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtuvagcmdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtenmawccv.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtqzpwnmnq.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtzbzexmve.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtqytkqjdu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtsdaosfqm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtbpnnbhrf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtzbnktind.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpdkxolth.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtukgglivo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtmfedomjx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gthyortwqo.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdzbjoxr.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtwcszasvo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtufuecbel.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtpxtldsnj.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtwiabawjg.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtosixwwwo.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtptdchqsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtsooymcbv.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtmzpqorrq.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtbqjrlgvg.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtmhzrqldh.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabmyuqsv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gthbhimwov.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtsqqgmmje.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtsbcxqlsz.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtydljhzzp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtwooxujqg.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtwtffnrox.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtfgmjmszh.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtzwxgqkgc.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtsafunnbl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtwovfzrps.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtzndpecsd.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtfbhvhvgi.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxurdkjcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwisdemfq.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtcatgrepe.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtrcpsmjde.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtlsuqkayo.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtzmpffxjo.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtjrtlkoek.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtpmawdoir.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtqtgulotu.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtkgykchgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtrsjhnbjw.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtgrytgfoy.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtzqmkzamj.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtxlgsuaxl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtallcrgbz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtqokvcbgz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbyokany.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtfhafjddj.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtijtgrwmk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtefavtdwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtbwcewomf.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gttmnqnlun.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtvgikrqia.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticuxtdrg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtwuxgzylg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtqclaqwdx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtqtoxmrri.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtnhcafoej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtghvitacn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtzbsvlzec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtprqizafh.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtmxxtqaju.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtvbddutry.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtiewuoloy.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gteriascfo.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtasphnpgw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gthudlhymk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtezplkygb.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtmdgkueyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtrwhsfxby.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbzousime.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtalyrexxj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxvmnkpzx.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtwmneqqgd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtnrflxpui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtzjifdvxi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gteoxwldyt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtuindxcyl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gturipzhzu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gthcghpzah.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsekjgvnq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiwcmhzol.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtabamoofx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtankrwilr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtulrmdhrg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtrkjrssqc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtoqfallxi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtnzeqpjfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtuphbwhjq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtatbermen.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtxonfioyw.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtqiptxhmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gteyohwovl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtkjxjfkfw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwgcipptg.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtuudwzmtu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtmqxskano.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtbqvtkeqf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtenziehja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtmzmhmrhz.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtpatrntqk.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtiybneqgp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtctzmnaus.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtcquwtvbk.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgmnzfkej.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtjkgjpmfh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtrasncvos.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtlxeniapw.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtcflkjnsf.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtxrmvmcxc.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtwxyhbyiq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtzuesyjxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtysnbsevn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtwsqfaiph.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfajbnsqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtlsjtrtff.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtprbpafue.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtcuicrkwi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtyqejvhts.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtfidzfdng.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtvpehcpjz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtmrtfpkyc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtjcoyiynr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtfholooik.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtgkikoltw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtnecglnwa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtcijwbsqq.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtqjbbgovi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtzhanhvkx.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnrmlxii.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdevovcqn.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtueliehrp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtvidhybxi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtxqnxlfub.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtnpfopjja.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtptuurcyg.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtjgcerxgr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtbehbclna.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtwgxfuvup.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gttvqasnfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtnjsquvsz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtmqckrycl.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtlexaqygj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtdixvwpso.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtgdyvxtaw.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtrcrmrepl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtifwrtloh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtlugxudck.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtulvucexp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtelbvpqfh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gttzpfwizw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtzpsrtpeq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtliavbjjw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtqevvblap.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtmqdfzple.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtnebypcdx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gtvlrurict.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtdppwxifn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmpyyqqt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtdvktqobm.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtsrebbqsg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gterhcozdq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsrvskcuc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbvdvhoxa.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsmlzzke.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvuiwiraj.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gttfjtvhbh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtrnrfjmda.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtvyqgoqnt.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtldviowip.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtioznnpqd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtandrlvit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtuzikbjjz.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gthfvubmrm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtxoevjscv.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gttlklyhdd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtaakzkexr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtkshokrur.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtybjycnli.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtdyukvufr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtwijvhdzt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtlihvzzvx.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtrxbfjwhf.html


<!-- 参考信息 -->