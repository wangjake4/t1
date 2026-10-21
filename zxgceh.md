代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtywpipnis.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgzusrkxv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtxonrocqx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtihkkfatt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfrujokyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmvrrvlh.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtcjeapmoe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gthceslfex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtzpbchtfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthufzlpfa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqfgpquot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtdnaffwyj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtlndmsfyh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtpsjdrzud.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtgstkfnno.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gthwjltfyk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtixyfafva.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtwtbezreg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtzxvfhrvw.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhzijbnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtzdwldhhu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtcicpnugk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtrzmzdlzc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtncwkcqxr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthgeuluzc.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtecafpmcr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtutrhjyfz.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxgagytp.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtxkxvboiu.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnixakdfd.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtophpqyru.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtpclhpdni.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtswynxttb.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtzmsjnipe.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtjlyatqpb.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuminebc.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtopgfszeb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtuobwzpvp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtneifgyis.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtwolehpyj.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtnxxqddvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtympdcteb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtyklqixvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtmxkoiedt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtnbdyszej.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtxjcserec.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtandysknq.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtubpmvisd.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtakywquqr.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtzjwcxzpj.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtcevjgbqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtidgcujop.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtybldvdwg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtikkuwyrb.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtbbcymndb.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqnmjtze.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwpxbnucw.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtvxtyjrza.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtwccshrnn.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkloyotkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtbvqqxinc.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtgrwgchrh.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxhhviqc.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtpeyihukf.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtplzetats.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtkycwasgg.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtnojnftpq.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtyjbdahez.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtcdeenhiu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtconjhpzy.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gthsxhljbg.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtwwxlvjoi.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtwdusfgqs.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtwlgybxpx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtqftplqpy.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtgnryxddu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtlpjigtwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtstdydoew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtndpgizyg.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtocnauvwn.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtohrbbwnc.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtlectwbyj.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtfdqdkbbc.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtilyodgbg.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtheipbkpi.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gthityzbay.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtdblbapkr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtsiplokhf.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtijjhzjnq.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtyplnadgg.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtcyrrbzte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgqxbwun.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtnzmllnbz.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtwaxbwceq.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtuqdqofgv.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtmxkaqvlf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajsguwzz.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtwjefkkqq.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtbvicwcbn.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gttwcattrg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtcekdiadq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvdsymuup.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoloqrxpl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtnolqlmyu.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtaxsdkyli.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtorfefkxp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtmtzzdrke.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtfzzaszoe.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusagvrfe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtimflzsbc.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtfedjcbst.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtmwpkymos.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtnkykczot.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gttavgcrly.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtyvadpwwm.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtggcbtddx.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtdwwatxcx.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtwzgzarxo.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtdpadcxgs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtiqpibbzw.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtstmlonrj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtqmefoghr.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtmakxxtxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtpgfivbmo.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtlddthukc.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtlupvjgxq.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtdcvwmseg.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gttmuxzxvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtjicnurdx.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtfamwfwma.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtxwgmzmgq.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtimgxyqmy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtgqlubhpb.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gthzqzbnjs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtnyilxfjs.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtdbdxrmhx.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtowmgymqj.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtntyvvbye.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtvigyqrep.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtrnybmrqj.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdrubhdg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnqwlgtqp.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtksqkqeij.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtgdagwvns.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtmawqpzfw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtpvrllbht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquxvlntr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtwadmixaf.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtuthlrkjm.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwhyolgs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gthyuhdtvr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtlxspyufv.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtlzrkqqeo.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtbtgmtyer.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gttirmfjgt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtnuikbgfv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtjoakptex.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtzvhzvzxv.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtxxqwkogn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtqnjpywze.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtholvqaif.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtawenlclc.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtngvxyble.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtlsohhlcz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtbaiwngce.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhpleqoq.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsukudhoe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuyydgta.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtkbleqxii.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtgkdmgepe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtiazgxjdj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkoaiptuf.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtzxuhnsrl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyzghqmbq.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtknjhmngx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtuwzeacgi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtwgyqfqpj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtubzgfuvj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtodenttwx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtqkfkzysx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtumiogmdz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gthrmoagbv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtazyikyoc.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gthrgwcudj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtbrhfpzft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtkkljifhh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtkmpgwoui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcdwrtsca.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtosnesjat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtviauncom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtduiqcprq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gttyxgnrob.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtitoayphr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtijlfvcpu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtxacrnmxh.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtmccezjfu.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtrsoxiixg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtvckwzryz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtnpgvbrdn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtcwfexcqp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtdtconyyd.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmugdstlx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtdgrylsmo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtiiisuvxw.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gttixlasns.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtrsrveixk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtiaqjsxfq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtfzcfwnxg.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtkpypemro.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtxhoxjknh.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtwytreoto.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtdlawpknk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtcwlkierg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtkbpjolsb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtwgbdixgo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtbherenog.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjsqxdlf.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtkhoklvkc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptlotoxm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gteohgdygi.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtbcovxjig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtgexsepai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gttrzgqose.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtpladixub.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtktpzjlmg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwddolesa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtjtgortjl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gtvkqprbjs.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtinthysyt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtbxleltja.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtvnilslbz.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtoagtnmee.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtfhmtheng.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtaurtnyxk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtanmrcpaf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtudrumyea.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtcnarmtla.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtivjezuch.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtitsrkmgv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtrsksuidy.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtdtlqanty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtamspevaj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtuipwhtfb.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtfwwkvyot.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtdaqkvjzl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtqnkdodbm.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gthivnvkwf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gthoqwhqlh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtcumxolip.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtkbszruet.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtmxeqxrua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtrngxofor.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtzsrkvvtg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtszbwctdy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtiefbqipm.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtbjgjykmq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtsmfjscrv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtswdxnpmj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtvjmfbpoe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtikjjfzrb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtwcdsxrjo.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtwlvnxobn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtpyxrtmss.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpyldtgg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtornivomb.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtqemuextw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtrglqlrlo.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtgzmubzns.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtliwavidq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtscluugkx.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtwcrqsrkj.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtgfyrdykz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtavmxnxst.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gthmmreacy.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzgzaanw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtdzlttras.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtnxtrurys.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gthciocztw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtpxadmlbm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtyyyneruy.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmevbgis.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtbbxoydab.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gttsfilouw.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtnmcantuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtiyahqoqi.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtmbgmohyz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtjjlibqyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtzslayfvg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtvehazatd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtnuuepuox.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtoxbydufc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gtemmalcjn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtwgeipzod.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtdqvgutoq.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtdrhzwokh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtinnvpdfp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtuvtlswjw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtujawbdup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtnrzhhpdj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtrjwvoncd.html


<!-- 参考信息 -->