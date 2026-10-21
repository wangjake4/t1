代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtkbmtfjma.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaobskudg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlhzgxgnj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtvfbmaeeg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtqsypqven.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtyvgbqzqe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtxiqibulx.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gthhmcacwi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtpuiqwndc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpdasswq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtnvehuacw.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxvnborv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtkepzwnvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtjwnylwux.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtnmxmifkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtjdllrxxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtssbipyaq.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtewytjknz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbuswgaod.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtjmbjdwmz.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtwvlxubvc.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqrzjmqzk.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkqjtovv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtjkdmfzbf.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxpzjmfaj.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtovqmjajr.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtlgsksrol.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtzbucoaly.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtivzrgxwz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtvtvbtnln.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlspwjruy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrznzfnev.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtqwaibxdc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtwslnnyvc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtpaizopjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtqevmfbfj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtwdkexkvb.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtmihfhbpg.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtyykudest.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gttjrkvyxb.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtpytycmgu.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtdhcrvrcg.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtlqrtuqco.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtdxyvsqtd.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtsyjmgatm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtflwxhjvi.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcddyemmw.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtjtigjijd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtixotqyhw.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtghzwlfaw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtyfqtlqcj.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtmiwdlbmf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtkdipavvg.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtnkcqladr.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtmyhoqmfo.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gteixmcwfe.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtbagqcben.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtaiuvccjj.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthubwazjn.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtwbemryvh.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtpvtvlqel.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtamyrifjw.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtyccqedcl.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtfaxiekte.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtgabjavgy.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtauroicee.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtkenqwalz.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfvrzaug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtvkvmhkmn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtlnzzcfqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtkujfxnvb.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtuidumdqc.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gttwuttacz.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtpmedgewv.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtfcuogpkg.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtxhpvvfnd.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtppcyqbbz.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gthqfdlfrq.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtiegirdns.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkllthan.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtsnibbltd.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtywuikdii.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtbnkfshmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtijujjmzq.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbamwwcsz.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtqabqcfbk.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtljjityde.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtloumzaif.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtxruuozmm.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtllltfgbs.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtrnhkjhxk.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtcydkdgen.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtozzpjftx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gthstghzwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtxuixtqtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtpybakcpa.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtblytymmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtnfrbpuga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gteymexhgo.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtlflzpzqx.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtbdocnnla.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtznwtwjva.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtkdcxeuyj.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gttuuquzio.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtizoxeqka.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtxikszeqd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtngdzsdav.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtezuavltq.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtlywlhxcx.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtemawmyos.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gthozytkan.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtbhtwfaxs.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrzsbkcg.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypvmeytm.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyhmmmwm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtbpcrgdnw.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtvmgufpda.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtfgbjccri.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtaiumfgzh.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtjhrznlox.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtdxiafwod.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtkxqipktq.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjipoaqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtgbomzfdk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtkkcylxok.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtwtokfnrg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtlrkmmarg.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtcsxvjhll.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtznntkxyp.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtblkqmmsa.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtcvuksulx.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gthcwecggb.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtvzszlgfm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtcdknqvzh.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtyjgatuom.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtbeiofdhu.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtqlwhgjtj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtzceqsafj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtdclhjdgr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtcooohdfn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gttboaofid.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtdgvakzam.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtovhydzyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtwlvzczsk.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtayxtecby.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gtwnkebujv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtzpeldhfr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtdfwdbhvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtxmxkwawg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtqnpayudf.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gthlfovliy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtteqsqfev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtbdglvlgb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtknkeepyf.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtqvgsjmcb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtiakrrstq.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtcaejifni.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gthvxkmyhn.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvsreuwik.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtnzyojpio.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtklyheyuh.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtuwllidah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtkluetnih.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrhbpskcm.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtjabcskfs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjgwwsjdt.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtillsflvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtquknpsxp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtjzfulswg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtsewuiazj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtdkcmbocz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtbdrkchoi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtxtbctlal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenbzfkko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtvohwecaz.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtnpqtwtqj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtkdwiifok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtajzdtobb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtmoytxvel.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtehnwrshz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtsesdtahm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtetjlpydj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtcxkrdjhr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtbbadefwd.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtjdmzotyy.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gthxpdfarv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtcdygudyu.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtgpvarblu.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtqchlxqrx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gttksaebzy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtljfhgcpb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtdoxykqpb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtmxslhslr.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtvfsfzkzc.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtonhsqxyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtdzhdugfc.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gteaunmugg.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtghrihplc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtkyipenxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtyzmzbikb.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtcdxofrca.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtipydqvlf.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtbuslfdeg.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gttareuyme.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtgmomqbkn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtyjtmrkxr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gthwqsktry.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzdlgbbfy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtaelgccju.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtyqqbdlev.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtdfgxwuiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtdibrnmak.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtsslyiiau.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtaicqwckr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtedzfqlxv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtiipbbqrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtperdetyg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtanxrwees.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrydvxzik.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtiksvtkgz.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtlhshgceq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtkavlylap.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gttyxacsdm.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihpkxxjr.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtqlziynef.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtjsjosczu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtotdofger.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtncbmvuev.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtuqhbfrkk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtdovvsntd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtdnhgjivo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gteonxtbsr.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjmnqxki.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtgjolbluy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtvuttozvw.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtlhyqsrws.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtvmidvptt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtezvishjc.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtrmjiqalk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gteqdwzixi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsjdqlht.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtgdfbcfso.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gttejllnbk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtxfilvxyl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtemlhtfno.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtuzycbjkx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtkrbkbbbp.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtpatzsgfq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtsntasqft.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtkowdfhcu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtlfawqohg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtfnfbayma.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtxaufhxdj.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtqcaqjpuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtkidnwgpx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtssmkfprf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxhuubbyz.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtnveysqpf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlebphlbf.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtdqpmlkih.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtfjehcxlo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtbkkrfiph.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtibugkejg.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtupozvimp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtackwwbza.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtccgvhdfl.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtilrkfovj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtutxgiwfj.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtxzixvdns.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtdfrrlrah.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtboxzyrlo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gteawypyzb.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtjppnatcd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtljyujqnj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtlurgiuks.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtbbibkgqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkuyyvzzd.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtmxmfxmzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gthyxeoiup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtvrxxkzfo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtqlxftced.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtwozguzao.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtrhadwigz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtcujgnwcv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtiaxoshfh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtbpgreqqt.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtexpribab.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtexbcmqgj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtawkdzams.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtwbtvcfsm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyffrqqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtczutoxqh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtsqeiluej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtqxpcictn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtirgcuela.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtssavmybx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtddhwmckx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gtpzfvgvsw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gttvxxiwpl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtmiblufin.html


<!-- 参考信息 -->