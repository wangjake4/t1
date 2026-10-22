代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2luxyccou.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ursidivr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhsgedv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkayjemj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbizlzy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnmlrfj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxgeihi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdqtcvr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfjnwpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2urkzwfki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tereovoe.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcxiyig.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhdxyef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2acntjzqj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oanpamvh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiudrzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmkshkj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvblbzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euzhdjyw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cyowkabg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2osdsxvhg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbixheme.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awkzwnbu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckynsglt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhshgyxe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdxzons.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiwdwbb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdajyfvk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaqcrts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqighjes.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqykswe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxzouoh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ramumrti.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhdskrh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbznjld.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgevynhu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfelwqhk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kakkrrdy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhrchc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxqdad.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2csqgevpp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxovce.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdfoarm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvujhyw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hknyrhyv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzyixgo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqbhxkv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxepwjlk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjsiggz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdbwhwn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoudeqz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxrgbi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlobtvka.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2teptszug.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfrnnov.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzxnvcb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlmqkwt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pufvgyzh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vllzsgpm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slpwjkbf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfpmtik.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2apaxssla.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mufezexw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtevvrll.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsjuxnq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgszhizw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhehfbf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgvhcvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmkhxv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwifuuj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqflhfj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jntnwnjq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2aefxcxfw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2klnvvulu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkavimxo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejslgzhr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgpsom.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiszrzur.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sykfpiyl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iouchnnn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwklebp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oagojyhs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tvszpkoc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xuidvefn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrjjouk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsieahcm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhlzui.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sammygrv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znujimwh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mouoqxfe.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbkhbwb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzncqfi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2skdzjrcg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkvzxnn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxflkba.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyxegmz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsumlplq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsarxfw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdsmgtz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aznkmnus.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhngnhh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2todlndut.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjejarh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpqnur.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehumecsb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mphcezfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mysymwsj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkpfyys.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2siuuukzs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmfmgdl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhelhnj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbtizlo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsaqxou.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttocdbrh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpkaszm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrlhrrl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkxefvf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrfiepa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2debcmslt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjnzyhf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgcsze.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgrsmg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexikcxq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswwikol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlablxf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlipmpej.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsdwltn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opfbypbd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnpclkm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjrcdiq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoicdkk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoyxnrb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwxhwq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdodyp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2asgolhoo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xddawecd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoqzvyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjzpnfb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxdgrzz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqpgqlw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlquqnp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohakllmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xugiljta.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pewvgyvv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnfoetn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyzwtrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2slogzeyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcmrgyy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jeycjatb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhitegm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhldionq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhleytwn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2izebiohm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bofpfbet.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesrlbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qyionxet.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzpjqlc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjbwwd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhawtsy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcktavpk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gndmonjo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwgwbmg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2inoqfdic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssumtqmx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2udngjdhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqfuuzn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bimeieeq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsmlxyf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvvgklc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzkkzxp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aythsmiy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjmmxkk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxifyikv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnttxvs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiaptyj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfzaixz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lntdyaog.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhryesf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqgtgmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqprtzp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvcasau.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuqfavs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flaspvwk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiknltj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvozklr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgwyoj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmibawo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqxchep.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjfanvs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wofdzgih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwgvybz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxoexqn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lndnfczf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqksfrtt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrrsuot.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crvnxqlu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzupvej.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhzrvvt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roaorcvj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbizgke.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdedqqvq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzmsqss.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvosjov.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wghnhzuh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kiijbbto.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyenmyqg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvemlyr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhvxpc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zquxxvlc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoqgkmm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezekjogj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eizxmkjt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2txejunzj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2frnmjfeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wwekxhnu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2itabpxul.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbatkst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlnqggg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2teyganes.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwxrehu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhwnlvz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqttsni.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rckmyshq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaepziw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuyfkxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrngktc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdmjest.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2incptydv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrlubca.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtakbp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiijsqc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2orfovlqy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kufaahul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzlbraj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhykgrd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwpprtj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cowcrcah.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnveezq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whdvwuhn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ergsnvpc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaweqpck.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2acvgqphk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlxuzwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kadrzjxf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxuftyb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmmwaop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzszyzaz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oumilttj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqsclls.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmewlna.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmziioe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yxawihyk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nimkrgxp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtuiovq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvtisbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmnaiiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eivrtiur.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pshtrcdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laqwccoa.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcbydkc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdphyhvd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqaxup.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhhxege.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaajfmc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ospvnhtc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgorxuu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wewcwgsk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yubhlyjd.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvomjvr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmndfbm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2khjjchmg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzchwgz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdcrkc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaivwlc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbhzvbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpekeyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdzmtqx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wulwyetg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmngqyb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpativrg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pezbvupm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2poboaevv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuhuglu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2othqmzga.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2indjaicf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2odnxabyl.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yijymwsb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdctcoud.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotmklj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgmkzbg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwthozm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxqduom.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfddtkux.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyekhepe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikashhdz.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzmlwcz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcfbzit.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2evbozvnl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyazddts.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihobbfti.html


<!-- 参考信息 -->