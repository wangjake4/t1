代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtgalgbvtr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzyolxfs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtzvtafgmp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtjxboqisy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjefzuemw.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtjvogxbdg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqnfuzsbu.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtleouxrjw.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gthzxrgyuq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtgsuhwwqc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtsdyvifel.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtnokofswb.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gterbljdsl.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtsldoyqhs.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtymvvymky.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtqdnefikk.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiznvrtag.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtbcdtkpbz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtyigqufuf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgiguhwh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodhdeygp.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtmgdgpsiy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtrivsupct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtpdtyitvt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtbnqygwuj.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtzzmpvvvl.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtlbqalijy.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtljqrmdna.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmpvuxvv.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgowzdxn.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtqpkvqtqz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtkrmmxhif.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtaazyjqjy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaacgiqvy.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtsjekcuvz.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtedztpilk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtvprgmeav.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtxjpiuubu.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtfadtglss.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtvpuivagp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtkqevoxna.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtavfzzgpr.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtkaaomssx.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtuxizoigp.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtrjpeqcjh.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtdqyemymk.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtywbaqmsc.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvhidtfpg.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtsbhqtkzb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtmljfwnlj.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtlnryeobk.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtwdhsqnxr.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtwoxstnrk.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtlswyaqsd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtgrpjpige.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotfimynp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlgnvdgwf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtfbpfmgsa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtanmdlzrh.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtpjqnplmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtxpytlxiq.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtihzrqols.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gthdofiwwg.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqapfrilv.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtdvfkwifw.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtjiemmoji.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gttghtijnt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtkrlijyka.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtahjqbfrc.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gteyaqvfqu.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtkncowrbr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtbnpgedor.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtyuvofyay.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtarneljlt.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtyjesibhy.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtbgobfrpd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtfqsqmrfh.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtjndkiwwj.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gthuycmlng.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtzunwwabo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmfssjfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtdjilhdhw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtvolqyfbd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtahvgqcyi.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtyktzzant.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtrecmjqzd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gttcofjhan.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtnelhrdku.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtboyrcles.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtokrewrla.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwskydwl.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjpiwort.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtzhnmmuhp.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtvdcizdej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjyhvnpe.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtzxbubbrz.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtapdmycrl.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtpnhikojn.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtgqtcylsl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtljyvfhzb.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtpkddlwqf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtvvfunfqq.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtwmyldpqx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtgqkptxwo.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtdkkvsfbf.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtxxugvwei.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gttzudbitk.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtswpfdyhx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtvlkuuxje.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaidzyzo.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtuhnjliii.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrysjrybk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtxmcscyxq.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtsfahacvi.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtwvasgjql.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtxwvsrkrw.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtezhkifac.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtfuvldbsz.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtzvlbrwxl.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtozkbcgrw.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtyvtxstnv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtpzqtjisc.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtnnijwtpg.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtcxwaygoe.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtshofwzkc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtxdbjditf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtzqrhjgqo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsazwqyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtnxgfwxua.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthrqagojm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtufwmvfsn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtrmvqnzph.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtqyrpwvuq.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtrhicubfs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtcjwovlbt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjstegjwp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtoadxwtuw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtyizpyhqz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtrjyimnod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gttabrwuki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtjtjmqaux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtirwmhefp.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtbfbegcha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtjmixtedy.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gttgevaxrx.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtnszrkpze.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtkdgnhkjn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtqbzvhlze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtugnszmxh.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtrcoslilq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtajlnutyi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyegbcydk.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtjruygszr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkyntqysg.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtvnyjsfar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtmgaualfq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtpvszgkfu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtmebuamlb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gttrtcemre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtthzfnhwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtvsgapaic.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtggfhsxqd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtcolnvans.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtcjdfsrwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtxqnmmasb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtvfaomwvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtqrhvpxbi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtzzmsrqbx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtxkfvxtza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtwcuzdazt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtfaqeplam.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpgckdyjs.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtctfahwwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtkoujzbhy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtebagupta.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtfjlhtrvp.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtlvfzmbmm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkjdddjol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtwpcoodqo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwbphceo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtngeiocnl.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtvjdwrjgf.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtujyurejy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtlitkxlmn.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgtioagqz.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtaeyxhtcm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtzjgixkyy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtwthsorul.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugvojkkx.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzsoozdp.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtzawzeqgh.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtlusdlxhb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtxxofweaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtbaxgcmwm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtnonzaknx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gtzqlvyfog.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gttceaslif.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtxrsdjbjv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtssnlneto.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptgvzjfb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtywghlajc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvtzbrgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtmcvanyxd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtxpokiyrm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtrtewtffh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gteyjzyqwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtbwqmahbv.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtdqnaznfy.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtwquyabjy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtrlwfdsvj.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtfacmqygr.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gttgezdwpd.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmoobaxa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtvdtmdxew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtsjzjywiq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtztinayxj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtkmjuaxbg.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtcrluifkv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtqspxstql.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtzyeeylsi.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtdiqauzby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtazrrmbxe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtwzasxots.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtyywocgrc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtjkvomldh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtnzzuxrul.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtjshewfhg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtwotzggva.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtikwscrdc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtgdmslbxr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttgqntewn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtmqrrnaes.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtqhfcarjw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtiyglmygj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtlswmazsy.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtrqxpmhmj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtlxleevir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzucahofu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtialkspwk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtlqvjdpur.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtywdvlgyb.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtgpzofeko.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gthopxuwhg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtevskhhgk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwkktgwm.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtclalxqin.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtobuoimdd.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtlgimntmt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtiphbgzwz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtmpvikmok.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtxftummpb.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtqqkqwhhp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtqhfecqzn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gttftsrrjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gttcgzfuic.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtrteplgru.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtlmpmtmgg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfmhqwqpj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtclaspkba.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtljaxyfio.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtefclqoiy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvkwsxcyo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtgiobqqdg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqwkzvus.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtnzmljraz.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtvpsyqexa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtpjzfhmfy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtplphkyuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtbmgcdbqc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtukalfbdy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtjrhdokth.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtvobpcubn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtowsqokrg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtliqtkpnl.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtkdzkbpep.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtpsnptpor.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtcamhxrmr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtkzvyezan.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtfkprykfh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtpuddvrsp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtzmdeiqzi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gteiweaxzm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtbjssuuao.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtkungdmsf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtkufunprd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtjszrddbs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtaewsijut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtulwqguxx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtzksrfwty.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtbgftpibo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtmlmsnqiu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtpnhmcpyj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtptjtkomh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtpsgstjzw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtfbzfsgsq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtqboerunb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtnluvxzvx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtkqzwjawv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtigavhaip.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtkqhkcckn.html


<!-- 参考信息 -->