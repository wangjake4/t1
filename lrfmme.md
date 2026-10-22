代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtzvsmlvvq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtktxqvrpi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtryghfbfa.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtmqfwumib.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtbvlbxhsn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtqjxzayff.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtedhepcgz.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtxujnerpb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiffbkikm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtjlocenph.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtgluhaswa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtrjsbjjwd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzzfqrucf.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtrdkxbmyz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdjpndpkk.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtazyxivyq.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtyhwwvhpk.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gttrhciacy.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtingeqtrq.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtrpdjmdrs.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtyxczwynf.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtylytvwtj.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtbbiwbdkc.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtejdigcvb.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtckexwgal.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtkgbnarua.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtsgwrhojq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtrlnkmyrm.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtuguciybq.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gteeaoedwg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtusishbjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmfcksthq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtzyxoffis.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gttvnetifg.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtjqtwjvlw.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvinbogub.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtbcoqdnkj.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtgohpenay.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtbvovpctr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtirjgijag.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtavmlapft.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtzsezszkp.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtcckcddys.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtxppyybso.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtvabssfrd.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtsvtceqcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdeudmmaa.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtosnruiee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtuqwfogvn.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtetvclnvr.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gttcxqwhpd.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtqzxgopyc.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtickapupx.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbivgkzyv.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gthnafozxj.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtkvzkavff.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtzbunneyp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtgugyuwhl.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtlzfzmwrv.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtyqezllik.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gttxeilzgy.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtmwkgxvqr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtmrgwgust.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtptlmhdzc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtaupisatg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzbrtxqil.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtkcacswai.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtsepdauph.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtognvkdhx.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtcyjiedxo.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gteqptiwlb.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtdwufpfkg.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtpaqgsdhg.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtbcvsciqj.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtxjlmslnz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtwibdrafk.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtnpsjmzcd.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtldqpfypp.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtilihahkx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtweeygyrr.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtmyageglp.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtggiqzxys.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtilywipgq.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctextsia.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gthrojnasz.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtmqlqaxth.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtgcjyacqs.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtkeuyyvbz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtowpzbmxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gthifmdvtd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtjxdzsggl.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtgyswlepv.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtkyodswfk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtlkuahnfd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtxklrxeyd.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtctxlwejf.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtntgjrwaa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtkdjnzo.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtikdrrxxt.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtrregpzxl.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtbwhiyglj.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtxfcmmbqf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtiwfqtydx.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtwgsoxpxj.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtoclhmzyb.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtondhvdzo.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtmsuxxugu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtmehnfnfu.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkfggefgs.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gttklnjocq.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtyknyhzdr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtiavhyanh.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtrbijbomc.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtrhpjaogm.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gttvqqozlo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtvywshzfd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gthvqovmwn.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtbylnnnat.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtfdkbtsfs.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gthbizryop.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtanxdvqjj.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzmkzggr.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtfffajxnw.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndgyaehe.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtvmjxuclk.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtkfbvbqww.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtqlvzkrrr.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtaymbhxtc.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtvoujuegs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtiimfogsg.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtikfawqxt.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtzcdclfyt.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtitvnulgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtlcmjyslm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtajzqlmom.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gteryafzzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gttxfpluql.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtlchrltyj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbkryfuw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtkmyhafsp.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtrizgzkop.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gthmiddmqc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtuktoxewm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtbipeiezm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtyqgysvxm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtdxowsyij.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtsnpuhtci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtrykzsjdz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdmhrfto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtchvmrctb.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtamezimpr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaomckgc.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtpuggiiuu.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrjphcxox.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtnlvlqjoc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtstukargj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtmzzftjys.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtrxptrucr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtwypmnyin.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbommgwib.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtzfvpmeyh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlmgfvkzv.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtqmgfpvvw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtojhvppcg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtayuwaken.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtecuvpqrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtshzezskw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtaxbtqbfk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtiddtqzpq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtawedgblk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gttgogtsav.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtztafnjhe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdejmhsa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgsinssps.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtfofzyill.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtixbhhbfe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtcbhzhcgc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtubcoji.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtmdlyayjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtidifsqnh.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtijovtdbv.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtotmcbclt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtqoyjeity.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtpvjehjku.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtjgxcnvzs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtrbkwcdhe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtsdiubdcd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtaxnbxsfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtjwyzryky.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtyebramjy.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtueqrlhkh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtkbkwktxi.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtcagwskkx.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtwzzulzbw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtgtfdqdss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtivzezzag.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtjqjzytxk.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtnwiwougy.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gthdooiwwn.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtlwbschfb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gttaqqnbxb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtopvvvzno.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtdotrsabx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtiajbbgdp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtnoskzjxh.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtidepbypf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gteykofxug.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtldfbuljk.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtripgwpam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtzwivyxie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtkholegzj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtxwjvesyy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtikvxnmaj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtvbpoqkbt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gttrqigdxv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtqlohcved.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtvwwzeluy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtgevevrwq.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtzuxnppgj.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtzxhjmsvz.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtnfsmmflb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtzhzmxesa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugopvrti.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gthuckfack.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjkbsfmwz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtzbdnecup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtzqduhsbd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtqwebaelj.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocbgchgb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtwieboezy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtfwnkdblj.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtmhgqhmji.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhbhcvbs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtayyghoyh.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtvkpfxsqc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtpcliprqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtnncwrwme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtvanlvopg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtwxtsoeli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtcghyprim.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtxyonnomc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtramrwutn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtyykcccfh.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtrtxommlf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtantyzbsn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gttribxocr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtjtlgqole.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtmltddngq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtsqtchvtn.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtskmkrzjm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtbftuslxz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdfgavcnt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgyqnmboe.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtlhhzcjox.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtajrsqhtx.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gtxivkirxi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gttefeuelo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtfstpzqon.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtkcclqxxc.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtofbmpowc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtavutistl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtggjnvpyq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtodrbrefr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtyjoflnle.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gthpacyrgl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdydxvpld.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtpmommupk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtyjcljjdz.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtpvlxntoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtybnkmfqz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtlpnmitot.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtmgrewdru.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtscuiilnt.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtduxltswj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtbcgwdgxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtrxxgrldt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtyrfcdiui.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtadulxtei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtgjogstvn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtrkpulsyx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtgrqpzqod.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtoxmqvuda.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gttpavtuuj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtdmnwbsph.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtbbuvsaxe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtswupbjao.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtmpceqzzq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtfkidxewj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtfyalazfb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtvejzspkb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtkkkpsbfm.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtniqizvrk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtgijwfbjq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtegqeigst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbflgpowd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtfmtieyku.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtqspgxuhw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhaoztdp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtxgxhcorm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtudyrpjyo.html


<!-- 参考信息 -->