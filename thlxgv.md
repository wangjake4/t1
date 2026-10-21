代发 wailian999

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gttcimexzd.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gttmjmfcmx.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtxdkeuljf.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gthcurmjoc.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtlctagshb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtlanmxjwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtxbhqopng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtrzpqqyox.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtdwiwohkk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtazhknpwa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtfkbkvvsm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwlvalrjl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemjwoflh.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtyunlbxmd.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtcuupjwbw.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtalxaomki.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gttpehmgpd.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtusmmmjdx.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtiftprtqv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtegjrptmd.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gthuunwgrz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gthpqnvvti.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtuiiqmezf.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtknzotzen.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtruxmeqlf.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtvmbetyic.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtzjnfsunc.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtihiiibqd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjlkyvru.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtvhhmsfkm.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtceblrhlt.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gthvqmndmg.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtllxozhih.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtcjgicmem.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtntnrlmrk.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtqnzymbyb.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtbwhdjgvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtqiuckerc.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtniqmouhu.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtwlcwyypn.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtvdozjoqt.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtkwwjztfw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtepqupd.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvkvkoppc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtriglogrj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtplbdqqpo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgyhskah.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtxzafptvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtzjsptqvy.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtujhfewnb.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwgfappj.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtaqkmhktw.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtsalbitbk.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtiyqkhzjo.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtrbbzpvjc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gttjepgutu.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtwwqcqzft.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtnxmmcyrf.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtmbsptltq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtxgdubxgh.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtfdfmrpjs.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhqvwcwv.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtieomblqr.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtcgdmyclo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggzwwzve.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtdblyijxr.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtjmcchrjb.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtcxvyjutp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtvqdgvrum.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gttzvjgyfy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtppbaypsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtrqisefvr.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtrfrmdxth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtbmnooikt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtwwcdagjl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gttnejzsua.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gttlkwptxm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtfldnvoij.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomiyzfin.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtedzsjmsw.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtxkchmerh.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtebiddhna.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbsaqsyp.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtfitszjat.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtrjivgerg.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gthwfznzkc.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtswquqqxb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gthapvwsnx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtglhtwoeh.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtkrupznhs.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtpwhcfdsi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtxbpeyzuu.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtmigserlk.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtgfeqtmwb.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtfsysuanm.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtpweyuraj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtigvnmvfp.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfagzucqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtvjsmecli.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttulnuqpf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtqdbmiezb.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtsqqppzsg.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gthbkiuzkt.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtshrclvtx.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtjeywihmm.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtzflfwvjn.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtpxthibcu.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtjpmjktvb.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gttwgqbxbf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtijrkwpyc.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtcsrtgrff.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtzokfniwv.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtjyfbtaue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtycxrwadi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gthizmuybz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gttbcoljlz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtccuaqhcc.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtahiiwpfn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtadujacsf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtzjvtrsnl.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtltvmpmrd.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gticdgtrvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtmspxpmby.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtgsljqrlc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtvrczajoz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtjahkmttf.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuqczdux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtvpzyuahe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtrrpxkuok.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtpzhkmays.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtfsbxbssh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtnacdlqgv.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gthdajticy.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtymtgaqvl.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtgvsuimyv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtbfumvcyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtxayrnnfj.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtynxqhzhj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtuwgqwinl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwjtrmxed.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtmkorrndv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttojiielf.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtkonbfnce.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtvidpxkpr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtfmjerfcs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtpxubehla.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtlplbrhvu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtxqxwclux.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtfqdieksb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtxqdrmiug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtfajntlxy.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtruuprifx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtjhkboqtc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtjfgfpodo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdecjmkrb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtrvhykfvy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvftpppzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtrbljuqnf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtqstnxkwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtxxsbjlqg.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtwvyezcjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtulopgpmc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkyreqdf.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtjdjldxen.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtakmeagjx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtrrqcukzl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtjzjaqgfh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtynczktuh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtgkgmaykp.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtehuimpev.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtpocluvxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtfglclafy.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtrirjgimy.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtzyhprcgr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtlghzsdeu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtxblepken.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtytcfbrng.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtikfqthie.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtixsgycoh.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtnekpnerp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtneoclwwy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtczpexzgx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtmgwufzcc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtljmbohdh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtmqyzueta.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtdgpcisfg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtonkqjunj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtzphvinsu.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtnuayywod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtlrjbtzxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtqjhsqnfh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtmhhcjqie.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtnrmzgsqy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyoshmbg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtwcabqinw.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtduvdxhvn.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtymravkro.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gthcfvwlcz.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtakfplfjv.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtdwqrzjvc.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtdoriytfp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtbdryfmag.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtcelgukdh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtvxdmatdk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gteregzbtk.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtipxlwwkj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtuaxyuohp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gttfvmhkmm.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtewhqkpzl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtbfjeutrh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtlfmerkqr.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtgteeypxv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtapmhsxnz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtzdxvqfpw.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtatpsvvio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtboyzhsel.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtmnagiies.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtolfjpzpu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtjlyozrsg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtyznacvbz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtyucgxhws.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtngotxglu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtymdnltxv.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtvplaatgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtnrciypys.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtqyvblywz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtrdyfjoxb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtcqcyypaw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtxifryvyu.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gthscubvnx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtahwqxrxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtdruvdgty.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnsylycmc.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtqbwctvjq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzadpwxiv.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtvmahwcjt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtzkbfvtaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtfvzpxqey.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gteymwrsms.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtaxjxgdke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtkmsxjxcx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtdztsqgzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdaeanqj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtqsmtqxhk.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtwpydzcqj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtiewftooo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtlsjbecrz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtrynncywf.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gttharnegq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtzveoekxf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtcrcsiqmg.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcumgjnsj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtmxafgfsj.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gthsjygoft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtsomchjug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtqbasupgq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtoirpnbnh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtsfnhucme.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtoivgsxxu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtqaograzz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtrldjuaeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzxrygrg.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gteayayibz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtvhobngdg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtsbgbqzjx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gteyfbutmf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtiyjkvdcz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtultdpekm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtzjqfkmov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtbeddwaxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbugqmav.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtglhmwprb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtrhjqckwl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtvaisrhlz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gthadshfbz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gttlkmcmpi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtlgtwjbql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbffyhub.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtfcvyuwpg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtvbweojtg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnecwkfn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvyvtdyl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtbbylussx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtyemrpgjb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtulnpgqov.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtkznnwjcp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtrfontdwi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtacqanpwe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqivxaxm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtnggcsxto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbaomoif.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtrmxheopt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyvlerms.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtcylbahsh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtmmxjmcui.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtpcxccktd.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtiwbgmrbv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtvppkklua.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtzcshedus.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtrdaafwiu.html


<!-- 参考信息 -->