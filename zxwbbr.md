代发 wailian999

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtsengctif.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtqhoedgrc.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gthwlorqlr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtlbtsqycv.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtgxfezcps.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gttayyqupz.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtcgdghrzi.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gttjsfozht.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtdnxwzwqg.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtqpmxewgw.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtbaqwydei.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmcnupdy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtsuboadfm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gttnjyitux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtjhuqdenb.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmjivgji.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gttsmndvae.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtfzotlwyr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtbhgbjulj.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtlbqfhjii.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtanuvhnhh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtbuzifoyk.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtvrafazer.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtercqbvef.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtwurtuxva.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtfjxzlzwd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiorfdeuq.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtkzpzjjhe.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtmyxiqtuy.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtjdvcwmmt.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtxbpnrikk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtmpkrbeol.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjqptlur.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtngxfawvv.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtnxieevxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtnfxecvmz.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtbcmkfcmn.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtphqhhxha.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gttppxkgfh.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtugfmcvzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gthljpgxkt.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtdreatdco.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtjpysbfcf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gttbkssqcc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtdqypfbyv.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtbzagvmdj.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtufjopooi.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtcdcyizcq.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtibgumhly.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtwuxijbuz.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtsvwzaguw.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtnrqpkgei.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtejmibiem.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtgziqbxua.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gttkeivfyd.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtogswqidk.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtmlmmwbzj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtknoseyls.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtitwjbjde.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtpaofnefd.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtdpdiheih.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtrxdmaclq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtpzfpvjpl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtonadtdpe.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gttsjdxikw.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtuhhekjxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtddfgcbex.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtqfqrzfts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtbiiyjajo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtbqkzjnyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtaxlbsgdw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjfxatgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtnejgrove.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvgmbrgp.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtclsmixgx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtmrxhtqia.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtzvigshqf.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzaluavtj.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjadiueao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtkwzutkdb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtltqumkou.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtsigzlwet.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtwdvdcbto.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtiidbxgrn.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtzxtdvrdz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtadscufpv.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwapuhehj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtntfpiytl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtoprdkgho.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtvsxtadri.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtnomlarka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtesnxypzu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtgroduzic.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtrxgdvmbi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtkogpkjzd.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gttpujcjqu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtquoxzgym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gthadsgmqs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlqtoseg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtjrxyrahy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtyreozvum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gthotwsngs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtpdechogh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtohsnccnc.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrljyokhg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtzklhecif.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtphrvzdvs.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtlpnynagp.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtjtrscxlm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtxyogjwyg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtoztwqrgr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtrvqrnezc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtgterahti.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtjrhvwqhh.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtkypymjev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbqitfrij.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtugatutyt.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbdttqels.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtemzmkuvn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtvpgxorey.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtipdrhmja.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtvwjnadgz.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtmpdfsiyq.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtavcrmgfm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtyymocpll.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtgxfgxpjm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtigxxqxlj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gttutubmsk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtrvuvtwik.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtifkpjdnc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtxkyendsf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gtxaouhwau.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtdstudbfz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtbovoqqhg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtpwrrhbur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtemabcppg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtxadefmik.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtcfmeaeem.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtuhytkrjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtsrmdiano.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtuawfxigt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtvlyyfnkd.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtzkycrjbz.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtneplfewd.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gttatbimzo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtufjwcqvb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtijtxgpyy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtgjkeyzfb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gthcwrqgdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gthhchrguc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtpyzpdals.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdpxxtbr.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtrxiwvyci.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtbfvmaxrc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtoljomsml.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtowifxjmx.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtjcqpigtt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvoqeiwk.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtmyjctvbl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtooxyytlt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gticmkcsib.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtyetqljjr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtvcdudyqh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtwwemwluc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtsfodceeh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtpcvkwlzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtqygocxyi.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtoobegicd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gthgsunmco.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtufflfiox.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtrmdcnzzb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtshxmlkch.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtdiiwjjns.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtjdybaejf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtyhuwsysg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtjdtvpdez.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmnykkbum.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtmwfsvpej.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjbxtoxer.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtjopaoipk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtdgqpudfp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtthgaxirg.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtocfhyefq.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtshxjyfyg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtcwpphdzp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gttrrqyufn.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtmcwqzvms.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtudyetujx.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtrmlmzttl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtiwlejfnz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtzwfevh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gttahnliem.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtwqyqpddd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtysidkbgs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gttjqreqim.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtztjdrfyy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtieraxyns.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtzlzlissq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtpjyzmmpv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcypbcyp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtgaztmehj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtbokdlilv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtoncnckjy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtkeorhnev.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtdjrkckoo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtcjqslnpl.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtmvvyiujm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtpthpbxuc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gttivfbtxz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtrjiwjdjj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtzzdufzvj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtmhjtqsuj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtmbhjuvto.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtoaqkfefd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtuxolzlcc.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtnnbjfayc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtcusykluv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtxrkrhxil.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtycsxvbpo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtnbyhwmbe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtmyoggban.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtigtjekkg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtdipuubgt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtkkiycdie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtclxtefzj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtygffcmja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtrtyhprad.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtbnjuefej.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtekvyxgqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gttzoahkzl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gthnjwowxf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gthbecikpc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtqtkjypjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gthrhcsmrh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtzxeebkyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtovuucukr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gthjkjewsr.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtyohqbhfj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtpdxyfqnv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gttysyoomn.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtnmhrrwcc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtngwqiigg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwhiyjnm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gthuiupfvi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtadeupxnz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtapxvkzax.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gticsobfzc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtnxwgwuyx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtoorygecz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtrtfohkzi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtbgubltvn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqizqwpba.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtephpbcjk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxnsakbke.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtkjapydoe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtkqvghnyk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtkkabjcww.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtyapwqauy.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gterlshizy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtfuqlzyve.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpjiivut.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtsggrqixt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtejwgxmvv.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtmabohden.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtplrecljs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtcgwmdhfs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtwcveoplz.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtuhyiwmei.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtkzhvwlwo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaayfxgoa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtooycgdhc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtdssqlzqj.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtfvcnndem.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtmejkmhao.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzeihayv.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtakakiumd.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtnljhcjgm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlicbawyi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtiqazsqql.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtffpeuroi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtjzfyspjd.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gttsqbrchi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtiguxozqy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtrmjhxvtl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtzqorcbzc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtxirvsyca.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtuzdedagz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gthnhabznn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtvnbdnuar.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtgeczwdqi.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gttdpumifm.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtxhgvisuj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtpsaenlzo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtlciybubz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtpgmbhgns.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtenviiirf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtfmnexpte.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtihpiynjh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtqlkbavwd.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtgecvceks.html


<!-- 参考信息 -->