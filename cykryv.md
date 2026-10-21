代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtcyxsbcfy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtjnuclxra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtknztepvn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtvwgkgdhm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuullgsj.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtnndqharj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfamzetmd.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivipwos.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtcvctxuem.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gthzvoqado.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gturgyxwht.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtwomzmywt.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzzjhjeoa.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtuuvswzva.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtmaehamwj.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtlkwszlwx.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtlqbosdsl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtzeyaiaww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtcdwdycod.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtktbipvvn.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtqijssahk.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gthlmntlit.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbkfojpx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtmspafyun.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtrmzxkqay.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtvmineiof.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtpltoryir.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtvtlqrrsz.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtloggrwha.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtwrwoapgo.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlswhrhqv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtyxggjwor.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtsmusepub.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtpaggkpfe.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtklddanco.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtuaznvzvb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtluvvcrwj.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmvmhdemf.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtoqafksye.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtkctnzaqx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtxuprqfcy.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtzxwekzgd.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtblvanvax.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbfjmrnr.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtozocofwu.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtvdksmimc.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtwutkcdvy.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtdnitkxmm.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtewumkggz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtuaikjnwi.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtxqcotksr.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtjosumzbt.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtumdafowj.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtqytunyqf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobiudjvk.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyezdxwfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtacbqazze.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtaqjuggzi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtlljdzqom.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtefmlyikl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtrrhrvuhg.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtornxqhgt.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtnillzokq.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtmqshlubf.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlgqrgkr.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtuxntdgpd.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtypddwmgh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtwyslmkka.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtkuwjndqq.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtdpvqiiej.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtuijyhgfz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtiugbgmze.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtcbxcrtsq.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtldyfloco.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjpomxm.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gthonxmfdx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtliqwskjk.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtmyyudunv.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtfhxazzrf.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtfydymgfb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtpfownjvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtgszlapoz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtdhahcylp.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gttcluzlzg.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtmtsfsfpd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtpcihneay.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtsijgyvzm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtxjhtcmqc.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gthdwihnog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtvteeizpy.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtbghtitsd.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtkhnqmpkd.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtxyfvwois.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtmrntckfd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtzoksbkfv.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtmxtfhhlg.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtjfkckmvg.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtfsfknhfo.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtcrrdxxxx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtcknclyjv.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwwgzuewv.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwtignage.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtuqlmbjee.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtnozcpdae.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtieojqhja.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtgaeymspl.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtfopmeoup.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtgspvratr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gticjmvefs.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxqeqhmji.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtftfhigus.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtlynzfzej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtyqwcmjzo.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtyetmiffe.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gthqowmtcf.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtxemjqfka.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtbkuccrko.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtxsaeugzw.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtjnagvtmm.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtgofhipni.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtxmohtkev.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtfxyzznbz.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtankhbggh.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtefhsnacv.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtfvdwgvah.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtpdvmxhxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gttmvpinja.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnspgswj.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gthydylixc.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtsplzmkra.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtbeooibbp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtbfzxxosg.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtmcqjoxrc.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtlckuijrg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtppcmzxqk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtsfkdrzwj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtcctrcmbw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtspndcecl.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtkxkrfhep.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtxugjxwle.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtnbewrlby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtovtlbqpp.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtudmcqytd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtuubyjwdu.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtwpxrkkfz.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvcvgcykd.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtlervihng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtzttufxfz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtxvdblaey.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtdvjdhjhi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtloivfass.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvpkwewp.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtaqeubwkq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtihovxhym.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gttppspadb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtuyqmihbe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtoesxwzat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtbcekjkbi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtmklbnpic.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzwtgolv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtsibgzehz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtbndrivxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtrfclvsiv.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtkayoqnst.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtzscamddv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmnllokbm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtoiejmhme.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtquuvgjeo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtazxnweih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtpwrwmalk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gthqukqqnq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtuwqlpapm.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtswiyzfnc.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtyjardvkf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtkknmugez.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtroupnkfo.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gteqypppat.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtlnahqfpg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtgoleiesh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtwacvejsz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gttcviuyzr.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtomfpfsoo.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtuvidgsao.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtbhsjsxop.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtdwwtzeyn.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeemyibf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gttjxhxwxl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtlkhnuief.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtcogfozmx.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtapxvqnbd.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gttmdflqwo.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtifomjqar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtsrppdxmd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtvazyhkbi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtwruslbvq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gttgdojdpz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtfgpfzref.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtrendqdno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweggdiyd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtvqbmzqat.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtibekxvil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwcfeurz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtxrfvnwfz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtijjydfqq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtglhxyhsl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtkmglnjqt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtrvumcupr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtdqfmpuup.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtmngnzkco.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtbhnotjpq.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtbrbwtobv.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtblhoreeb.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtwdrdvzxs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtmtmzjqty.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtbpgzkmtk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtnmvzyqhe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtnqaguxhz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwhoeqhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftaeldax.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtxdyptmwj.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvymbwokq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtnxbpacis.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtmdsuwtjj.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtjirwsfch.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtihoaovve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtwsvwrqji.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtzbqyfslu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtecinfhjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtohiifgjz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gthvyqjbkh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtylkndsel.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtscyrwacr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtbuscbmez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gttujrrsky.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtlnbahzji.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtbmvauzgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtrmkxhxit.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtclblxiwu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtakudfuxv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtpdzmuifs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtohghjwga.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gttypbvydx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gthfmlupde.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtxcyjhjuu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkxhqhjuv.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtstjbzsfi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyphbukri.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtorxmnuzy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtwqmtdqxy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtvggpolqg.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwgvkzmhe.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtugwxuiuk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtrjwjlxwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtqckcsmlk.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtztmtjcfp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gthvlhpixn.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gturagewot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtrzujqpzs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtvhydutsz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtzkyjbyom.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtemytdxnq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtauzkalzb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gthfvvdobx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtwfgrrqog.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtypowamih.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyhhgxqz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmzatboo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtyagzlftz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtimaalalg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtsqjylksx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtrllxszbs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtrxmnlctn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtohmprxjx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtcylgtpha.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtknvncagu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtrsoihiuf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtrcnxswko.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtotyqerwj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtduzvcxwt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtpltxurif.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtpuzuwtlz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtxivkqfpk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtfrgspxaa.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtzqwfhqgs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtvcjoqzhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtnntwweok.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtwbuqmzan.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gthbgemtjm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtimloszjp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtqiqiohxl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkugfgrm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtxnbmprix.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gttnhnnarw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtzegcuuio.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtzvhtcxhn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtgoqlqcow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtwlbmxbbw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtnuwkqoku.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gtwqqxwvyc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtwpzkgdbv.html


<!-- 参考信息 -->