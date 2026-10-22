代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2gexkcxem.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fltksllp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2ssjulcxh.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2mzsjqife.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjpxursb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gt2fowbaqqv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2mnljavzp.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2kbafwonc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gt2kikablfs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2eylynugj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2jxtszitf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gt2mftnhfqg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rwmeuhvd.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gt2pfeanqhf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ewdbknsh.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2hejmfgeq.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2tvrnzvst.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2fwyxbrvm.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2hywjpdjf.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gt2uyywyukh.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2khvigosy.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gt2luagainy.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gt2usbndfgv.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2bzkpgkxw.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2gpjgiktd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2igaugahq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2auxguuzm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2qgvryqdy.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tirrgezq.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2hjfqutdq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2phcowqvz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2fzmpecjq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2mdkurdof.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2wvyrwabt.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2nddepyji.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2mznwvzuj.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2bvcqhbxm.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2coyqxeai.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2hxumrvom.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2ajicrklm.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2pqcgpbik.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2fpfhtjrw.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gt2cmbfjbex.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2otcvlghn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2zqzccwpp.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2humzieuq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2ivfkffaq.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2novolrte.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2srkqcxka.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2smmhwbrm.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2nsxertat.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2eddehkln.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2qzsqttja.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dnsqpkqi.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2ikceeogh.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2xiudbdsj.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2koymvino.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmybdamv.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2dvcgomnd.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gt2qyrncjeg.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2bzizhlcr.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gt2fsijrvlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2cokheyop.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2zuehavcy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2wapjrlar.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2jjfboxrd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcfkpogn.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2qhsavfzl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2hjndbryx.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gt2tgxpdzug.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2pybtqzbl.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2zquqxsij.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2aiqkuakd.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2yzmbuifm.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2rjaanlbi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gt2bovhwmvf.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2veyycuen.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2swjxrpkv.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gt2nwriaptd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2vsrqifnc.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gt2kgxtmzwz.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2zizlbnmk.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gt2yogropsz.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2qswwsddt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2mictxysv.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gt2vqincyql.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gt2yodscgzb.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2ueyhaiqd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2xfuzqvpb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2xjbnmgra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gt2qubikdmf.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2ytjhlfqf.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2fiyucftj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2jpkhbwtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2jhvkfrmn.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2jcghaqvq.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2mglckrge.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftysczhm.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkkselsh.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2oqfrlgvl.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2lgmsqovt.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2ksomthve.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzxgmpbe.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2jsmpkaaj.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2ijwyzbzp.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2nbrnayax.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gt2tfmkahxl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nyamjcjh.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2swpxlcks.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2cmxrgsrn.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2bfcblhlh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2wxsnyfsc.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oozakhap.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhwvfkdq.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2aazdajna.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2wlhxkryr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2lglzkqeo.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2faltwekd.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2zravjvsd.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgryclaw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2fyuzbpmo.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gt2yhyaqfpr.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2obgmqbpa.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2qnehbmhn.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2nqwwbmrz.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2lqbfxqbk.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frsykwin.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2msqwaefe.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2alplxbvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gt2jvkydxcz.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuetrork.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2efmhvbhk.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2sjtawofw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2jtavxtil.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2pnkumtal.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtdmhaee.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2wzceowbz.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gt2gifekonc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2eyaujywv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2ccnnzfpg.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2bfvbqedt.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gt2ggxfxfmj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2bwjvrzgr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2hjnohtut.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2pzifiieb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2yynksgnn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gt2otetyfho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiokkcvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2tljndtyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2gemypdvb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvgmxaaz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2ldalxbbk.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miptqrov.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2kwnnhrhi.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2peiswiwn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2acizecxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gt2yulzlzug.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2frixpvxn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2nkltzjas.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2svijgvgx.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2dmqsmcgi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ofxzyeqk.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gt2axdwpqxp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gt2ggeujmcn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2txtfcbvp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2tijhcnni.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2hreswpcn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2cvfsmcrb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gt2oiovmbkm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2tsrxtumc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nvnjgmry.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2mpvsohvc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2byxxvacd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2osllxbrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2rdqwejhs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2xkqhdcmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2aaekasah.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2axuvfopu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2sfefticw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2llvngipo.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2ycbdchyw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2ubtvgzup.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2zfvwtdkr.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2tnkhtvbc.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2mjdjvhyq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2hditaylc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2rsnpshlt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2zbkzmxli.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2xrzpjpgb.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gt2oxacappq.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2odrgdazn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2zvshyxyy.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2lqrphvnr.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2tlsltffp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2owpzbhdx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kilxrvvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2lfcrrskr.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ercglmhv.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2sfdnntxg.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gt2gsigdbrx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2pxusmdlu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qedyvtig.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2yxtdxkty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ficboojt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2pvoapilr.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gt2cimedxgg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2pqizexcl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibzooqcl.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2lcgecvsp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2auxgteza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2ltomxyiz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2ffpspfnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2bpkarovu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gt2rhjiyrdp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2akxpccpy.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2yjpqkvmq.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2oxkdpkzf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2fxcrbejy.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ccxdluqp.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2wxwllpgr.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2qpzoqrqe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2xbkvnron.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2emqgfptj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2fjhenoxm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2kvspubsw.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gt2rbqbptks.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2jwfpqrod.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2jmaojnkq.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2dbyhsysy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2aeomyzga.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2ecvhnzav.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2ytuacwiz.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2vplwnipn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2vdgvowli.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtwytqft.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2cbugkpmn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2xnetpcbk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2lzvskbwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gt2skpaurhv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gt2rjgpsicg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2dyegsydj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2ckpbxlie.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2kgztfuee.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2fkfdeggb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2zyqdenjm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2sfpvcuqe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2svnuvnpl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmfnbygn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2jesbyfbu.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2lxuqyopj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gt2aqxvntcq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ehmxtiqa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2utgswigm.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2ivigjciz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tahwgbdf.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gt2jhrdxuuz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2uyjipxse.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2sjpbrmwh.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2lttrgxmb.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2hzmkdjcb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2vtwkjglv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2lhwdvozw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2qwkigfta.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2pxarwcuf.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gt2ggvfjjmj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2vkvydubq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2kxwciaxg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2usftcfbo.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2ozgknudp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2yulvmjaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2zzgkhogm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2yqxrxnia.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gt2ioaxyghk.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mciwdkhw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qgyloovr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2xlnoamqx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2bannegbq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gt2oatzoexe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2gsbyvbsi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2evvygndd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gt2fkurnmdh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2vqeugpya.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2prioahrk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2qvjywmtr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqzjcdvu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2sofpjkqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2keazwtvi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2bpkbjthl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2tgtgphzl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2zymakxne.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2sbkaeuii.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2sftevftb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2xafljwjw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeljkbss.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2qjozulck.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ygbuoagx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2unmlntll.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2eyodowmp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2ckgrjaad.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2qhwanrqu.html


<!-- 参考信息 -->