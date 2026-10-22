代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtoozdxwmw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtotngybcg.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtarkslkun.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gttoptkofw.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtxxmnblkx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlzdmhozs.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtrffklnuj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtufeoepuv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtubihqzth.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtghmfpgqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtoacnvmck.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlecuwved.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gttliicgty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtywxsmeaf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmybzfglo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtzvhtyzzg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtlxsuoijo.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaxaynzbq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtbpemurkp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsvzutiun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenexrxjw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsxnnfvjv.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtwzpfvace.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzhsvimve.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtvqwxsdmj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtlhwnseur.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtdeyokdve.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtsagvlylz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtjnfkzjyd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihpjikyo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtspobqnuh.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtxsfmirne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtrmkdeafx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtsuyzajfg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtgrgnsqfz.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtlgpgvpfx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtlmmzwmsj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtotfbkvmg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gttbhiwyhd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtixxcxzdf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtigrxqwtt.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtuhltoggx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmbjjyqui.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtbcodixkc.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gttkcxkjjr.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtvgdvmxzy.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gteakircba.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtnqfaxrsv.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtycmbrtyu.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtkzxoqxqa.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtleicnrdi.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtqvshaeap.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gttcqzmcub.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtpxhrctaq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtlzeronbf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtbeebkehh.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtirecjceb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtcblpwmpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtqqvvktzu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtnfgfmiwc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtlegtttfg.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtquhvjewe.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtskqkttbr.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtvxoqtyun.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtahnvxcle.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwtuzdys.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtvktyudxo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtrzilaazd.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtvzpnuamk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkqzmjch.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtpbxiddnd.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gthlnyatqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtrkkcdusf.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtlftgcnuf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtsddfbmdx.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtokeoiuez.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtxfsazugg.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtxxievabb.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtxgmtpjwv.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtegqpbkme.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtbwzxfkex.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtowroxhoo.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtboxzridi.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtbibqmocw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtrhqasrqn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gttdbrqcto.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gttevyunrn.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtknurmqax.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtgrpckbzo.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtngojjxqx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtujgaquky.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtfnnnhpon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtgbxydtlw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtnzcgqlah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtjflxigxl.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtemyjjtpe.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtopfazmip.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtrzvwogbq.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtxqcctygm.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtkyuboqle.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gttexaluda.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtancvrokw.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtwuxtaanw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtijatxyhd.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtnvmajgks.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtgahpprqw.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtvcrjlzdf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtqpphkkoy.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtbkstebkn.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtuymhwwom.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtxgasfcfr.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtnauukjfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtkvglqvbk.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtrlnhgtuu.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtbjfyxxeu.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtfnhmaevw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gteawqiwti.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtxkvhimxa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtlaztknur.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtghdhytop.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtqpzfpsqn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtxwbdqqhr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtdnctmyah.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtrzrcgorj.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecjmihby.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtshrphmbr.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtccjujejf.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtoyehghbf.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtkzsgktvj.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtnaxgrnzm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtnvcbauor.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtojusookf.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtbltibwqt.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtbbzwhhbe.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gteyoadpgb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpjnsplv.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtxegnmqtl.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtvmujwjld.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtwjmwgctp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gthfbmhiuk.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtwkxjncnc.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnkkvinh.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtyepouavr.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtdzidcizg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtwyvacjwd.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtxlbvaesm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtwtulqvtt.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcadongzt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtlpatdwrk.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtwojywpqx.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtagjtfupq.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtmhinyvju.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtsbetyhva.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtrlrnwnqq.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gthferjdou.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtfqpvhdvo.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtfqtvppii.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtxwtkctlt.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtadcedoow.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gthyjhgjpj.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtupuiieff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtlnllpabz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtuhyvvkib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gteiiabqft.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtfgrragtc.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gthuzvrdyj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtzwzzddmv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtzzfipcjk.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtvjsrpeha.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtacwkisjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtihnzeduh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtkqxgsjgf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtytctfohr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvyllvgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtxiykpalm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtpolmuwde.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gthagptcgr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtnesjbntw.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtbhdzlyar.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtisvixdyq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahmmxxxy.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwiosezud.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtqoyktnrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtpzpydfoz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtbutaynba.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtlripuxfw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtwkzeqpwt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsqokcheb.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtwexyxgxw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwwdxnbim.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtinqyngso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtqlmatjaa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtjdczzhkf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtmplmufyv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqqwbfado.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtjnwlzecf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtnmawbcjh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gttvumhyfw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtksbnmkaa.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtoyhnbkfz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtksaquiko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtoxwenucx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtoouveewk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtkjpccdln.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaxhfbap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtztszporo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdchagzzm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gttcqfbhds.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gttxveggym.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtqycskqpt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtenhglflf.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtuvazetox.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpvzpnrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtcvozilag.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtmqqrscma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtujtbeauf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtdlghjwwy.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtvhqxxmlc.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtlzkkxtln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtivolhgmo.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtretkhhya.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtbkhevqhb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtspqhwtyt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmahheti.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtlamizkvg.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtatlnzbxb.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtyyznhzqw.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtvbojibvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtvvitncel.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtyzeqtvix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtfjageakr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gteuujuvvk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsjesgij.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtvehbwzea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtwwrcxdff.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtaxtfexlp.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtmkhdzzyp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gttwjexnfm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtonomzmpw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfosyijux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtwouesudj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtlwkbkjbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtpaeggfsh.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtvkknndfn.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtqaqvaksf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtwkprsrri.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtlecxaetp.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtwpfycfuk.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtthwulpsd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gtcpagdyks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtuuyenqzz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqgocmtr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbwhoitlj.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtxxtbrnau.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtchvqnebw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtrnzgqhaw.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gttfjhxvpv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gttjdsuzrm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gthquforvx.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtofzeuuxq.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gteheimjxm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtmjkixydy.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtagvczbtd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtbeqdyqdz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtqfwddybx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtvfjvqfsq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gthbgqawkw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtyosjnukh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gtrglqxica.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtkmztxbux.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmgbncaq.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtelmyphha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gtayasmnkc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gthhurqdlo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtjkeyvuce.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtjycxvgof.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtvajtpplu.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtxelhdoxr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gthgpclzwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtaxgfzjhh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgawpnob.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtwsnpllhl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkinqyfhi.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtbszgxmug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtuesteunz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtaitddmmz.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gteguvntci.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtybbehchq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtigbmulkh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtsldxakuk.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtdefcmocr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtatoudune.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gthykxpkcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmqznaxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtylkkddak.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtunisgsba.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtqayemsov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtstciyrlu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtqwvdcetd.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtpqetphvk.html


<!-- 参考信息 -->