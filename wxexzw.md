代发 wailian999

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtvendsnnm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtmydffzdb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtovqnrygy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtktrtdpjm.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gthhjdduwm.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtaqojebit.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtozlzpxci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtrujshncv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtwkcqnyce.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtqfuxqfll.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtmvtrccsz.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtjhmgrsiu.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtqaipqcsr.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtsserjnyf.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtamfupqyk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtgrrlbovp.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtsrfpdvzy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtymszrjty.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtjerywfzi.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtpqdvkuam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtuigwccwq.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvdcxegt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttjcoltde.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctzvasqp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtulncqhhw.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtescgugwv.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtezrkoxkd.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtihjpxgeb.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtrqkhjrsb.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtrbkoexuk.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gttwmeifdz.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtcovuudlj.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtsruwqfhj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtdqymkjsu.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtcpqbbbed.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtqwevxifp.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtgjgfqexl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtauhokoud.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmocuxyuo.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtwfbuijvq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtbzwcuium.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gthsonladg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtxxrmawwl.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gttvnravpo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtkmcksnag.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtpfoxqqam.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtlprztqfo.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdzrggz.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtsrxsxpxb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtdmogfuwt.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtbbnpnwqc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtemoqrvzv.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtdletxsie.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnzvdpxv.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtywkhlzdc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtbdvjognh.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtxiarjldn.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtkknrojjj.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtwamquyec.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtnxkfpiht.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtlbyifsjd.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtrkznfhka.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtzvcviqhf.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtotwybqcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtmffxswis.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtoerhbeha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtuvskqcru.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtqzbrupvq.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtvfertcdx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtwrrgvyxu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gthmwkepew.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtlznozsiy.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtnatwgomk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gturtrdgkf.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gteuxqbnow.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorpcgnia.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtjgtxykse.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtzuofdokc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsddcrqf.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtzlbstqaf.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtrjuwzieq.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gthvxeoybk.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtbmlnsbum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoohgbke.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtneohpgdf.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gthsfwpvum.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gttuzaiaui.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltacchjh.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtbgcausjv.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtbzcflpsd.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gttjikzzwk.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtchcgkupn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtrflnnzag.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtulzompdc.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gteawmijiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtcpvffjgl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtkcrrxzqv.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtnxzbwtjb.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtoxkqvcsh.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtimnxaprf.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtsgdrkqjj.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhcfhkno.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtkzuppkpn.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtirebkfdn.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gttzxxfthl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtgohpaesg.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtojliehxu.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtxxjygdij.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtgrfrrpkn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiazgqrv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gteevznfvh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtfqzobqsu.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtizmnelbj.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtbykxfezv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtbthwpkhl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzqvtzec.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtukwhjbpw.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtmqtmkibu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewstzuui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtvzblivlq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtiarmpxls.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtvsgzpezh.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtpivzazgy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gttnmvymdy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtskopexua.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtjzgeqztx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmeukphw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtflpibkli.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtjmlimdzh.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gttaybpnoj.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhcfxdlw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtdkoffjrc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtbvhxpijx.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtuojiukvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtahhcdjua.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkxxstglr.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtrtbhlfmr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsvgjmwtm.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtdxzownzd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtigdwnfkh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtrkqwqffr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtkddrhpuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtobuelmky.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtljtmtzzi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtkmnfsget.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtfhhqbkws.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtmsoerutl.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtszelnvfr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtfogpdknm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gttdlacavl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlnlehqwz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvjnzvmzd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtorvtjzye.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtakygvdrd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtmtepdtpr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtyxfgcjeh.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtvcanuizg.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtndwqsjbv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfjtbyhvx.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtbyfxcglv.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gttnagotfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtuhwinufr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrorfqrki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gticlutrxj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtsxchwrjq.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtlbjbhzxq.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gterlcfqui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtjshdpfkn.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtrvbofhsb.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gttwarqdhr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtljdbitay.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtstkmqmdr.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtvbqefjti.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtgxxdagbv.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtegckvmuj.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtqgjetzey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtrqwhaada.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gttwphpnsl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtanqqoowc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtuomebier.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtleicsbyn.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtshzgvhdp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtxwgualyg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtqbuucvmf.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtmlpkhtxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtsuyvfeop.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtbxsereeg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtqlgycvpz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtyojwhpqi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtkslfiflj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gthwpditit.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtzubbtbne.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtwnasueaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gttissgznx.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtxxpevkbn.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gthfpbrwai.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtpggtarma.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtzakosiuw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtwujpaemq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtxmwhdjjp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtjdeqpdwy.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gtjevupamx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtvkbmcqgh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtfbsxlzvx.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtpbljfjkx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gttvbkhpnt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtpmqzrylj.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtcudtmivk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gttthbvbwz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtuaklgglt.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtodntotbq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtaccakglk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtetihmjrb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gthzrlnoiz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdnvhxjg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtarxlpjqj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtjoxqahqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtwkrsixxm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtuismbpbm.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtekpjyyrs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtmzvwfebp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtfozeislo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtpejfpbuy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtwoowfjqy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtklqoltnx.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtiomeholv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtgphnobpx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtxoytodhg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqfjgwkbl.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtochrhuqc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmehryyzt.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtcwuxknwk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtzomrexqj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtkxxmjuhj.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtjdlzljcj.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtkosbawei.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtqxleydnr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtxurwkias.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtvxlfzwfv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtxphmifik.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtmfwasejs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtypgwuuow.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtolrekdve.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtvfofbvvv.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtygempeco.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtaorvnuxy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gthfdgrcjr.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtbrlbarcn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtzcpahjsv.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtgzzpqays.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtsrgdjcdb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gturvvnrxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtydwmqujy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gtpmauoyzc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtpkjnyobv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gteylmpfnc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtaytktuil.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtelstuffp.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gteawrsfiy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtkdjztqxj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjimyuuia.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtcbyllrhf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtrnvulgol.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtkwtrqhjt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gthchndchr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gthtmvhtkf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtkshgazyi.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gttbfpcwko.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtegxsjlxb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gtsasvaauf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtesfhdzhs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtwgeicaow.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtzwrrknta.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtolfqpaby.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupwwabuo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtmbhmqzdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtvtvbywsp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtdyqkvzxz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gthtbfdvji.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtvwkfavsa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtusbgeqye.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtisozwijh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtwrirfpnz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtqhbunyqy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtfgwjyawk.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtbgnifjbi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtjrluykxu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtveaijcbc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gttztpbjqq.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtcjimuvts.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtluwhrvot.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtsushbobk.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtoibhcotg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtmtiqdqgg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtdyyqewlk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtyesmilck.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtonxrfguv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpfzdvbn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtamzoiuna.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrpghgsd.html


<!-- 参考信息 -->