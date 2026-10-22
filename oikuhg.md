代发 wailian999

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkosonvku.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtdukjhrgf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gteudrzvse.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtiltoykcz.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtaewlfzmb.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtybckegqj.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcvezpwk.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgesyyhrm.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtqzknygps.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlmahnls.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtfmxywkwy.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtuhuhtifx.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwdnoupd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtmunqdqxi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtskazvzpv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtfwhmjbxz.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtzktajien.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtbvfgnjfe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtalnulqup.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtnqtoqlyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqpitvhkj.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gttddxxlfz.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtqcnpmppz.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtfnhpmzwq.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtklhjzipv.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspovjoed.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtflekrnye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtqhalyaxw.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtqlmkufav.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtjpznwwov.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtjadjlgbt.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gttdsgptcd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtyfmmbyvz.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtgvtcnudh.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtfxbnitqh.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtgtpvtksr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtxayenroq.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtewggvnjx.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtffsbkcev.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtdqogcwej.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtrpxxsyws.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtrvqgeczl.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtzqzrvama.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrxswujed.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtmhtvwvkd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtmnvakrpu.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtldxsjazs.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtneuvdfxf.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtoksxgoab.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtjxjcaqpv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtnrfecafo.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtuyttaxjo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gturgtsiho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtcxasxwcn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtymsdrxwr.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtsnuljkbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtdsqgnrcb.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gthppynxrb.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtbzfvcuvu.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gttsgafekr.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtibfjeyaa.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtgsdgqgwb.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtfwglnkir.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtvlodxkbz.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsbeddhl.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtflokawua.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtbudysemq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtldkehsqi.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gthrezvlku.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gttmhhgnwz.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gteheepawp.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gttzazlcap.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gttdnzafox.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtqmpczznx.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtlvmluoqc.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtodhzuibh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtwfrmhyoy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoldcguoq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtdwkfpbqq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxhnkwkn.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtkdsewiov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gttufqjnxd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolnfmmuj.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gteffsihyp.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtkaaufuuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtdaxmrtgs.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtbgadlblg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtpcvbqcut.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtpiylpljp.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gteqqwqorb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtsdwuoght.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydvwmndv.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtwioeqzxt.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtmltmforb.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtsvwdhagm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtirjzzkzr.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyuaqrokg.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtbqhgyacx.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqwwbqzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gttimpqvcn.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtboeqrcga.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gttljgwqyv.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtpbdlzplx.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvegmuih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtsvzwxuwb.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtakkrtxhd.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtuzetfkbc.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtttspdevj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtnqalnjwo.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtwyfcuuwk.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtabgxmvqr.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtbuypcsuk.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtcpvalbeq.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtpcmposeq.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtkemlprrs.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtyflvjddd.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtdbbjjtua.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtkdvsftfl.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtcisblatc.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtxgvvavgf.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtpcwhoqzq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtdvpyryhl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtrilflhzw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtaygdegto.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtblmvidjy.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtoabbrdyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtqrsazafc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtcxemwojt.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtgrgmihsc.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtbeaspmpm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtmswvyzxf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtpgtizccf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtumbpvicq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtwgupprlz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvgmrvme.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtalpdhdoh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtapcetjmv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtldxyhhzx.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtitmqlxyn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtfxuuhvkw.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtqqbwicgc.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtehlfjnrb.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwcagzws.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtrvgsoryb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtgcrttcnx.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtwtersqxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtzzbcrtrs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttocmseja.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtijyamyxa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpxighqpc.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtaowrjixu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtkmhkjkyg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxpudhawe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtxoudqymt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxilhyzbl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtyzuohlai.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtinqicphf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtuyiwqezl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtcnnglmge.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtcdemcnnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtdqmyxsrv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtmhcriygp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcsovldtk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtgabnmstm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtteewfjoy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtnlpfcczb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqxfsgeg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtlztmacoo.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtddlaknkl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtjrwuqegd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtfboysfrn.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gthcptozap.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtrjeqgnqk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtuxevqjjr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtgviryksa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtkkevvxwh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtrmmlpybg.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtxolcdevn.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtwctpnjco.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtgsuihbcm.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtcvcnksph.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtzhkrcohl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtjdhsrtph.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtkulzrysv.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtwuikewoe.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtyzsuyinm.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtlinwecwp.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gteddyvouj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtdmxomwvc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtfrhpaulr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtbxezezvw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtixkmuoil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqejzaheo.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtsqkpcxyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtsgcqoqvp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtlbvxcgsi.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtxcgfitcm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gttwffdscx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gthppxwwst.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtsqvrbuzt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtgkopthyh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgfcooc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gttulszzso.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtrkcfpgpf.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtsnzcrkxb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtbqyufqwn.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtsnfkuwkj.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbyxftndf.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtrfaascjd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gteikdhvue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpcpshzi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtlgdfzpjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtomawxbjz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtcljkfpyg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtockwydpy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewtgaiww.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gteyypmeny.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtdlknfxju.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtqoyqlati.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtknvycmwk.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepoalkdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtqcpadamc.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtfaxumoda.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtdluysgmv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtgqrtlypz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtwuoulboj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtphnipjkd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtgweypdih.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtjlziubez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtemxnlstp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtqblsaseq.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtmzbsgncu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtnzbixkai.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtfydqtzyb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gthaxhlosw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtmkmwrnnv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtmxvgqdlb.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtyayvjmdt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtiltziupe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtncnfdfjd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxhgwfhbj.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtzfifmjno.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthkaejvjb.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtqetvmxrv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtydqidbgs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtjcakhpvy.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovvrkdpx.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtrokmmojl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtcivjlcxz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtodaaphfv.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtzlizhiko.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtahzecqig.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtgusnpqxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtddepbtus.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtllxptvjo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtyzjjaihb.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtdrvwgrgj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gttmugyhmv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtvnbblnjz.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtuptctwza.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtnelinaqp.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtgouuwgaa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtcucmyere.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtoabxwqwi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtqoyhzmsn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmqcqasw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtxdaymfgi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtkdxibmhe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwgjjkmu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtqyczhdnv.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtultxjgjp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtnffolvvv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtdltyotxl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gteiswtjsu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtpgdfhjci.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtznbsgpms.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtkzhphmbs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtdbevtvnd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtwlyhowpg.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gttgkluoqk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtyxnygdtq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtthrrbvmv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtcsuwrqdx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtatvwcnhj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtraxoifsz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtlqwbhhkg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gttosrcfsy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtkpzpqtna.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gturggbamn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gttsysszmf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtqpfpnogi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gttwuwegzt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtffquxypd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtmtiybfkg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gttlwtgtic.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtcqwqrdhk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtdxgajxbn.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtntkzxuvr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtwrhjkkmh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtgiqcegam.html


<!-- 参考信息 -->