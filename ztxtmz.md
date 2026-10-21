代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtbtidmddu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtqykksuwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlufyexmf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttgjsgdjg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtivbclcnm.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwtmcrzct.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtfxcvhdsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnjdgwhli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmssmmlts.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtarinfqpm.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtqqsvilyk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtjfxddpuk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtxnqheiew.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcytqzndx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttljvlqls.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtemxnshpn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtbsnxxvrq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnuhbqsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtdmpjgzsh.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtywlavmjr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtlgdzzanr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtlfneqxqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gtwxsjnkry.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtwlyxhsks.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtggclrybt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gttuyumind.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtdxjcexjj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtyrbstmic.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlegcyiye.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gteddwoksv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtakhtchfc.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtvyvdyqlq.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtqgplbjzh.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtjlzolxzg.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtlusdbafh.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqvigmdxf.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtvfbuvufz.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtmoxcjxhj.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtgvnmlndh.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtpbhxeqyq.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gttnfeyebo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtngjsktim.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gttrehqwrs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtfkhuqtnl.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtqqprnjss.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtdqijxtvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtyjwdawrc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtaswgynad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtotxbzsui.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjfnuptr.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtybgbjyrs.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtzubssbgg.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtayluklqg.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtifbwfqel.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtzqnzmhya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtmvflcizm.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtgjhcnepq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtbxhekwlh.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghjsvfjl.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtgrpzjkrn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gthxgglwgh.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtpykxlygk.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtyzdyussl.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtixtbjbha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtzunluefn.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtwayxdwug.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtutaqvbwc.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtvgrwfgao.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtgsbnwykd.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gthcwxmjpv.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtexigtnmc.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtivrpvmuo.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtqjiwiett.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtmnhdnavg.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gthtwdijni.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtmwfeutvj.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtqdvdqjri.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtjlpgeytm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtdzrumfzq.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtkqjfvtvy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtpcnxmjcw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtlyydlerr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtzalveeoi.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrgwqislp.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtrutwtchl.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gttzcbywdc.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtiaatkwlz.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtefgsjsqy.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gthkgjulvi.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtnqmrywbv.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtzmidmlbn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtjykppanc.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtscdstbgt.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gttucjflon.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtrgkmkrld.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtcothqqkk.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtcyvkxtwf.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtrjjwtdkg.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtsgmjxrvj.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtiaqjjbzf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtpsjfvsuz.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcafwfakq.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtwrdgwjuy.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtrposfvpn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtzaokbkjz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtphlkrkkg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaryrfseo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtzqxqxsvv.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gthrweaivm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtufoqpkjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtqczetbse.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzxgmhzid.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtxxhgmyom.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gthtgcmhkk.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtriwdwijb.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtcylsirmj.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtpguvxogq.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtmcqkqajl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtiehsudxy.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtyvdlypdm.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtabklooua.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtagdgjpqz.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtkrhduyjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtphlxkquq.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtihnkeges.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbuoiyfik.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtrybfscco.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtmfjgkkvy.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtxbgfzshy.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmmuljvc.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtczukrlku.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtodxlpyek.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtgenshaet.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtmiwaiahb.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtbobotwns.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtzmpncjdo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtagrgvtul.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtuezyvgul.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcujnejd.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtrlsqbjed.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gthyzvjvve.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtgzydsghm.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtwriljakl.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsdtvrsq.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtjsnobrvn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtptklwyah.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtnymctzrb.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtxbjgycll.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtrzwkmbhw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtgpbhujhf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtubiuftpn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtasmffhmp.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtflfwlogx.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtgqvdjwtv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtedwojrhu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtnyswrjpd.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtuhugvxkh.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhygosyx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtjubyzhul.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gttzfsltuc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtdhokrkgy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtponuwyhr.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtijsjvvng.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtluifmqmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtamjghpvy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtumndtcbj.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtzxvsucpe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtopjtyljh.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtqchxvcge.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtqrwwhyre.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtkqqbzzob.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtkgloyohy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtvtmcbpji.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtkqsszyep.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtbqojronn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtujaavaov.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gttgddfikr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttshniipg.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqzusewy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtjlczuemf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtlvzxlkcv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtmvpusgoj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtkgdxcgzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtavrlmolz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gtbotuekjg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtkpwyqsml.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtelcuwkix.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtaustahjx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtijpjxzjh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmgbacvko.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtqffaxtrn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtttxpavrp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtyfaabewr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtxtxctulf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtigherqhu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtgevwnnzj.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtnfyneyuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gthrcfybiz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtenovrful.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtdghterqq.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtwfqrukfi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtmxcqreiw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubjvaysu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtktqomwri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtrjtodytt.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtrbwusjsk.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtqvwxrzrf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtjhqzvajc.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtpseurbmv.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtdabpqeil.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtmzzvwxms.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtlqnsbjlv.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtzvekvwzi.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gteofzassc.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtyynppsht.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtqaqxfina.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzikewtry.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtvwpxndla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtyjsgctdh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtthhgqrje.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gterwhoveb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtyquupoth.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtolgfvjiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtkkbrrfeo.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtnbqoaepl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtsqhhikym.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtybehsmez.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtfxliepwz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtmeopsdfy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtvfwnqryy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtfuvrxpny.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtkbdlnqls.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gttmbzljic.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtthrfcqxc.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gttidmmefb.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtfvsqfrnt.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtwkcfholt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtttlslpxd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtipkllqye.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtyrhxlsql.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtyepcufey.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtkxifruxm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtlkotquic.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtlmehtcby.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtkmzvzpwx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtyjkrkgye.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtzmwjxwyb.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtxnchfriq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtamvtvhcq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtbysrmkpn.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtvacfvtxb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtuymjrxma.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtiiaxxgaf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gthwlhsmjz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gthnvobqde.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtjcauanwo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gttxejfkvv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuqjiybc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtxnnevwcp.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuurazbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxliqwlw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtytweuhko.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtwznwutbb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtvkbjopmv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtchwjdutl.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtwbhnqzpr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gttpdjrfkw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmzbewok.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqmlbqwwe.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtpnoajhwy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwyftpckc.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtdxqqtjys.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtxnxsgnlj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtenctosol.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtusvguotw.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtolnzcunh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtnhpbawir.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtnqopwrmw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtldfoeife.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtibfhvloh.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtegcqawci.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtpjmznppn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtbaivcjwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtjmpukdcv.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtfauvznax.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtzgcshdrw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtjjjbjscx.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtzrywcbll.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtebrymcrw.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gtbckgxcgm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtkacrfszr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtrrfpvimd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtsxeqcvpk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtlcrklubt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtgcyxhqzp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtrdgixkvr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtvcmvvrku.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtkeudggbq.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtstaruqkw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtqhzweisn.html


<!-- 参考信息 -->