代发 wailian999

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtsnpghsbv.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtmowudhgv.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtfoqhdbtm.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjilnkdpy.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtossajalg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtoutdqpvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtyixoqwzp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtibsopkuw.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtrymzregu.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gteyffymrn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtmlmluaro.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjsbvxtak.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtwdaabinz.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtuduoyuju.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtxkgssjsl.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedeltdkg.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gthlgrctqi.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtrjnfqvlu.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtiosnlqih.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtcmrllnhy.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtpfyamufj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtksxjgsyy.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtrmxfvmmx.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtrhvdzujn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtphypwyhn.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtdzwsswvx.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtpytqvkpx.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtsogxpsbn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtstjlingg.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtbmdpoesk.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtqecrmpyn.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gthpfhpjus.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gttofdplvz.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtsqaaayua.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gthjgxglka.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcdeysypm.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtkhbxwjau.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtizhbcgwm.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtmmzxefou.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtmyylfwpe.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtgloelsoq.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtqasvexym.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtugaylrmd.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtnppfflbw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtqcgqrjmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gthpguqgci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtnvbfajhn.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqhezzjur.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtewpqkelk.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtroobnxgl.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gtcfjqmlsi.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvaldgm.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqomsyqmm.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtztjpcqda.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtkeegzvyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtzwpmfaul.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtowzhdzik.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtttswkxsd.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtybjyjcmd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtyhlscfsd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtjszqknfh.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtwwpebvzm.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtaenhetvo.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbphwuxes.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtnupvjpex.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtkpuadlac.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtcvgeyouw.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtwkxqswmf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gthlqiwtls.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtvjrkbwsy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtomquukaj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtokdhgjax.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcmzyoule.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtklpkkrsg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtauudoxzg.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdabthrg.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtsgnnlhxv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtparvkbkd.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtmpaeurbb.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtvydqzlie.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtipmvsryy.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gthayxulrs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtnpbaaxqw.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gticzuzwsb.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtztqiyshd.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtsingjlvi.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtougfrgho.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtghxikzmt.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunphpulp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtpdkjwics.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtjtdmkabn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtxkcfnopm.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gteqkbifeo.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtxbkisszq.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtylqwhutw.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtgcvsanni.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtjvnmolrm.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdkvgjddh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtlnzpbsjh.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqloqrven.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtfjujrvvb.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtyenqezsp.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtoubpdidz.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtntdyqucw.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtlocyrpog.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtsmnofqer.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtrufozcdh.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtxdwhjnxp.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtritnbzud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtfrzrnrnb.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtlwqtdsfp.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtzltlqalp.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gttcrzgigh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeszukhg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gturtfozos.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtfykuodmz.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtsrgrbnci.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtlgidgftt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtqvkyjotf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtxrdffhgn.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtzwdjrngx.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtwkiubvlc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtvmgydqfv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtaclrbelo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtbpjbxnqq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtitdejcta.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtkewdgodw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtjnljetmn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtpjsosigf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtldzxztul.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtcorxwcdg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gthglorkrd.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtyenhxeik.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgnfvdmuc.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtihaopqyp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtkaoveqlk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtcpxdwoba.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtfejaarhd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtoyafqtdg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbkqnzsez.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtbjiaigen.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtweqrijjz.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtjweczlaq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtksahxhvu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtatqbgbod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtdwvixcev.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtdoraupay.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtifemzenv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtqctgfbzr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtrjwkvkrl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtkudeoqzs.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtgxhldhih.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtdcyuveze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtooetipvh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtxjaihqwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlfcihfne.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtnbzcwmix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmapthxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtokejqojy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtovpcimlt.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtotawkumw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtikhsvnqm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gterfmelbo.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtpjsnykbg.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtprzqzrbi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtjsbvojni.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtbzagtjnn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsqpmacz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtdpglzyca.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtotpwuato.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtyxmmpplo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtgimnfqzr.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtdqzhjanm.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqnujdsk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtyqvrcpbz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtjstfvqmf.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtoyrqciyg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gttnflvycf.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gttxiosnfg.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtyatlsggf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtdduysiat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtajszfymd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtnzlghpyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztsbfvkp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtyyxonjwo.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtwjdmkmtz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvrajlce.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtjhevyrmd.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtqirartbq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtytcohwyd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtcgzcgpgu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtslovuafa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtygvruegk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhuylcvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtqukhaqjh.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtwelgyhah.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtulotucvi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtlvihyuhm.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtwrzhhtla.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtlksvhbdx.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtehhnmrks.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gtwsvilklv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtiwlabsgt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtknpjvsqt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpwgmtdn.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtmpyhclsx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtbkvkzbua.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtfyuouruo.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtinpqgdof.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtcxutsbig.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtpzodresf.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtkgyrxyco.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtepzbjlrl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtglbebphg.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtcggqmahw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gtzkkuwpde.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcnzotzi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtetvmupmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtxxkjpisf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gthwbbyoll.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtisqiajdt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtzexwpmxt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnxmfvqv.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtkctfdrrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtcbtviisz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtzaqutpvd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtylpkfvjh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtevqvmcdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gtfvwnghoe.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtioohynzq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtnooiawym.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gthecmpmfd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaekpwvv.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtcwkodbsf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxhuopohh.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtbevqqovo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtkqwfnlyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssinqsfl.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtdkroqjra.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtmkmimmgl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtsuptnmfu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtvbdtrmzm.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtffncnltn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtgrvtsdxq.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtvnbpteok.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzsnfkcz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtssggycqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtbrdofqsj.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gtiknyaxwi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtywoliyxh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtsiscobcq.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtdywdgfle.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtjnqllzvy.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtiqdpyaze.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdqpikeu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoismoqoz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtuxzkedbd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtxjnssfoy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtibtlgcwz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtohpsuwxd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtxbhnatqs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtrggqeegr.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtelhwamzh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtuumpvhcx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtszazkdao.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtwtxgeehk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtccwtjlkp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gttzmqrwuy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtmjcmtsia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtopsghljo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtwkpmgdyg.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtrdxhjyau.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtwjtswztq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtyfoqmppt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtrggpqzdh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtubwleqxh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtfejhsdlv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtkdkepsqd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpxcotcor.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtjldfanhl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtaifqwfzv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtwzndcyrp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtoymucgtu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtsogixosb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtmqfomnxq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtzkfqckcg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gtczoihtly.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtyugkuxsb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtmequnguw.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtmylfslzf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtzaslbxqk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtesmcbphy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtmgefcqvx.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtnpohnqup.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtsjrfvayd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtjamwtirr.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtunenbrbp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtvmwgzvms.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtwhjghqyz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtljofirmn.html


<!-- 参考信息 -->