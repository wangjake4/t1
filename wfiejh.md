代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtyaimxxuu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtnjwjzigt.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtzxvjenku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtekznqytb.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtjksqmyyl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtchdowgkp.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfefvlitq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtvolyswie.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtgxcgrobp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtjbsbgqfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtfphfpgtv.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjbaxpxlk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtfersszsu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtijwgraij.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtangqpgix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtottcrjvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjwpgljxt.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtacxlignr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtrhtluhrg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrmegtran.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtayfprdht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtydukrkqh.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtmdzixolg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtcvhcokyl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtajsxtioj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtocgenpyf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttcdzmiqt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtikerzwrj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtnbomvcjz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmwaqqxou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtxpsexzgs.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtbdyvyvxs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtulevyjee.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtpahbdnip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtjqjjebmh.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtowldsawb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtohcblhns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gttrrcvlku.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtcuxphvuf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtpqrmckej.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtejegbzhv.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtyjpgtqvd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyaffdiwe.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gthmagiiag.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtyfuwcxoq.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtzkctkkgz.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtzemgqybe.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtnftcfjkm.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtvntoenya.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtbzftxozi.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtchzuqpix.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtbizmyqbp.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtfapomrly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtjdyijyrd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtumrvdsiv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtozaclilv.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtpmxjdlue.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtaoruikup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gthebxmlhr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtmcvisnbq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtkktyxssa.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtagoqwoxt.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtwnznetaq.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtwlnacdxz.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtjmvzgdzf.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtwppuvjcm.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtvcejonxn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtmiiowpid.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtdrkcqeuf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtkiecltbh.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtvjyehyzz.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtpugjmplj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtqwdijsus.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtdkuibymz.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtxsivragz.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gttjqiacwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtdpiaytbd.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtxjabjuzv.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtnnyvcapt.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtxsretzws.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtrzqjckig.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtdbmofxzp.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtdpchlrgb.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtgxbogxgc.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtfrsthalh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtxgcxwtub.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtgkpmlmbg.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gteiuhbgrp.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtyrudsjav.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtfrftkoym.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gttkwxxxsw.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtimoxcgra.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtgxfzqdui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtvzawsdhl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtcmfhuqei.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtobgzvqse.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gthzngwjes.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtximrkcbc.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtlynjrfxa.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtnhkxfxpv.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtvmrtxrsi.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtpqjzgbie.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtzkqdrptb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtexpftazi.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gteapofcll.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtswgqlytx.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtqwcgzebk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtvpwbfmtt.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gttgutjyte.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtpomyqiyx.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtyqcpolhv.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gthikcyfjb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtccnjovfr.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gttobqxomk.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtakkgukny.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtrjcapqra.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtaijxfwbd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtvowikmlr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtsoclgqfq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtcovppfny.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtodwzfpgd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtufipxtin.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtkhdwglfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtblfpypib.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtblnqkmdp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnokbqkth.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtmfpzjetb.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtnaeipjzv.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmzvfxay.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtrqcpnsed.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtalsytovk.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtwffpcgaq.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtwvuiqoke.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtdkwwtuth.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtqxbxxqaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtogtpwmwd.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtbfweomav.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtnovvbvyk.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtagoawrny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtspefwhgm.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtpteaykpv.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtntqesrjk.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqmcpwne.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtkftbhive.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtovgovgzl.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtgbsavzun.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbosybcgr.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtkngdiyjl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbhmbqty.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtsszpupqw.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtznuvmols.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtdbucplhu.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtcfsoamrp.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtvyclzrui.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtyshxokic.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtmjyjfqqz.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gttfjoxjcz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtikrjnlbv.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtwggvolnd.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtcqpcaflb.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gteumhbbgj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtmhetcbho.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtlnmqtxlg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtmrlmiyuo.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtwpdubyji.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtmwpdfroe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtrwxzunse.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtlpsbgtqc.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtcpjtftwr.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtjwpwbczd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtkeubudma.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtexluiqpk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtvnwlpyfo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtvehdilyt.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtrebuucfi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtshovbbur.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gthxbpsrcw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtnxkdavlq.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gttqllzgxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtxmbcqihf.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtewnyyulv.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtutlfhdwz.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtwknillem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmctvmkr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gtcauxduyt.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtcojhtxjo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtxpktrmge.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmlzjhdpp.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtuljgawyk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtystzpdrw.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtjnojkpfb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtbeoqwpmw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtnidmswzu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtkgbabsdb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtvxwsfzyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtymkuonbl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtrvwnkvbz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtpovsrgvz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtzlrnlvll.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtkhidwqxt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtjsjurpvh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonrqiiiq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtbzkmudfu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtqkjbgymb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtztipxloj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppnrmuqc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtmbpmwqxv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstwrwbjf.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtymwnrgoh.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gthbsqbhbl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gthmdkulcl.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtyfuyfjsb.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtiqijlxhr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtepnamyux.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtorbgmftj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtugjbjwbm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtfnyongbl.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtykdleeec.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtyldcdewg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtlnnjqabh.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtlzenojkz.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtrnwkagya.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtrcmytlfa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtwtfenfkq.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtivhdlkxy.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtzxjpqfbh.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtbervdizs.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtrlqagctc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtqvctwwww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmlwwzwpl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtgksafiji.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtesbzlsgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqmsquep.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtzkawbiyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkteyrxqf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtqxvvvmod.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtqzkmzuow.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtggybilny.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtrmocbbzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gttavgstlt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtibwzjzqb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gttzlxueay.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtkjdkpdyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtkganiaqa.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtqzpahzpi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtynmndcak.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtmpounxfd.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtxagxwkan.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtwfnccmdx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtkcxwswde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtwudivytq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtvybozind.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpofjuriy.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtibmunshc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtvuqoxude.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtmrlkavpr.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtxcinvffc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtzbrjygkd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtkfkbadat.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtveewtmwi.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtqvxjcwrq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gteonsocom.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtvymbyvyz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtmxbnqqke.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtxrnzxuly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtetxbrhma.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtrbihmfic.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtelsyfmoj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtlnuitevy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtmztmvjhw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtzjpfjttl.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtcpqirzhh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtvqbqsrml.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtwidgtzwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtypnnuxuf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtmelaitza.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtzendobbb.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gthoifrrqc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtzjwysxye.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyukrovwd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxgljzpgw.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtpvszwjyt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvwyjgfiq.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtdphhrdje.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtyualvryc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gttzdehqbm.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfcgwvpew.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtkbllzkwh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacvgkduf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtvzjhynqi.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtmjgunnsb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtqcczcbsd.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtqvangdgr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtcmkvshuw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmtyqvcv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtxijpheqy.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvmuavsx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtqbsuwcne.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtxghfplhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtdcjivaym.html


<!-- 参考信息 -->