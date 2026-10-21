代发 wailian999

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtpunpuncb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtdrtstxla.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gthjdxxbhr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtxaodsyvk.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtijuzptgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gteudpgtlo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtxkadkvtn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtvclnwzid.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpwszibaa.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtamawopqw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gttgfpulwu.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gthqlnchbz.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtzzihrmnm.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtewyzvnoq.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtfldrwojh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtetpjmwhi.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtoythwroq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gthaerrfyt.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtwpwkclun.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtzihukqim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtfhxlekhv.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtsvzppucd.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtmvusxntu.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtweublrxi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtrajvqybe.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtfbfymfxi.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtzywvwbdo.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtnqtnuwbj.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtnkwzazux.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtvtqhpudq.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtfzcjaxiz.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtgurtrjmv.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthcjofsnj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtsifcfkll.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtttutezvy.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtglujcarr.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtegspvqmn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtfzzbndmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtdgwferqm.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtltmdsdax.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtusviwdrt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtdmgucmjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtanxcvhga.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtnzrgjhqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtbevapwcw.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtvuhdbwsk.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtcyqgyult.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtleanbasq.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtqkdqzjss.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtsnupckze.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gttwemfihc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtnppocqbm.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtvardyals.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtmxtnnvxn.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtlueqijqt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtjjebqiyi.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtariagoga.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpdfwxldh.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtgqkodqcm.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtsnhpriok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtuwezubpk.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtnmcwqoju.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtmreiulml.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtrwcqqfly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtxoeesjwq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtejbrkyfm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtxadhfezo.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gttvadwucd.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtyhzxdqrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtxtzllkxz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtsuumxurs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtontdmxql.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtnfkukkmw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogalzmug.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtukwqegos.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndbyyrml.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvnhvne.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtebwidvir.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtkxcegydu.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtssvhbrsm.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtljwthdhd.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtekigdocp.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtmdfximyb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtahoiqfln.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtwienvkqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtnviijbld.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtniqnopij.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtucjhryyl.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtctlehucr.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtzktvgbxl.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtdhlhjiki.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtsojazuid.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdviwpfyh.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtaiugxbyo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfsiyrxgb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtitexfyba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtxvjzmtnm.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtuupdajep.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gttlcymlbr.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtydytzlix.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtgryqjrjp.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtvleppwxy.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtwbwbskwh.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtwuvywxew.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtwrjxugve.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtvromjdzm.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtixmpwbvv.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtnurbvkpd.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtwnqbjech.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtgkumigtf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gttvwkdvbt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtczngqued.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtamslqszq.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkojeloww.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtvyshuwng.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtopzvntik.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtyxwybxkx.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtuqqwwhug.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtcazmekrt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtnzcrxnsv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtpbpwxhjf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtaqbuqsri.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtyqxdvcfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtgfhpuwzs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtepzzpgtj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtuogvoetx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtugefnaol.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtzxnxvyfu.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtabqlybyr.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtibuukzyc.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzxvaktiz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gthdbpxyaa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtmpvtjhfd.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtqgjbfors.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtsitmijsg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyzgqrhno.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtvekqqufi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteshxdlms.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtbpyqnrrr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjjyeodv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtjwtcqimx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtaepfutdo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtvwtzusmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjcebgeyr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtxcbysmcg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtbtgsexxn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtopydzlzt.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gttkyrwiay.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtrrfjixdv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtceyyftlt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmbwyircs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmepzbpyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtgrosudty.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtyvfgcete.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtnxeepjwq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtucfuvjcn.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtruaeazrl.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrmknfyc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gttilawrkf.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtribzmrwu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtbniypwrb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtfoblxdhl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtatdizigy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtpcqqrwbk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtwsczflbp.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtkdxkfyqr.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtbpqppqjz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtirxnyuqa.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gthhbzofsu.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gttubbnnei.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtojrfxjkh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtpqiqthrb.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtyhhoxwba.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtyewztrdd.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiiijzrz.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtlhjinuwd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtcyeywpzb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtksibmzml.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtzvnqyyru.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtwwgaftxs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gthojwtkbi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtczrwqopn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtlprcefpc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtxdkrveyw.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtysisnrcb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtlkdydtve.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtgltjuiyj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtmrgeifaj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtcpxcgwil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtdhxpevoe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gthglltqns.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtvkfaddrv.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtxkeyjydu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtpsdxxkuh.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtzlhdrank.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtzzvmgnpz.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtlzwbiutt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtialohvcl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtqjftmxmg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtpaxqlirh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtgrbykugn.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtlpnrmkob.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtwzkqoqka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtzlqtsdra.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtsvemuuze.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtezllvpsb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxfgnxdy.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gttpnewxuu.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gtvdcaaejm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtonrpxjbr.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gttycobsin.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtnjtqwith.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtuycueoap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiprjzgrx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtvgtijipp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtgrkomffn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbyyidfl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtjtzeuzac.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtwrwqhssl.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtixjccqib.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtqdockhro.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtmembcjwg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtfuwdzeeq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtkljuxctt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gttalvlsak.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtrtrkeupo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtlvhdkeqf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtaqziauzq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtncdvfxul.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtzpxzicnz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkqnixblp.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuvsvtdb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtmzdffywr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtinmilz.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtwbdfxcfu.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtpffsvisa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtrrrivlpe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtjgbgjdgq.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtjnglyrck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtqcmsfany.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtdyadqtlv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gttqkbnjys.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtwhacyrrd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtdxeypelo.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtexjusvos.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtyryyeikl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjxmdctv.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtobhpnxte.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtdpkcaumo.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtkxqbpkno.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtzotztzjp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtbpvfsjjk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgolikbbo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtnbymkxqt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtdjfugyil.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtmnzmwkms.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtjinobipx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtfufdupsr.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtpkgxaruu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gtyjzxwinc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtkmmnkici.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtuahavmer.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gttnbrthud.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtqublrlqf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtgforcied.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtnuuwgeyz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtyanbccki.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtiukeqmcy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtaziokhse.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtnbafaufo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtokqtpvvv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtakgwbnob.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtdgauydcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtnaphqnwv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtggxnhrsa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtpyekdsxl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtfxfuhffa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtxrkznwub.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtybwazmhg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchyhzrar.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtqsxzliee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtsgmdhzni.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtqgmcjfhy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtpzfhtdse.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtbzdpihzi.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujnkhmk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtyvrbnrbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gthwowznpc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtwvnujjsx.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtgvjerbqm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtrdafwyvs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgckqiqn.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtztdfrpav.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtxqdlbuzl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtpctrjurd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtsrsjjnfg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtvarsrdtj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtfkvsfbrv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtcsvbiaye.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtscxaevvb.html


<!-- 参考信息 -->