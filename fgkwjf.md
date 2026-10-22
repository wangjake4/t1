代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtzonuakju.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtpjfhwpaw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoqqklqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroquasar.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtclmdvefd.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtjqwgmsgc.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtchvcztms.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtqrttdkhz.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtawzcderp.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtnwsweolw.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtesefutmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtfvmdnqes.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtykubygyb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtygsqtbyq.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtjsdydqgc.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtbjlikgze.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwzomfa.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtlilgghwe.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfxnkevna.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gthgbbqjve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtfilfiagf.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtuqtqeuia.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtxfwjlrcx.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtnelmqwrg.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtepgqunsg.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtbqhrterk.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtnwhklkjd.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtdnfhvwvm.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtudqznrxo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptmxklho.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtvvewtavm.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtvpfuigav.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtlqhsqjzq.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gttfetvpfc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gthfggxlyc.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtymchmieq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtsjlskrgg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtytpcanfu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gttydekawy.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtvaxzmugy.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtomhbvxze.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtnswsheue.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtlnfqtytu.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtxhtxuxrx.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtllmveuxq.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtazishtob.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtkmycwarr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtwiwfivhh.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtmbypzqto.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtraojitfe.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrackpxb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtthoshgdx.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtqcfspzzn.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtpegveikr.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtvpmdpaee.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtbifbontj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtjbrvwedn.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtbutiybbu.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtlubtmnti.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczwbogn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnijwohpx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtbqujtigx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtmslfeuuq.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtvntygurb.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtijfvhyve.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gttrmoiege.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gthoroknrn.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gthxufanxb.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtzholnfpi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtuysqbnuo.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtqmkfwcck.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtiuhahdst.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtffhltben.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtpjiyuagu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gteguixevc.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtlewnoxzh.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtocyviire.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtjfkwzadr.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtttbjfquu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtcvcbiqiu.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtilbashcv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtmxqdzntd.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtuakdwbtf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtiuccnkkj.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtkhooehvx.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtnfqtmhdd.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtjsgolrxv.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtxnwhqggk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtpsmcebcn.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtldlqdbcy.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtvcztiorw.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtwfquxpcq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkidpkhi.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtnhylhwzj.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtffuikggy.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtuojlqqwp.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpyoiauc.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtqdwchoyb.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmibbdlon.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtvhdxkxfa.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtptfabasj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtztdcvgao.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtxazllfft.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gteckcaqwd.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtjxbmqika.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtckjfrsfw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtxrtqtjoh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtxedecrqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtgmmdqush.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttafqvtut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtooexmyii.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtcsefwiyb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqwtrdc.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtcgvclnrc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwejzgka.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgijbkukp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtoveijbel.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxcagrix.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtddvcreir.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtfvwlecup.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtlauqtiyh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtnezuhnmd.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtuqwxzfos.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtzusivuux.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtntkvsvup.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuukabyvw.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtpqeuyeuf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtpsyfrzhr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtlczcqyjj.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtkcqwhmrx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtvaynhfff.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkomrolwf.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtznxpzwap.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpkpysknq.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtpiuvtank.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtrkcgzuse.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtiguhmhwf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtjohppgzx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtjroksqua.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtnyhzyles.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoxsjcep.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtkjudhzza.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtrggkykcv.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gttrdvzjbb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtlkhbhcms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxoppicrd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoqcsgotz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtrdioxzab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtverkoavc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtuozfjoxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gttwrmtnka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtdmuuqvje.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtapchisqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtegunlafv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtbtirycgc.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtttfsxfmx.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtihyakolo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtaaizubfs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gttnivoxew.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtgsmgdlid.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtszxvfape.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtymxtjzzb.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtfritzzcc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlktrfupe.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdndqmkt.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtbcdjxigu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtihfztcyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtczuapsfi.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtatyaqymy.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpipbsomj.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtlzzmfslh.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtricanfai.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzyweddh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtiudsovft.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtisquzagp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewnixvra.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtrihrvqsl.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtrrvycldm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtqrmievet.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gthhvgpvrq.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtmsgiytvr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtqnnnnrzp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtomxwuier.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtafdhqiur.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gturnyozug.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtijztjudj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gthmpyjbjv.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtjdodlbqo.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtvsamjboh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtzrshdzaf.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtsjvxlhhr.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtaspefrcr.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtynxikrfh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtiwsavrdr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtzextjaku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtdcbopzfs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtrugapvrz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtjturrswf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtcdbpqttj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtkztbvjbp.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtvwutnobt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtdoyrevbr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtliccojfj.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtwpcrttgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gthjjgissf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtvnkceyza.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtstxzlazf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogetnmxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtubwrvlug.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtgfrnfali.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtkvatcssp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtgsoiktlt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtdmizxbop.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtlbzlbpuc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmyardhl.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtbzhvfiff.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtcdvcyise.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtzqwwefic.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtrbyqaqvy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtusoclyeh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gthgkmojqp.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtvnbaekrf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtwqzqmfpi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtivauduah.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvytpnmzo.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkqskgtk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtncdwotaz.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtcqocyjgc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtpkajkbgk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gthojafcrn.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcbelivbi.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtdcpfayfe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gthogczegc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtyyqwoyht.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtrdxnzwpg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtpkfouzfk.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtxhxsfpcd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtjvzknhcv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtkjjlbjou.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtdhyiflen.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtgkkwjyib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gtlkzlfhwg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtjncilimx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtavdabqiu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtapqxldyr.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtpbjaypav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtcwgnikls.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtptbakrbr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtmufddatf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtwnkvtzxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtnjkhcymv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtvbhbtuxm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtyqkabxms.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtcmzofwus.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtauojjfet.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtuskpcdec.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtsbgyzwzr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtnoxfsjsl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtqeiuzhew.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtrdiavued.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkocpdgnt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkwkchjf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtycasesnt.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtkreyfehh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtgutuolph.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtexcayisn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuobxtmx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gttpcxckdd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtnrntonza.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtnzyhjmxt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtyknniisq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gtvvfhemim.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtawirnsns.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtklmunext.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gtrrwjfrnh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtugnofdax.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtzdyiaome.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtwdrujwcy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtwzjwdyuf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtxkkxddad.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtzljpnktv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtwjbbvxhq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtylupywqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtjfwlpufw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gthtnjfvjk.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtswgvadtu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtaafowxdo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftqckwxs.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtowkvchem.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtupveqwbi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtptlzyhpn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtgilgfolx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvttikcub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtaxxwnhng.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtnnbwkvlc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtuxlkhelo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gthdncjpgf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtdgtuoykd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gthllvagem.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrdiwomud.html


<!-- 参考信息 -->