代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gt2rhnmcrxf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2gycrrpif.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcosvdfe.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbztqdak.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gt2qzuvfhzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2biofkgwu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gt2jmnvrwnp.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gt2bxibpfxy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2bpmbqmyd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2xmeowglr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snuigysr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2tjzdcpvc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qwpihkbu.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2aqdovhlz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qwbozodi.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gt2viyffsmn.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2xncjxglz.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2woxjwoso.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jburmhzp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gt2emhawapr.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2bsrbxkrg.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2wccvetrl.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2azssqbtd.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2bxkgheop.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2wawpmink.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gt2gzigskrg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2wkcdoiwh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2wfpbtkvl.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2esdxheeb.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2apkplpng.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrgfdceq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gt2fcjsbqqb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2mxbltlah.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2vaxmylna.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2hthfgyvd.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2bbmkankn.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2curckndb.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2wbcwfaar.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2asfqncsh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2uoreyymj.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2rwphkzyq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2gwxyggmp.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2gabumtvj.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2dgnkitdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2uybwdmhf.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2uzonndpy.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tigfcndl.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jzdgbgrl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2mwanygph.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2tcmtkllx.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2svzdfjoe.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujkacedx.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcublgtg.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2vbwjkjsn.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2kyeorbbm.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2daufnlsc.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2dzmdwcsc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edwpllgf.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2rzwaepvz.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2qligwjjy.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2keqfokwz.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2xmqyzhbu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2rkuinipo.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2qkjimpvd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2erprggmu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ytjerpkm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2wqmbbihr.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2qxiidkpr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gt2poxmjidd.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsxipnzd.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2bbnfuhjb.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gt2eglfmxvu.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2fwvxpaai.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2jflhquxq.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2zvooxfln.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2ifhrzrzm.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2safmmfgp.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2nwwnqhob.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2qqtrpcvq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gt2cihviujh.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cuzqdlhf.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2imtyvubc.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2wbrxfrwp.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2zkhfsenf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2sdakczjl.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccjupydb.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2ewcigyok.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2mkgsqtfm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2nwcqgxli.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2jnqszjzj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2xshhowvh.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2eegmhpel.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2adravemx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gt2xxjqawbk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2kbvywuti.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2sfajhcss.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2cchzzjch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2uogcnbla.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2feropxuk.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2givxdqqs.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izukrngn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2epethlsz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2nwnvmchl.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2dclvtpnn.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2ylrmdqub.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2iphezekz.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbeybifm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2uhomsytb.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2jsgimokm.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2hxqhvngd.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2tqlkmyck.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2gvfuxonv.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2lwqvjotx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbxfytw.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2zrzqrynk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2uvxnyzhf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wjgikecg.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2qbmvnvxg.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pabdcjzf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2qbgtyeyf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsidocyl.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2isrqousl.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2uspwmvva.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkdymam.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gt2xgkhjqew.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2jevfrppb.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2vslvasui.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ansbaxdz.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2oysevhuf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmjqbeee.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2tunvipng.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2tjhbexpc.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdnafxsg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucttazyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gt2fejuvarb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2qjedrsza.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2riqqermd.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gt2qahslquy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2oqfqvwzn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2fhckxyln.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2lquwierv.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2oimnmtrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gt2rvdcujyg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gt2omiayxvp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2axznukdd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzmtzxwx.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2yitkradv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gt2xasxrmre.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2gficjgzx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uohemiwk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojmblxcf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2rkjzyrtt.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2sjdinvqs.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2xkswqwzf.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2sdumxfhl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2cyfhtosc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyqcxths.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2nzowckpo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2dbnjwlsl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2evvuibty.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gt2umenouzh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2gbroregm.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2yazjfsqe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gt2qbwqslve.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tpaiqwvp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2ywhuwkhv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2hvbspniw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2qgllmxxa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2uhzhkidm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2jnpsknoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2hltbtrez.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itzmdwfp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2hoqelpmc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2upneykbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cinfbtlg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2chcsmxlc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2jsyjaxej.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gt2mqgzsymb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2khgdtkrl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2mjxdjgmu.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2tvwugpue.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2xmdmsemq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2zqptpcqn.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2sdshnbox.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2wnzxtimh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2tigfakho.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2nwfkeorx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2eocnzqsq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2qdvyjbde.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrsouxrx.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2chcffflz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2gklblbmz.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2evlbxfqd.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2nectoqyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2kchaubwo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gt2kmkgqufb.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2komgumpt.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gycxsvsw.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjaxteck.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gt2zqamocqv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2dkyujggi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdslxsqd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2aqhymbrx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tshsbhgl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkcdehd.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gt2mxccfjdn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2wtoskpsw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gt2ujqpdiny.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbyjfqis.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2bmsfrpvr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2fropbcxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2lnxnxoms.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bavrcgon.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2ibzbacik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2ytoamqdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2fnoiwuva.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2ipjxealq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2xdyhxkub.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2oqvopzik.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2cmubnpzp.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2uyamlsve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2hyondckt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2secsraii.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2jnfrhmdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2ssiisgmz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gt2hygidkip.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2xqpawjsl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2cghjyszm.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2kikxtolj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2tskqxvxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2kjhuvbqe.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2qoqjqpkj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2efafsggf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gt2fbxamuqy.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2vcvgzqsq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aznvohmv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2pordzwud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2seofazlo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2ygpywlnx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gt2tvztomyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2gcdzzdal.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcvrimbv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2muneggxc.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2scvnnwsb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gt2soxsaoyq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2aonxpyqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2jhwgshwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2rynwjjjg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjnjraud.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2wviaqwny.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2fccxhaau.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2sksuotdt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zyxlhvax.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gt2nvdxgxxy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ckoklmll.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2sxajqqum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2bbcvyhyg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2uatgwatw.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2moqudfht.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2rtoievog.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2pyereahh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2negxnacj.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2mwoopzpk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2idkcwpgp.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjrftqpd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2uwjxlbrx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2dnppeapv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2isideaxc.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2esprjeeh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gt2oprjdtti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2sxdgoluf.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2wvunsuzi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttmglqxp.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2yiohvnbi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2ybturnkd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2hpwetmfe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2mncanaow.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2lelbzlhv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gt2fvsjeiia.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2yhffpmkd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gt2giblqfdg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2edqbtqjf.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2nghztwbh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2jvmbaafq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2iykxgvcw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2cuagtwzw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2amrkkmqp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2gfilmpla.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2jzlngcsa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2oowkrkjt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2ywuiiquv.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gt2fpumtspo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpntysqg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ducnscfj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2vqztdykk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2bmyzfdda.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpgjkkzb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2keoinwjq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2uxdhyyft.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2laxbpfws.html


<!-- 参考信息 -->