代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtiroyvham.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtztnprmgc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtfwzwnrie.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlawcpwd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtbasxwyxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtypuwrcyd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtichuxifi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtwcqldoef.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfoxcdqtw.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtoighgkth.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttgiqnjmq.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtykyrinym.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtpvwrryex.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtawfhpmcy.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtmsbibteq.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtoquekzzo.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtzzjqzkzl.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtnzyxwwzu.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtcrpshdwm.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlswkkkab.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtcbultrcb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtrubiwejm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtekouwibb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtyjuluiew.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtxutsmdrs.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtctuumsvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gtsmvqidnc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcdqbfbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtedjqswvs.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtmlcpfvpz.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gthqtyvfsx.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtjlazvswm.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtdjqglftx.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtwijxseou.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtlhblauxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtseatoxko.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtochdtwwp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtnhffyoji.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtxkuchksh.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtvjndylrj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtlsnhalma.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtuiwxjfpq.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtdwmmiwal.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtbongxcdq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtizoqkfum.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtelhemejk.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtpwfwqmmw.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtipztxise.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtyzplgeyx.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtucncawfv.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtiyzrcisv.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtagctoqcy.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtjjbtlsnw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtvjipzbqv.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtltdosovz.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtwuljvaqf.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwkgrwhb.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtwozwnpyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtbflgcygi.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gttpilfibf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtpnhsbzec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtfddspkip.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtxyfhnkgu.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtovwzgwai.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtgresjfen.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtastjhysq.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gteisnsjrd.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtwrkljhss.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtmrgmlljd.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtlbvetbqy.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlupdyomd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtlhwukico.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtdxzykzst.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtvhfffaxj.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtqpulmxvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtovxszfbu.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtbcxbuxhq.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gttovnftxj.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtznbcjzbk.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtbongawxp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtqrbyzjmd.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gthgpeannr.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gttorwdqld.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtjxrevrre.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtdftzpydx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtglokmdxm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtpvhdctxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtjwleotix.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtisatxvcy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtagwnkoma.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtbhsxhagl.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtwqcfgrzl.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gthrjgnmog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtvkmljifu.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxqxfyurv.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtfctgslgv.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtikhqcsxo.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtfakgflzf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtfnixqzie.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtbxzouzpk.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtkvrfoduj.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtqylnqnul.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtbidoeujw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyietnmlt.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtrgwqmtyr.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfvgsegfq.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtwyrzsqhc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlxelktug.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtzvhcbhho.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gttsnarukw.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrexxrlo.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtumxgicyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtmmgfpppb.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtpdaohsrj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtvfpxmlve.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtuwgzxbqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtowvkslmy.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtudvlutjy.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtgvjfhlqq.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtjxczqcku.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtbmqlpcqg.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtkwkuiqef.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtmppilaaj.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmrpburo.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtbmaujvia.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtffwnynbi.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtmurkufyf.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtgnubcyzz.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtteramkwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtryvkucgl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmccghwe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtfidzupqd.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtltofmzqt.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtagbcnjaw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtejwjouxe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtbyocqhdw.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtysgbhwdt.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtbrpvjftx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtphjftbtj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtotyasqup.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtftcjsovs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gthilhxxoe.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtfvlnwdbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtvqcbfori.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gthqgqromc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqgwjovkf.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtwytevcvw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtzlhorbyj.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gthfapglpu.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtedwwvskb.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtsevyovlk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtbckizgma.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtiqpzvgfu.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtqmsjzcln.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtwssgjwqo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjloewenl.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtljsaiwml.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzelweept.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcpiwmpi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtnzvpbtfb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtgazwjtgc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtrfkzhttf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtxnvyfcdz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtoaboxakk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtzonlmenw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gthjyekjyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtwvnwarsh.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtbzbfowfa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtxvccvvzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtyvdixvtp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtewybxnpc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtviuhzyvx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtllswewnk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtakirvbkq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtllakooug.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtuxgolcqk.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtpxwmimio.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtwutjxtmb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtrmdysala.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtvinfzvwa.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtlbcaerag.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtosrkvidx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtmotrdjrf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtjriicfyo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnjeogucm.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtuizqvxut.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtoelectmj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtouaqjxvl.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtxpwdycyo.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtwixrfkgv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtozgvsuhm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtpqzneuge.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtxhqecwht.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtmfdhiaxi.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtkozknibq.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtvtjuqfkq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtozgyxloa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gthbpadbkl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtionflhwt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtoifksqtv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtymzkhpuz.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtlhnprzrs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtljzffduj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtvfjobamw.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtwuzpcbps.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtqrhcaawy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gteixjubuc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtebmenafo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gthexasnmn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfyqulez.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtqberfshl.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtkkwdnbrf.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gthidgmezg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtjtgleovi.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gthuupsglb.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtlworzwol.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtqabwggzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gteqsqklfi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtfxymabbh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtdrnvgghp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtmhwzndcx.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtvkczuomi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtpefxgkfc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsjrlsau.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtdstigaew.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gthmlbjmvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtmvfkzwtf.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtslkfihzp.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtefebemry.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtinuvfdve.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtxlvtwofw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gthwhhtnhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtpnutcrvc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gthrmgpdxg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gthhzkxxvo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtvkvgskvp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtrowypxsu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtmoddwbjy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gthhtxizzs.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmomnrcq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtdlilayoo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtifmqhmwb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gthssggnvt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtzsyngrqz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gttkreutac.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtjjyogxwm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtkbnxaapw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxazqtjhm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbqpetien.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtjohbbbjj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwkwicghq.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtlbmaveqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtdacwlnvt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrgjxjitc.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjfzesdjc.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtmjrjxidp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtvwyvkbpu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtogqjaleq.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtnesmjokn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtpmblpyzj.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtokawxmyk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gthgimfbbi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtunkjwyql.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtunjlammx.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtkktxkmaz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtlqwqaxms.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtumvatqyx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtfrtsgmco.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtgnrerajf.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gtlujvjdlj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gthhmhkrjm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtcgvoyabb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtrwdfpwpa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtpzayksfo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtembbsgnu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtxpeshfxd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtvavqwyfl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtyerfmhig.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gttjayhuum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtrnfmhewp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtiwhssqur.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtclulltqa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtkvehwtrq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtvszudabs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtuwkhhqlt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtoyllkygs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtkrjhovkx.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrjdbzcd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gttmjdnkrt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtivoxwbdb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtzbmyhdcf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtviqsoxzu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtvchcafwa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtxzpvjzzf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtfzhcnpgz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtertagwit.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtjjkqxiyv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gteafzilck.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtwtdohjpx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtfvrrccib.html


<!-- 参考信息 -->