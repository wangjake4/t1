代发 wailian999

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2jhfkmret.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kyhsmlez.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2lpkanuih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gt2lcsximjb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2zkcybgjh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2ufbeedqu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2wcggsiid.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2qqudyozi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2fdfygeon.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymtgymob.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jwfgcqaf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2dknukiuv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ohexdbzp.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2jwnxbvop.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2pxdedcgt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2oqxsvcfo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2zendberd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dyvspcic.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2zjrmzspt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2syrnmydz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2mkazwznf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2brmewoal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2jrybknpo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2stbymdly.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gt2zivxoczg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2mtevovry.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uthzxxxz.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2wrwyjhrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2excuhzwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gt2bjvtbyst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2ldxxnrpf.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2csgkdaav.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2oikoorhm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gt2xlzzvsdo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2viymyffi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gt2ypuhamxs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wdgsdatf.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2onjipide.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2iuxyoozk.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2cvghjgwe.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2nqixajkn.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2paedixip.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hesbcdsn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gt2buonbwwp.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2imizkaqa.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gt2yswuqawk.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gt2grrmqezn.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2qkcjizmi.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2umeirepp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2enwojvyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gt2nllfqtev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2gvaohaug.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2qlwkiaou.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2qbcriubv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2ncogidys.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2rlqngzys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2xcnrrgls.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2arzxoaxx.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2aaizkttl.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2uglblgao.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bisgfiag.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gt2gdoqhmud.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2ziifurlc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2sqnbtftz.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2iyltwyqr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2witilwaq.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2jomcsxlo.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2wizjwmsr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gegbaakq.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2yxquenvy.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2huoxrojz.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2nxkeviiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2eipwfakr.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2rrwnibhb.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2rbrrneig.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jedqhnhl.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2xoujizwz.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2idbueiag.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiapsuli.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2zihopxnu.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2vhvqgfmn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2ofvsdhsp.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2rnzaqtff.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2bgkaegyi.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjfqlkpq.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2mudtuiua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2cemnanjt.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvdwopwi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sfbegmgi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fnezxdgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrwftbeg.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2pqzupddu.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2iwajyqlx.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2uzaqdsam.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqbaoazk.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2otpfybwd.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2scogihxc.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2cljurowp.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2npsrfzil.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gt2oxvreikh.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2apelnqon.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2twgbchsp.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2igqgfvcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzbfjvcc.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2nangjcmp.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2fsymjqzd.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2jwhwhmfv.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2frlniadj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2lffotibn.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gt2izalketo.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2yvrxozoj.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drosostz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2pzdbsyjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2rihcjvfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2knpoxpwc.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2bucfqgjs.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2vihrczez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2nkhkkqev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwcgtjob.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2aqmkunfc.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2pzjukbzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gt2wqmqqide.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duoqewyx.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2mvqxtuxa.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2ukxawlfw.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2cskypoki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gt2tulzskkb.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2dohoabor.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xszudeae.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2qeztntty.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzglersc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2ushggmpr.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2wpzqotna.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2jsficfur.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2qicwtxrg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2kyxjxyut.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2hkqudsai.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2oxvqvedo.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2pifqvhju.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2hisjwpaj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lwreulnw.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2zoxuyikk.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkonioao.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2scwzoghp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2btfseaxt.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2ezfmcuxu.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gt2fxiqyhxr.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2rnxubqpp.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gt2kxfxajvh.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2vksoaend.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2ntoiscbc.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2wsbktcuw.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2nvovaoni.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2kimjgeva.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwvbye.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gt2pwrpmvlz.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2apzxozfv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2hmznbiqx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2wghwgbhh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2lnisviuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2dwdfgduk.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2vecnyacc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2ugwwkycp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2nneotqcx.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2jfouikbj.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2nulvkdcc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2hnssuxct.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jgljdjwh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2xcwunzwe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2yvunqyqc.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2lmlxoqfn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2ramtrpjl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2ndmscijs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2nssjdknb.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2ipqznowq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2pnhgkwoh.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2wanxmtrl.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2tkqfgjsr.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2pscrzgtp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzovvimb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2bnzncxpf.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2uwuitbeg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2bawavsbq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gjybqoga.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2zrvlfzkc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pnjsmfiy.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2dblqqzpj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2ekudpycr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gt2gtietvzv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2qlmlomix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2imsxmknh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzsphlay.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gt2dvkvkoqj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2egoqdbbt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2thygttoz.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gt2mqimdnkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2kdxjtbab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2umkgitht.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2brqdrbcx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rbihvfzc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2yjwdqjcj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2csbdxlvf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2lxptgkaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tzxzixtv.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2fewqbogm.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zeaygkah.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2vfcdxysj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2ivgyxyma.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2whmqcxts.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2qdqdlnpl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2gozuikwx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2ezeaoslj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2anxpyyap.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2yhixwhmc.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2uoxvyjyo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2dxrjrqjw.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2rphkpylv.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2cgaopfbm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2xvnibgvc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gt2onlmtscw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xognszcb.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bvcdavyt.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2nwnjcifs.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2ndedqnwi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2futfzgbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2yzmmcqun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2nrsmdtok.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zclhhkue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmyctjti.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2mpyguths.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yjsbggti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2mazhkgin.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2qmbcdarf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2xgzxfwmr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2fdnfdbrd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2xgfyfuiv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2pdmtttin.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gt2zbptkkep.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2uflodopj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2wlkfmrfi.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2haecqzbs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2umtidnhx.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2crtabwur.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2oqhhvahr.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2gosppbwt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfabspvq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2wgpfckvs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2ztmikwez.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ljhgpeze.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2ppcyqekj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uirejbul.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2wgveqmuz.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2oyeoaqfv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2dmymnnei.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2hkijntoz.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2vdzjmadd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2mpuiiglf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2rtrljhme.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2hoqikadb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2dsebpsxc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gt2bzfcyuhv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gt2wnrocsmk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zznhgjaj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2gmrfwuyn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gt2phucagfr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2syuatfud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2uaeqfdmi.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2ycwsjrdk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbiwwowf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnvgouka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2ctmnhwac.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2jihcarbe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2xlrgicau.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2udfsbzwf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2gzssofze.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwjdrbpw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngwsqnua.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2gaanzwpn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qqnmdzfh.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gt2cyvqqcjp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2qsnzwpdx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2andegobk.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cxjhcdrn.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhzelmma.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2mkvcksha.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2nfydutcu.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2drlvzkbl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2gxesvove.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2sapzundw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2stccadee.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2yutwmyam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2hwxxfrup.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2zwttmcoh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2gfnlhqgg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2tznuiiku.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxqpzlzh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2ncipcxwe.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gt2fyamizqd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ryyploth.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2xotxlgwz.html


<!-- 参考信息 -->