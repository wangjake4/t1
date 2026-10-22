代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnksrb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thtfmgtr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxdqbru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtykxyd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abcqzkts.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzenhsp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuclrhc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egmzzxzr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkndbu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbivaxeo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqocwjnd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iuslcbbc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gknatnch.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzkrthb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsmnslk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ditbcrjh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2iobjkttp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2skdmutub.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeljhlq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvnvonj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgevcq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ekymkfvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhjicby.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bacntdre.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2erkyvjex.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfyizpj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqiqnaq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsncqme.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wljydubm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeovstwp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzazcvmb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xegeuxng.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hislyeen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvnqia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnxqkrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkidgpqj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heatjbix.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkjdtbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpipoynm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvtgpbw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcyyejs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvnhohe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cttqtzmp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzprwaaf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwykzsf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfuyeyw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalorewz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nitlenki.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2stgppdxn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcmjftg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkrbdwj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxpjhso.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjhotbf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afgbcccm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnucpla.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtalsptb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjugixs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rslrspaz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oziomsmv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkxvxpe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2szyclwsp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kesosyym.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czokeczs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hratmxoc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ladqiyvk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2spjecuev.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdzdclg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdhnjvc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2enothaej.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sacsvkgm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qujqmuet.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfegbwr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzybacn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imzlsswo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oogcozrc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdrbwml.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wketbknz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xxckrxlb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtcfwqq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojloiyqu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfixlzy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2itkfpqes.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxrjptc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oalwrakv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ewffpiye.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmjuavf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cptcuixe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lwflnzxp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrvvwbx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toyexhxn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pinntndp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clzathps.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjcmgdc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2neokhpvs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoghpbzj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyysqqn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sasnipzq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhqdfvv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhyzxqu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsurozf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdykjhz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnxaibo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cejdoryj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummjnvxs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxqbgnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbcvgv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jykxcvfq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqgfqsx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgsawse.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lglkurgf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcpbfja.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bswnhhmm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiuwkwm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tavqwfgr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvusmu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtptaay.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwymyne.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgqgzbz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osqedopq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsubplkp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybijosuf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfspzmfs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2klpxuldk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eptsafpt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmibjis.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuvchge.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnoxtje.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwrlbvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmqvirz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnhbltm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2chbmbqmf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dktdabdd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbknqecr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwackso.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uttvhqxq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvahlba.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfhpann.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrrnflj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrxpvem.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmqrksb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvlymej.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ndikynie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuqvjar.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2igdkplhv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fajtjbxd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtxijd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uamdkwbn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rnarjthd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yedjqepw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iulytncc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oeklpady.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hduyifqu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2viufyvix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjeztcd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqbuilz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcqvtbe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhqnec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzhqsva.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqsaudd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gajvbwmk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lraqrafv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlchnvzs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hupjtooi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqjzxnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ieffoweo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyzlsum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdkrqqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odamfgcl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuccmtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmewlynd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2igkxfyxp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzvocbw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnzbybo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iprexqoz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlinvqv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2siqqjsas.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wyluieth.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjlrtcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaogjspg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hiefbvav.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2yopgtnlf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgdjth.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbozfzzx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fastrdsi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbptykym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2oscpqvrp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdgtcav.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vszxzwin.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsntooa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrowrbd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2laueqqru.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eujcxkff.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzqplwq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwnouyo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxpoijp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yseyerhl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wencttxi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shetmjxf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2blhwfouo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtzbwm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvatdvh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgwtllz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bshfmxbh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmefsiah.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qohedzfd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzoopwc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjrzmba.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lzagofvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnqtwil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qefslden.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjziyyij.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbolter.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujciytnb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vjefpijr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzljcvc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2elqzrnsa.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2okluuawk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjkbiyw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2frzxgihr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnzyadx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2grgoxupw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpnmvja.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skuguyki.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2leuircll.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fuewcplq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mglbmkov.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavoguzg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqwubop.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlsxerz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeqfnud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrsmvuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wngpngbl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlettni.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mopkqczq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhmkvuy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2chtrfgzp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvaedca.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkforrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyyixlk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxredin.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2assuhrya.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgldamh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqmuwyn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xmulimvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcdiqri.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrgqrib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzhskkq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqsbcmw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvzregk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhggyhsu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mozosaqz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lypturxz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcepblsy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2itxujboq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrzziib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zrykcahu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dycaazdx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdjzrjr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhmxlhz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2myuhwwrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoiptap.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2raufhkjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eputsapf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrubefz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxxzbwi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2psftjlnn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmcajgo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eybzjoov.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedltma.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxktqaa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfjjwxh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuyumdt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbwwqok.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkignkx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvuxevr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eohkzbuc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihcjplg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bikvdrss.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudaajg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhtglkz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyylasj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqhyzt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdozrtk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxibnodx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wburjjqu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhkvvde.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqnurvw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2frbftxjb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbukldqh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2pvucsepb.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzilwdl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwbyxwj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobapfnb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2onehqooa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2crmkfvnm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeoaeuh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkflwja.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcitidyb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcerlfmn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2txyxaaxh.html


<!-- 参考信息 -->