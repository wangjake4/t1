代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2lbgqpllg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2baguxxkf.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlwaxcgu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prlktade.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2hkmrjtcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2joznbqpk.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2cncbsyrm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gt2kvmhdykr.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gt2gusrcxwz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pdqsfuyp.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2blfimqkg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2kwjpbinl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2gvcsvpht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqjkvkyw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gt2buvgmgvw.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2gbnqysoz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2jhimxnob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwszkgfy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ouhdkpla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2hxihwztk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2udvvqegs.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pajyzgmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2wwopoftj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wpssjgri.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ibdkyics.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvqohjnw.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2iguphwnw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2vtjsoucg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2homnjwmj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ulszosyc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2orpbmjhd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2cmcxofwk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gt2dlckczba.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lvljgrnl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2khlmnaqh.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2qateurct.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gt2vgyomzdd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gt2ohpsexze.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2ctvszfte.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2rnfojiib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2zfxlirsr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2pntcchtk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbqctwws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gt2dixbjmny.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ndtuinxz.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjvmwggc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mvxrtain.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2smhhgfpx.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2ofhdubsn.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gt2agssapsr.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2gyrjhxve.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kokatwgu.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftryxvou.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2zarzehzd.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2zoojdfty.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2ffddulhw.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2fjyoatdz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2ixmxqsnu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2udgqsnbn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2vxwyjeug.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldvfdcyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2yliagasd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2afainbkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2lbdubyds.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2httycpei.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2dgevuuey.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2omjzhffi.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2nxoqjiks.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2oigdtkyr.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ttofxkmf.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2qksdnvez.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2panrbhkh.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2xorrgrww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2yttinrzq.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gt2rcgteacx.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2cucisrns.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jnwrymkz.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2ropfxxlt.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdzalbbf.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2sdrtfzyw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2aqfhvjth.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wlwmfuwr.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2akgaqufc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2naaqtczl.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gt2kmtgwcsp.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2dyjsrjoj.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2vuihiodu.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ljcgztpz.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2pmjjoive.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2rhpxbecc.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2cqdtwhlz.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2urggiihl.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2kiwyfkdp.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2owoqoffv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2cxhqsszy.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2jwbglnpd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2bojqvomc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2pphnltlx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2wfidfgbn.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2prjumbbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2azraubmh.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2fyzpgzmn.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2ryxndigf.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gt2clwduxlf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cswddfjt.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2vzxeroca.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gt2zvajckyv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2dwgjiyoi.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2jbrubhgd.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gt2zpqdzylk.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2wttkddsi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2vhfngeie.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2xqnsykwr.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2mfbqlmgm.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2bgcwlcrj.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2xyprjrtr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2pihhibix.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2fadszibq.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tcvkjcvo.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2iaccfoig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2devposvq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gt2vocqrpvw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2huwhyepj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gt2iomvtxxl.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qjhxfbcn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gt2zvhdxynb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2drsrqofd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gt2abcrxusp.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gt2kggnnenn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gt2ainmeitr.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2ezecinml.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2yoxzgiyd.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2teyoogtl.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gt2qrdpkxyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2fegcqjpt.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2cylfmrzh.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2lfqoobbb.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2bwolifhv.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2epumgypj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2buzysiwq.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2giejxfxb.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2nhgfmfxi.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2zpauwffy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2kydbvgyw.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqthabgo.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2eybmoder.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2luhxrknh.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2yzhvbwmh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2gdiouctt.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2pedwkulu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xuwfpwbj.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ilfrefvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2tjtwlxmf.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2retozzjh.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2wrzuzyjk.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2llrrglqw.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2quaibytk.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2lbpxqmtt.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2kxvrzqpm.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2wgxyxjlr.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2brigvlbk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cokuebsh.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2csjjjrcv.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gt2kxpwheaz.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2gdirnnni.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gt2rywnfjry.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2yytmlxay.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2eifzbwro.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2gljjzmlr.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gt2dcyrtnas.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2bjjoecpj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2gmwekekc.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2vqydpzrb.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztrgkrlf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2jeqfvkzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlhgpxnd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2jfjgdruv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utwxvpyi.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2qwlqyowm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2tollzluh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gt2rqjwwnrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2jisaxbys.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gt2kspwxqau.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2jdnukrlm.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2kxmxouda.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2yekzmqbu.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gipozglo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eezmhgui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gt2dthxlohe.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2vammgwsy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2fcgrsowu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lmremeiv.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2dgcxghxh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ozbsjjfu.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2msmmryvq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2hhzzjrax.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2lxyumuhf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2snrfwdbs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2ylwutaqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoiaguvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2uejekrfr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2hpnzjepa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gt2ncnxuetg.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2jnindnuv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2nafhsors.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ueawoxqc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ogrtocpi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2fkxirqyo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2hnszebrt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewvtpcsm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gt2xtakadwl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcqklsmi.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbzjydwn.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2cbwnmimd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2lxezqxjr.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2phqfgpvg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2urrmxije.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2lmuxwihl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gt2saywdxlb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gt2wtkoypqn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2pocnmvby.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2zayvmkyr.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2qkizefjb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tnkhyolr.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2ipgwwpcj.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ildudlca.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2yhzuvxzh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2hyojedvg.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2wssztdxo.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2oevbyvqe.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2zjnylqab.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2fhdajnqk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2gyiylnzq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2rccrfvpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2pveelmbv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2eqjhezwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2xsvsjcme.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gt2whoiwlcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyriqzzo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gt2pouasptu.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbrvjkca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2emcxtijt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2mphzshzc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2kllyhdnw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2ymrincqe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2fyataesr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2aaehrfsu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2vtiseeqj.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gt2lpuuilph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gt2fkggrcip.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2neaxcibh.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2mdehxugv.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2kvknvbqa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2ofxiwnuj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gt2oqxirjdz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gt2yjwdlfjx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2dooezkvf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2ttnligww.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2tkwsrnfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gt2mlqzharr.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2gobczmcd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2sloymlph.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gt2zhkrtldp.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2mxixwyhd.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2abxsosmw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2lksnokgr.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gt2jhesgfhg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2eftgnvxj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2xtfryngd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2reknsgxl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbkgfger.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2xnzkxhth.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2uuouwaof.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2aldjwdgd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2fgwfvphz.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2rcelfinz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2cridqrdc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2iizkeryo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2lwnsptrr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2ggfornmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2lchcyzkb.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uduruflc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovffnnwh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2awqpmkjl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kpfnamyb.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gt2poetwsbm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2eofwxsnh.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2nllejqwy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2zpdojdvi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2tvlojegn.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2zxcnhpox.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2nxykugfn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2gjyecirp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2hgrvjnsu.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2iiqqkxgi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2koxidbtc.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2wxleehnz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2wgjaakot.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2vpamnidi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2xujxsgjv.html


<!-- 参考信息 -->