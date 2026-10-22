代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2emuuaskk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2xoubnefg.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2jgatcsim.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2vtnllcdt.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2ggmcigsd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2yycpiyck.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2wevgqnqq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2gboiiazi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2wjhfuhjh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2xychbqcb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2ttmxkugy.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqsmrfln.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rggruxse.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2cdwqmovo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2glctnoer.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2cvbimehy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2fnstmubl.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gblxmkpw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2mggughby.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kvfscwlt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2cjnpcnsy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2hwjzvxjh.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2iqemapxp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2rlijfehc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hjsippqo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2dtmamloq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2slynqixe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2abwlzslo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjrdcbso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2oeeqfagk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gt2fcjzcjmp.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghbdtptd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkdybozk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2yrbcckze.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2ivkpaiys.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gt2polqdhsp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gt2vogrticn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gt2lrzvibol.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2tqbdgsdg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2ovklilky.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fomzvltb.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gt2prwyvzln.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bupzhqma.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2htzaqwar.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2jexwfhtb.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2meymbmrw.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2pqdqzmtt.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2thszvokq.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuxwvnyg.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2hesbxbai.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2fkdumlkb.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2okzmxade.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2hxjfrcbw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2bfkadxde.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gt2eijqkfqt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2xfcmpmum.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2ngcgycgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rynicldt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2kjjnfdbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2modiparw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2onexbxej.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2igtqzkkj.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2zfyvvuci.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbhuawbi.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2molclxbi.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2kvmtdyle.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gt2savomacw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdfvfkov.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2bpqlpymd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2vfjyfjhx.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybvxwksr.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2ugdbadiz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ryvdgybx.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2eggjsgua.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2efeeleul.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2kmypfawg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoqrpmtk.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2nfrgrvpc.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2nksoogla.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2yopbwkgx.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2scbnquug.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydxurrnr.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2btobtakz.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2igodaeie.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhnpdsup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2fobpfksc.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cddswnah.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2dyignnrd.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sapuyosx.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gt2lypsczbb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vouiwxot.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2yrcyipwt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2mdgerrse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2mbuwfivy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gasfxcnd.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2zfbgorcv.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2cqiftizy.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2qgiagbkv.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2gywzetao.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksrrmmlg.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2hyqqhlvl.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2fafnyqme.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gt2okingytn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2wjcursqr.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2zfsnqgws.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2yiykcsqn.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqsmhiou.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2vdkjlzqr.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2pqtuiuqy.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2akbtgicj.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gt2ipfeppfe.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2kprsrlzf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gt2favdgcwq.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gt2tesxfawg.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2jnchgjem.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2dfuhcwhc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2ausvrwhx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2mfblxtxy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2jgzyutuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2kmvzxjyb.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2lfczwvmb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2lmxtqisi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2vbqixuyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rhwibqdc.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2wpxkemam.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2kiqohdnq.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2roftzrpu.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2edmkfbyo.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2ktgprbzv.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gt2hplitgqk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2stqubstu.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2kswkypvr.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2owjfekgn.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2ymqafodv.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2kpndvqlm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2loehadxj.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2mfzxcjrd.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2owhgwsib.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2nbhqvcky.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2lagyknlw.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2gvmvdqjb.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gpghnywl.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elgwboeh.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2rrdcxujg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2dfcadlis.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2jtgucklc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2weptnqoy.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2thncfbwl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2zghpygik.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyhsqeer.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2vayjcuqa.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2uvquokhq.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2ynzdkwoi.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2bsdeumcz.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2govmtisn.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2rvlutnph.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ypcikaam.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gt2ldqnkpky.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2sbtqfyvh.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gt2naztgbdd.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2olwpwjap.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2dsfavegc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2xdwasxnk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gt2zsfizofl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gt2okgyznyj.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdhodlrc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2udnrxgej.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2tnuloxvh.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2ugbljzih.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2jedoamyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2sqhszdyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gt2jafmcvxq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2uxokbrad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2tanyukot.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2hobvlzsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2kblkpcot.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2lqqsqpfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2lrqzqmsg.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2eaoirphs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2egdjabpq.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2lqrridlw.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwefkviz.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2crbgsmkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2auexkbxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2szlgbhxv.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwwonpxl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbprejjx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ulgogsvq.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2azmzxyut.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kmcnqflu.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2vxcbfbte.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2fqtsabtu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2wxrpxviz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2mqzgqtmk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2orjslgqk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2tspnmzkq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2uamcgtdq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2fbtcdhsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gt2obssbspr.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2ffblyjbk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srhjxkbx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2zaaiukyc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2eeuytezt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2srcdojmv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2mmyrljeh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gt2zsxgatqf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmhiqzfj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2wrerdkip.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2gosrrorc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esgylioo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2iolfdlgu.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2cydaslhr.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2zyocgiqx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2qnenefrm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2comlmwxy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdilyclc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2lfquneyj.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gt2aasvkkoc.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mctelhzc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2vgtavxyh.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfiwwfpl.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2cfdokbzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2xcotrera.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2jlykqgew.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gt2prayedap.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2bnuljbmg.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2rbrktidy.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2orxlfadw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gt2kntgmvjc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2uadvhcow.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2xajpqmwo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2gsanzzml.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bevqulwb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqhmeawz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2lubjamzt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2gxbhwkuz.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2sjoxekno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2xjkvqaqt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2imhqzjgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2srzysgeh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amzvzfhk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2kbhiukdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2lppusabz.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gt2shoesvki.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gt2tjbibkzw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2ifxoqwrn.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mejohqpg.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2sdafqlsu.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2zqmprggh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2txsybibc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2axicfhso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyvrynvj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2hwqxtwvx.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2fcybrijx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2ewbqqiqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esodlbzp.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2jfwfcsly.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2pqccccdr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gt2zmnffhcs.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2ubozqfes.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gt2qpxzgims.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2ippsjcht.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2otjxmcdo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2vijkyvub.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2utkwlsnf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2juoeaszt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2lbfoyyxw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2mglrgegz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2klqfdyje.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gt2cvodhfnx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2saqtwpyq.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2jxycxbog.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2byncxyvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2ejkgpclk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2rfzztxlg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2qbitcwfs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2bfnovpyo.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2htsnxbrk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2zthaohwc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2zkppfxhm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2tvkrgbhz.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2ygdvnvdw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gcokufqa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtbjmsi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2pmbindix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2pnomtfap.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2imezppyc.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2xvjrttxl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2vgonjonp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xzqhupua.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2kdccriqb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2vootorvq.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2vwgdhlun.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdlyxua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2cktzbpjy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2cbnqntpj.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2lmpfrigx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2yvutzsds.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2syrrmkih.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2kcsoijtk.html


<!-- 参考信息 -->