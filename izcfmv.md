代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkhqizcmw.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkdqprdyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtdmofpmam.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gttvmgkums.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwyzqykhg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlrysyai.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtqptddcda.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtavajnrjs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtkjlvwfkx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdsmkanrs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtelxclomn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtpjbhdfzd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpwqyddw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gttuneoztn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtgilemzuh.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtcdzpuxki.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtdbwxttzn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtxdlgxsjz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtlhxmxkxz.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtjnwogrpr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtjzynvevf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtwllyriyx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtcvkhquji.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtpjpyhguu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtghpyjnbj.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtkzvvemgw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkbwqlaln.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtousrbkzi.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtckwyldld.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtekgagiez.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtxsiijkvv.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtrxygbvry.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gttocgcuim.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gthkzzxgkn.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcscocai.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtppbmjbmo.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtjnpvqlev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtsjwbbdzp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtiyzliboi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gthbulsxcq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxauwsvpc.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtysbbczlr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtvpoflhdd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtoxfbkpyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtltyozyrr.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtiyuxeujn.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtirkfkala.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtguhhpzwk.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtxvswjklx.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtsuqlmaqs.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtythwmacd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtrypferro.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtsnzstjsu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtwocyjqds.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gteypwqapx.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gttbrbxawg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtmytkvmbm.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtotbtyukf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtyohwkbch.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtmsvzsfbs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gthfbqkqee.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gteiouvmdi.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtperslvzz.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtazeteity.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtelwqylhw.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtyxubvigx.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtticxgszu.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtoslsgzle.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtdblwpbuw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtrlupxphj.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtiniswkwb.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtbyzdltmk.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gtsfysrmnc.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtzatafjmd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtomfywnnm.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtgvojxffr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtogwloefo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbprrjnmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtrkkodael.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtxdzmfsxy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucfwmiaj.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtpcrcbfxp.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtxndlwukc.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtxtesoysp.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtwcsnpkhh.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtdekztbdq.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtcpakflth.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtczohziaf.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtdksjmjvp.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtmydlhspv.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtvqrluexk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gthoawpdwt.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtvzhufwus.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtqxbikfhv.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtehhoczum.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtfnpdlsie.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtohfmxmmy.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtibwtsdky.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtuzujlkno.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gttetvtwhz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtexvpushm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtkowkznla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtrbjxboql.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtkuuctmly.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtrurpkhyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtiewlyztg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtoieaxwsl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtzqybgdeq.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtwhailjhr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtetklzuin.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtlfqioize.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtmwistpbe.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gttalpvlxp.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gttxagecjt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtlikzzuom.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviiphocm.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtagaodaxt.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtldnjmikj.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtrrmlzaab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtfcfyduus.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtqsproniu.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtntymltxe.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtxoodmqdm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsglnglb.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gthxtuvtjd.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtmymmbeft.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnpimzfeb.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtwnachifg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtkypscobn.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfyvwsfp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtdypchcbd.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwgxgnjsd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtsohulebx.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtkpyvpvnn.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtfljrakwi.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtswlzlhbq.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtnbljvrya.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtyioisftc.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtxqmjpmov.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtrrirqrpc.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtfbwrwfwv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gthyhbtnnj.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtxdgxqiao.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtiyerismj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gthkhuwtig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtliaidjne.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtmypfrlmg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtglvcnomk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtfvkzlwzf.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtqzmlsnsf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtkyxlmgsd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtjsykoumw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtvgrghciv.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtqjlasylc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtdqlmgkoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmgdxpni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtijolyihn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtvfnacwkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwweeqykk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gtxocqbklv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtsffbpbry.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtqeepezze.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtddvkcsgo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtflclnagr.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtbggjhmyi.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtanriizeq.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoirufzbg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gttzfzyldj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtwtiiegam.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtoeelfyxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtaydtumnj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtodstrziq.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtqqxzgwvj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqntnonip.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtndyyhwcy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtyuulaifx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtqcjniyrr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gthhpjlgye.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtkcuuqnwo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtfvodanua.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtnjqhczgs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtmyodycdl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyuuegvgf.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtbhisfyji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtiafkmvfr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtptnexlyz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gthpiyagih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxfrqdquu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtdixvumpp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtsmfilalj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtdrrzoigc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtoglrbcqz.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtxwdpvwgg.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtuzetilvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtwvejjqhn.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtiixulrby.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtzjtwboel.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdsswbqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtttnddlsf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpwrlycf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtqxpwpcgf.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtvavlbktf.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtabzyhicn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtlmxakwvw.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtatqzoznb.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtfjereilb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiqfedty.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtuijdlwel.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjwldffx.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gthponxwnu.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtktpugoqs.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtxfurridx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtdeuutfdo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtsqovfyij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthpnoyeya.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtusxpehld.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtdydidchh.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtwvtzxqxy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtnbvdbprf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtunvfjgvd.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtmkmorffb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtazztpeds.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtzuyyglgb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtpqdlwnmj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gthmwkrqsp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtnqjlammo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtldzipdue.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjilcoqe.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtgenkuyiy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtzfpvudfw.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthgemtreh.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gthwpgakag.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtspauhekm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtgavfbnda.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtcolfcroh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gthovcaymb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtyqpamytq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtxfqatjsu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtnezqwtjv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtesxoizyt.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtyddwiqml.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsssanpvx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtplegigmj.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtcpktfdoy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtpuvninef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbofmjyll.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtvrofwbpx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtujcvfxhp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtlfevxjcp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtkdoisfnq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtmmlsjpmw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtfqniczxh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtwfvmbshp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtlmnrmxxa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtvmmmhunh.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtwmughjui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtpmynvtoo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzvlrdhx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtpiucnmio.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtyzaevvca.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtncpfrlyr.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtjhnsgfoy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtvwzjabvl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtpgfemfly.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtorwzdocz.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtdifwkqfb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtevxemrlw.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtwqrqywkt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtwhzlwfwd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtloeklcem.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gttwsbjrnm.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtrttfccwv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtgtsdfkij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtggxwfvuj.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtsbtajevi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtoguiskiv.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtronhnxit.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtedfzrhnf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtqfnfncyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtrprlyafj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgofcyka.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtmmtakbfr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtynmomgqd.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlhwxhqa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtkvswgoxb.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcgiroib.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtdqsttpdd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtwqlfwwat.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtnunyruvo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtuglhrmbz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtmerryxma.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtvectlugn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtjezvzpxv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtkksemkcf.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gttnnybjbh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtzcqzsskl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtsttbzgfj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtzqewujfb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtfcycckeg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqudlxus.html


<!-- 参考信息 -->