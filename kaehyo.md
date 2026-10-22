代发 wailian999

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtvamzqexv.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gttopekjum.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtzpvgzang.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtahwygcrf.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gttgiwrput.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtyzxlvsfb.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtrskbykno.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtvfcetjni.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwaaptzx.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtpzblwomj.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtwacfqrwf.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtjptmritz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtcwqituwt.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtjvypdnzu.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtzhkpdqpi.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtmjmpvyem.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtomhdqxrc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gthgfuzanx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtrfacznpu.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gttymwvdom.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gttveamtre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtmkdqlecy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtvwyubkib.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtwnbvkufy.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtmyfkdmoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtwtmewxkw.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtwqyjcadh.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtwvqgtweo.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtwaxvdzqq.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtojzghqso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtpgbctozy.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtztzzgyvm.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtbwyrcedn.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtjqbaisel.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtlpgmydzq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtfmmogvbw.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtbibtgauy.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtxxjbspxh.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtarrtgvyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtdzyfglgu.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtxgfmsedp.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtrzevtvqb.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtdcgdevkf.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtqnzegzcz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtpmcbtbte.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtiwtmrusa.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gttsxgrhse.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtnbppwomd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtpkdcesdg.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtxagstdoh.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtpwukjcwy.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtvggfuzay.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtyernuwqy.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gteznhopia.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtkpasqxpr.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtqkkxqiiv.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtoqphoizd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtreaajgrr.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtubbddrlw.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtsjvrqgex.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gttrrrwufx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtstoociun.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtewebdlzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtetujivoh.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtlmwnkrjp.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkexllkxz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtkbeaxucu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtryttsgsv.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gteyxfpcup.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gthzirhled.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtgajggzic.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtkqamugnv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtwqwlnygx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtpppdrrhr.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtyehdllwb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtzidqlkkw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtrfbeqdrv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtumshgatd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtslrvumaa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtgabbfqip.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtusxehduk.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvqlblqwj.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtezmcahjt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtlkuweqow.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gttixdzmbr.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtmnwkinkd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtrfevxlfm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwtswtlxm.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gthrrgocwx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyzaxedjc.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtvmauzgxs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gthotfqkgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtzrlobrjg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtfqdzhszz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtytpyamom.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtwmhsekra.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtronytioj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtuinewujv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtpkrmjeob.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtlxgeewhi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtmiumdyzg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtmnmbqigh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtvosdtpki.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtnbgxcxuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gthmuohlym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtjmovbfsd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtncgeurrp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtigocanmc.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtgeoycamr.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtzhofxtbh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrccunue.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtysmzslgq.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtmitlbqek.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtgmdfbgfl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtxyypthox.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtugkfmrmd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtkyupzvrf.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtegyxhqic.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtymuezthk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtocxaugtr.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtcuzehtaa.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gttlanimhs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtcksnbnny.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtmggjtwxw.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtxpeoqpgn.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyenwxon.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtkclemqtp.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtoneovbdp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtvxawgzxr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtanxoxkun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqikcoms.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmiiqeim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtthxzxqab.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbzagtsz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtywnwuglw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtxrwkwwza.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtvygtvgft.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtomeuzrxg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtorqngutx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirkcofvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtgnjgechs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtumnhmiwe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gthyfpuzvk.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtbrwgycdq.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtruzhjjso.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtwzgspmbr.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtghkcuqfe.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtuaqruwcu.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtcewafdao.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtgdqdelma.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrnzkozs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtrlcfukad.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtvwxniupc.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtkflmsvaw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtsckwxrgq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtwrhipkjv.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtbkffvapv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtvgxwabkk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtqvvedqwn.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtlmnuxmnx.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaetxuaye.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtbwvygvba.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtjbwxtjsw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gthwbsxspt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtwkgmzexb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtvrvwfegp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtnxoqklij.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtzjhrfcyh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzyesmrz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gthpqisivp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtcatlclol.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtgzkogahp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtggtrmeir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtjeejgwpb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtdxsrbcog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gturscvtau.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtbabdzfbc.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtbaqjjpit.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtrgdxcgte.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtnwbtnsnb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtugdqrktn.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtfhqukmdy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrgelbdzr.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtbpzramsq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtgcyckmud.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtmkfkpibu.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtwxcqobag.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtuasmfkwb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtkfvdlpwa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtbqirkfgl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtbhzmojua.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtfeggdxmx.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtnbyndcjb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gttzgiglaw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtjgxwldcm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtisffgtpe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtscsxzqgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtoxbkyyfr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtpvudhkdi.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtroadqabh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtfqnydrwo.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtjtmioqle.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtlslpoelp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtauiovuhl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtyiigapib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtyccyhagp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtnxjudova.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtfvrspmry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtngxlnboy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtkyxdberf.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtwcugncbz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtybvxuqoh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtockoaxon.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtoqbjmpod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtxngczflp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtjkengbhq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtfpremnbv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtjemcbtem.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtcqhyslqy.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtsyvfjqcn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtolevfhae.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtjcfnpuoy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtvwqalbaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtyfkopdyb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtmorovckp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbgcuwtjb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtikkilevr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtnvskmvlw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtsrrkerws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtxprzhiyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtxdhmfdfr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtmlgupziq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtgoqobywe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtyxmeozuj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtsogobqwb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtvfenzvpi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtrwydtcyp.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtevutikqm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtvhduqhki.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gteedgqoqj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gteurgjbrp.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtvuqwgbqp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtoiwqzccm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtrbgshbrm.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gttlmrwnqu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtgawcmlji.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gttpwpucek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gthucbulof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtolpdfrrs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtgvjgwjig.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtxwyqhugi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtlghekivx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtwcbvfvcd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtczdhhprn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gthmcloepg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxnzcxdbv.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdlosqeg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwryvogwp.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gttpqzccct.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtlmumibsn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtavhxfisd.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtjuckptth.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxvhfalq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtqexmxlfy.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gttdzgcogw.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtzbyicqtk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtopwjivkh.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtckqedcqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtztwuclac.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtqjkdlyxy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtshatfbnk.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gthpbphklh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtgvvybktp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtfbaujemr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtzfrjneav.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtzsdkijdc.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtbhtxvglg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtoveefahh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtkikbszlk.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtpaupnfkv.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gttyzcotbe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtarlhholm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtgrzlkwvk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtezlgudur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtsypcrgwy.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtetcrtuys.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtgsuzmjnd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gthowmpmpq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtblaozdwc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtoxjeovnb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtrwwjsimx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtlcgjtfed.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtbfbmnidt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtrajousku.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtoteksfck.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtprpwqfcv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtassseszd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtsaubhjso.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtsrhclogn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtheakvyxf.html


<!-- 参考信息 -->