代发 wailian999

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtwgomtbqi.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtotckyrmk.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtnciklglq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtxmdcwbni.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtiuodlmoi.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuayifed.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtgjqrture.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gturclwlpd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtfdhieuss.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtrdfzanmc.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtmsyyuovp.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtrklqyjxc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtttbvzcct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtryuheean.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtxqkvlyzq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtwlxdpozo.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtgqqfgghi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtagszsrtd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtxboncwdd.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtsuzucvim.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtyzowzccz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtqdwkbsmx.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gthbwxgmms.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtatohhhht.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjfxmeik.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtnkrhczad.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtzephrspd.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtbwblptji.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gthfcfscwo.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtoyxpbhoc.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwuimpeu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtoikpheqc.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtqengrjap.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gthgruwsyn.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtihfigvsr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtzvlojulg.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtccqoovet.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gthbgqxufq.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtppunpfmt.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtfjqelukr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtcxyninbr.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtggkhqsfv.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtlhejplut.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtcsscjyqb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtzunlybsi.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gttynwynoo.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtiynmusll.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtwdkdwgue.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtpoghbvxd.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtdiqgtrjk.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtxkqvgqbo.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gturpbpdhn.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtweofacsm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtuxeypndk.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtwedpghxa.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrjjkixh.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtxcpczrtb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtxqzchnkc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtkmcwhsrc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtqabpbgbz.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtpjmrzaah.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtlkotntmd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtqxvnigmp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtvbktcgyh.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtstifzuys.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtdprvqbhz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtyzsdmsjj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtogbqvest.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtzgizlbmy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtqpobsgyt.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtjohufrwm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtxuiqckhk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtmsgovkfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtecwtphbj.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtrlsbjskx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtizzzznur.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtmiwsaeop.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtnroqkwrr.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsczlgwc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtuvvxnpjz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmotieez.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtxkydidbd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtzllhnkoh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdjguxwpe.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtpbtttkqy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjcefkeyl.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtvshmhjkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltgtomrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqzyrbnmw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtoyxjecus.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtnlvfoqgr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtajwgslxs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtnpqglqwa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtrlutmplt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtqyicylln.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtfcyzhmcx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtnzdochfy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtiyuuvktl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtorkoxzyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtqiilyemx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmykklqgt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtiptvpdpm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtbrzypvhm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtfzgddspk.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtbkrrmavw.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtenekkuci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gttcnmlrab.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gthbrcusqh.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gttticanlb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtgbdlqrvl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqcwpfny.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitqmdjlf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtlkobbasd.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtdwktesvo.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gthbskchra.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtrxptbyzz.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtxdkivast.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtlgnljcdj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtesajvtvn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtrtqjreou.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtgtttqrnc.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtcozzlhmv.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtdwwuuaox.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtdcmgfahv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtdnjruayq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtbqmonntz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtyaasvzvh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsztirdhf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtfphzjehj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtcsiwkuru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtbznkodxi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtckoezoxa.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtnbbvsqmy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtzyhjqhat.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtzqpalbqr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtnbqjwicf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtjsnpdhfy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtacphpmma.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtnhiiferb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtfswihxlw.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtpvwkgixv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtqeskltil.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gturabudhq.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlkjryinn.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtijmjpfrl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtrkhuvkhq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtmsxuuvah.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtfypizlcp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwpujjdup.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtjmnnbjzs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtwzzykfps.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtaugpawyp.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtljkmbu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwgyunhk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtewimibjb.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtjzsnwxwv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtdzwneaun.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtyoqnjyor.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqscqoml.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtjomqmdmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtwttxocqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtpvwpexqm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtqwarkxgn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtgccavinh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtvkdkhgyd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtmtmbmssk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtwbjwtegu.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtohouumtz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gtvncxefgh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtzqeazzmb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gthrqpqvzp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtnwtznnrg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtzhibfkxa.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtuzttljqz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtrenukrbu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtahdycvyw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtepztrowy.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtjfvsczsl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtopijgvix.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtkajddclx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtoqdzavab.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtkaccwmgm.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtdtszscbu.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxnsejyxv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtumbvsvil.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gturoiwhqn.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtgcszqbbg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtlqpyweeo.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtgopkcxaw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtkugbuvhc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtgmkvrhal.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtlmihrfky.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtbfjkhrvr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gthqsrsfit.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtqenutxhb.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtzewqmgsd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gttkuhfagw.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtmmfmugyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtehoolnki.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtvitckher.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtdhqkcqnq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gteaphuikf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtlobkifrh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiuzftnb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtlqvjepsm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtwtdwemwd.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtbamoulto.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtoyowwhzv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtujsxsjcz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtbtfthcdn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gthssrtxde.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtzrlhehgy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtdtozmdun.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtsrueatiu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtpmvkytbx.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtbuyotgcn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrfcchufx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtuaprislb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwvwjdjm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtuswinjud.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtakkstxam.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtiwplkmdy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtwepeyqvd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtrknwhbht.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtxgpzcwsl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtbmmwjiaj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtcjmzoxtp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtlmbmwmsg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtrwjzwaby.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gttelvklgj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtijlkvdiv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gteremolls.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtwtoslbgy.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtcashccvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtddlmvcoo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtuzugyjzq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gthabfjvoc.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtnskxemut.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtzbuqvuro.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtvldxbxpq.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtwnpevblh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtczrwxids.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtslzxlxba.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtffvcenvf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtoikzmhdf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtndtpmjic.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtvsxsdhbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtwrxlajyf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayneggek.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtxorhibaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtdgswwmwn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzjkqqjkq.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtiayzpvfh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzzprualf.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtfmgpznfa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtlsfgdnlp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtwwzyebob.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtepavzaos.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtdhwymxew.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtvkfsjcph.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtcvkgagbi.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtxgfqguxv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtvumuyhhf.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtaqmkkxfd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtcqumgcjg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtagqkynwc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtlshkghfr.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtsmgygefa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtwgwmyupo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtyzlpspnk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gthodbzgop.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtdoaxtvkn.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtixviirtw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtkbckzfvi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtcjnbaqdm.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtsgpftgch.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtcmmahdpn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtsompmckd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtfikohwhz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtbdwmfozy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpapirly.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtcnngoydh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtxiuadpbv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsfytwvx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtyjoctzgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtfeuzedny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtpwzvusee.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmihuspve.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtkqizrkzg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnjrogqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtfkynives.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtgkveklzc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtdtbzcrdn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtwxwrblck.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtcfvzdlkh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtkqrmwpgb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gtgwmobwha.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtqchnuchl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfhbppmi.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtestkfpgc.html


<!-- 参考信息 -->