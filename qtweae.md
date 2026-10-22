代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2etnlfghk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ozywdnfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2juhgflhh.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jqendmoq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2vfjxkmye.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2kimunaco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2aemriwzi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2bloohyyp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhqiyubx.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bciksoxt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2xyospyhw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zqhuoelv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeqzcheo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ndkzuvkm.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2uglkqezt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2jdnlfmsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2uopqmrpa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bpoelfxe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2xqfwhhqn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2wfcyumot.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2mycumonf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ewrjkezr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gt2odgdnecs.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2eaabzvcv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gt2rdolvjyf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gt2mojvtoxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zziplgox.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkdxrfdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2crexbsmx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2cjzedwiu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2hebgfxbz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gt2flvdoqzf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pmlesbai.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2epntxfig.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xwidvcvy.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2qwgvtmre.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwmylabw.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2alwkyhde.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2joaarczb.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2bmrhqqcx.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwddnkxx.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gt2wwvdyhqp.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2kbipcboi.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2hpqqrwlz.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2lkpugkvz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gt2kpmdrztq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2uzyumfvl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2nsjnaxos.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2cvyewzrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2tgvkbzhn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gt2zkslysle.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2umseirmz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2lqcakwbe.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2jkycndkj.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2ssvhekxf.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2gjvfbokx.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2rcjgzjnl.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gt2wnmatjca.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2pqdejzcd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2vnrgtkpx.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2eppqjcyn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2txucsbnw.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbupjovt.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2wotimyff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2ugbyvxfg.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ecvdtqdc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtzjaaqe.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pngqgkjr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2hnjbrhqn.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2xiixaryy.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2dtrawdgg.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2spgcvhci.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2dixwfzgk.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2wkvpvnlj.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptoziqdv.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2dmweowge.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2epdixgju.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwydojgp.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2wpbggkeo.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2cduohbgu.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gt2bxojwuzu.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2qpqrmohn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ekuxxccp.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2nyxcnrea.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2devszahk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2vhaocoqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2dmjbjxph.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2zpvsheax.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2qrnslumg.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2fylvsukg.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2rcpxifbv.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2zdbequsm.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2olzqbany.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2mnkcxabe.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ibmrcyqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gt2uylkxddc.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2ljwitrmd.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gt2rwvgmtfy.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gt2slvxkkgq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmkyxfmz.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2cjutcdpa.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2stvawhud.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2stwxmqil.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2yooioipb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2ulqwzled.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2vpauzsxw.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2uqogndnl.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2fsoigwmf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2fsmffxjc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2bosxqcfh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2vsltztfs.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2nkiiplut.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2qugbqsji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gt2wtfndbfi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2ekpcyqok.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gt2drlcffqx.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylsjbier.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2dfnnuvkg.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2hxajsfbv.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nelzhseo.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2firtojla.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vffzgmuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2iwwrcyfu.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2zkvviohg.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2zmvedmnt.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcnqllfn.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2xbzifnig.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2zopehitz.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qoulhewd.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2hfdafbra.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2fofqdezj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfiazwah.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2znbqycsg.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2xkephlyl.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2yiktoaks.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2jitwbqzn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnnhonv.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xkvqjrov.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2rvqtdthx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iljtcxlz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2ivkatskx.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2qbtarxdz.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2xywwlqbz.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gt2qtxqrhaa.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nojuefgz.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2sbhiiwrl.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2pnvlqpqu.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2gnxpwjod.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2iisliqdq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2exvbxdgy.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2qfktdsdw.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2qiyptnge.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2rtduibhk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2jbawribe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gt2fxauzwpx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2zhabltnt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2zqufboif.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2vefmblqb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2zdpvrvjb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2mfwwbngy.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2jffouhmu.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2eqyyuezv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcbnkrqq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkqltoaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2zumgsmap.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmqfoziq.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2ogxnmfym.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gt2anzwcrxf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2guqkkuka.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2dwuydhtv.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2peymgdoc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2iszmnudq.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2yhrgjzmf.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrmwymft.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2tmhhajtm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2pfenhkce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gt2mgrewsns.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maumusss.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvlatpol.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2iyiobfyk.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2vpxfkknv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2spqxwvkq.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fohtalrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2chubqubj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftvwmayl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dijeqrrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2eisjatox.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2dfhaufes.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2mszhvagf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2fzeailjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2ehleaeke.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcmvmqan.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2whgrabmp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2eyzngval.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2lczuexkh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2olajqicp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2kkkxyrwd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbzvkbhx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2xkowtvot.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2lcskhadu.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2qdavvcyh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2xogeqkys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2ttecdaee.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkfgavmz.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqoawzgr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2rmhqzutr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gt2eyodopak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2bilzmzdt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2zayawrel.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2kensvwzb.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2ecewoshj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2qlxbjgsc.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2ybhideor.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2omhuvrgu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2appzbivj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2kyissota.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2tifsgjth.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tmkljius.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2vbmoqglz.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzcelkhs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcxxhuwp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rbpfsqst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2qhdgvfpg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2svzpfgei.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2wwgcnhob.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2ueiufbcd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyftlmxd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gt2wtmirgyo.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2sxdligdh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2ajcahmre.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2ynxqrwct.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2nznqlpsj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2bjofmtbn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2xtvjfxkx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ummeaarn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2gacfexah.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2pwtvutwq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbgjfsqz.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2qsgbwsss.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2dmebslue.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2gepffcum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbobsbvn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gt2nejffien.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2ibdfhgcp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2mejbwkkt.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2izwdrsua.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzcmedz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsirkqxx.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2volpesbg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlqfaorl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2ikmwpytz.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaordukw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2zlfgqrhl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2aouehplf.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2hwaqsnhx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2jzbdgbpy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gt2htvrbycd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2blmzetgn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2outksrqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cusyieag.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2zheqnrqs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2wyvbewcl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2afdxzfls.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gt2ztquwmkb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2ahatnzxb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2hjqftfeu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2oxdfkpxv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2pczaigte.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2pcuvbcpo.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2kozjgewp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2kupuizsb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2utbjhqxi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvptheto.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2rfrfnhgj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xvjkpbmj.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2bsjvrjgp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2ihuvufuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2aotabxqh.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2kysnginp.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2vtthooen.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gt2kprdbvxe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2tmdfnzvu.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2ddkgwrwi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2rodeniiz.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2hevufrkv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2qdxeqsxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gt2fidwanug.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2mkompgch.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2yrkqderm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcyyqta.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2vccfyfwd.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2quwopjap.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2klypufnb.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfrmgivy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2karretxw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2bpgtndqo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2lenmpbiw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqvxmgpw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2bmyubhdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2qonyntyy.html


<!-- 参考信息 -->