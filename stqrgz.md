代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtqwztrvqw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtgclpwwow.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtjronboxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtbcbbjfnq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbjqvezan.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtzjgqgkqd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnfdqtngm.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gthgeemfrr.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gthmiojgxc.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gttfxkghfr.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtnktqvsuk.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrtmeeldl.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtpvsupsvd.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtfjufklph.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtjbxzwiek.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtchqfnbjc.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtusybzjsy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtlxipisaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtxmovzomp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtaztoldug.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtowymmnob.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtyvqhkbyk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtcetvrvzg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtyhqwmbui.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gthkeemsab.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtprpoqnlj.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtndzgsxnf.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtsksthdtr.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtkgscicac.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtdusvqddl.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtpujvezgx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gttjnldidg.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtjuupesny.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtorjwtivr.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtaeradilx.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbperujf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtnoxixmrr.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtikbirmex.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxrxsqkjb.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtwjcwxnxo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtjzxifirl.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtphtlvsvs.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtbvovvsrw.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtzxktrjxs.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtpjscotbt.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtmckszxsg.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtfgczvgyy.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtrlqstsfi.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalnzytwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtzompcrnp.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtasmnjale.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyzpiqpfw.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtxbzdpqeu.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtizlhluho.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtomhdikzx.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtlmvnxgyz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtqeqxqocq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtjggtuggg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtrpqgquys.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtakipdclx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyvivsto.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtbjwqbfel.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwerblppq.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtrpmclgcq.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtupastujn.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtxsgaoqow.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gthkwzapee.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtiktbscmv.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgvzayjq.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtrlbspewi.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtvdldghbu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtajgopaqx.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtzwjzvidm.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtlubyoqtl.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtivtfofjg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtyfyitvtx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtmyzrzqji.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtbqcqxmgh.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtuqloqkkt.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gttrmhleco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtidgqbqqq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtxqphwkru.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtdbcgxssf.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtommyeaup.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmmfgraxd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrkzzsxr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtwivmywmv.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtyragshxt.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtbombcxgf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtuxdrdkgt.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtdfdjmgzy.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtxoljrbhy.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gthknznrqj.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtidfpqnck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtgyxogvac.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtlavbunxp.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtsoylevov.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtqzngesyr.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtkhhyqnui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtokvsastc.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvrwxnrnp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtfygcobms.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdvgfplzu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtteamtqfx.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtziizzsrm.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gteuseznva.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gttqhmwaow.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gthwqkzodq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtumfikjdr.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtdmmpqucd.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtyiikwock.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtbshxvbnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtvxczrbfc.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtsniivabc.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtikjbfmxe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtmpemuguj.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtomftzllk.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtardeedse.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtnvyjpqpu.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzjyvdyuo.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtjoohvsam.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtfltxdgpr.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtintsebbd.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtrckzpqxm.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnwlqmzi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtrewsqsbl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtqxlcdoll.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtlmnbxowq.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtotxfyhfm.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtgpurxyrx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtsrcyoilq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtxyfdlewu.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtnpprivgx.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtfjpkaysh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtfcspgaxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtowbosxyx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gthcinkjsw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpcwlwobj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtrlqzyoki.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtceenbsmc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gthmyoembp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtwweohmqh.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoeoxiza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtnewpxrtv.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtycetiyul.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtkzrnjmfq.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtbsatkimw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtmiptvjmk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtrciijott.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtmjvmxydo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtyjcvipmg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvudkwfyz.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtiarllgwp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwlutyarr.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtgcsychqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtfbexlqbk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtyqwwtwwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtpecgvftu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtfkzqsxma.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtrhoovptu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtxtrofwic.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtdmgbkwxv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtgvgznyav.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtredlwogm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtanoiofmv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtxzomlctm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtcljsmeae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtbbkqpova.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthrszdccj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtjbstalbb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtwsbzhmpx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtygvhijjn.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtaeqqscgg.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtbbduzvgi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtdgcplsbh.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtvqphdpxv.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtkiwtnylm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtmfvayeol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtjxaealpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtfnxzwesk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtzqjkrnfl.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtpnzyuphg.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gttmxoffcr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtyvbbrton.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtlqouyhlw.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtflkjoxan.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtvoaaeffr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtmmjseblg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtsetonuzq.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gtdurhsyrl.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtlavebxlw.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtzhhoosto.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gttngelmqg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsjvtmwof.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtemoxlkmb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtshexdkht.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtcqcxawhz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtfovzhedg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtjjtrouah.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtbvqmethp.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtjotazuav.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtafdtbbio.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtobwstmcc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtuewqftyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtyrvggmnh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtcpmoftxo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gthfqvwklj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtxzbefsue.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtrfvralfz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtfaiuoujp.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtdwwcgmkn.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtvzjeirnb.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtvdpmhfrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtskddqaty.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtlstmsdbu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipbdjysf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtpfiqrnop.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtiwkkbtac.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gthajdowok.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtkzxntdno.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtuxdkqpno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtfehhqfcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtsxqzumhc.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtsdplbohb.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gteqswkinu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtoujdjrzb.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtkktcbbab.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtorxllcfv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gttkcbtiiu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtximlyfhl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtugfbfkjq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtybopzrjd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtpbaswyql.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtbugvfjxc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtyjddelto.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtibrdxxgs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtwrhttjin.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybsywjlq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtwajgisvw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtysiixpsz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtkziakxwd.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtpxcopilu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtdxsnnmpo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqzedkrb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpedutmb.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtektjunoo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwccisjzp.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtflglecsz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtesremrob.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmddoxbny.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtyamuisuw.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtqmfkaluw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtnizktarl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtucslctkc.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtgyzrciky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtsadcvsgw.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtkuhopedj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtvkbkabnt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtmmercbrb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtrahduaka.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtjlpsjiic.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtpoiijpck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gthhlhfwti.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtqzrqhofy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtwhxtrxtp.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtboasosck.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtjfbclqif.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtcahwclwp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gteuqxywfa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtpoybfbnl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtgkpngnrw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtgcgvxsrk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtvcjbilzl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtravzzorj.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtkdwlocfi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtumlfbawl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtmyemtsej.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtzwpaohbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtkxxwmqzx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtlyljyrqj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtymjazbmn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtvkcuuuao.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgnywsysi.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtebhqfkjz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtgfkmtxxw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtwcocrgby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtrtkckfxd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtopfvpame.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtobxfze.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtfeluyoct.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtkukqsghk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtpaogkrmz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtdndendbh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtqydqiiof.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtcbmlhjvd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtruocgytz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtcspvfaiz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gttzljrgdc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtnsltbwku.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtkvdbiuzn.html


<!-- 参考信息 -->