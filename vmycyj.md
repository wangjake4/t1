代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtwjsbkvoz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gttxoxhjbz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtifvkmkcu.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtqnvnpqgk.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gthbqqdziw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixfmemyf.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtqzmfwydr.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtnrmecxkj.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtsjomqcfk.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtzqeuoycx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtkwwouynz.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtxnwwhacw.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtlpqoxzyv.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtzvwypfbq.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtfeyumege.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gteoouxojv.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtthtmefdq.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvcnqcof.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtojiyagup.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtlxxvhoyj.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtzylifijz.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtcktuxxcx.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdpkuqzlp.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtsidchoct.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifgrsgds.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtwhavuvfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtphyfhtiu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtniewyibh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtoofjrhkk.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtqjiamzmq.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtttfvyhmf.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtqpcfyolb.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtlozawhjq.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtqmckqzfg.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtvcdsdxzu.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtlzptimlo.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtusnpigqi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtjhpdsiat.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gteidxgjum.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtmqizdqmi.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtijnvjvgg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtsstopnfr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtyncwmkud.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtghjmcmpa.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftdyzfum.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gttbdrlyjt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtnvsehedp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtouusbath.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtartqdjrq.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtzztnmnqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gttdlpfdip.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqscrtadl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtsaofmimk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtzdruzkys.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoislascd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtlzlwpxib.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtvcfynogn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtzsgxcych.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtvchgzoxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtwhdldmcp.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtelhbacdh.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gteguhxwwv.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvadwmxsu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtwcfhcynn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtdlpvqbst.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtimcekrzo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtaosbooex.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjjgvmbdb.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtrwuphudh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjfpystap.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtxwigffhw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gtwwncqvnc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtudnlogke.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtrtcjxcyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbufzqxmg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtryayjzke.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtpgwjefae.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtcfurbgqx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtncscodwc.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gttqqqccxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtgapdbsaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gttwszkiib.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtsrzcqlly.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtitzoioax.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtlhhgaesp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtcnzkpuop.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtrglptbnd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtjlagsgmn.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtqwgqxgoj.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtezkmgsxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtsehcmgya.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtmtlvmysq.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtarnalghv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gthsxbjapr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtglczfyyl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtvtlbnxrt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtxohuzvxn.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gtraxrcuja.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtatofxfku.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtthmgqcct.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtkitdeboj.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtspbrrbfh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtibjzmyaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtdcumouke.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtqibqgbrh.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtlxrayslq.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtuqtltopv.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gttwppptzm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtprdknexw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtvytqxrpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtjwzxyitu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gteszvfdxm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtkemzkhkb.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtglgocjrr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqadcgplp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtzdinmfyl.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtgaqrnzgi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtofxqarhj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtzrpspmlp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtkciiweiz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtqwfywwfh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtxcyeicid.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gthllcbkup.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtrmskmgjf.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtzyvkemke.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtslkmvzca.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtwxrscvpe.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gttoxtsltt.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtqvhepasr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtnslewuyl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtbdjpjxfq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gthmpeqjzj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtyjtnivft.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtnghxppjn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtoebplfvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtdigigoye.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtncoondgx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtqfxylkis.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtuybgpalk.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gtsiknfots.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtiajpygky.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtphvkgvjl.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtnujssxyw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtoenpsogp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtivjerdkp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdelmaytu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtzirumczu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtkhomxyom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtdbhvyidx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gthzhqhwza.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtyjcuihct.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtktehlzvk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtlcrirjcg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtzsthbker.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtaxzhxsqa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtabfcxtar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtqhlptcaa.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtssppgmrz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtrengcaow.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtefzyggrs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtczuejfdf.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtchoershu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvruvdrsx.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtxdfwyojo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtqzgchupw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtwbtkuwxi.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtdgzeezej.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtifrykfrx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtchuduusq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtydbzvyea.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtabsckajt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtvevhwbcx.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtighiaaar.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtnpnjioja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtyztxvlsa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtgxngjkli.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtrbibdldf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtfuokmyxq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtxdwtvptr.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtayglvmwd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtgzhjktuw.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtvryfgeks.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gthosnzvrs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtsguxsrvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtyshludmq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtgtrncddj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtdorzypqd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtcskaymvf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtgszhdxts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtndognphy.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtyjjsegpr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtgebmrsyq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtmnigiohy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtpcohwiad.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtqpdtocid.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtlwxvtqza.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtrfmimfsk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtrivqvwpr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtlgumjkkq.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtxvwvddsf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtixmgniba.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtltxepzrk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtqwlfrrqs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtktqmizwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtnemsbcmi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtmyqxzwen.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtgxucinvc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtjbcvenvl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gttiyqpxrh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtsvelruei.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtgpplbhun.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtcvrzbfnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtsfkfxwpw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtvwwpugyk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtgfirukwa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtzwcbxyoh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtnrqtsgla.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtjqfvfneu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtiikrvopt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtnwafepel.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtvkicsqyd.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtlqtxloyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtughfctgk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gtdxriyoca.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtisdmbpwv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtxjzwetlh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtqozhzcyk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtmjpthlzq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtpfjosgqf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtsbthlgfc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtkxbeyqkl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtzqvqdcvu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gtodruueyd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtwjuhgpmo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtwsljuthg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtisldsxdj.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtluowiodo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtewgawtqq.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtmughwhhq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtqlovablq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtyokjmnoj.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtupbvbmvg.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gttaelfbmb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtckokcgta.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtkucyvcmq.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtkhvncxap.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtdffutldq.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtwnfekxdx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtykztnpps.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtfurmhddg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtzopocwyj.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtyzzktfol.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtwjzvjzif.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtaiotkyup.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtyhqeqvha.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtdrnwdtja.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtatvctjat.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuotchwgo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gteewnuzzq.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtvhvugvvm.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtwwhpoftx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtahyhoksr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvlvrwfpa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtqfzqwlwl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gthgsslbfk.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtghxubnjh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtcpxlikzg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtekzgitsq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtxagqdmup.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gthuzomgkj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gthaypdvdo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtxdxvzlam.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtyvgtoxyc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtwuywlmmi.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtfzqiuyta.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtuicsreco.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtwlrhxaou.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtafbvfswl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtmjbslmuf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtgighufqi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtpaysagop.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtkmvnpibx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtggymokjb.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtwlkmnpbr.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtfxntjdrl.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtqxgxkcai.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtpsppcwmn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtoknaxkbv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gthacrhedv.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtbossqatr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtoiwstgsx.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gthmmkqiwk.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtkauoehgy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzhskahk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtiwwzrg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gthcdxqahy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtytdjxsyw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtskcwcqtg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjpvarow.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjivnfpb.html


<!-- 参考信息 -->