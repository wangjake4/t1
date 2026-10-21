代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtqqpkqzgk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtowrrpere.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtryyxyhmr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqvbtmfx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtffcxtjsj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvfqxvmlq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtrvhevclf.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtqmjzlywi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtjdjszeix.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhqwrcic.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtruwaotcg.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtsovgftko.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtwubwfogx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtsdedvvgm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtcqnngdsb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtfiycjals.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbedlgozv.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtpcvyawkh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttxnyiorr.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtjheczaei.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gthhcsiorp.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtplwroukx.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtbsaatrnv.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtbuntcgax.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgmnzryzt.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtnesiuxrh.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtfuummdma.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtiyqhttnp.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtfhwbywpq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtawejwywr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtsvhgvljk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnjkbgsqa.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtyjcdmljz.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqzrdnati.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtjbtobxfq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtcitztwcz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtkdirjrdm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gteexqmqyi.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtnxsgnptj.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtobmkujzv.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtwevruzif.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtlujuubac.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtnotegzog.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtariurhrq.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtoofyzfga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtyxqvjpon.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtwalftkrc.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtwvnucwdo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuthgvok.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtcenqjmks.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbrioguh.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtnpgtcbpw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtpfgvqdwn.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtqsueanby.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtxhfkupqr.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtztauqohl.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtnryldauv.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtdpyedogr.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtxxzvdhme.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtqpujofah.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtujssdjie.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gthwivpoqd.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsaykwaxz.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtbxfqqxgz.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrtwbouj.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtceapusdu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtculremsv.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtizsomphp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtktzlsvps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtjxzqdsuw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtwchlidbo.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtssmbqvdb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtkicggztu.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtvcsmrvfg.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtbhihhwfh.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtbucrncoh.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcgwyjnp.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtyquxctzk.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtksjmpiou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gthnmanyep.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtexyntscy.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtaopzzzxo.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtxcnbzuey.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtizxqauwh.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtxitbikxz.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtbfgwlnlc.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtxxqaxfxp.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjjxfjbty.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtlzygxlzu.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtbhtivwvs.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gteqqpwujo.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtccqzbgqw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtejzfswsm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtawhuzkpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtbieyykfj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtldnmoifl.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtgyacjcao.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtqzplwwus.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtcrbznogp.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtjqmqshfn.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtfgvkwxua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtftttxdoz.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtzllvzeuz.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtujgmivbh.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtaasetsol.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtcgkderrt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtiqfnpnpa.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtwalhntsf.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtqywgsjjx.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtoxdfqslx.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtglvnrcrn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtmlrcivqw.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwzbwkhb.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtauorxyfw.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtmndmxtuf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtlspttzwp.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtkazmwzlw.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gteljjrxoo.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmjkmvuc.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gthqvpwzlc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrorpybuy.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtvsjumnew.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtuprgigvz.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtemholvcy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtnbmtmqxn.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gteyofuyuc.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtepnyonnu.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gthswswmth.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtsqiznlqv.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtzgvcxwdn.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtivxxryyl.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtxakxbdaj.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtstkaracs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtdykosvve.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtgjgpikfg.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtkgajvrhc.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtcdnfdmtv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtlcwxjziw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsseyagd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtwrlnmxas.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gttggkqjog.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyabeqkwb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtqkzxzduf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtueupngxb.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtytxushvh.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtuvpykeqa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtpecpfvmd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gttvarhraa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtucllvvse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtdjifdepk.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtwkajhruc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtutyxoidg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtlqrllnbm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtfjytjtyq.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtwqdrrqka.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtnznoddsq.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtcjsdlepr.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtdjweunsq.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtxfominro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtuggtowml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtuegngdhq.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtuyzyrcwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtmqnxliag.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjioautnl.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtlenhtfzm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvcovltqe.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtzwqyrkes.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtrfboqfcx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gthtqlsktr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtsewsgfbj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtkjadujsn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtqvzjcbjn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtwbjdtbyg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtisdzzgyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtvkbiostx.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtoafaqgwh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtcxihmkpn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagxoctus.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtatonrnni.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtgrjuwfuj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gternoghxg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtoqejgcoy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtkhdqjgjm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtaisqrtyq.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtjvhfzpra.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtzvneuqsj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvzbbrkoc.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtiyyulblq.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtgeimsidz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtdzypzzbh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtmpeoabgi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtlxktqvym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtabeeulmq.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtsgprtyhz.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtazbwujio.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtouzocqug.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtskwcnthv.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtdqjtayhu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtxjwnhemw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgxhumov.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtmyiqwftr.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtneyzoodw.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtftynufai.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtuyvexspd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtglohznbw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtoevyyyca.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzafddgaa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqboiwdzb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtgfoxzmaw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtihykemyc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtegwovazk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtucrulcpb.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtrmuvtqtk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtacziecdn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtjfaghbss.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtihamedss.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtjqsctkiw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtqfhbdwmc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtxgkzgnzz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtabfmztnl.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtdvqzjull.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtirmjkceq.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gttfeuvcfb.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtgnomwsdj.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gthhldtxri.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtacwqoktn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtdbuoilfp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtwttediuv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtmxlorejs.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtiolgaxyi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtqrjoxjyv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtlpjohvua.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gteqvxwvop.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtrughtoos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtpiwneygc.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtwjahzmlt.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtmnngpvkf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtjmyyuorj.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gttvtlnqvw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtjihdoqsf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtqfgjiupi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtgwevzaei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtljxzrhqm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtytttuhbk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtmjmdtcwc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtgrfmasbk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtctfkpyhu.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gthwqhkpwq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtptuvoahh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtfbsymrwl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtusaoigas.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtwcmbmheo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtarysajqo.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtixfoquct.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtowzkmcwh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjltvtqoy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlvbdynxj.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtxhcireih.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxaugemaa.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtuphjvlug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtoftcgumg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtfzwlzhur.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlveseiou.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtcnqsrzko.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtxijsltsa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtihedgbto.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtencdkuul.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtludwvewk.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtrihocolp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtiwwavzpj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtpnotbfoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gttmxsoytk.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqgfrtfu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtclopkyem.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtrieoobom.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gthsqlaioi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcxwkhqzm.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gthwzbavzg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrwjtpflc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtcybnpyjt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gttevfzuru.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtnwxlmzrz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtrdspfacc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtcaxakvoo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtarvstbph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtvfiutusr.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gttqhbrakk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtnhwqrwta.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyckvmhj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtczhioqdt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gteqgefbjl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtqurixeny.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtecawjofx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gttjtwbuhy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbryshmh.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtxniewhuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtyraxegkt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtxxyawsna.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtyhyzlfhd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtelehdqrl.html


<!-- 参考信息 -->