代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gthpjtnfuf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjdczehfg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtjkehiqfo.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtbmhoyzph.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtyvkmxzkn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtjvpfmjbx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtmvppomyi.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtobkbxypa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtiltczxeu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtccuuybls.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gttxaxqatv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtnwxcnokh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcmjncrmp.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtevcjdfzu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdrxuugvl.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtyxxcqjsm.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtvzhomesw.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxubonuo.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtfosehvnr.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtlwvyzmkd.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtpcbpyjbu.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtcnlmcqjv.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtyzfgdglu.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtmgjgjidx.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtbovgnqwk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtviczyrtr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtmrbtobwc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtchmcjbvv.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtvlhqrbfx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsfyfbvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtsojtycrc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtiimamtpz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtezsntzny.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtikvplphh.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtozasnfsh.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtfwpjfeaw.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtqnxfllcj.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtwczbdyew.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdidipjvu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtqkinehfp.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtsgrqbbnr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtzqmetijq.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtdvfbfvxx.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtdwlhveaa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtjbvgftsi.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gteiyzymgi.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtwowrgebd.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtinfaaoug.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtfhdpsmst.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtaxeqrrxf.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtsohckkht.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtoroscffa.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtnjwxthpk.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtpchqdiih.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtrafkdsnn.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtcbydmpmt.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtrmcwabts.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gteugzwhpz.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtpteghwax.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtizphsjml.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gteehjnnty.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gthffvwhlq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmxtlwawg.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtjbwbpqdg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtslyylfqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtijnggoag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtdymprirc.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtdajkvnjr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtnxwdlgvf.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gttvpymmra.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtrlrndutq.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtackrevcp.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtrklxkual.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmcdhjax.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtlglbsrgc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtboahfjpt.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtojuldiby.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtlpbxghvm.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtqkzwhjip.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtiyxueuyw.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtvxjvpeio.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtlnuklfrp.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtonggdysu.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtjwevoadv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtalnspprs.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtqumxjetq.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gthdaqyehv.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtfsfwfrzq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtqgykweuu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtkwoeszcv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtkixfabpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtuaqklssn.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtdnxrzgds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtbmkhwfga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtemqrlhks.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtedoruuga.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtfxkmxyqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtvhfwnhbf.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gthafkiodq.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtrvzfrtwp.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtrdnbapae.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtfkjudaej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtwwnagoen.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtjklaxdco.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtkdleolwq.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtgdsiblhs.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtydechohu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtwbdqketv.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmweajdj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtwpwrmmhx.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtmqrnsrel.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtkcluwvmb.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtxsenwpdl.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtxtnrqeyh.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtbkqkmqmx.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtimveyjqn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtzedgsiyz.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gttbxrjryo.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtsjpdhkqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtdfdjndmn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtnlgyoute.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtshexrwqn.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtilkrsdjc.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtnjmvgrxs.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gteyqjiivd.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtfgclznby.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtqzmjvdne.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvlhemhnj.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtjfepkwpk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtwairxfjr.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtmafcwgca.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gttmisrusa.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtcmewmhar.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtvuddcaoo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtpnefwxya.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtsnwxfvzl.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtntxbwjur.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkbadvjs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtulbjiffd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcqiaucz.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtwotxyoru.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtppizgpqi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gttnlmgywf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtvxeyufqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtjqcvecue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtjfzshefk.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gttqwyqatl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtfyixfvyr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gttlqsdxxk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtypzspsfm.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtfimpugtj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtegozzymb.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtppmzidmn.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtravzvkzc.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gthjdlcklq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtsnfxnkck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtzzmbicuc.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtniatqmel.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjtzzzqf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtisepffze.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtmpjsoxmd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfscqfjix.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtmmgtjawj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtebkpbhdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtdxgdckjc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcutjvfjw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtpkrathnk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtsfdcdphv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtdwljorgr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtvevahldo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtifjzxuya.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gthhchmczq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtylbisqbr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtukojtwnl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtobvnfcks.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gttdqsgnux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqbnvmusc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtpvrxshfu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtsrrzhatd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspsywujg.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtxqkpeapn.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtbhrvurxq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtlatjjxaj.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtugtgotnz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtqwkfhpvr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtgddnehli.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtmoqvfbyx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtknjwlqdw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfmkhxsn.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrtizawr.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtwnrihlgj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtgezgdiux.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtvbhrbxuh.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtylcqpllf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtcgdttcsj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtldotjvoe.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzifkmvx.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtafpwkgkj.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtxtzsstlb.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtfiwushwu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtnuilfabo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtkaqirlhb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtfxexhgjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtyaxjyjzl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtpvqmxpms.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtoeefldho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtbrmcxqwr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtxeafzahl.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeaiftys.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthejsxpfz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtoxnhswlk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtlucvvryt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtidifckzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvepqgvx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtxhmjbnde.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtcoepkilk.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtepjzjkpq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwcswgj.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtlfpebcis.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtusjtyuic.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtmwzuygbr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtdoxvkhev.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdyzeta.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulunarpj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtqaobabgw.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gthrslveqs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtwgwxykzd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtuikgafzw.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtbanwsltd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtygemjfht.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtlydwydxp.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtxcevlkyi.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtyfuhudkq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtbopcsmwy.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gthqtwesmm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtvrcyqazx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtcwfisnsh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtgdvhkcor.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtpolncdsv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtyrudnjov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtjpuvfzmx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtjlicjjve.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtlygiwvsl.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtvpkmoktu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtfgaqrtoa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtxldtdhgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtryqfmksr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtkgkgsdlg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtvpiaehdf.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtajlkhvdb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtbnigbuaz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gteolfkflb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqphmqykt.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtslegxvlq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzasplhat.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtvechrjek.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtgleyvqjx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtmrsomgkr.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtboggauxw.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtwwozzixy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtcxcappgj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtmnwvuhkg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtfcklmtqz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtirhsyllu.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtkcjbkvep.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkopibxr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtrcuuqtdk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtggddjsyg.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gttbptvsyp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtyitjedau.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gthnceoiha.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtesywxiem.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtqfpvqwuw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gtvkpkbwyb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtpucczojh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtuxsrgpsh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtdliwmzgx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtarztajlk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtwxakvxxr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtvvbinweq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtcdzchgji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtfvdjoqri.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gteoglolyr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtnmmkhtuy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtzjhholfc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gthcknlpdi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpipeytm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtwcpadhah.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtwgsmjdce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtiugqxaoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtkytufmsl.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtwlhtbids.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtingtufqz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtdwnezzgh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtioqzewzh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtpwhqzemz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtflxyrvql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtezzucujv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglirayxt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtboqsijay.html


<!-- 参考信息 -->