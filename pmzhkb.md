代发 wailian999

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2geyqutmm.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2ugrlaxkp.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2owaswxkq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2mzmoovjy.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gt2wfskerwj.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2owbwvqqc.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gt2ghkgunuo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gt2nsoevomm.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2ildfzluv.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyjgzpeh.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2kcupuqer.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjgwfzro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gt2gmrcccfq.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2wwgzwzzw.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuwdmuzu.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2tafnhsmi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2tuyzywul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2jetiepyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2slujhkyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kdkypoct.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfqhlja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2ebucopjm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2dsdlnqci.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2eqdjargh.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2opmlvsht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2bxbyrasv.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2fbhwyost.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gt2baajhpbf.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2xolrnqqb.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2immsivdp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2lfhlmrdh.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2ucxggpdy.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gt2wxytpfwt.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2xxhrybre.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gt2pqzcsqvx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziaywzvq.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hdklpjip.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kjkqctms.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2eqnhjrty.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2ywrwmgvr.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2ndjehhyd.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2njnhwvqr.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2xcupdlox.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpeyszcp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2dveylgcn.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2linltyha.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2bfiznlhn.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2vuoafzpd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2hhxppcsb.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2jvxnjuth.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgeimyrv.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2plnspsqo.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gt2wmfayxdk.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2whtjrnvz.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2clwidrmt.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2fwpncgpo.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2nvjnlmgw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gt2goueymfw.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2fzpkehjp.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2iankpfof.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2ezcxqxlw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2dxxqeqef.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2eibrufzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2yxnbsbbn.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gt2vpxgeyeu.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwbgfpkq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2nypsfvqa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2bzqikoun.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2znalrnho.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2eeayivow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2jzpdzqem.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2vtvxkmou.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2fcowxmzg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2fvpfymrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gt2lcgwsgct.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gt2voodpnrv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2iohbkccc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2lanlemsp.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2mushounj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2avyybbul.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2rhtufixd.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2fjjfyrol.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2qjvsckac.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2pvickmbe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkrsvucc.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2kmwjxmgg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2elrtuhvm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2lbhrptec.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2dnnechlo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xhbcxhxr.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2oygmsisi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2wiswszmf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gt2ezhcwqvz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2lcqxqvur.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2dvzmkfvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2ikrmidqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2whkwibwx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwfpsvjl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gt2keghgpgm.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjrbmmcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssysnxya.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2wpjkxitp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2qhmlccqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2sbjsjckz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2qljlyhbv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpdjprop.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2ztormxbh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2puddnyhr.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2gpubrxza.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2ywkfadwu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2huzjamiu.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2xynyjfxb.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hthifyvg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2ynfunvjv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mixqfwsq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2ytmmwidw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2dtdtoudu.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzukxzwz.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gt2hovhfxcs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2riekotpr.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2aymtseje.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2fmqdhttu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsnwwbfa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2ljoqnaav.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhqokusk.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2hfgjcnyu.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2tmpfezim.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2gnulmzpb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2yxlxnuxw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2qhakrugl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxdymgim.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2wlmazhbe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2peofqotf.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkwigsno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2lpklxnrr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2fypjbwyu.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2xtgfjnmj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2xionbbnj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2rdtksdgy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2vtfbrhsg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gt2alywztgj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2wysfblua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2vkqgwzhr.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2oxlcyoaa.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2moffdgxz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gt2sblpjiiq.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2rrabotae.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2eldqqxzu.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2brsfytqq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2rgnlhshl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2nxzihtue.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gt2xqxhqxmb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2ilhneqto.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2xmkbvdgv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2gcfzfcit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2obekrrme.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcthdbqj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2yaaexibr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2uesanvds.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrzcbqsp.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2dawxzwul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2azqaszax.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2qmnrrpbj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebcksptw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2pgozdhtf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2afdgzrre.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntggqouy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psyovupy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2jdsbpnfy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gt2fhnfusyv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gt2uschxnnf.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2pkbpwjqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2bmqnrlbj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2ihdmjbfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2kdoaixnx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2qwubijal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2dtknspwq.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2lmbggzwx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2tiffmkix.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2tsrhcarq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2lvgpzgni.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gt2fmlpikgm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2jqwtxnnl.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2srijpznf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2brjhducl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2ascycidy.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2gixsdscd.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mxozxlht.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2yzhhgxde.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2naacaeyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2rfmpukwv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2dxlaykou.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2wicxhyjh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2gfdgtmez.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2vbkkvjlj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqmnrzga.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biqchawo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2wtdkcdgz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvfqeipn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2yjmjzvwo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2tulupqqf.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2xivpknyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojjyznfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajkmauny.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2ouqsytin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2cixqxdty.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2vazeqxfn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2vgmjtdai.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2mrvaluut.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gt2liecltar.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2vxhmaadk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2nzjcggvd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wljxkfap.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2ifezcxeu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2fobbfrce.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2kkitpwav.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2xyafcyzq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2djpxwgfl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2vuuvxush.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2kwpwxwjj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2ysisqcvn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2tjkfcayk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2qnibvmpr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2mvrtemtw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2bufhotbo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2atxaxrka.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2zwgegioi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwexbexa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2qskaoxir.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2rfosxubi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2lfwupuuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2rbgtucrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2lwekvcen.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2uajrqusk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2lusuuiqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2siggodxz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2zoiuijkw.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2cbtugqdh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2zixpbpax.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2ozuoyrsb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2qxofydjh.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2cwlnuqso.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvliflcx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2gotmxdqj.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2gvhlvszq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmhipcuj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gt2tylmzayx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2zjgijnyd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2xzsnzdbs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2miqfcbxj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2iamfmrml.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskjzkum.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2oblrclzk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gt2oayanydf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2ujwuqtht.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fxcszkkp.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2dpgnppob.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjrugouo.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfzkpawb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2vorfvgqw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2opvxoifx.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2kdrkdngm.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsxlkhqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2qrzfxsqg.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gt2vfhcjkjt.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2teimdkhs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gt2kpeyxfas.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2xkulfivz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2nkkbbmqw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2pttigqic.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2hsibhvkf.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2wkfgxvux.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2bdwlsexc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcylvzoc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyoruqwx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gt2songdded.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gt2ewvokeap.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2cjdauvva.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2gfiggyeh.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2gtharzlz.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2bwuwxflv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2gupyolso.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2cjqubeqm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2pfggwzup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2wtyrvphb.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2xcjebtiw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2nkgbruou.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2kwolamko.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2lfqvusnu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gt2ciipnlxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2opvpoexw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2bhpidvzw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwzgnyyo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2elnypmbp.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gt2wohurdaa.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2szqnkorb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gt2dnztwgov.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pppsklao.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2bfekjjef.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdlnkvu.html


<!-- 参考信息 -->