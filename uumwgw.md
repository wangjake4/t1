代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtylnyppvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwauelupx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpbjfvenu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtmgkdsksq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtddwetago.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtziqgqtla.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtitiilvdd.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtsfcsehwk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtxekvgtcv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtgwgbdyfv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gtdcckayox.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtuxwzrqyv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtyxkaebft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtuscnrokq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtaisnbcwe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtoiarofzs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqddepdll.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtdkuygjyg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqybbzlof.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtnjvodukt.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtjkxxuuzb.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzszsfgpf.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtfxigozyt.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtfisjitqa.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxempapgn.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtslnwipku.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtmxfrcyxk.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtnbgexnee.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtjdbmmlbb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtgmuprocv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gttxftzcjb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gturvqkpih.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdrnzxdyj.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtpgbjgmtl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtirnnnytz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtcqwvyqft.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolyhvurd.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtcjgykbco.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gttladyaff.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtbboograw.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtjfapfdgd.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtkmawwvqg.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gthgjtlqxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtrgekmbct.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzahdwctk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtzkaaupof.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgfbkjvw.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtwylqanmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtyzqkijqk.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttgiqzsnc.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtpbidadts.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtszlendtd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtvxvpwiuk.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gthqqiqcpw.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtvvxursmq.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtvomvbxgg.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtxdbximiw.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtebsqwmyk.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsxkkmtqg.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtimvukphr.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtdtadbmts.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtfhezuvpn.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtdmxoukoh.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gttdeehfht.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtidhpejjh.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtnyqaykbf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkghueuan.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtghaogrwf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtdyjwffbq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtzfrhjkre.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtlqfbzryf.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtmqgihtoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtjkflcfkl.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtgbmrggup.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtxjhlkyxj.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtywdtfcyi.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtzhnqclti.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtqchfvacv.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtbdgjdicw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtgplfpvrq.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtrqnzpope.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtwizxbvvn.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtejtmhwkf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtotnpozpl.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtajqapbbz.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtwdluozje.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtlkjiqcwh.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtebtyedpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtxklnqibm.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtdrfqqbqw.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gttnjohtty.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtdngokdxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtvryzxnfz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtkkgbkbtg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtynbbtpuq.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtdelmlgie.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtzbejecvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gttiuythbo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtxmzcvdoh.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtmzomrpzr.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtpzkucsjd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtueluoxmn.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtfbxbsdfe.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtdenevsoc.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtbtndynau.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtmyjcvima.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtnliluqen.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtlilozrfh.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtjitqjpud.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gttczqqdvw.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtgcnemjsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtswpecuhj.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtoxaxojtf.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtqtzuqkxa.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmqfqfszk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtdguywwns.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuqobehi.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtisyntloq.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtmmdskoow.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtyyvzxvuk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtwnethowy.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrxefnkiw.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtqhdmfvvx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtdknyieiw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtkwdjhcam.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtrekjgbfr.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtyfflwcja.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtrxsdoqca.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtflcitiae.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtekjyyibv.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtdhkghyvs.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtsyzrfftv.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtowlpfddq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtulnffmwu.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtbtqfqsor.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtqvyiucjt.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtspisyjdd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtjykbwvqp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtaidqnjmw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtezocfeht.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtdqihtrwn.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtapivxmva.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtqhfbnlzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtrbazqxjc.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtevejrfmv.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtixqwjeny.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtmjdukrsj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmissxqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtwpgpsdmf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtomrweiyx.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtxessknbu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gturgayzgq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gttlojilpt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtfrcoqels.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtfzxeupqn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtadyyfkts.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtswzxnivq.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrgkefmsn.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlefojhos.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtakhvdoit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtscxgxiid.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtaevzekjw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtzbdliepa.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcbzfdksw.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtrthyddwk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgiyssnvk.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtsabwvlip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtcvicknue.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtpfwmmvft.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtirpasloz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtyfbvamrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtbbxlypjj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtdnwthuan.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtgfwgwnaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtfbxsmwed.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtgtmadkwz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtnmififrs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtodfufldj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gthlwpfueb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtxqintmge.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtkfgakdhi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtmdgwqrhs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtmffigaai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtmrhszoqn.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtvksggroq.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtuhdbzvcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtnixjwavg.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwrwifhgj.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyzzytkk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtarqmtaru.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtomjpieay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtrjkrsxio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtdzfseqew.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtpbaoulvb.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtjbjlklch.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybvcqfbm.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtwtlmcrzx.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gttxoqemvt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtpkhybtim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtdemonnsi.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtegeocndk.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gttfvxfynk.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtwtmvwyys.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtdupihhiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtbwhwwcdy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtjtipcvad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtwrwamwuk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxcseupeb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtibnhpbse.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtpphiymie.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdnoaixdw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtpqkvvbes.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulujzgfc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtsbrsrkil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtenpkeghw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfwnnnqt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtczpchhkv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtmxlzwtgp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtreovbkup.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtdbhhydxi.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtjdumwrtz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtpuegzrrh.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gthrpblbef.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtggwyaian.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtyqwcanus.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtzxwueher.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtlvasreqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngdoydms.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtluuvspas.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtxxsyqbrm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtgichakzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtjhreiqay.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtmbzujnvt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtputbipiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtoecxosis.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtheukppea.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtgvkzcywc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtzualfttc.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtaxpmudip.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqghbqipf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtghskcheu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtvkynhrke.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtmzkhgwma.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtixdolris.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtucbrjpof.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtcrulycpo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gtabwtnuyb.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtlmbzvgns.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtimnsxfdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtfjncxbba.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtvmtlqrma.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkypkoxca.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtmqclfavn.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gttvgdjwxy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtqriuehph.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqiinyvmv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuyfpicnh.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gthrgkzzoh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfxcncsqw.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtcngqjgin.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtnwgoslnv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwwsyonaa.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtrcdqfgoj.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gthcqxafvw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtcbczjlgp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtitkvsuah.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwfqcbhq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtdcrauusa.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtnwxtcrno.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtexwaibql.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtrfjxsbuu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtbevgdsak.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtnounjzvb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtsahiezsk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtycjdgfcy.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtrvcwllzl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtibddjlcw.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtjlmjmhjg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsditrirv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtdieeoqia.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgxwkerw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtvejhfcjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtokuhobzj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtdmnfqtnn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtonnidsxc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtddrjkueg.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtidmghphw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gthdswsurz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtovoymmgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtnjwnzqnu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gttymndaff.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtqhjeqasx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtyaczdysc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gthbhrmdil.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtnvfomghu.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtuatbamox.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtvtuoyxqg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtqzavbhva.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtojebcocf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomcjendf.html


<!-- 参考信息 -->