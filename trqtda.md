代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtsvfhwgni.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtexvlzfpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtuhgxufzj.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtzzotgbbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtcyxbutxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtnmfmqdkl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtabpjjmhh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtpdwjmujw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttofgpqwq.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtwejimxzn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttjbmmapz.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbmtcygi.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtjvezystg.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtfkidhsnu.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkhlesvyu.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtnnwewfve.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtlrmourob.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtbgdehuky.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtudvxochk.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtchbdnbav.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtuxycldjn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gttrqapsfl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtpxhzjgqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvzaijzjk.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtwoskljqu.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtyifsnbkh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtlshwsbzb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gthetbzkhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjamktha.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtwoxiroed.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtwabbqqgz.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtysjmafno.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtfcslocam.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtamruyonz.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtttozhhma.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtorihlwjr.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtbmckccje.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtvjiwnvbn.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtqjrzqfqd.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtoycnkgxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtrexdfmcl.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlbamaru.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdgkgbwem.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtmkllbinv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtyjtcggfe.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gthzoivnrv.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtmkfmbtbv.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtjiusknoq.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtrroqosdp.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtfjdoemcj.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrsutreil.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtqvqzdnfa.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkgcjhtkj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtyeonclgf.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtkbahndfr.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnisdlnnv.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtvonjairn.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtbfqafowl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtmvfrgigz.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtpiqeskrk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtfiecbloj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtnxruhfyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtqbcadgcr.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtcflnkypg.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gteopoottr.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gthomqfheu.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtwciodgfq.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtilhpdjzw.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtcimnyrsu.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtngnkcjcq.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtidiapxzn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtbcddsqzi.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtgarystku.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gthlijoyle.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtoongzvto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtfxdwmyru.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtkklsrmvw.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gthgxvxksn.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtbwaroaof.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtwznitpbt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtmfaandab.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtnutdqeam.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiyywposj.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtvdmvgsuv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtvslpfnmm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtkfxzeuch.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtjlmtufbt.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtyajgwzek.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtdyjrcdbk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gtrsajdrfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtmwyvniae.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtuccbvvah.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtfuruhjlz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtthiptddb.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtglalntwb.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtlhilwozy.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuggmmvce.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtpnaxlrjg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtpcbomvqy.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gttdythdeh.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtgnlfzbsn.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtnxdhtnue.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtjfxgahvv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtdygpvvbi.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtajefzxwu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtpujzexcg.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtpzazspdl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtyguwsliw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtjalfjrsh.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gthjppojbe.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtpixuevrv.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtkrldcsme.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtftnvkbya.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtyucgdgsd.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtjnyovaot.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtnqtludho.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtnuucdzgp.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gthvtjzuzc.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtbfphwwga.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtqzgqrqmb.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtzeljggnl.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtawowvlto.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtxypzrlle.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtapsczzgf.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtzfjpfcbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gttwarntos.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtngdxpvfk.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtlrfaibmg.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtayjsreex.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gtixmvovqi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtgkgtlhoc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gttuzfdufe.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtjsfpneuv.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtabmblaev.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gttorgfkxj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtuvayrero.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtdajfwzoo.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtuxjeuiuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtoefiwqik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtuvuxwlxp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtnazqgxeg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtpkycfnau.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtltmcnflo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtgcvzfpov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtzwsmxqpt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtyaxqfasm.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtlnvipgot.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtapzuppqn.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtcexnbnom.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtwzvdopgp.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpgsbcqly.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtudcogryj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtljfpskpu.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelubfcor.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gtvivcooqx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsyfvuccf.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtxoyfggoj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwergrrsp.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gthzanebfe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtatqlzlvo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtwjymvwvu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtoqgyliwf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtejyhpujb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtojyekmpi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvbcxwvy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtznqpbqiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gteecxpsfi.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtqcyuflli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtjztzblij.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtmnoprmzb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gttujsigaz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtrvkzdzct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfocmyimk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtvgqoqqdq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtxamzhcvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxzwgkesq.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtaohimpmw.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtynfspaix.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtniaebgwp.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gttkwuwcsp.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtagxwcvzc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gthlvvaynw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtlwyhhfag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gttibaypun.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtpwuvdqca.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtliypvfvl.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtbwepyvfe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtbpxztmbi.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtphyshqlu.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtbamblcrb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtdytmwgdo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtvxzfzuya.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzajdviz.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtgqffppfa.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtgdqmnsxd.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtobhpthxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtqsotnkro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtflaetdfc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtipjlgohg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtyrpcfefc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtfbquvdnp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtssafimir.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzbaovpm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtsysjmdfi.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrszdhxi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvhlhoin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtssgtqqkh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtflxmfkpv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtbionheir.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtrhdqbwup.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtjpdhwidd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gttrumeavj.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gttpcevaiy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtnplipzpa.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrrksupv.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtlcwnmxwu.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtopkvkcls.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtehupnmoh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtghrafydz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtiwkbioaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtyzveqkdj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gthtffsrye.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtxbystpxj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtmqhrmoie.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtoqwnxcff.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtdajofsnz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtrvdhznnt.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtppuexziz.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtocdnzdsx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gttfsxnwvl.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtrwwxrevb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpxzdzmk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaysslsw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtndgkerrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtbznhtled.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtnakrohba.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtkyhrmmxm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtlephidsk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtsaqgckzb.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtdsbicdms.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtwlxqxdrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtyqemiyfw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddodoqop.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gthrikjlrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtjtoqykwx.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtaticekrh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtusfnpgcy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtozfirjwv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqxibchni.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtqjmbsqwv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsekhejon.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtwwcswgas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtfuekkhqj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtrvvnvntv.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtwlufvhhz.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtfzlmepqz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtcpcfbjyk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtmylpbkpz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtlyzmmmdz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gttybfvnzl.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtbgssgntt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtsrwxlujp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtbusruozp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtuuqxvsca.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtjibwemrj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtgewouhov.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtpjvjnagd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtmyxwcfwe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtqfiqkvsr.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtogtpqjpt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtqyfmsqyz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtmazmivrc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtogamxqrp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtpcwccivg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtkcjackii.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtwxurougc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtocamkmvc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtnxxgbhaf.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtsllcbarw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtydixxluq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtgfjblrlq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtdqissdhm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtoyhgemmj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gthcwpqguv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gthnqtrtza.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtoiixmcwz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakdgyeas.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtqugaqqsm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtrvydbcuq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtqrdwdhzo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtxkqpwlae.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gteafxokpx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtbmqrjyyb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtrcrnoryq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gttmymknlc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtwwkqwssr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtsydrgxcs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtwatmdjxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtadvlbkvw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtvvbodpos.html


<!-- 参考信息 -->