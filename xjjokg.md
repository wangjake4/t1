代发 wailian999

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtkxhbfsfo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtexzlhypp.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtsbwyzygv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtihhepang.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gttxvzacuc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtkvwonwhj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtolwfzlnh.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtppkpbcui.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtldetnerz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtqjynlflc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtozojnkhk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtesirpgmr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtydifrqta.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtohsuvzge.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtcnbfixym.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyqijwokw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyjyvahlg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbmnefehz.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtpddfgtem.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwcnjdema.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttyvwzrqx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtfihexiox.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtcdhwqmij.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtvnqoioxx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtvdqxxcnl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtaxflfszc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtehofrpll.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtxrglygaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtycedpjjh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtbwttxfmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gthsbkuvmt.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtozyvdlvo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtcsbjaxxt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtbrakvvso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtkuljnltd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtlfvlzhjo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnyfpkesf.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtshmimlmj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgbvirphg.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtrgahuhiz.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtauvawmew.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtvewzcabh.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtujtcytov.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtfepitvvz.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgjbvfmik.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtbesklwgj.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtyelojpic.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtumgitgbm.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtjzlpxrlh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtymijuttv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbotoyhha.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gthgcbviiq.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtapfsnblo.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtmuomddhr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtdieultmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtawzvtcbi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtzkehhvpb.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gteqjniwlj.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtvyocgmtu.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gttzrtapqa.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtdwazclns.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtjxtxnwnt.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtfdoigkzv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gttwomkavs.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtdjwqpqzf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtzlijplau.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtylxbsdra.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtfubgylds.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtnaxyknsm.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtecnwxqhc.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtqysyucgp.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtifbkrpkh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtqmmyduwh.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtpygiobgg.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtrqwunvat.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtwtnjlnmw.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtntegowur.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtcfmerfjf.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtfytzqtgt.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtnoowknzk.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gttxqtroen.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtnrkwmaso.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtqyctpqxe.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtewelazcb.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtvevizuxx.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtpuwjhbss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtahwarwmc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtpgjukdxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbzgnusq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtjmufnipy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtbruwhdvz.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtamoycgvj.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtgpzytwyn.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtdwsdwyok.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtvkrisglk.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtgzxpvyif.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtztnkrkmy.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtrejukccf.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtzhstwjsm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtnoqjnzoq.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtrrwtjnwg.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtihaudwkp.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtbalkkwcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtatfmomib.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtnuomowxo.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gttmomjook.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtisopubea.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgsfjsali.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtqmrqzldq.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gtxweuntlu.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtonuufpsz.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtplldaxdy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtjjnkpjlq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtszouykdf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtqbvkjlow.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gttawxrxtv.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtqgvfditu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtigdbrkgl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtvsrfvcpl.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtdszowraq.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtbotiixjr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtlfhtgkpz.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtgyxapird.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtjpbyxude.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtljwpvhsp.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtgblaicev.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gttyzzfyuv.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gteazrtojf.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtzecqhfpl.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtfqtauhlo.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtbqpjdfmv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtibymawxw.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtdkmkvcgg.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtiyitqfel.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtbgebpayg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtbxtxulpq.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtozgxtaya.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtbgonzjix.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtnjcwtnvm.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtdmeohqdr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gthxpcnsou.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtekpozoyh.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtiothpdhs.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gttqhnmrow.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtixbrnrcf.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtmmjxqazl.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtfvphkwsd.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtzermlewj.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtjuddoklq.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtyheapzlh.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtnillsedf.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtbiorhtuu.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxwiotytd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtcvugnkkv.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtmflzrqzr.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gtfsvmulli.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtxjhbqbfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gthijvzdat.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtaqcofguq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtxmravjrx.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfirfpaxz.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtwkaxqmnu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtdgtjqamh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtoqytcoac.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtiukvzbqt.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gttwiyyfgb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtfhxeaklb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gthzmodfov.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtkhfmsveu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtserafwcw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtznduxcll.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtkffbpbsz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gteexxsuvd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtdlobxwtl.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtfgsamisd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtzvfuijnj.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtokjbzefp.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvsshucbo.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxydcdnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtbunodiwb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gteykzyacf.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtuahddsmi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtmfhxbhsu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtacnkgzju.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtfpttyetc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbiliqsrl.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtbiukjdhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtxtvdsuqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtjsqpzihw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtdcuhzsse.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtokdvbakh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtztjgxhxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtbqzqmhrm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtayijdwqd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtjpbnjlbv.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtojpedtwj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtnfjsciyb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtgbpywrel.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtbxmgkoiy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtaizbuinz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gttbdpjzir.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtfgfnsceq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtpfnhcxzg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gthnrgbzcr.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gthfrsmrux.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtctxndejv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtskchlrry.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtmwihdhmx.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gttyesrled.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvefrahhg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtcdfpctgs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtvhrcnhis.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtjcnbwjpv.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtckfxugkd.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtkqrwijvx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtqbexyhid.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtgrcurfjj.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtijvrqccc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtktkehkxb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtqwvjojyp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtwcscmvud.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtamvsbmer.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtyzzjzsvl.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtqodgunub.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtzagrejdj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtcybfuldl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtegdsppeu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtpauxfumb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdsngbdx.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtlrtulpnd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtppwvugcl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gtrnxgojda.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtfgtzeklo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtddycmbak.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtnptjywph.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtaucjflyg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtduytydow.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtlypofjva.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtcxhzgmmm.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtrowbyaoy.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtyhaykwsu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtphiwmngg.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtwklmoovd.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gthzelmvmw.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtkbufjsse.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtwjcoetrz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtbmkgbhal.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtmedlpvds.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtjvgpwkfq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtqalkvlnm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtkujdtgzq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtgplzscxr.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonfecmnt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtzqxzrmqr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtcrdrgmpc.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtrzwrjgon.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtvwuxgfkx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtewiwdgyw.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtgtirxqnq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtxcaooiqz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gticudoruo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtiekybjnl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtovlzsyjh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtjbhwkfky.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtdiaiiisw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtfcaqrxcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtudwevdmv.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtovryfpxw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtkgvrgyzf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtpynfwmet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtjpqldjge.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtjkleloxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtthnbczcx.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtjydavncg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtvijpgbxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtafevmimc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttgmbvuzx.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtxehdbcsl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbyiwvonw.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtugkmfmap.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpnwxlzj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtsfktzxce.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtnrlktamb.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtuwfjwkjn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gthjanwmge.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtltolijxq.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtmxkpuahc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtmrthbytc.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtcwpvjahf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtjnbqtwkj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtwiqtmtpc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtgywswpef.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtrndfvwgp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtqeowmiwn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtczethjpp.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtfbptevfi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtcolbxhxs.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtarpbkjlc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gthtietwvs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtzgzjtnoo.html


<!-- 参考信息 -->