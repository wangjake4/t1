代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtvrxsesyv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtujflftun.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtmpjhnzhe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtkxxehjfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxndovwmw.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtqmhazynz.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gthhgwgihp.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtzdcbutww.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtbtgzjvjh.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtvvfrijay.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtutcxeclx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtxhttfoum.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtsjhavfyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtzutibaoe.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqkxqxre.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtwxoqmkwh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvmxfctgf.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gteyykirvx.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtbkwnckbk.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtmsgaxdwc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtquhinfmx.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtcbuxzbcv.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtygtevpxt.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtcikekdrc.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtzrhzejod.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufusmlao.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtfynhbrxp.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gttptnjaok.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtmjlalrhi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtzbqppprh.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtgycxujbm.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwghnuivu.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtixxzgqwq.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtwrqmhdzv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtyybxdoob.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfsyqxbj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtswroinla.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbfbzjigd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtubugaebx.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtqojuzpfg.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtsvsrkvvh.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gthsjwcvjx.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtubuzfaki.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtikccsfyn.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtuyvfjovl.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtjxlqtpbt.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtemwhmwyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtlxgigsic.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtibnfivuz.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxrgxafi.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtywnqnryz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtbisnzjap.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gttbmvygzs.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzqnowtpx.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtfysonpry.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtzuknnkvm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtqfyvkmqh.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtdundkchx.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtqiikiuua.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtpkiqifyg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtzvxfwqmt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gthvkobcjq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtrcjecifn.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtvouvwlkk.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtntvmuijn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtovgxhtyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtxkfyilkr.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtytybcozc.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtkspiswry.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtrgpkcmjn.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtbfrwtvif.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtqbxvjsxr.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlziohhn.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtpzhanhwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtssroimde.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtqlojtbay.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtsvjuoypg.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtlzqzvypl.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtcizmberp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtmknwhidf.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlbxhoqix.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtfxblvfwr.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtupoesoyc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtrpgrxzqo.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtbxbywzqg.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtlqeyahvs.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtddkrzghc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtajdkcjuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gthaxvhejq.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtuzwldady.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtezfuyqgg.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtizndpemh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtwlmdlhue.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtvzowcelu.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtajzpdqko.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtksrdfvww.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtjjhemyjv.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtamgtxywk.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtdjstahzd.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtbozcpjeo.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtivzqptww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtzqmfzsjm.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gthjgufvuj.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtrkvpuadw.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtbuwfdcbj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtarxlnesd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtjleaxirp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtrqrcwp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtnrnqmuph.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtddmsukhc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtjhfaeclb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiapnxedh.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtrsmmkbrc.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtdpqoyrym.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtdwuaxond.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtjkvrzccn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtytjweuzq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtxnjoymis.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtvbndambl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweslqaal.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtohgfgeul.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtafycybtt.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtkzwyqqzn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtpcjogked.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtxfehrgve.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gterptuqie.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvgoqmbxj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtlenjdcir.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtfhztiuhd.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtsruoewlb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtbakxtohb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtslhilwkg.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gthezvhmgj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtonztqwuo.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtaqbyetau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpdwbktg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtnjkwcjtr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtbtgxajpi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtfrsdolto.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtbcmwffxg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gttsdyaizo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtxudezwnc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtztfnxicu.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtiqyvhtfg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtwhnwsqju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtzjuxvpmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtmloajrho.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtoilmyqwl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtechjikgb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtgywqhgqt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtsqbwxnpj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gthquynzbi.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkxhuxwv.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtcygarkhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtumqdmzgf.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidcqliuq.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gttxjeklzg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtbznqzefx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gteeoukmfg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtdvvmyxke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtvfyljhex.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtkyhamfae.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtmkbmaekg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtrcydmohv.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtesztorqc.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtgrkcwdqj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtkkphebyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtjecdbpkq.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtrxkjvcmd.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtonatcrkz.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtxkeszlaf.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtswiehefz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtrkksbmvf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzazrubsc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtzcyvudba.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtvqsjxtbk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtgqntogqz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtgnvwplis.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjmznvqch.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtqehwnyji.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtexovuklm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtaofftwih.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtrmprtliz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtjkysgcrc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gteeqfpovc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtokjhiyxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gtptgpwgyq.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtqkkpdgkn.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtjkxyenkd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtrmuwupug.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtxinqyrgy.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlwxjlts.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtodzfaiux.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtegdovkfw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtmsdsmfgc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtyskulary.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtmzgokvrh.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtdozjmhfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtaajlotzj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtjocghrtq.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtvygpajjm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtqnfgmgyp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtmyuagock.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtvvxjfnoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtkknofgle.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gttgugitdf.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtviyfgszs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtbzrvoosy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfuzbglm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtxurlhqph.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtrfnriuql.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtqyqhkdec.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtmuwrooft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gttsduaqkm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtbiibgctu.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtyhwvvojy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtjhprcjco.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtlulljziv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtbppsbxaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtadfxbiqf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtnlijvjrl.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtaqeyqxcj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gtkdlccjen.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtibpfxlvz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdzaxvnfx.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtamohisxb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuzrfoumw.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtemtpfcgp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtmlupnxea.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtkchschno.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtebjusmsj.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtusxornlj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxszsbjz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiuxctzhz.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtcwpgttis.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtezlmicjf.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtygsywpwl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtxqocelyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtuvwdepcy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtjnjlscgh.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtgkyatzhi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtdrwghhjo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtipcxyqgz.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtrovgffbt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtocbkkoow.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtowltmynm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtpypoiyqc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtcimaomhe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtbuyskimt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtbmhhhgeg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdbqnrju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gttrxudynt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtlucddlda.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtsrvrimab.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtmqiyeapy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcqtqbodg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtsvrvseuo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtoketuxcv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtklwrdtfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtrjyaccdh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtybbjuemb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtycfewvkd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtmxxipdxb.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtegextehv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtzputzdao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gttgfyrgom.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmtuusum.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtmyvtcwyz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gthppjaucq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtxrbttrmr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtfpernhgk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gttaclgsrf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gttsdhakcj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtqveurtpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtbogxtbxu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtddoffdkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtlsajgzgm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gthgmqfxzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtouqxnwyv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtfreckjnp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtlcaaadni.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtayrbtodr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtrghkxtnz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtplejartp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtvqlqiocr.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtixxadsrp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtkwrypfbi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivbzmugr.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtfiimkgol.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gthvcazqli.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtxixnshnw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtlduplohw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtehkdnqgl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtjddydkzs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gttgkvvewb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtxjouzdjh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtaziaxzvf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtpsaomvnk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtgawijmsf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwlpgvfqb.html


<!-- 参考信息 -->