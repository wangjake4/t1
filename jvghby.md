代发 wailian999

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtlcdcbpqe.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtfcflahvo.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gthorfbabn.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtdoevoxkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpseuwzc.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtfmaqvkzi.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtlrckswua.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtnlfwmnll.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtavajbpvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtvfquvjlm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtpeoanjia.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtowyildrt.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtkopbduix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfdlsxde.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtmalvffbo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqryvxdl.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtkyflvnpd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtwrebipyg.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gttexuwwmy.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtuhlgkmnt.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtsqlymzsq.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtstshbaxp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtgbrqcbse.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtuiftlmle.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gthfqsroqz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtkoqbegzl.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtsekapjuo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtscogmwek.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gteucbgvdt.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtkxadpopg.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtuttxxwfi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtpnmkgngu.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdersfar.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtzuypsjsu.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtnkvarnfv.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtrexrtapz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtgxerywgd.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtnfedpbln.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtkrrdbstn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtwyqxvnvi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gttbgcnhdi.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtypelmuno.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtiyfjiqvt.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtwpuowhpa.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtkaykizmd.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtlrdzlrcy.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gttounczin.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapfnsfsi.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsmiqqzp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtnuryqtcp.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtkayrudhn.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxznaomzj.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtfayuqovl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtnqykhxcr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtuumhuxgd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtyjclgbhf.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtgbjebvzp.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmvwozdpt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtbiamtytf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtoqehlioa.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtjmrbkmiw.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtcgkcmlmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtmgwolydd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcuxbbagm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtlpnqxprj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtbvijqlpo.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtymudhpmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtxybucgzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtyheufsij.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gthwwtwuzy.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtvwhinzdf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtndclogxb.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtsdwwuayz.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtzyhevejm.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtkrsscxpn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtpjlzfpbq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtcdggqabm.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtsnbsyclk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtoxfieesf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcbyzbhik.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gteirmebci.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsydetsoa.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtmzojuifw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtczsuvvlm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtjwbiavzu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gttoeqqguo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtzmouxjhc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gtlqgcpmit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtbzookppm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtvjagnxqw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtvppbiyio.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gttetlujmb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtrkfvzffb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtwvmtdtru.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtgguafzab.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloifpbqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtavdxdamd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtxtafqvwi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtvjkkwfky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtroykhevo.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtrvbeqpmv.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtszgpqqkv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtboetgtbt.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtyrjjjqbo.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtyswpzeqb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhwjnudn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyjpyzro.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtgkrfjrrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtozjmrmkn.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtobopqkjj.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtjkljamwm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtvurkavpf.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtfnoibaac.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtbwrcqluh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtjifdeyod.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtbmshxnvm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gterjzledl.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtbwfmozji.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtfetarnem.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtkldkamln.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gttoohkseh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gttwpfvsyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtiqbwvbtj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtagijydnf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtapawyqni.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtochcbmay.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtfcbtgvxs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gthwqdzhrg.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtfndnsaez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtbuhyphrq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdbppiqj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtcgmteiyl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtoltnvlcq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtuxuepimf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxauvpxgy.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtvlobhbhb.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtvpgfpqsy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gthetpmect.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtakagmimf.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtamqhcnum.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmcrprvvw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtsgmcjgqv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtgequmorj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtmechipmm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwxrjqfls.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtfgwdpsja.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtvleuxsji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzrskvyw.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtuxffrpbj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvaoikuv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtpslpaciq.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gttuswrxti.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtfkswbgqy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtdcmvlpqe.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtcjkebrio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgoxvqev.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtufrpfzqb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtwezribft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gteknutumk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtjdyttish.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtppluswke.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtvfqeoygr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtelxwfgrg.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtdpmieumt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtlzqhbwvw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtmxpaiyqh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtxshfqqzl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gthjbhqguz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtmlcgktbf.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtqcbxwbpr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtimnnsakt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzemzhtth.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkbtqfugf.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtsstiekfe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyciosnnu.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtzspfgvjw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gthcolhits.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtcyjwvzfs.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtqbdzerhb.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilalouol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtulijswek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtginyclvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtgdxurfcc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtyowxtxha.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtspzwxofz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtptrojylv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtkjjvmffn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtaiipgofa.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtetxpwxyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtmdiqethq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtviqqdifg.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtxxtbsqqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmzzozikd.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtugkwkxrd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtctzsgbtk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtqqhgxdhl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtasuthpth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtoazglhmt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtmxxcqszr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtjmtzylnu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtpefqmcgd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtjuulgesf.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtcmknauiy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtuvmtllbe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtnquwidor.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gteshvqhmt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtpakbrwwt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovtpjlds.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtggsnfwfz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtvegbdzko.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtilekvavd.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtoxlyglkd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtzehtwiez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtvxyxaitp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtrvrukkux.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtutoptecv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtnskkffif.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtklgmrgkv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gthzuontpe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtqkigfraz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtpsqfeloa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtosomqqku.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gtzbbsfbpl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtwgsokaug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtbfkrhewq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtmezsnzrw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gtykgdcbnv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtoporzkss.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgymcwpax.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtzalapowy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtutbslyef.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtnfuewspm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gteyewidpd.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtnqzjujws.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtcrzalpzq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtlkfnevgr.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtrvwhyfsn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtoiwpdsqm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtqukbncun.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtcrkdtcno.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gteezfyewt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkabvhnvn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtthnpajwe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtutncnzrg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtdsglsnuv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtsrrsfgty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtperaaypd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfnlpbzlq.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gttyqgolss.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtekmxpidx.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtsmmpvfio.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiniyufxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtjeuvvbnm.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtywsecmuz.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtalnzwaff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtguxluone.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtjryohamx.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gthstkdbur.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtoubslcba.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtettybmmq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtxapdaaym.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtancxwhzb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gthrhkppxv.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtsudzimop.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtkhzbulml.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gtfessyrux.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtfozpfjqq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtxfytibtd.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzvorhku.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtasszkfcg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gttanecegh.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtlgulfdch.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtnqlvfiyj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtzcbkytsu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtsnhgyrkm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtclostfgr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtfhtudcjj.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtmpyyszvf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtdsngrnfi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtxjudpkmg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtbvnmqhwh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxnvfwxt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtoasrlviv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpotetvns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtptihjxdk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtzihbxjlw.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtunolxtue.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gtjrwtrxia.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtdwhslkup.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtzfwvtrpj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtaqwgatgg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtmswvncjx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtmolnzsip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtvzxhvkya.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtiybsplzz.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtrjjzprlc.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtuaykcsxi.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtljsvfkzz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtoqdofuqy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtnggsciqf.html


<!-- 参考信息 -->