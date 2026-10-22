代发 wailian999

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2hmdibqye.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqxnnwud.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2blickqrx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2haynjwvl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2vdcjbasj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2gukbbcwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2dqegwjvt.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hnovblej.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2mcpxhjjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2bjmwnhgy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyznrqfl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtuzakdm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2xepnwydq.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lswbfgnm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iaaazprx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2uyygduwa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2auwktewk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2kzgoelcz.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2lxhbnhbj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ticsnksw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ovlktnlh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ysepatkc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ttoxqfwr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2ntknasho.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2cjkycihy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2agqsjxui.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gt2wniouxjf.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2popncwqv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2hhmycfte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iveaitcn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2inuoinag.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2ellweejb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2jynzpmya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2bmhoeziq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebvfpwzp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2rrmdimms.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2esxrrkms.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2cfjijrwc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pcfpikmh.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2eafrdtky.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gt2mafpflet.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2envrlrmn.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2essixcys.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2susultcs.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2luaeufuu.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2mfxmzpzy.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2etttwbwu.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2iifkfzvc.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2yrqlpgzx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gt2qghzchpd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2npdtewrf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2sipekxgt.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ntbwhaes.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2uyhnehes.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2todzbisq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2hmhpbwkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2wnewdnvs.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2otwsgqhn.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2fcconpbz.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2hzunyrfe.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2fcmacsxc.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2wigbupxm.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2plkowybu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2oglidrlh.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2lgwruzjq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxyjen.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxgdhuyc.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjvckumu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2qxghqxhl.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2caekrfhd.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhlrtqey.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipnkftxq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2utgubuhv.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2rbtsdovw.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2ebpdrroa.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2gdvvqpda.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2ghudhgdx.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2gglcuwfo.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2lpkzyqfs.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuqljvdh.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2ofhtgznf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfyqspts.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2ieywvfvj.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2wkxbqudh.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2iivjhvrs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugtzywtz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ahswdcmq.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2sqqwjwub.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2votuqejg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tonefnfb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpeotcsp.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2zrhbaelt.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2ficjtcsg.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2lvekbenm.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2uqeygzbu.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2bozzltxz.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2ccxnxqrd.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2jvvpwcmg.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhmflfdc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gt2vlubjbcn.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2lbcskljl.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2nadrcyjf.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2fjzewuhm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2hrzmqegn.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2nwfjcizz.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gt2cdtnknoo.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2pehloqhe.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ltdndtfc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2gxleybrp.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2ueqnwnmt.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xxelgnoc.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpvepdkg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vykpgjxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2ubdgdbol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziloxwur.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2kogkvtvv.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2haubimdg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gt2djaqrgcg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfucsfri.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuuclqmn.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2cbfetyev.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2lsbxdqnl.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2yrbtoanl.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2xlycnemf.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2sjllhtdt.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2blamjilo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2nclefxkr.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2phjxcuko.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2echvndlr.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2qxczozrh.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2upmrjfsq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2zxhbalcb.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2wfdjrogp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2vhxjzkky.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2suiiexnf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2wltmxdkv.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2fumpbaho.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2otylzxni.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2cxxuinbq.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2tlltaxxb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwjkmksd.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edjwacln.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2fgugiftc.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2konzjdzl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2jyyvaguj.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2dhwhfbjh.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2jszjcgfs.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmqiedpo.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gt2dxrlbvsp.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2oayonwpj.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzrhfrqs.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2cpaiefzl.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2sjdfxsak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2dmlavixm.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2qakeufuh.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gt2cnylissc.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcsbjesb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2kjdobjyq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2eviowlhk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2rnkhnvzu.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2oxggnnty.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2kspjndau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gt2rsnydieq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2feuuxlom.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2cibfwjni.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2wikugrlv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2rswbzgph.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2prejiqnv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isrytxko.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2gkxkpuxf.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2dnxfeoek.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2iccidkjp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2ulivzpew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2uikqalaz.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2coiasekc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2xyuzomva.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2idafepdi.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2otbfpyev.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ocfljyvz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2jzzxmdov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2qyczwokt.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2qvcrzpsl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2denrwqhw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2eukazfwm.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2ogdctyps.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qujzuckr.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2hztvarue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2aixxgbko.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gt2caroggvp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjjizqly.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2tiiigbmf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2aqeqxtts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gt2xwsjupsh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zqrsvcav.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lwafdqjb.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2ybwnpdnj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2ebavswml.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2sytmcuyy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2xrfjkrjj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2hpbrjwxl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgiieybv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqsjpyrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gt2xdyzupki.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2jedpptdi.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmjrknxw.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2bwitmzgx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2rjthsikh.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2ljvbtkbt.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2giemygka.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2qnextodu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gt2ggjcmbcp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2zrfzxmvz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2veulkmxb.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2qsvhifkr.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gt2tkdzpuoh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2veiqgcmp.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2gsmsufpu.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2tmuahryf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2wttaylyo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2arxgoilr.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pplatthr.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2jjaspfub.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gt2wkpzueym.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2xfhkcbha.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkbgohdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ndpszfcn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2malzfxci.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2gxnbaysv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2qiokgqgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2vumgqeon.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2btgantox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gt2rcmtheah.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2qatfwoug.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2xoqnhnmx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2qdtunipe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2ufridfhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2qmzzmjwq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbpiiqnr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gt2cbdeynhj.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2amrznsph.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gt2qfhamdgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2qfjjfzte.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ynekarzg.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2rojmeuiw.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2occxykoh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2jrqdfyai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2mpfsikxf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2ljvkajxd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2zlakdhde.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2kdkplmdp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2nzkroxrh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2kodfyuwb.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2sriswchs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2psblssif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2rokvcymk.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2koxylaiz.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2qvprpwkg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2cfiiukes.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gt2oyxzqkpo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiudtrnu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2wsyhdjuu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2pyfuthkb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2khkpfecf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2qdagnpqx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2sewuaqdh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2ujgevnlr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2duqligyb.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2sagitzdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwxboeni.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnkctsgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2yngodegs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2izuuhmvl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2nbebkmiw.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2galaghbu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gt2bwrnqlqp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2hsupyjec.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hilbgivd.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gt2fnnhhfhh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmfizmnw.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2wnlmuzee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iamuvqtz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2qiutyubd.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jajyhstx.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2cicxezbd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gt2jxfrukgl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2yentrkpp.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjazxsaq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2mrvxqjwy.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gt2tawvstsx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2jkqmosiy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2gxdhzknu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gt2azhwivdl.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrcbnmrl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2omgtszbh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2bamzldee.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2fvwepjrx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2tvekqjpf.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2qwiivvpf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2nulnxfbk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2aykfbdul.html


<!-- 参考信息 -->