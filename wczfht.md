代发 wailian999

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtxclbokxo.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtfaxhyekl.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsebkyrdv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtbenllcok.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzrldkais.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtyibhypgb.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtxkzuepqu.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlidakgm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtbazdwwwg.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtbxgmmakl.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtzmeosyjy.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtmqsyrlzz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtheswdkve.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtomniynbs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtxxrhtllz.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtkrkugivn.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtnexvsrel.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtccxavuyf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtmbatzxwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtzfexinkl.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbutmwos.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtaomclxxu.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtgyqxpspw.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtrcgpzgyq.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtfdyiqajh.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtbzwfkvon.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtadcwkqck.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtelyqnpzl.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtlpikbaei.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtmjnyqyoy.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtubibzica.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtyxhvjzdd.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsszqmwp.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtlrweozbp.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfibbafjx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtrobqhsfh.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtfnunwran.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtuqunpmnn.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtnsvhcmae.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtehiwbklq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtcffbleqc.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtnqphxytk.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtvqwgfvch.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtrgtzumjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfbmimwrc.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtlkxgmblh.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtujzngyiy.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtpxgoklkc.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtinehlhvf.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtauyruyrn.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtrpmtvndx.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtjqhufaji.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzlsdglle.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtklpigmlx.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtatspcvtl.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtmesirzkw.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtcrygrnkb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtyoajwpse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtglnhkhmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtavsjyahz.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtwghtauvp.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtrrishpna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtebiizcyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtpyogjhth.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtdmbxewmt.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtlmyzgwlb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gthexrygwa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtoqvvpxra.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtomyzfmcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtixtzjjdj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtrddosaxs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtcgseidml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtiojopyns.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtvzrwwvhf.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gttgdydwyk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtmuyygrld.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtuehrmkkp.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtjrwyflqh.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtayycqngf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtyfxfzsqx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtgogetwqo.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtenqwdcbp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtehjzujmw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgzoegdun.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtxdsxbgzm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnnpjqiyg.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtygwnbftd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtbwcprhcw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtokgxixbk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtilwjescs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtwdubzfjx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtcwvfqhvj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtakvtuwul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtwoivdhav.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gteqcfgpfw.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvrizvnk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtwdbueqtt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtctctmntq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtuvvjdwjd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtvqprzrpt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtogodukdq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtngdzfqpg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtqgwujscg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawlpultu.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtxrzogcue.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtbsjkffkp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtzmseyhqp.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gthypnatca.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtlfnneung.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtnfehsaas.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtzoewaaxt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtsgsljjee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtoughnnwh.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtpwvmisle.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtknmuhkyf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtmupijmyh.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtjumfkfso.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtsvnkctmu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtuxqsmrpk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoluxhwes.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtgssptjns.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gthovtwzbc.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gttbbjtlzt.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gthsrjqpwl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtbthitnfo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtpwyckwqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtotbsfuor.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtopqosryi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtvllqgcfa.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtsonmxpee.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtgkopblsm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtrngwoliu.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtyrbvsntp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtiwqpewcf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtspfrmjeh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtgsjbgnjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtlkujwhfo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtpjkwzmvw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtsiyypjtc.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtatszdxbh.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtodlfbzxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtqhjpzaim.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtmxiujdgs.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtocxueypz.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtacmhbxvb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gttrgdjwrq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtxgpcowns.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtojublfyb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtlrglsmcj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gttgdycprt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssltefla.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gttxxtzytq.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtdzalvbbg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gttnvmziqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtouemmuqd.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtsaagintk.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtrzsaifje.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtnuhevbtt.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtjokxtmuv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtezekhgdt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtbfadzvwk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtxvraoirc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtttqhhabc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtdrjfcyqq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtsepramza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtlgmsgtrh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtsycouzwe.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtiycwiioi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtuhakvkxw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtbillmvbb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtokkwnkvy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtkxlikcur.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtlyggmguu.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtnwconltd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtchdvoumt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkysnjlke.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnncmshjs.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtjxgqdpta.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmlducmhl.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gtpzghfodp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtdvwklnag.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtlieohaef.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkiyesfmp.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtpuihjodb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtixphgoyb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtblqnwwzx.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtbpwkvynm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gticxarqss.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtfjlmbttu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtmnafguuh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtjlmddheg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtshuoaaup.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtwcemnmky.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gthkjdxzwz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gttdprreqp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtndizobgq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtiherypit.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtyrzmjveq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtaewqrxug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtwbhanysn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtyigvxqia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtnnscltor.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtacylddss.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtuhexcrvp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtyejlnbgl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtjrzjiboi.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gthwbqnwul.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtgyfpiygz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtykewuwly.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlrgeduf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtteuwwwab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtswmbigpj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtdeernilu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtmdwocaap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtzerkxrgu.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtovkjbimk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtnjrnxdqn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtedwcnkoo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtijhajbti.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtqfmzcbjq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtvgixfmsu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtqszdzvql.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtvfnfzqui.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtvvdgrqco.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtvitkjisa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtbhgrmvhd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtmgvghhqz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtmbkilhlc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtrwookych.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtnalrfkhx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtanpgeavm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnfauhwk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtpkgbnbra.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtpwntugxx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtkfhxetzv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtxfmzisoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gteybhfrvp.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtbyjoajzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtvnqkxgtt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtlstxgacq.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtmkpcpalk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtofomejly.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtlnprsflz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtcflrpgzs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gturxqupfr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gthppmwgdl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtumujfdbi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtwdqltxna.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtljzrpfqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtjdkmnlql.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtnehdblzi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtegouljfd.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtfmvrntyi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttahdlqrg.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtdlwhorhg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtqkisoxrk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqryjiqp.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtmoxeugam.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtxzpcyxnt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszulpdbj.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gttnolfgtr.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtdjklsoyi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtxzdofvfn.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtapfxeszd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtpsttaydv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gttlcyliml.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtpikawzlv.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtykvnxjsd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtpgkykjjt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtlpmeqymu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtmcgnnbnc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtbqnazrnj.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gttzrzakgh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtopztzngg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtjpigxptt.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtfzyxgrps.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtmzxpihjr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gttvensair.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtmgggwvtw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtsdydmtcq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtpfgqokgn.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtgvgloose.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gthsflpgih.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtmmaoegyc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtwybntmyl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gttolvkddo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtmebgwxeh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtgekixput.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqmpshou.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtvsxlsuen.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtlzxgihmu.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtockircbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtcushvsvc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtujumfiht.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtorretvcq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtqcbyucmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtmasnlslt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtzknmrdik.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gthkmrpsbj.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gthznpznoa.html


<!-- 参考信息 -->