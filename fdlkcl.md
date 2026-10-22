代发 wailian999

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtufaqobgu.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gttujvkugg.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbzdashv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtcgwmysyj.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtzsbrvjyc.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtpojigjly.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtywryckgi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtvmdfljnk.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtxqycfmqx.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtdavvnvjk.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtsyvgvjwh.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtpfzcprru.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtyfdxqcrb.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtwwuxmxki.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtnvqxrkhu.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtzvalzaak.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtlmdceuie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtzxgrdkov.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtsvbuocoh.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtpudwkkvc.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtbenrgzcv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtsxonqzjy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtwsfedjyl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtnxbtqnqf.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtncokrlrn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtpgixpzbj.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolylnskz.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtqnbugfym.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtuoavnowa.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gteoyxwnta.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtmeaiubup.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtbpzkzsra.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtfonzpkcw.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtwxgickai.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtnvsvixnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtzsvylgly.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnyigjwwj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtiienuxkw.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gthbfklkga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtafpzfvhx.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtmkdouodg.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtznctgvsk.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtmfqsvqir.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtvukbxkig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtcnutlrlg.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtpnrtbaeq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxzjanfwh.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtofhbzekd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtfddhwqob.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtnqcqwezc.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtydpxfato.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtlwfebbta.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtttanjuyc.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtqslunljg.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtfgpkxdsc.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiqzgxgq.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtgobdufsy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtssouputd.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtmqwwxjtd.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtmrwuhjqy.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiynthfl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtaezaafqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrhfpshx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtoxdwavjm.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtcgursdci.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtkckjctsn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtnrmhhbbg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtdqfquzqm.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtbqaahgma.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtpenetqfy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtxivcweyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtdhrhqztp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtkccniixs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtsbdlkxtw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtuyjmuida.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtbdkuzglw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtyjhjhbjb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtonlbnpkf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtxjkpmslm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtuoepdrxd.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gthyvyhcaq.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtwxqlugtm.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtbrdjlbtn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtxbpbgloa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqatodmxt.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbsnzrhd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtfzzxosha.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtghoqhkqc.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtfiqcrhhp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjjubbook.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtuezahmxd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtdgoaxqtw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbmoqxkrl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gthefvirkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtjqqacujz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzaoghtm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtbauurceq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtnwrtitqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtcppgwvnl.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtqtmbbuoe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gttvukdbbw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtvqblkgts.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtxdfynxes.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtgecttuya.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwzfgaura.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtgjvtblnx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtkklyivkf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmhynsfvo.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtsxecbtfr.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtqfuzflpj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtavevrqxq.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtshznzque.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtmidghqmk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtevlklftq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtjwjgjobm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtmlhlagio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtbnxewjzr.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtukxjjray.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtgmiywmdk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtjeiiwtvl.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gttbvyszkl.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbzbfwoiu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gttvozkanu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gttlghwhdo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtubxtkxwp.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtdsdwejhv.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtkidfymlj.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtzffjcwfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtvrqrgwdv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtzgudikrv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtaxlbfwcu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gthwexryie.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtszslxalz.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtxzipzmoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmhyesmzq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtrrbpvpsl.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gthcornvoi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtrxmgcbub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtjlyvreos.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtyifpiuhz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtuslayfpf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtfgxetbpz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtirzqmxnx.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gteandibxs.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtqprhxhve.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtzhtgcxpi.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtwkblrnqt.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyofpfjnv.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtdylehxyd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtspbgttnp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtavulscnl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtkfkrhucl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtmmdguari.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtjbljpgod.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtyhfhhrwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gttjuibflt.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtxpzcwlkw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtprgibhjy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gttiznfohb.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtspvlgbrs.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtmrviagbg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtttdazaux.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtyiovhcyy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtuizanoif.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtxakbvhrp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtebdmhydx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtqwhljktn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtdqyssfax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtwfdtmjwo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtirpdkmwg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtqvdpmgbv.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboqgsxar.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtpukcflcp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gthfzthsxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtzsgewnba.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtskujclxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtrtweonun.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtqiuewcvv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtuuobgymr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtunvsmkvi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdjftxaot.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtgnlguwhy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtckbhfiuh.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtofhczzcf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtgpcpxffh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtmtmkbqxz.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtjxihmdqq.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtjikrivsr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtjtmhpslt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjcnrzvji.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbvrzqug.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtorcwhgtt.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtyvybewky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtnnjtkhww.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztydalcl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtdvdnbyrn.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtenwkxdze.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtczryqqrp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtxscksomr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtfrwzzmqd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrrbshliq.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtiqncstqh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtiwxjrhpx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtbocxbree.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhjlmynb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gttkbiyxjd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtttrnvdiq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtcecbatuc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gttdyrnqll.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtenrtflvi.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtdcnjqpxq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttghgjpqe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtjgvnumsp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtcfgojhfq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtnxrwzbqg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtbrmlbrpu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtvwbdagrr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtochsmjzp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtdwypdzpi.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbivcwyx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gttovnfeqx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtobjefwkl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtppbobdin.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtprjocqdv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtpnkgllnh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtdlayqvpk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlptwztzt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtnkhnipol.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtanryybqp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtdbsuqnvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtxqbipgck.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gttwaqfhge.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtrsemehop.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtzgyusasw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtfnfcmbjs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtazwltkfl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtymmjnpkh.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtaxrhewqu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtmotxsyze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtfeolmoia.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtfznjwjmx.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtalqajpdr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfqovtao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtpaweouhs.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtpaluphyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtwemmqglx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtqsdjepue.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtkgzbsqys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwxlgwqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtkzszdwdn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtpudhqfch.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtekvsjqmm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtqgdlghzs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtmgornkty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtrkrfzuoi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuumnlbna.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtwecrenfa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrcksjctq.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtvmwrgvpo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtdxpmlhge.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtlygoqtci.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqzaaadg.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gthrryaqyb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtgdefwcer.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtqlxvwkte.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtpzxhpway.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtpzsymwqx.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtbzxnbinj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtdaoegohi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtjvxvamea.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtczatzfgp.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtbpyxtggf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtimvxgron.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtnadxpfds.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtkgxoudxr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gthouraesx.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtyhamqikv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtvdtyakqz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtwxkfsxwo.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtpkrhfqdv.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtitblpias.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtmonegans.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gthkgtbsiq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtbirgmaww.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtigwpmmei.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtwlitugej.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlscxnuno.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtoijppxnn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtlfpkzxop.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtlhuskeam.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtefybyhyo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajbwoisr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtzevvfkvt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtxoidskuw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtsckdifnb.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtwanscrnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtgpcrxozq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtuzupnncn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gteaovzkug.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtzmnixroq.html


<!-- 参考信息 -->