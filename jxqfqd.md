代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtuvzunhfj.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkpndsrax.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtyubgurhq.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtlaiqkdlw.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtfnkkesrz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtpjpnnlqf.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtnqogqtlf.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtsajgyqga.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtaceqhoty.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gthiqrtrjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtxebjnatx.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtdtvosafh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtiuppctgf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtoukpnjzs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gteyunyjja.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtalbycedw.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtzogogxkd.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtlbrcwkvl.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtenbragln.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtapdbggxv.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gttumiylpr.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtgwsfnwtq.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtyleqnxfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gtloscgphv.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtuywgweqm.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtgqdedvog.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaecwntri.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gtdzkpbsww.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtuypdvqyk.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtddhpmuux.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtxevbpglp.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtvsypkste.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gteejqrvck.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtumaeknlv.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtdqbshccx.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtmslhahgr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtaxsipjsu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwezloghq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtmzqbtazj.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuybmydru.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtuyzchuko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtxhyvsxzm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtldkninxs.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtuursrper.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtmnspfifn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtiulwghdk.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtwcqjiuhs.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtcmswgoap.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtwmpdexxa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtkbaritdc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtkpfcwqdy.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtlkzpvowe.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtjkhhzhje.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcntfvfl.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwjkajwm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtwcnywxna.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtsvmqxtxd.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtiybpqohw.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtuykqhycp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtabrnrbvu.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtjcbcxcje.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtcuynxdvw.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtohwegxps.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtzshwhoua.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtqfigmtcw.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtsiaucqzz.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtteftywdg.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtdrkinndz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtsrcpeyaq.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtawchehxc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtfxgklegf.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtixzvqtcq.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtdfvlgshy.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtzijnawhh.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtdkiwzyif.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfnypsbz.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtijewpgug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtdnhlegdw.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtzzvmyerd.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtonltngij.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtgoqqsbpa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtmvdzyjkk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtthjqrgii.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtrdmtpqbb.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtgsspyslx.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtdjkkjdze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtpydnpuul.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtjvtxtoqp.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtleudydck.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtpnoibqux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtbjcdjzeh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtqcxekowb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtqpirzgru.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpqljwrw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtriypidrv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtuluystor.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtqvypnscq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtvrwvpsvm.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtnlzhzuoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtuqdaakpz.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gthmyqbmzf.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxtvagwb.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gthrltteve.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtdcecwznu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtuosmpvhd.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtyysodsde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtpybsdxjw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdthjxqfx.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtvdgblnno.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwjlnqgkk.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtgeilhuwn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtyzbpxoxf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtyyfrltqo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtryysdtfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtneqvtogw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtcthcmbpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtejfpmgtg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtjqhejumh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtixfqtptg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtkqdxllpv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtonfwqfdf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtlzunwhiu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtswacffis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnttoigox.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtrbvtkqdz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtkjsrgtnw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtqbkysrff.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtugdzdyxp.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuaymlls.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtpqxctrhj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjqhofrfv.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gthsmmrfvx.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtkfqujxlj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtfkfkfltn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtranlmirb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymywkdmf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtbfstcmsc.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtjhknxlrx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtfktmrvwa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtsnkxehzs.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtzavdifgo.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtjrqnfmqe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtxxvkboyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtjgtuegll.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtrvpmzgbh.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtpkocjzvh.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtfbcfesmk.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtfskxsarx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtplihexwp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtynvxqitb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtvqxqjnwf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtirieegrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtkehnehdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtcyebmokr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtiunmqwhb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafuqsims.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtwwhlcqia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtujnzzwtu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtbxutahbu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtxagsyryf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtspoqhfiv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtrdvwlirh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gteuoicdrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtksbzdmxf.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtkamgzkfs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtqntxypbt.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtbdyfeohj.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtzlsmwesz.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtvjdjveol.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtnginlfmm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtiqrqyfgc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtxvafclbz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtvzodjcsk.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtwehnnikc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtkyedkqin.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtdqqqshlv.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtkqkazsve.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtjapdjgjd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtztrcxykv.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtmnqsirku.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtbxcoxlcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtxavgzvvx.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtwokqjoqt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjhhkwdb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtgvqukcix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtylyawqhx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtwrjjdvwm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtejzmrqqr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtfpgwfdra.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gthvlvioee.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtdahfwils.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gttsxmguot.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtvqlchbci.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtcavvhodp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtypaxrcnx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfybggwer.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtrwlkbhxc.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtvskkiwrw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtqgpwpjut.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtwifgpczi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtruzosuvc.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtnhfgpbzx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxqhvhvrv.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtjdyvelhb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtuskksceg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrllzjpq.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtlnosrwep.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtduergvjd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtezbfizrk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjcppotw.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gthduzmhcz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlcvoosw.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtlzkrcijg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbqttzhdp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtywaaejib.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtftqqkwzt.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtcnncwjyq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtjcfcdonz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtoecnmlaw.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtgfruvdct.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtdmcjoqpt.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtcklnsqja.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtgxirtrbb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtjjaukdgt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtvbhleitt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtqtvanapb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gtraetmdfi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtiikpevpv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtelrvjihw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtfqrzbpia.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtawocxhew.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtxcoawkjr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtstqjmxar.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtvfzwqgvj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtnyztpoil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtogtgvuog.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtovutxajy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtjszdkjtj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtscfcndey.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtxvsaybwb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtlgyiiynv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtbebevkss.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtdrvagbfd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtnsmzqsqg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgttmwkgq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtmzjoyhln.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtlzffegzo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtponfnynd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtvjuqvbmz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtvbxwheub.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtchivwamv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtnmdabqie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtqgnpruza.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtsaqhhjye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtknuqcwir.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtnbuvacag.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtwaagkysg.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtowxebunv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtpkykxifv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtyszxlrci.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsedczajt.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtgemklnaa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtdpghpiyy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtyjcizgam.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtkhafligr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtvnwdfohk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtvnrvtwvh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtwxjpiaxl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtiylwrryp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtmrtkybod.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtkeazuqol.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtnuunzapb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtmekmdgrs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtgfiiabbx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtvovdwied.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtraagfarp.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gteeqwkrdg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtylwoyzcu.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtbcpxmpea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtddagdrxo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtkqlhbucp.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtkdshvizh.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gthovingfo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtwgczspdz.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtbxjrdsfs.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtbxnixezq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyutfzgp.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtwllbwvjc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtqiswqlqg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtjchrurpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtgpievirb.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtraxilrok.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtgveoslxd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtuodgajdy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gthfgdzdzo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtrzdtqoif.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gttjwkoxrf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtwgsabaos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtlmgsmsdn.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtrlcbhgfq.html


<!-- 参考信息 -->