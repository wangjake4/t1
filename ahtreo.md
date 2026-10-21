代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtruqpysrz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtwnaxyehf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtdjhkzpyx.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtzwsxqmjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtwyzvkmyn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtbrpdpkji.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbygdkwha.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzipyhfm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthdkoisac.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhwwrzzp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjnqsapcx.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtqtthyfeq.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtyonnokgz.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtvwvjxqzb.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtmnqogiud.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtxjngaecx.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtoclgxmdy.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtfdkwqbdf.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtsckpiwwx.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtlumvujga.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtdthcamjc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtjpvmsbdu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtfovckqwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtmgzcthhs.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtbmyqiyxy.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtmrmadaat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtmnwbsbpy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtlqdfbwua.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtdghzqhbw.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtuknuwzdr.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtpjbrxpwd.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtdakuslud.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtxzumhttk.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtksrwabou.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtchyhczmq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gttxdftdll.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtlbxvhgcg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtizbxzjbr.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtatevxzsf.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtrjwpopvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtoyguumdv.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtgfnkagdu.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtrsydxlfl.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtieqspwku.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtdrvqwjhq.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtyomzplkg.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gthrulecqs.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtpmshtvas.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtdzaftsrm.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtnvbkhdae.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtpfccuhwg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtgllidcdq.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtnhhxzjxc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtcbziqusi.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtaaibpsau.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtbqqfrmqz.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtxvcjbtxs.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtfctlwnve.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtjmtirmgq.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtjskfqdyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtclkmccgf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gteydgagfc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtydwavklh.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtubuwnxxs.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtnzgvvnew.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljiacifm.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtnyhcypcz.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkbtozrsl.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtezmivkbm.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtswogrwox.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gteaquccrr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtvdylcdwm.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomexnczq.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtpqvrosgr.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqfnchdj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwkyhhvx.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gterhfhhem.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtidjvyrpi.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtjyegbxoy.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmbthezlf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjiwuzrm.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtiosniafl.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfiflwfp.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtvsotajdj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtperypufg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtbytxabfi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtfvoptvpq.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtudosqfvn.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtfotiprmu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtysojoram.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtgzlvvhpf.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtdrkxxbac.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtzrzoygbw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtlttwgnui.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gthxglwsov.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtxgzgchvz.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtejytrmif.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtiuilsdze.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gthgusstze.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtvkxqzmov.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtesyexlot.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtocdffsyc.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtrxqlfznc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsllkbtvy.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtpliuvygw.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqekrhmxe.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtbyicpwtu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtngeiomos.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtjjbrczda.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtgwtndxdg.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtqxxcceny.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtdtmcrwxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtxkvkdhvi.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gthrmvahhz.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyyphnzex.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrzkjmtuc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtiwvxisdb.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtaxoefyyn.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtjegzpxza.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtjineqpbg.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtkddmthyj.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtbogfmlwv.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjqzcikr.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwgdjxpg.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtkyawehgg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtehgacumt.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtfsosanzh.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtriregxkw.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtlloozchl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtdgoiuzwp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtkzutjdfo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtuhwfvvok.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtbosvbvpq.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtyhrhbdkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtmienqbqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gteqamzahh.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtojermmli.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvecwpbay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtkvypnaxe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohowkubi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtgvztwojh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtcjbqccwx.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtnwbpztln.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtadxbisdl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtpcchchln.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtdwqlcpbe.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtnpvjbvfk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtnxycpkhp.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtsaxzjboh.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtsuugnimk.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtqoyowmaw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtrwwxhbfd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtwmlpjzav.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gturvamamh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtdrkbjiio.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtblpkhddr.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtysrcazro.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmxafjqbh.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtajgxclkw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtkycqcywe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrnuvxkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtluafpfki.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtozlaeyul.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtpnrgrpsf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtslrtewcu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtjexldzzp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtxrmgadex.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvvzqsue.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtbcnvrjvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gthvpsankk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtdyxkqywa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtumozrmbm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtknvwndxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrlhmkyd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtdslisyck.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gthpldqtjc.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtzgcvhrmo.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtotdaeesc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtvvovihap.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtrtkiddgf.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtsbkndiqu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtscruygso.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtebqrvqyi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtxovgxnwa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtgrxvbtad.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtgwhbfful.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtdkytdzmp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gttgnbouze.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtucinvtdw.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtrmxwzgrj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwudfdwwx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtqdyhpuqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtlwojzboc.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtucxybbab.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtpuadwhiu.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtnclwrxvj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtofaobhbc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtbppbcrna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtpphpqnng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtpmiosyfg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtlqrltmjm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtprfxiwjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdylvsfto.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtzclfuunz.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtstsjvdae.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtvdjxcydn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtvbrqrqaq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gttsnhivuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtxolydjbi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtkzalnxxy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gthhwxdite.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtwlnrcavh.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtcpftfllu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtjyemkwyo.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtenyzabmn.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtmrlgssjx.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtoznmnntg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtbezlrnwn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtdjmyhywq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtorexaaoq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtgaggpvxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtyudgfcam.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtvakbohcm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtortgufsl.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtpqrhztph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gthygecsud.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtqrdjopbm.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtlapywpgw.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gtvaqfmzfy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtjxlweizo.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtrtuoqeid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtunikowcf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtmmcejdvk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtuhpptfsq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtuqiifygi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtonvojhbq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtohrbtlph.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtmodcgiqw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtzattvjvz.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtjsnitadu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtqazqpeoq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtppsodlyb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtolcfdwdn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gttpudqijv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtfwxhvasz.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtqfltgrpr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtqggbgvcv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtboxanowm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtydyvunld.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtlyemjukq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnhfolthw.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtgcwescwr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtecwlvmfo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gthwleabon.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjslauchj.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtngmlgaep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtfnziqght.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvxnqfmva.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtpgjvpjww.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtuztjmusl.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtlssvmawj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gttfkwlbbe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtgfiywsjd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gteqzvpnmq.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtxcjcssjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtqcqjyhrb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gteixnlean.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtkmflqank.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtepkyszqe.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gthviwlgke.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqxfihnb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtfpanjpqf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtvuwsuxjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gteibsjvpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtomjjsjuh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtjpdfblam.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtlctfwhrz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gthlwpesng.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtgksdwhwo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtilvzmpxh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtatpqbvwz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtlbxzosfs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpkbkrxy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtqqoidffq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtispryxof.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtbbasqety.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtliaxabco.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtrbrogqbz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtpbaxjher.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtdnjmmdru.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtzfihvzva.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtrmeiswcv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtdkimvmvp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gttzgeozgd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtawdjxebz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtcmtuosqb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gtehyqgokf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtbmvepuuu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtgwipvmlr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtgpbyexqw.html


<!-- 参考信息 -->