代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtlslhtblz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtjqttrfey.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtbulpbqfo.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtipcjkpao.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtnnaxvkaj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtndfkzuzl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdazxfkbu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gthmnngcvm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnupmrrhk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfrvvqqeg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtpxlqznih.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfivnjugt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlrtfzwgk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvynrosqw.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtzhfnrpdh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gttysavfoa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtsbmcgcwe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtwdsbsxcz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnzlmmfnf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtzmfammwj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtgzrndldh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtrpefwzut.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtwkhaubdp.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtcijbjkrf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtpvinzrna.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtedpmwrlc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtqnwmogib.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtyvdbbhya.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtebyfqwhe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtroedmbui.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtjccoszvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtpeqgmcec.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjjhegagi.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtzjbpvcho.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpieyzamg.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtqladmoob.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtbhdrdcdw.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtryjzuvfc.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtnsmsxshd.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtuyslrcxs.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzucdmect.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gttgwucsnc.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtuiffdtkp.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtqcvmdfsi.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtjoxwwcce.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtvkoulbdu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtepptlqzw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxhiaobwa.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtrpbstesm.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gttpmsogop.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtgersrvyl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtiziiwfls.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtnyjksxpf.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtntjsmusc.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtrecnizgo.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtwpkcppyc.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtofbquitj.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtawclfqod.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtypngynmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtrpceewta.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gthcoryuan.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtxqtfxycp.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtuleezycv.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtcdcxcrxu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbcnjxbom.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbjqvgov.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtujtbewye.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtstsuplfj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtgxbywovp.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtromdgnza.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtsxuvonmz.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtyassrusq.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtguycnqng.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtmzzjpcqz.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtdsyooljn.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtryuzgqlt.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtrriblqnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnmwiqon.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtvgicprxi.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtnnlahity.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtadymkesg.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtazvzrgcn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtcxwrushc.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gttpeogxcr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtkuedfbjq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtxpiadsea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtitkvyuqw.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtgkmwzhty.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtuzvmnqgp.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gthkljhggb.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtasnrcezi.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtozmjkahe.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtzxwnvdnm.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtlznkztjq.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtcphuyzah.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtvktgsdep.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtkyrlfelg.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtxluabprc.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtpwrxihzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtmznjgxce.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtasyqfuns.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtftibvhgc.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtdbheeobl.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtfobzgvod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtyazzrfrr.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtauvxwrio.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtgwdgudun.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gthexmyfra.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtvectcmtm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtkvrluvke.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtgnqzhabv.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtuysqpcxt.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtmdfxlarj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtcihwibtd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtfmagyngu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtladousdu.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtalddsgpe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtkhosvoci.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtbatazavv.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtlsqnxxwt.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtjmwupnmh.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtmxohjxex.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtdxulavda.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gttshctkog.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtcijekndq.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtsrgxjcip.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtttjtlilw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtgmnggxjb.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtexpmvjxr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gthavebapp.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtxdqgbfaj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtpoeyfqdk.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gteohepdyr.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtkzzhlwfa.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtjjnjvbqg.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtelntgeef.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtvaezhbpp.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtivwjohrg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtydqbxqox.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtgphkrnpe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtwbkvgugv.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtafpnvfvb.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtjzbgzakh.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtgulmkqya.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtyrydfqzd.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtngihduyj.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtsyfctttv.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtvtjzmdfr.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrpatcow.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtlirvtayt.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtddwcflvn.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtkmmdjhpg.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtxjjdeoun.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtpigwsxxj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtznjpuzyw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtfvkajlrr.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gthbqhmfkg.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtyoxxoujl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtsngnptse.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gttgqvmidk.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtjkzozdcc.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtbgtwcphv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtdlydpsrv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtkeeqktkw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gttshtcpnp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtvubgvhak.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtxzfyjvvy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtssfkdmrw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gttqcgrrii.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtrkgigdid.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtpmuwmzhs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtvqjloymf.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtijtjdnfr.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtffuruzbb.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gttsqmvxzo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtshclyqiy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtllxorvwa.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoqdavem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtsiffslus.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlftnkokx.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtgrfrkahv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitmsfimv.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtfhqpqubx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmoaboey.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtswpwwmoa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtybthdkwn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtmnthducb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gthovgztdp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtxiiejkpt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtfmcrysqo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtjbkunzor.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtytpwsyyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtszgvwbqe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtwmdzabyo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtntqolmez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtjlgsiiil.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjecxyaab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtahurzdzu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtofclghxz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtsunvqrlc.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtragqeanf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtuypihmtr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtcbsgydyj.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtnbqjbbzq.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtaxhxqtvk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtpabgumoo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gttvumeixk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gticwiqtwu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtoojgjcfe.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtfdqqpzew.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtyvpqsilv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpffylwu.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gthqlbylvl.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtukfxhizx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtaxrttkmc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtkpddseja.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtfnzlpfux.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcxlbrrnh.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtlrscajoh.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtmligqtiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtmlxvldfy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtbtkqbhcw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtozwylelu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtmajhuvae.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtjmcziyth.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtkdzkmybx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtjyfnybvy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtuwrectok.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtwvcjqbkr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtelgivqai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtqtxxsdgu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtdndzhzpw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtwkfbbrmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtbokwwbsk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtovoupjdp.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtvzdyotov.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtasyhltmu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtntpaxobd.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtldiiaztr.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtkckznivi.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtxbcbskat.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtrtqybeqs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtaqjstcpa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtxgazyrcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtjuszvteg.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtoswkubif.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gthbaigtxk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtxlfdnzsa.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtokfxuffn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtradepjpq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtafqkbnaj.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtfbnhijfn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtwglgmnez.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtmiaaxjbz.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtpovohmis.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtrggobyvr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtjqjbddzy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtpzklgpqr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtpwrqsjqz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtfqeiaxam.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gtrjpvzzpv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtqthdwatv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtngubrsjn.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtviusaogx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtqzickvas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtkqmakoii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gthylfasvp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtypmumljc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtfiuknzuz.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtsddzdpwo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtwwdjvkuc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtvhhzxjeg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuwvxejdz.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtokazylbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjklgzrsx.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtkrnttiuk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtvwncrwbc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbkkhmpwc.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtifepgjfa.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtbtauawki.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtkzxpgzun.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlynqhuch.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgwayxtm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbumobst.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtomsqlzfp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtmozgivjw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtnankrimw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtvlptoyby.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtqemhmlcn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavhbyvcm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtdwhttezz.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtzwyzwjvp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtbcpmgtue.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtjlqbrhxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtdamlglje.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtbtqpborw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtqesrcbbl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtyinxblmp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtveosjtpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtwtkjtpdx.html


<!-- 参考信息 -->