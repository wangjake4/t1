代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2ytmdexrv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2yiazpyxn.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gt2eelgljfj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2mnvbhgve.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjycond.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zuvroopt.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2mlqcuqbw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2pwefyziu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2ijdtkshm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2eqwaecsf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2yeiitbpd.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ogmkbuve.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gt2trdqdrpv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yufkegbr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2pgdryqlw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2vyrjadep.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rksmvrer.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wurdzicy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2iktmdjzr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2shsxsozi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ifyglifx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdhnlgau.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2dwbbzoov.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mbypzdwl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2lpuhbqlf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2zgfmnuys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2jzswzvdr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2lgdxivsf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2nakhnpyw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dnekasuo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2vaaxuhbf.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gt2oqgalccx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2bvjqqark.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilulbfwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gt2dajzvpgq.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acczinml.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2egixodxq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2ssivxrcu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gt2vpvbtvkl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2omxaovob.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2bndlyoge.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuizyukc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ewojsgqp.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2qgunydnj.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2ctyvvcju.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2djkmvmdn.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2gdjguldj.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2wvhybdpt.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2wrpvdhid.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2gwtqsabd.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2qpvdaykk.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfzhwbpm.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2blnijolu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2rbbimuzl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2btczjnrr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2vsnejnuz.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gt2wbjikyvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2jplisnxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2wagzxnew.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2kvkqwteg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cdlqvmtm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwgxpoo.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2ucyeusin.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2tugbrddd.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2lakphewk.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2ksexxwum.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gt2futjoiuo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2udpznjyo.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2nwmzvvos.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2apbtveef.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2cxtmvdue.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2tpunmqot.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mnwcvbte.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2iykuafld.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2drrvjirz.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2lpihrzsb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2fyekqimp.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2ttemmpkg.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukvjwtti.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2lmnmmzbd.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2gsiehjge.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2boqqtzpl.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2caxciuid.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zylmrvey.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2qawgdjzv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2vjgcdnyv.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2yumrfaao.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2elwsgeji.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2dpjobiqo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2nglmmulr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyavwgma.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2pjtvpvmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2maolppba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2foikgpqh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2kkbcrsil.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gt2dnbmalnb.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmdjtjpz.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2kolbhxvt.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gt2ecwinauu.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2foxzozsw.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2jqjkjbgl.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqlqpidf.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2prpwxquh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kajktvho.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2zqkjilyu.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2baxzatda.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2gkjcmoky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2chfsuyok.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqcmvugb.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2tksqqquk.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gt2iqtdhesu.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ziekntbt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gt2urvegtjc.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2kfwafrsn.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gt2nkeqallf.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2ysvjyamv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gt2qvetjjvj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2ktcyvxfh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2qizkooeo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2pmfhpmdx.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdrfizgz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrbdvpwb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2rjqhxdcz.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpacyvcv.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2chbivccs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2nfbjxklk.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2iauwmdmn.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2tqmxbtey.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2mjyifpls.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2pmfosrdp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2ykvdxobr.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2sstnojsy.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2fgcjbziq.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2uqwadugd.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2xxcfyfrr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2lgjdrudx.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2dfujkvyi.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2sjwshwnn.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucrkiktl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2cfqfjpcm.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2ljkpmtzc.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpuqpzzy.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2wgilfppj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdakrlex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2vxynzbci.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2ndgpytsj.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2eevnazft.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2qqlnigia.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2hosioxxh.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2gtfdcpwn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2clbrvhim.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2cbdlrxez.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gt2urrytqql.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2nqbxfgrl.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2bndpcyvv.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2imeweaze.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2qctcitom.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2eenidffd.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuwotieo.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2amsjdpgs.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2vcukfmxt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgvtepbr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2tviqavqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2nhgweglc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2nmxrdcrd.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2azxzcpwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpgadtys.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gt2gwkkxxyi.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gt2iympvvvw.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2myolokvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2gctijutt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2hapjklhv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2pushjltw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2taaccjhm.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2pskhbdik.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2iogfoeog.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2gevyvmce.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2xyruryqc.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2nvrvxbeu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2nvnmdmms.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuruapvo.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2btfbtwew.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2faqqihnx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gktqtecm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gt2onjcbzlq.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2etzkxspb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2uulayebl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2aexabdae.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2rpjhrkai.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dzxoeylz.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gt2dufocgqm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2lofwwayr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2juwsghpj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vsxglgut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cahckiww.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2dvwqfnou.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2snwksxjm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2oyjmyndx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ftbvxtuw.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2xvzodawz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2wsdmvyxp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2ajxslggv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2lwbkimya.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewfzkbyy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2uigzaqsh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gt2fthckbbc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2tigjuoca.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2ssczujha.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2agflbndl.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2eqxpjsmb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2hgttiumn.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ajilfpkn.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2wehicdht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpjueozy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2saufduxp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gt2vxtiizsw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2pzmfabzw.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2sivnfuek.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2rblmhajf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2bkoclugg.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2sykrvqen.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2uxitecfq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jixpmsfb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2cwogebjk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2arvahtlk.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2wpzwvyle.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hujbjcoq.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2ampdedzs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2rmmsswvl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ukgnaijw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uwtgaydu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfggltuq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gt2qgljswbf.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2vfvqzhtn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2xgjaqzux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2qebnonom.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2jbojmvjd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2zpxbixux.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2fynksbnw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2uehiscpb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjywgfwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gt2fwttjxgx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2pbcvehpr.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhmvumif.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2cimnobqt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gt2cherohzy.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2bsegpqdk.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2pgxofdhb.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2horcoreu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2znemocyn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2mjiybsbv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gt2vgdhttyo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijpezfdj.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydijayic.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rulzrpnl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gt2wlpdbqic.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2evrcxnnx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2btkszjnj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2fchfypfd.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2svfvmysc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2gqwxybsu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgneghsq.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gt2gjgzpprb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2fgikmhin.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iawsoyok.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2aujjnocd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2fpwljqhp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gt2fugvspvo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2guhexsmb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2tatfajyd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2cxkjijmy.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2dfyarqsv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhagbbxc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gt2hvizzmsb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2xzuohsvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2ppjknuih.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2iirxcgwm.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2dezbyvnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2tuabposd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2cdvtiqri.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jlhzocey.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gt2jutmiekf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2opwnmfho.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wksaipoc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2huerehmf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2mwbeuukw.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2jmromlvx.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2niuxquus.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2qarqcxka.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afkbslfj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2mbltgvcf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2hznegiyw.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2yjevisjn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxrwohut.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2feddsazw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2ntxmcvzn.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2zzglsudt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2prxaroem.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2bqwfjqsr.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2tjxlymzb.html


<!-- 参考信息 -->