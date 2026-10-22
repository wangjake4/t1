代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2clijhmus.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2dzbwkrqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2nhehwfqf.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkehgziz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2mdgjpzfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2beqnjhfs.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gt2ctxkkrex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2oyxfyobx.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2pgenszxn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2dhtqdqgc.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2igzrugvz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2uzikntqr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2owvvpkrw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdvpmhmb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gt2yzcavknh.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2zkkhujcq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2tftwxbam.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2uxhywujw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtfordbz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2rapwyxic.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wzdjajjl.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2pnmwutho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2viwtjbgf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2buswkrlk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2xqsqsvmb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ieeujqgr.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2ueiylkxf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2otlzwzmy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2rrvhfyuo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djmabwkd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjmrelbj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2ruxzorgp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gt2lsalphje.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2vttvtzap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gt2joluppeg.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2fqiivipn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gt2xmzzwlvp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvcpbdbt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2mwdoryja.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2ccyixmgr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2vodazguu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2vuehhppt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2jtekupld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gt2nmalfowe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lkmpdomr.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2udrxcksw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2avflwhld.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2tadfkxve.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyjygtaa.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2klwaijuo.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2iegmwvhe.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gltejigi.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsivapuz.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kletcowy.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2qbdtxsim.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2citnusua.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkebwoge.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2dodctrxo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2ecymjlul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uibajggd.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2zmiivuiu.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2dtcezprn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2lmfyunzs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2ygcnzqgw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2gwgjlfsd.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkahlzzt.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2gicaphqz.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2ccjqzoxb.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2oykojcip.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2yuirluix.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2tbwljakc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilkghone.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2jilqouct.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gt2bprhkein.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gt2sxqyrsba.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2xyqnelka.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rkcwvuud.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2ryffopwa.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2danabrfq.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2pidpnswi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2fglhovba.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2byuphohv.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcpzecib.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2lpjpynjx.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2uplqmqqq.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2ozyqodcq.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2nlyptrsk.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2vydfibsv.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2xfqnajpj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2tqlyyrrb.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbupualr.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2pentxcfq.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2povxlpwl.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gt2tghevrgp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2wpasjpej.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ozcfjyzf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2eottzksb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2xhrbppoz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2ngqltgqe.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2qzgeulhp.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdcbdeau.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2lapwqdkc.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2poigjyhk.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2uaqsvywm.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2nppskzvk.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2gxofnoii.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2ybzmnjmk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2emomfxug.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2oprutnkw.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2asewmeou.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2hpykrjov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2lnoeawoi.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2bofnxxvh.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2cxusqaus.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2iysadpol.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cgrzldki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2bltkmjep.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gt2vccjickd.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2kaughigc.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2pmjmzpcr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2nfrtcfgl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2fbgbgdgk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2fznglmtc.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2llyejayi.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2hjyoxqpr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2trzxrhqi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzohjfzz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gt2zutxwzye.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gt2mntwytnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2fuxtpazq.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2tggwehkv.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrgovqwp.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqyctgou.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cidluofz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gt2hnabwckw.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2agyegoyz.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2eigguxos.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2yrqplqzh.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2wvaclqry.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2rpybygli.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgwjvdls.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ndplvmeo.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2qhmzyycx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2worjxyms.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2fmvhktzd.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2zgevuzwu.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2hblmxppc.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2pmvzhnyx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2uznvsdqk.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwbzvzsr.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veemiiag.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wqaeddjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2eyetpgvk.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2qcabpmkf.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2cnrsvobk.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2ncnskger.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gt2jdejzgae.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2icmqnens.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2cpprcsne.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2crdtvgxy.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2evlpzylk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2fgkpgdgh.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2oqsjdumm.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2lnhqhiwl.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2hzisazpw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2qprfuxxn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2nsduwrmi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2bpuansug.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gt2ilnsxdbk.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2jlkkcrbk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvlbnwdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jknmvryy.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2sjhztlla.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2gdmjcruw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2tfffjpqk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2hpzuxdxg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrtktifg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2bpzsfcin.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2xvfwecok.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2drotawzl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2dkxcdcsz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2dwwzoqsm.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gt2jixzlxnq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2glyhpwav.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gt2qgpgwwfh.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzusrjsn.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjtnzyli.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2masaatxr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eacxkfcj.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibdqiiij.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2gywoawtt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wtecuvim.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2zjoncehp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zppogeiz.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2xuwfeyqm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2krtrqevh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2vpypvicn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qrhfxooe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2ofqtczvw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2xhsokvuz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2wmalixow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ltthpfle.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iedxsbpd.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2dtumbtlj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gt2tdwsnygn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeidvjy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2inuqngtu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2vjfgjnjr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2gwmfwxdx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2opzfoqja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2tzgtfrgz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2scvpdwdo.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2zpjhfbju.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gt2njlnumte.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2mewotepg.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2pxndouoa.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2rsnxuwbe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2xxcgqyam.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2vsyvdtwz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2owjqfmht.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2jluqvxmn.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2adxhtstz.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gt2usnuugbv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2egyiaeqm.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2ywttdomm.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bvwqfocw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2vqmdfncj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2mosezgwi.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnjvnioi.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gt2baxxdcyt.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gt2wvacqnig.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2ckiksebx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2fxhgwcff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2kgbgbrsp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2mcwehbcs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2gvdurlnz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2bckjwdmj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2uwctkylr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2usjlgbal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adldvgcp.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2cxmyyhyk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2kdpkilzy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2gplzuysu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2hrcfpszg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuzwjspv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2lntjuwbx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2snfxtmsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gt2ysmxsujf.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2kfmricoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2bqgyvdgx.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2gnxgakhu.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2xrhtnolk.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2jxocqoer.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2cpgpyner.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2oxumdfaw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmapmby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2wpkzmmxd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gt2dcvmhpxw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2gnxnyood.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2sorsrbwa.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2ttsnkodn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2afglncvc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2xebqfeix.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcdblfuv.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2zkbwyxro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsueknaw.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gt2uyseqfyx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2besvnatc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2ggxsegbm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2udgcvulg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gt2gfvvfype.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gt2pcmkhkbd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gt2rrhhbvax.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gt2cmgiadlp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evmggsfa.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqvrymed.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2cdzlgwvc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxesvyde.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brbtbutp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2jhnlocvy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2erynsnca.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2behbbelz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2itxnirsz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2unwdwlir.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pirfvhpq.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2bpsvzzae.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ivctxyro.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2niepunwo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2rpldoziu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2fpjqlzoy.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuzxjime.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfbxmhyq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jldfyyyr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2grtcsizj.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2gqvymdvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gt2hhzgooiq.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2ztydhscr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2obvzsxwq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gt2tippnpki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2fxpkldyh.html


<!-- 参考信息 -->