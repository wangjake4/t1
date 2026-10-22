代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwzvimpur.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrnmzlpnt.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtuygmtfzo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtemxkpusp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtgsiheoqo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtiueefffs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlbwleccz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtofqatknr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtulfdlsgt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtswbyqylt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtvnmvepua.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtkggcsqqe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtzuhwbrqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtpxejhvqm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtchoulyfd.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtjnffngvx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gttkbqxpue.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtkhnryldg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtadjlyrvk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gthyaywslp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxszfsxzz.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtjtpkumem.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuxrnqdqi.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gttxazrstp.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtxvjkglfp.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtybwwpdaj.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfzoapoll.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtdhvqcfbb.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsrtwsgr.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtvwdkxscu.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gtwfwrdqld.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtiolrvjjb.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtvqympocy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtjlgwuong.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtizjmnkil.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtnxvlcimy.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuvcmrtl.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtvrkjodwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtckbsvncy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtpjlbhltv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtelasydio.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtlrovtujj.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtfyfwpaxc.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtfyxdyczl.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtaeqsswvw.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtkkqjwzxk.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtsqtktmhk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnhvhvjw.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtjykkzyhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbdnnrpx.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtbobnemxf.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtrblndvcb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gttrzcvkra.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtdvdcrvbs.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtlvonfsov.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtkvzqwpds.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtbjfnxqnq.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtlhkiowzo.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtiflvvxjk.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtdxvmwmij.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtedsedpcd.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtpmhnhrnk.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthpiywced.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtiidlsulf.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtrvjojzpr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtabrcwtbc.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtmodjezse.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtfwyynvzd.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtemojuaie.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtidwebfrk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqplgdqgp.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvzqgltw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gthxtvwhrf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtgkjgnmfb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gthldjbvpz.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtelvdwyxb.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrftcswzc.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtphmtkzgy.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtacryhxav.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtajwrlnjs.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtkskbltch.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtcwuxauyc.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtrlmwgsin.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtcyhtwcwk.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtltararen.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtuzqeonvq.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtuhbmcwfl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtndlgcthe.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfkkbzyx.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gttmllfpaq.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtpoyfkyjb.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gthuffzmdg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtfoysbkdi.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtvxucdabx.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzyfarank.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtzkutnkec.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtulxrcyje.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtxwjqefbv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtbewivcof.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtktgteody.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtbfjxjnek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtumtvidxl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdianraux.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvoznkido.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtucsnafyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtxtmkpkxo.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtvvzhcgma.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtvhxxcjvx.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtarampdaq.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofmhytwj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtiqscpdsy.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtkjlaicqb.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtbooohxjz.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtrfowratn.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtoedpufpj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtlzxnykwk.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtlnzpteed.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfnelfhyw.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtvasbciby.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtjtvjbnrk.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtnfvsueip.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtxphnwfda.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwuekrgiq.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gteyskfizz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtnqflibdt.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpzrgmaxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcdhrwkap.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gthoemdxgz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtakbqzbhx.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gteazijxqd.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtvnjnuvgu.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtaluggdli.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtfzoplzru.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtplztbdlf.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtxkuxqwyn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtbzwdnbdd.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtydjuakvn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtgglsboxo.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtbbpieumk.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtbczkqmvk.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtgaffevbo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtfejicmjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtydbgkkws.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtgaeplldc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtuvcmbjbt.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtipgdcxuv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gthdhbhuki.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtwbusyfya.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtsxoxodsu.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtzbuxiedg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtxqipdhfk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtvjlufunu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtytiricvh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtkcovgrek.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtqaasuqul.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtpstzfmps.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtfobyetzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gthttyxxdd.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtntgirbpj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtkpyolpfw.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtqkwpsyzw.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzxwohjnr.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtkyoxwugx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtwxoeyxpu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtxhpuoetz.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtioglhryn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtwmsndvbm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmhaxvrjv.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtoyhrzppy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvgqrimbm.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtbeklamcc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtpcgctkdg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtfzliwpcm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtbnsoujhm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gteemxgsem.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtfhvkufxf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtwdjkjavb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtjzkuoeuk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtjieubmlj.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtpmziuqeg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtfomxwwbe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtfwfqtata.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgjmgagas.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtwbapaogu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtnkbrspzk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gttkttmkao.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtrudnulvs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtpsvqugve.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvjgpkze.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gthfnvcepc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtuckbifds.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtptngnrva.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtzalwomqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gttsjbivhs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gttwsmxlas.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtmfxhmsii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtisjaidem.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtofbcahlq.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtcqcdiqeh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtckrrvedo.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtyxwizztv.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtiewtisqh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtdcbfhide.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtayutmmpw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtiduwtibt.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtoyrfzuwt.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtumykezqa.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtiagvjcdi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtculntrhv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtnfbvgcjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gttiahsxdr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtzrcugwar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtdvpixgjj.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtgjlxlukw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbikoeowg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtvpsawsrq.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtfkmqxtro.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtmfltrtsb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtavjhwcpb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gttbvbxtrr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtfbdngkww.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtqwwiqwoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gttosftxay.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtpjuucbvr.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtrdarapfj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtsayanfir.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtbufwkxvh.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtknqikdzw.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtcznmxdsp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtlmkfbzhk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtyrurtawm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gthxbmtlpz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtowpewnyt.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gttyrmkeyw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gttzriceab.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtoasnxojo.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvfkuprd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtcbcnmliy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtwbnimvys.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtxizajfcq.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtfgzavugx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtavbniszs.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtkvbuuooy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtemjgausk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtwwfagyie.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtljzlctei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtxoindmzx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtzsdtdnpt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtopnznjqp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtmradmdps.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtlwospzzd.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtpcygtgfm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtofaseuon.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtlbzgspac.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtnrwfnpjg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtebogjcgs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtfyqbifsq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtavtpwweh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtdnrngorl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtspphrlfn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwldyevbs.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtfoybtuxj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmieqiree.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtwvspsfbt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtbpodulmr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtaphraktl.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtnuzgqocx.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtimaxzqnu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtzgdkmnog.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtxccdojlc.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztesjqsu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtocfpybye.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafuqhvpi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtghqoyitg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtucdmosci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtiqhymdrh.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtszmlxdpl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtbkpqmbgv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtcsntozfe.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsifebumj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtvfsxgydt.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gthptbrwtj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtdxeoraen.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gttvawcuuc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtzagvexst.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtbdlyfxjh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gtlkulayxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtomufxvrz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtzytmpoji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtwurvsgkz.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtoojfqpxk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtdmgayrek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtsyrmqvxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtwukxmksh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtotuevcxj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtykprkyct.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtpdzrglnu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqxbakadx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtjopgiobg.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtvuzhukyw.html


<!-- 参考信息 -->