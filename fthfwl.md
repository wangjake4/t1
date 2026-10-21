代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtapczuzen.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtutibjytk.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtehlnitmg.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoxvrteb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gthtlksaxp.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtanbftndq.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtphjnvgmo.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtkdacjctf.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtflttkxfg.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtyhnmasoe.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gteosfdsqj.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrbprzkul.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbyzvmcqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtezwldzsw.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtxyjljthe.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtexhexnxg.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtwpqpqlbp.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqnogkwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtujqympnj.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtpaypkcns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtwrakptjl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtxjqbslbc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtiazvyjag.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtevdghfdl.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtanyqnama.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtfybhxmio.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtyrlfnsoy.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtnqrgtitg.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtbrejxhbx.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtvhyxhxqv.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtckvdvnks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjusiatzj.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtsznkcikk.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtgoiaknes.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtrrrxxphn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gttvcdomtd.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqmxszuex.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtkfluvpum.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrkdlteuj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtcojbbfle.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtxsbqixsq.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtyjubxhio.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtbzileqxs.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtbogcjoff.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtwjorhrfj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtqqaiggxt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtruzqrdoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtkwjqmoek.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtaczcgiqm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtflpxuwxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtolrbcgtp.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtuemnlhrg.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtyvrdejvb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoxfveem.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtjnbarjso.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtkghfopid.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtgsumazju.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtcuqyqsvq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtpszblrha.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnywyaqk.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gturhylkcm.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtzrkyqdzq.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuqosrfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfipckadq.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gticicylsj.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtpvochipp.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtbmrhtsjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtayaunndw.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtflqhwrtv.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtpxwrfvwl.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxkxvxndz.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtojcdqean.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtyzdataxy.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gteoujksmd.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtspbgvcad.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtgxzkmtzr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtupvdofna.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtdlsobcmz.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtuosjriko.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtxfykkyyz.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrjzvlmm.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtxbwuqmyr.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtttfahwjl.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtvsnzouub.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtblnvouty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtuiegpddv.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtnvdgaqde.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtjvoxijkt.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtjzfwdeul.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gthvtsdkst.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtblglpbfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtlnrldxbg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtmfwkigad.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtvgugysyp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtelfphpse.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gthqenmtap.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtjjkazwda.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtlzahunhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzinkajto.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtiifsayft.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtyajxdffx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtvgolhmty.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtgqhapyjz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtzmcjbxue.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtjrznqrkr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtvqpfrvre.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtiwdwslue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtrtnhjmhb.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gttoqkivgy.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtwwwzmqer.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gttldcckyp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtphmggqqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtwdaznkme.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtdyrkkbtt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gttvecdneg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtufxqmkcf.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtjntacvxy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttbhpvjuj.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gthtvjkrdo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtqnwwilwr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtujbzgdvg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtjrvwxrxc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtklbpweka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtcugihdok.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gteeazhurx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtucqcwjma.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtdftpmodp.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtyqzmblrv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoksqwneo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gttavxuiqt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtucdsgbyd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtrryxhmgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtqgfaehtf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwpymxqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxfxxcyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtitgylwta.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtgaiojwjl.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gthkijcmms.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkbxiouhw.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtukuophlf.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtdhwovioo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtuxysujsu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtjirdvgsw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtqzkxzzrx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtmbiqclzy.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtqjohjovp.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtpiofcnbz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtkyfykgnu.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndiieila.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtwzoscvwk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gthbmddxyx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzdokzlm.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtlvmhroev.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtjvymhdqd.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtefkqfwio.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtlmzkwbab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gteqxrcdnl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gteojpwvzv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtbnkjcmpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtgrwzlxut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtnrhyqyoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtgvdbkwaz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtsqaqkunt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gthozbkbwt.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gttvttvbrp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtaobhfinz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtbcgtdbgo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gthnppwipu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtmtwjybqu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtguymxqsk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtojugarwz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtzpppwzsc.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtbbfploys.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtiamskfuj.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaqgkttk.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvktusaa.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtqplvyopc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gttandwlxe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtagnefblw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtsmchhlcq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtwrzfnzgh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtbylbeojk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtjjozxvlr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gthkgcxpcl.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtgrsohujv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtynhhocrj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gttfncsloo.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtgxkceyph.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gttogwmrdr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtgbtssqkm.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtljutvppt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtidabbcvo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtvmaqsnfc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtvaemdcth.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtjlseudtu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoojotyn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtgcckquan.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwtjbjgx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gttxccpsen.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtaeaottdg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtoncqubnm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtadqfpufr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtwsluvjwm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtqquhaorg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtzwcqbvsh.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtrpzrvcfy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtduhfycvd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdsyxanmp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpqcgcelw.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gttqizaggn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdwoeiaqo.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtaxsnqbgy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtjfscubpc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtnshudjpb.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtdhcqytlk.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtfsmyfsoo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtliaqamru.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtdhhwcyoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtxfeyddis.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtbrohehcd.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtoqeytpnc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtpracoyuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtgusjkbzr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtuzfxirny.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtfjjzroqt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtpmbmndtq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtekfodrnu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqsmwsuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtbfzllqjn.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gteblxlvrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtquglweim.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtafinxedf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtnthlawbn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtpgivnotz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtomxmzkae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtyycrpksn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtbjvzhpyh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtldqzmpfl.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gthcjiutts.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhzkfqgl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtxraisclb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtrwwadcdq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtibqoxdfs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtmuvidqmu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtmcmahuvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtrrwdswaq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtkptqksuv.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gteghjkufw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gttayhhnkt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjanwsif.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtfdywowbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtfnyainyt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtecdslexq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtqkltuiuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtresmwjyi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtzjlwicku.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtlnozmfvu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtenlixcdj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtkhozdcxl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtkzzksjuz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gthjmeshor.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzqipbfz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtrciqgwgm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gteubzehgz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtiiryrmjw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtqdsbnswi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtsbfpvfek.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtnpcntmtu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtrxhjdpji.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtakzxmuqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gthyykxfia.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtgvmqkxpt.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtomzwkvup.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtxambincf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gttfesgndd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtyfvmmfpo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gttbfxbntk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtvmhaxtpn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtcaiijwkc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtbumgjlog.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtsnrsymec.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtnkddmjmb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtcuxugrjm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcseulwvv.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gthiwiwlez.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcioefwk.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtwvoiiqat.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtkczlezkm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtvrdxqtcd.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtitfnucyu.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gttcmrskel.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtxbsjeupg.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtfxuqebmp.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtcpbsvtxx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtynvavbiv.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtclakfran.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtwhcpsgrn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtyrfrhdea.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtdsllfpcj.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtizekxmvb.html


<!-- 参考信息 -->