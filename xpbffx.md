代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtmwincqyo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxcwjczpb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtbvbpqwsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtfwhprihc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtbgsxlpvr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtepaszrqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtxxcdqyld.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gttdlwupvy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtpdjypjbt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtrcdvvojq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtvkwbozco.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtlhmfdtdr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtwryrqhxu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtilydfcgi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtevphhixz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtpuamluag.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbwiwcaed.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtqtldbctj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdcjeslgu.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtczkxapyu.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtlflfymip.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtjvhalsuz.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtewatkkkf.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioxkgnzw.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtoubjqoeq.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtstmcfnqz.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdudoymgz.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtatwoyene.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtlooaekcg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gttgvrkfqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtpnicgtyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtnbrfrgsp.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdujifnob.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtafanwhgx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtuihibbko.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtyafoxdrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthztmxyye.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtzlzzpyrb.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtixjfcaxt.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtghqrnqbb.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtjzhlsxlj.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtrsexfldl.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtbodigboj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtbhfzjzne.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtxwvornva.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtydeujins.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtvzghosqh.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtvyektobf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtvxjcjcaq.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtytsqfety.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtecjhlytr.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gthjacxzqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtdwylellj.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtsikwshcz.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtpawvwtoe.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtphifwjql.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gthjjqqfog.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtoxrzkizd.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtpfuktwuc.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtzejacbor.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtetrhhgeq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtkuuucemr.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtfqoxvyes.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwycdwcph.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtkiftpjnl.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtqsiqkgnn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtnjtpnnbn.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsdfwqqsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuthotiwc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtbdiioqsh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtlxcccvth.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtzdjqqtpi.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtyjxvdttb.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtgvgokmmi.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtoxtlcsci.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtanlrgohq.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gteixgmbzl.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtoowbndzs.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhachohg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtlggnkdiy.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtvvaqxuzr.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtjgwnyxmv.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtgjnlpufm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtdxaopbyk.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtbualluto.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtbmmztesr.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtafevyzed.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtkytdfizp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtowjksope.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtxerxhhhu.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtbtibsxdl.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gturbyfenw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtcisyuwdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyyzbqmc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gthvvdrngf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtinomfydy.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtksfkgngi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtgomozqsg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtzogwxyfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtnysuaezv.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtgyeekadc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtudfuhmkl.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gttyhthxmu.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtntbbwaze.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtcdfsxomy.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gthonwvkit.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gticyduucl.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtmawfofvj.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtbfzqyoep.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtgbudayij.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtehpzmmwt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtedkqbsvf.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtaiitlflb.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtwcfsqczn.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtmtsovhvq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtbheeihgg.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtuwxwsrvw.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnhhnhtv.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gteclpxxqn.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtqprnyxeu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsmynvxcs.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgmapgcbd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtvlehopcp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtomunhjkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtrusyxtod.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtfenqvdyg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtfeirbivz.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtsmlzgpeu.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtftpjapbn.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtotafpbef.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtybbmjbbl.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtraxgfvsr.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtwjsjikqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gttkoxonkb.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtxysicphr.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtyxdqcqbg.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtqfmhbkfx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtykzwxgjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtuvfvoeps.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtahbrtcuz.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtjvswofjn.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtlkgvhvod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtvtirqego.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtcdgxajqt.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfynihemh.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtzesnvpla.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtihzbrgor.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtdgufikvk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtabeeszwk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvyqldao.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtwiqaiyes.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gthuvyoemx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtuxtugjid.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtsberhyhj.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtnauiioom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtzkmwhsaz.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gthvzvqrod.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtfpocalxd.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtitjituir.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtafvdzpsc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtojjjtbsk.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtomfdvxto.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtoixauzcs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrpobuzlh.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtvghsbdhc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgoioosh.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtljxdasvp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtrfbstcuw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiitopcjq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtcjglzmeo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtxlsiknbl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtvilbgkmw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtmwvbzekb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtnolossnv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gttoqomhjo.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtuzhqnjbf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gthwyczwtx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtbgomgcsi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtdgqubmrm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtlkmwxpob.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtkhdbqigw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtnyhobhcq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrjhdlkg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpelantsm.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtyddafsyp.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtizbranmv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtllhugyvk.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtqndcbgxu.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtgaidiell.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtshjrsodc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtdmnahwnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtzcwbhrmj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtzunipdcj.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtfdeircdt.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtrhyuqhhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtbggwpwrk.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtyuyyxjhr.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtlhxvpuvs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtywccpryx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtcxkfoxuj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkfjuahp.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtnpaxdbsw.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtgtbekcde.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtyjhlmnjx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtbqpkrhyf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfidztrtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtnxxfrziz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtdstriisi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtdayqzuaw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtbpacxxou.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtiuypmcwi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtrczpjjvb.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtnbptfifp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gthlutyguh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtcszsxcbu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtzugwjodh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtbotzifqa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtbmowpiuj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtqdlxykyk.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtmiakphod.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtgupwwxzf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gteubvhqpp.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtvodlffqc.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtyynztwrz.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtvekqixpn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtfcioiatt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtrzmakzjv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtudqfesrj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtkvtqfafg.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gthpngoggk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtytccqwfd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtesddzdiq.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtkjtjxgqd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gttpgmmcys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtwxoemyje.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtvqdhgbrj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtenvhnuhm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtjvfchoia.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtuefutpsr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtsjmzaiko.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtjplwxvwm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gttzsqrfyy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtlizickuk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtouwytmvh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtxxwtqsgt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtmvftqply.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtwxfbtcoj.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtnyubopgu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gttmptoprw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtieidgxib.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtvnxqvgau.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtgdpdyakc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtrnfitrzs.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtqizimoou.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyzcwnfe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtxwpzkbeo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtymlxhoml.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gteraeduhy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtffqycsyd.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtbkhyyvyd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtoksrumzh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtokbofzca.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtdfxhhmgo.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gthfndnlsa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtsntqjubd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtllqjgkhs.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtlhmmstih.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gthhpgddls.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtcenepzxg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtxiibzndy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtqzebcthy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtchdkhbic.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtuiazjthm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtzmzsvmae.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtmepoufhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtzsmutruo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gthusewjtq.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gthbccmjpq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtzyelfhiy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtukpynnrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtamyupyew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtynouevnr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtjiemwinb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtckkeijxh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtklyoprqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtdehyfugn.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtojmzzexo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfmecbpc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtjiiigzae.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtcletdfqz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtositkhla.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtlyoktffg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtikxfwmlc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtxgpodxrv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtftbupboz.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtywemaqgh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtsfljlezh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtljxrhmib.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtltqowaie.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtfbkbrxry.html


<!-- 参考信息 -->