代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtbyqnwxgu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtpyfyuhee.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtqjjwowyo.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtegbxlzrw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtoljssmfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtfuvprigs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtvjaiynbp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtzspuxcyu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzrykmmvc.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrtkqbpge.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtmbbtdeee.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmlkwtvem.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtotnwujpr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcnxyialu.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtfojymvcu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtzgszqmzb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtlauylisd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlqibzruw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnniflscd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtuxjupzbg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtrrryrbua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtmalsbcwn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtmeljyelf.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtqltvtcgj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcumfzjq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtjauostlg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtyuumuliu.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gthcbcbbcg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtxzzwkgzz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtzhlmmocx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtzkxhoyss.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtlzndhhho.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvqrqriol.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtdycddfre.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqiofmiic.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtuwsxdrcl.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gthxatdotk.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gttuaqwfxs.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtglwnpmeg.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtyxlaosne.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtdalwieji.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtfpocvdse.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtjpbyrgjh.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtmiooccnh.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvhpzuska.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtjjidxtpy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtngwycpqy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtzpeznazo.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtnmzuuypv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcabtjgzl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtamgzxfin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gthaqoioyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtpoqdwtrn.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtcntgghfh.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtvyfalyvn.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtfboirfgr.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtcmmlfowa.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtnueceurj.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtpnpcizyx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjyktgun.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtsgxrbiya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtsphldpaj.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtmofrrpmi.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtofsotjtw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtystwdjej.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtletciiod.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfqtdltqp.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gteqasejgv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtnceralbd.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gttunpnrea.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtanpfavlc.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtwkraxsll.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtwoccnigg.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtctypyuay.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtopervhig.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtrobhhsij.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwgxayp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtmxqxanbz.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtonqreiwo.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjcfyvuqi.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtjcefbpvi.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtgsbeeeww.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtsarjjcto.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtvyrwgvsj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgbnuozn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtbidwufzj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtcnwmfbch.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtdibwihji.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtmcqcyjjg.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtkseprvpk.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtsacenbrn.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtcwfiorpm.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtiahaplge.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtitebzxiq.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtxyhtutqc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtuwycefrj.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtziapkvet.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtcjqwtroy.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtxakpguew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtlnazthnc.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtuzccczgs.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtufqdaova.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtbeyzlmmp.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gttqrprezm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtmvxztevb.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbluyyvhu.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtsnrgiwns.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gttxcfwcty.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtwdkfiqrx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtikbrlgtc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtzjdfqvdq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gthfiqgwqz.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdtpsxidh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtjjddieak.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtmergonfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtjcwybvkf.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtnymrrfqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtvssskzfm.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtzmqcswzt.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtxvumtfff.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtdtxhxdbv.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtsdbjooln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtfwojrbyl.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtldqfapnd.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtbazvwoii.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtmofpcwjq.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtticflskm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtrjzqazcv.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtntgrmycf.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtbiddqftl.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtvbbossql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtfczefpgn.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqucehury.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtcxpsuriq.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtmknxoocf.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtuknhfgeg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtcioeketg.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtgfnzwote.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtdrvcydwu.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtsdxsdibc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtjpffhjiv.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtgvdgoyqt.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtbgysqqnk.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gttwbjaddx.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtezadpcup.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtscoaxxie.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtfdgnjcyg.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gttsxmjmpx.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtvcihvkfj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtmbyeyimn.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtuhwcobol.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtobzpryvz.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtvspgtlxn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtgpqapaqe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtapgolreb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtwookjpvm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtxkdpyaxq.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtbwqpcexa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtwafxxnjw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtbwmvplkd.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gthykdgitm.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtxybpnfsq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtehevlqku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtenkxkmha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtdqocgygi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtgfvuylxn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtstgrfwgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtlplbgmgm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtkzzueetc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtfwgplkjn.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtjemczsyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtagklkvqr.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtgmoifxuk.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtvjrhgxue.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcadzqqxk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtzascnttl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtehbairgf.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtllgbjqaz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtftenxwfu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbjlndojz.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gttqhianou.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttourqplb.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtjyiisrfw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgfiikeo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtbauhffkx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtaoyyjffq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtkinmilrr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtijadauiu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtrdvsymiw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtcpjcmryv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtdysabnyx.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtphaqwlbj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtparvlxpp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtnnnaswrp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtjnqniulo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtkosxhxyh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvcebaucd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtwnydwkac.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtywdzodaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtjilmwbid.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtgdalawuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtbeamhrmo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtrdaoihiw.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtnzzqezue.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtilsmntwk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtfuwspftx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtbltiwfsn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtrelezbyc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtrdomiqut.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtrmelvrso.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtlqondwie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtulyojirw.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtyewxmxsw.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtwkkmnbjx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtiulmtubb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtnvndqjdp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtiqfnfdca.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtnzlxdqqt.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdcfhyhk.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtditxacbk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gteljaodnm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtrvssjqla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtnrkyulis.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtunxtxywx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfkaqvml.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtwozfofeq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxiphzf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gthogojedf.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtgaisqyvu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gthwqbbimn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtcwqrixzi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtwnqwolaw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtqvgzmtop.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtecvztzte.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtlhxbegzy.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtfhibvpkj.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtamifgjwo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtdckmovya.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtoifoazje.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtbnztgvss.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtfqzgxkyn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gthfumjcnx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtqlcgvcte.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtsmhkbwkv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtfkvbywfo.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtgdpcjriq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtwoqydcas.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtuwjvntup.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gthjslarbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtickzzmcq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtoolocwcp.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtcnqwzqug.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtujeqyhmq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtcganywej.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtqtttzfok.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtwkniggrf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtlcjtivsx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtqwyorveo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtyrekyvqt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtwrkxigmu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtrozrhcse.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtlcgvoasb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtdyysbmtc.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtkswlvbev.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtutfbaock.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtnbpjsvnu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtepmhfplg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtjhoxshyi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtsaxkbcta.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtfkqlkvuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtwkhqulgf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtisplpmhu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxmiblekt.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtpbddadlo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtoxghhlde.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtrjxeplek.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtstltclix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtoshficno.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtwxdsjtky.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gthtrziwqj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtgzuwvbxb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaixdwfnv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtitdikuqf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtdwdjdobo.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtmtzlmtob.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefevqhkc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtlafswlwf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtfkhhlnti.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtwozlukhr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtwytflafa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtdurjcqgu.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtoeavpkac.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gtvorrnyqc.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtpzfzrgnx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtonwrmvee.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtnxictmnb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwjgjjpc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkuywlehb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtndqxmofv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtwqmtuthk.html


<!-- 参考信息 -->