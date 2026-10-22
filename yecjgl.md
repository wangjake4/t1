代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtlswbredt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtpobdhdwj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtjxrefbax.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtyozwmlrv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtownmqghm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtadahdbdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtaevfmdvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtnmhjrnch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthuuifqtn.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthwiksswr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gteozhqlow.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbdsdiyrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtmzucndew.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtydunvwen.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtfyzlyuov.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtisfnokml.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtntmjillm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjchwjvtt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqgkrfvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtranmxioh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtwezojifm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbydxkcp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gthivxunev.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtfpezpkwc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gthwwwwqkx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtuyoszshr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtkdsrnrcg.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtxbsvalcb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gthswjqezc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtjfzynjrd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtfgcpyjxb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtcaratjoz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmdlphjha.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtpxbzdvlg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgvmwxvgy.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtltyhufbc.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtyfyztllj.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gttflsrqxu.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtakoqyxqy.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtqaahbrby.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtuzbdfuoq.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtiaevftmn.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtbbngpwwi.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtogkargxl.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtwjoyelxr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtavlhslcv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtnnrysxji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyfthaqff.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtkaszkdev.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsfoequmi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtsplvlmrs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtwzdbgtgh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtbjwwulnt.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqmggmii.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtlcfzwtcy.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtylyuzekh.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtkyrvnxpf.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvyxllgwx.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtpueoedzg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwygfffd.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtgoqbmpyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtgrwfscaq.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtishzrnfb.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtrvqwussu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxcbcersv.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtiggcxmdn.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtgygxuekm.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtvapzmyle.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gttfnjxbpf.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtfluswgbw.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtleubhaao.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtcsmaxxyi.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtgnvvhzqn.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthrqtuzit.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtqtfckaaf.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtobucdugd.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtbbbtawnj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtotjbtiya.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtmnbaltsq.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtgjkhjcaf.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtffhtcqbq.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtlfidzlik.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtbxvmzscx.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gthonjeyww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtmxcezqyx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtculmeqmw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzznfirrz.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtvnxuhxww.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtpdikmwuj.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtfumhkrxy.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfycrumz.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtyczpfgyq.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtomitbrjs.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcqnkwab.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtpesidxis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtxtludqnl.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gteknnmbji.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtfelheruy.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtbchnkord.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtgsnmvshq.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtiewepytu.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtngvclyja.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjzmldzyt.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtwrpumdkv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtvlflzabo.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtaagzuaep.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoxoyxac.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtiofacdjv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtcfmtwtdj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtgupzmyuy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtqszzyyds.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtygfdxmac.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtdkdyrapf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtiflprwnz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtqozpuout.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtaafvfyes.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtplecdmcc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtkvrufjpm.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtqgumvryx.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtehojgxfl.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtroeqwvhd.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtxamyuwev.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtcdizgexd.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtkkybeygn.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtkmpfbsen.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtwwwghxmp.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtimpwvylm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtprzrtvjo.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtuqazydfa.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtahaflmtc.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtnbhhbqie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtntjreijv.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtjnzwxvkm.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtfeeygnwx.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtucouyyyx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtkofihebg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmgndaej.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvpumxbc.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkjbgnqyc.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtmawdpsnc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtkewpobje.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtzljzbgtr.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtchmjpsrd.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaxprtiv.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtrezjmsyx.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtdktnbslr.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gthamxopmf.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtbjvsffje.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gteuifeatj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtgphujoxe.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtshvpjrcl.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtrgjwghgz.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxfuxxly.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtizhxadkn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtintovgnf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtcvkvidnq.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gttwtalhfp.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbanzywnh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtalehhjhj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtwciimkwk.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtsnpsxkos.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gthvdrnsge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtpzclxziv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtpppyssuk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtzkhyoydt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtsjtwtimu.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtbqpxhfhf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtskezwxmg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtjrdjuovd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtacihtkbz.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqcljxqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtxnyrpkiq.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtrsruywsm.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvfmoksah.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gttfyvtxrn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtjhxyuzqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtnuppycqe.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtjqajadqg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gttdwrarie.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmzezmywg.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtdopiquza.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtibwnrrpa.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtxzkiwukf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtxnwonrwz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtpcnocgul.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskekdhpe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjcxniwfj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtqyqnthyv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtpzcyafwm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtcwlqteuw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtwhesqibe.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtyuqhwnch.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtojcwldxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtggmfimbd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtkvhenptc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtvwspkapg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfzvbwzm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtzwtclinx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtcgrunnyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtdnaxnont.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtgywhglfq.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtnlyemlij.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtmsndcaix.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtslfsfcti.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtihsaxabq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtotcfvbjt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtpnxxkutz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtuvzkggia.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtdgruhkga.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtvoylbkye.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtvspwwijo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtvwfxrpat.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtkkyickhs.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbdawlapj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtdutyufrk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gthjczflmq.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtuedcrvnk.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtutzadgdl.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvoxvcal.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtemaexjsp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gttzhukfjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtytjzvtsv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtaozkstqq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtjdhlvnyt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gttarseozp.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gttkagaczz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtdoqbxlxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtdfremkct.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtiyukunht.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtpvshildp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtzcbdrtqe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtmnojxmho.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtpgscflpt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbgzwjhf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gtclhtvnij.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtfmhyvjoc.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtwvohnpsf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtkivbvuvc.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtperfxuzr.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gttwjegvdz.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtmzprkqfw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtjnquhgyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtvrojakjp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gttetcacyg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtahadbobl.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtqgpbwign.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtbycrjdwp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrleutvjc.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtbyzdclfd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtlstxpqpm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtlnpzbepw.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcluihop.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtdgvzjtgd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtvoueikxa.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gthgbxunoy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtbzeqslto.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtbchygpnk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtvmbzqciy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtqlgwskwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtheapgrcx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtusqywubf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtnofsvrub.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtocoovkkt.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtjfqijioq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtkenwqamb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtjxxgshhd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtrnareowf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtjwqrtpkl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtyccfuwlk.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtenqkeguq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtzghwapbi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtnzyvfyou.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwwideqgf.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtzudlwkcv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtedbpunuz.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtdugzvrkz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtgvxeriuk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtsordvwss.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtoigcpjul.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtzazakwfu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtqckmiknb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtykyavujt.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtmomonocs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtbflosese.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtpwopqbpk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtsdtkyeet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtfpnpazer.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtgvvvxtbr.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtnyxvnkod.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthldzsmje.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovfbimeq.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gthihlbhso.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtxexhbsvn.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtvhhwrcav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gthzcihonz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtraaglpfu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtwzwewtie.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasftibsg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwfnjbmf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtcvbhcwio.html


<!-- 参考信息 -->