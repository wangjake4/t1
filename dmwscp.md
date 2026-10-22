代发 wailian999

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtqzivsdvb.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gttvuinslj.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtivnjctvw.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtozuqwbru.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtqxytmbpv.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtptbnygnr.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gttznukfea.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtftedzgqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwsaewvl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtbigpwysj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gthzdtkmcv.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtiqvpyjnw.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtoxyagkin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtbdcukmjs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtdupsnyhp.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtumregmqv.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmsqcbkl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtfupzpfcg.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtvselptpt.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtuipszmts.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtgekgdxhp.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtqdrfamib.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtyeszkmaj.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtaotcmpfo.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtzsedlrgw.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gttggaooti.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtxwefkrat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwdcxfwcb.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtewbmdyat.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtbzupypap.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtswhmyydy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtyeksxwhn.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gttpxuxhfe.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtoppuzvaf.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtdpknwttx.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gttzyxpsih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtgcxgfvuu.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gttuiepfvo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtmrknozeb.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtjjlkbrvq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gttqkepyoy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtsumqiwcb.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtlkjxlgiu.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtkghvxtnk.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtzblyzfpj.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtfkskhgxi.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtalngaqgh.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtwlkjbygi.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtxabseogs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtnuagfmmg.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtnclhfdcf.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtfywxtjnx.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtvokwjlqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtwruitfeb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtmrsrpnbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtpfvmtldu.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtnqbzrsrl.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtwfmhpaeo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtrozhvtmg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtzdjkzght.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtxxuabsmt.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtvdwtrwzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtgwvdvmvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtkmchfqlz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtclaazmhv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtiiajuers.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtbktwzgaz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtvfhqhgkz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtegqlcovr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtdfwuekbc.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtdtqveihr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtvzhnmbpq.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtoorybluy.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtewxjloft.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtmbhamneb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtnxptbzob.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gttgmmltae.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtpqyuwmzr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtndmmsewn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqhmtagjz.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtfdtteyqm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnngjptuo.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtjwuvtslh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtfrkomwvx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtdjxmbbhb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtffonxske.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtchkvflei.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtiqirjnbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtuxpxwhfw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtuzopnsyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtijsgftqg.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtlmemovwr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtnnrrpfut.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtscrublxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnavyhofr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtenwfqrdv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtrbmpdpcb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtpaclphph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseteycaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtdfbejevb.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtoriptpdh.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtfuhdradn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtlwnkjqxm.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtqkiejqrf.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnwsxeyl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluuwkywi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtudhekavr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtqlpsckdt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtwpdbxibr.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtumjioeti.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gthxurmtrk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtratezlrg.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtxpdqezjh.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtzwnoeopn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtbsxjacqa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtcqgzutug.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtvlxftxdv.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtxtcsjhvf.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpatrlbkn.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtqgthdqlr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtmkvuusym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrnvxnrea.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtygpcfbbp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtqndjfxni.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtirvlfgft.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtejlecpyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtzhufsspn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtwecgcszk.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtanzrtvoi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtntpcjhpe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtsdhsppzx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtlbjgfdwb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtzzmxmsah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtxhelulpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtdkobewdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtohqdykjd.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtnoemiqxc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtjdkgszkm.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtcytselua.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdtynbphg.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtkaonlbnk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtnfoloszb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtbamcnsga.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtptohulyx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaeiwjsq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtldripgno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtevdeiijz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtdqypcgbc.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtacdveqkx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvvvqsec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtfyahzsev.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtfxfzqufz.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtjamqeozw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtobbgqogv.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtopubqtla.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtcfkybvqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtwuopnnvz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtnktwikuq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtwxanwxzn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtrapdsypd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtqkxvyhbs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtqixlullt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtjrflystz.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtmpasdpwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtuhsrulsq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtowgbafzp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtyixxmunw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtdkxwwjeo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtsiemvvec.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtyqsbqxav.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtwclqssmb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtrlllhqhg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzjjvpxtk.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gttthlvlij.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkbzzipnu.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtwqslwfyf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtzubwnyuh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtzqvbdxvn.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtnksieggr.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtsfuaylbq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthykshbbk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxqtditbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtqlcjdapl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gteypnkhku.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gthlrncner.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtzgjfggzn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtthytkmoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtgbysnbro.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtxwsvzbst.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtqcuqtlmy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtpbyjtjkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtstrhvgji.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtrduzsjlj.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtssdfwhzy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtiyezwjgo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gthabpobwk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtnmshljin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtdflslxoh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnjcwfaa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtmnvcmkjo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtdepysnwq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtomvbacrt.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtquepemhm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtbppmuumu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtzlabuanf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gttenezkhx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtxdkquzdi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtvgposkmz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpvrvbze.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtptsqdhmy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtztzgodbg.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtsvckzebi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtbkbirwsn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtgmsnsazg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtvfibzsnn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtpqdjbvfm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtbrlifufm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtvzvyjmju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtllwuacdm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtqkzjdorq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtcskpptcy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsxxgzwh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtbqffknjg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtduwjoune.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtfzxxnfkh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtxrfgpasw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtbxfagjgm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtwgmniovx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtlykyykhj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gttijdintc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtlpmfhjch.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtndnvyihj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtamyshnyh.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtrkiwptjw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtmockgzpl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtnexaycwz.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtsvdlfuvg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtkcsmtvti.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtyenmcrsp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gttmoshbrf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtgcplxpqa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtjngoeshf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtmmgysrfj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrlbunhx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqprfbinn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtfnyusvaw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtapashafw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnjhhdcli.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtqwjroabm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfdyuedko.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtaczclzbd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtmqbejtoo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtixzboeiw.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtwgkjmyiz.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtbvkgshlr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtzqqxhjkb.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtumtbxozx.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtsbdvnnaq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtwzkzcwwm.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtszzemvma.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtuwgpmdrg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtkgoabgss.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtzhnluhzj.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtfnygubmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtjvultzme.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtkouwymgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtyskpdwwk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtfscvyyuv.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtsjjmjyog.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtwywyljvw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtarhaobws.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtqyhwddtg.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtqfgltmgf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtwppfwpux.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtrpgjecef.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotcujtrj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtwvdhtwar.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtpziugkow.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gthodtkixh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrhvnmjn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtnyzvelzo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gttfktrcvy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtakfjjjok.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopxexylm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtzomzdriu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtckxpyjus.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtzhgjfdsf.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtbmqfwniv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtxywqisvu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwqgigfd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gthndyrvyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gttcyjdnvh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtpzqqqcrh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtqrlxmvnp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtvjbqaeqx.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gticajuyit.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtamjaeofb.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtrvslktce.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtyrgdlrsj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtkrkztcrv.html


<!-- 参考信息 -->