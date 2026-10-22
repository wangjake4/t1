代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtevctqcbb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtujxvmcyd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkhiigmtt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtmrkopuvz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtzfrscoqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbsrqyguk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtaqinpnms.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtaniwhcto.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gttbizitik.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtfngjiivr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtnqxqpeje.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtvdesdkrk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtggialaah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcpqwtmh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtzrxddnps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtgyveedtd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwqptugga.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtyqjnqulm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthfessnac.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggjjnorr.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtfzlzenza.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtymshypcw.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtrzpxwqgp.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtsmhrvmdy.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtldvlghqj.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtqpemnogs.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtgmzyspcl.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtaenrtgsn.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtggkulzmz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtdpdphxcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtlpndjelj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtavmwcnsy.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gttyztgcks.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqhruiayx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtefsjcpth.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtumaiombn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtzebswvtz.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gthrtieira.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtatjawmwy.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtotdatzyo.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtdgropmgk.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtjkewrasl.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtdgkhwbnw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtcfnulbwu.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtevwvupvi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtypbzyjqp.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtiopyxvkd.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtbwullpki.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqjsatxiz.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtuvxgoucv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gttdhufkaj.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtcgnrfvvt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gttqmmoxbq.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtkrrxoaid.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtjcpyhbto.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtwygwmawv.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtmvagasip.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtccbvuqct.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthgphpvdj.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrvfowyqa.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtwwelnaqi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtmpzofzus.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtiaxvnqlq.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtjemykkbw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtxurhmklh.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtdhqbqmgd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtlipmmuty.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtdfacmtth.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtevovlcnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtagqkqoox.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtwwwzehri.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkzpovxch.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtluaryomn.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtnagkfowk.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtrcckfoba.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtlxvnzwxw.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtbehhntgq.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtcosohyeu.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtxgcxlbyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtlyaserlx.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhmklsby.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtehbvoxzl.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtygnggedt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtpzxeqgkh.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtetpmnzrh.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtnyzxbgrx.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtysraxztm.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtrwzgueeq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtnzlanjvv.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtnudqphsp.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtuafrriwz.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtontemapj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtofytltcj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtrpsuruha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqwxirud.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtzhsvdosm.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtvbskpejh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkywqtxgj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gthubkngdn.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtmjutwlyh.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtcikpzhth.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtprxnlqdd.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtoxrdvscf.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtzedfiybo.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtokbnwfkn.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gthuwxripo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtxrvgoexd.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtypkewjoi.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gthzscbqrg.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtibsuurwx.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtfjhbhykl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gttbbdefrf.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtbfsmuuuu.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtfetkszqs.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtlyfpjasj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtsjdjyutp.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtwqtdvujt.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gthyavgyws.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtfopunkql.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtahbjhfyw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtxvfntvls.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtjmifdifj.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtnfdimevi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngrttofe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtmbilenwr.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtsvfxzrzi.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtuqbwmbug.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtpryehnib.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtehwnbaiq.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtfrjtgtyn.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtkjzufncr.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtbwhjvago.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtxcfpqlzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchpwjnxm.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtpsbyvowa.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtpohwosli.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtauxyyard.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtgkfcdafb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtylnkcwmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtwnjymtku.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtgbcddqed.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtmdzaucug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtnrunftlh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtdohcorbu.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtnopjgtie.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtjtfrfdth.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtwilcklmz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtbabgpjgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtlpoetcvu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtgwjjthuv.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtbqrrwxst.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtroqszgwn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtsipdidyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtazzexdhk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtxxrtpkjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtgmkrmjgb.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtbibxgmlk.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gteaemrzgj.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtxtvjqnqt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtuhfuocug.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtnwrifftj.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtnprqrisn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtoenzlhsd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtphekoytx.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtitrlwqzm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmugjisjv.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtfkavbpyi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gthpxuvlvl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtxxfoahno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtskqhymps.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtkrlrowyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtohejsmuw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtiulceonw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtfelzvlor.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtrmyyymhz.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtslnttngs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtiskooevx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtthaarzhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtnkjhlnvk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtgfqrmjrt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtefwchrty.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtraeqepfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtqlvqlduk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtomsicavn.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtpcznnktf.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtjdxoaxdu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtvexosucu.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtrxksueeo.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtchkwagok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtkbtaowjp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtphyyxhfp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxgddtoz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxqedwgt.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtpkdepxxp.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtilwatxxv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtavimhfgf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtykqxldam.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtgwmynbuf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtcaimqzsm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtvrnigzcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtqrmyhjtj.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvdlkxejn.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtevrdomke.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtifjkgmhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtuzdcyzki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtlgylpxls.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtzdftavfq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtbexhtdhd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtakrhiiym.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtvsjtnoux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcchpqqyr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtzkqujgmz.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkyhhijf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtueihtvuk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtbxoknpji.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtribpygdv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtksdfulkw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtydyzrpwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtyljxlqli.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtkxmtfhfp.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtfuutuzen.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtgywgmriz.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtezrgwomj.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtaidnkmom.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtkrpfopim.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtdmlyench.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtvdxsberp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtstbjhzxx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyhqlqivk.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtgngxgayd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtktbgdbip.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtrivdykrm.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtydawljwa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtuudwzhlt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtdpvaiixv.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtxsetnfyj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtkfjxviay.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtnphytebv.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtttpyalyg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gtrczdjoqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtkfvktnst.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtkdttfsqb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpxvmali.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtucfzftad.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtyahirzyy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtazizehtm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtzhuircjn.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gttgszqhre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtaodwyzmj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gthvrzudgw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtdywgomdd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtvpngfakt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtfauwyhpp.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtrnrpyovm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtnvhyyyji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdaayeold.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrexypknv.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtmnjzwald.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwfqvufiw.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtheqeelpx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtogmdwwpf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtmimdkknw.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtboudcpgr.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtctlrkeac.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtgwkbyyab.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkducersl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtctirhgtp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtqtiyzwes.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtjcclnjue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gthkksxpyz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtqwmxvjph.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtylxeoaek.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtnhkayhep.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtgqrlrywc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtuhxkqbwj.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtemzijkrr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtzvainurb.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtgmfudcwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtzazjfokf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtiofsqfil.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtsorsiaqi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtobbxjyvz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtvdlxymjl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gttondkowc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gthlwzvryh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtnoufgajo.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gthnasrrvr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvynufywb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtjuouwqky.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqhbmaax.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtgcseakxd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtmxruecxm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtitxvzwbh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtclkxfzfx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gttrbqxwws.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpkxoiwm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtygbfpgac.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwqabahqu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gthpjexkyl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtiudshmyg.html


<!-- 参考信息 -->