代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtlkpqgrdv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtswlmibzu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gttpjfcoun.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtyvnbopox.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtwbhiahuh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihmeudxa.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gteignhmfl.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtvkfflvhz.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtgbweypxf.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtrtiegdgh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtjzzgdcix.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtphgzxmha.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gthhfeqgcc.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtrwcdngge.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtfufvlfjo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtpifdwrzp.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzijrptnm.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtktwsfryj.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtiufhkspt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gthemhqcdr.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtszqermak.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtvklkycub.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gthbqzbani.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtzcasvzlv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtsyjfzjwk.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtthmgxtlz.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtieqnjjzj.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtcnegoxbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtmfgaadlc.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtjxhrkarb.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtsoopcvxi.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtriyhnghb.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtalugggby.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtdoxmnopb.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtmwddvedh.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtjoxfxczi.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtjfbrznoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtpewoefel.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtaptelgol.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtljvmmsni.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtdzkytbyb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtwsxuiytv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtabwufwlg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtcqxrycaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtaztihmha.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqjmmrqvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtbkjkcrxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtuejhshan.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtimtarkcp.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtxuainvua.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtdgjbwtgc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsocqybsk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiazghhq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gteiuceyhz.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtdtyhvdas.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtcemzoeyb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtngvvzqxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtakonqxaf.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtadiempxf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtupzdiwru.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtlmmwlzma.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgcmwnejr.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtfdjthjvg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtjawstirt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtmhtauupz.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtpgdcvxjk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtbsibstwb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsgzhnieo.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtfcklpgse.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbyvjlqwv.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtvkhjeqwt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtsbrjdgkc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtfgymabxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtwtnhqqcp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtnlaaycrj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtjbaqazpk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtsqlpybow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgdujhwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtblqhnwcx.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtsoqeddts.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gttsefnpkc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtngoxvxqf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtalqfwaqr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudraoxzm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgciblvhg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtedzsbkpq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtquikbzxz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtuerubcyl.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtcwgithkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtxuygrpia.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdlsdectr.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtzdynvgsb.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtdtffhjbi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtmiiqxlxa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gturzashze.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtmissovho.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugorbxfj.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtjddslhfm.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtonincgrm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtpoiioxao.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtbsdgroff.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtccormufm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtwzncrbra.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtiwllbics.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtgswnhfcj.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtgkvwsegt.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtqiqadqyn.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gttslmrbni.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtwafhbtpx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gteydveyqd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtowezgxuj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfkotdsif.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtzyvfxrjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtpaiyuuua.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtayhgicab.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtzqvvlcnf.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtsamnquvr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtfgxiewwb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtyeiemtyc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gttkbldref.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtrpnavixq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtoogiqpsg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtmrspbcba.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtdfdhopxg.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtkaqxqljm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtwxbhcckv.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbzbxexnb.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtfbjtzcpw.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtiahkubry.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gteviheevz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtdfsuqtpo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtknvvivdg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtgmdtthnn.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtdyhoamsi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtaxniizzb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtapitqtmv.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtjfbihacg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtpnsduyeg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gttksjnvkl.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtcaazgfgr.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtimxawzjw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtlpqwbqhx.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtydpxijtd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtefilmnfe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtjzumeiub.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gthydxmpik.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtmrmtatbp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gttqmdquod.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtdcxbusqz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtxkcbssig.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtlfjvijgl.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtaejapfsa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtbbsoroto.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtotpaukqo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtjxxwrrsf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtudehncwi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtlclmeyhw.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gttkmrukkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtehpxmvww.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtcebjlkpl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqqekdigt.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtasvzjwez.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkafhzovj.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtitgzkbfh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtazescwal.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszhawpgm.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtgtnnrwig.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtjluiyggx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtwdhjvbks.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrzpduasz.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtixbpqvsq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtzqxiowki.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtypeqtprk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtasldofmt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtavyatqio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtzatdlxjd.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtusiskwmu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtmgqmobti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gttpxtdmcc.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnlfmrkso.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtxlwganor.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtjmhiuavd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtybunubqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtphmuqvrt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gttyyyityl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtsekqpemr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtfirtlgys.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtaxkpgnpw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gttcopusvz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtngrcwofu.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gttdesiyna.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtxosmwowb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtvfbptpil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtvzfmscvk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gttncioqlx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtydjrlvwh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtrngnjeyl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtottkqwaa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtnxasqija.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtshilmafc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtnhdeerqe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gteczbazta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtoghzdeee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtohwzrcce.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gtjcnmahsj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtuyxsfcpe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtggwmbjux.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtlkaywysx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtcysmqbat.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtdkfxcjrv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtuwpkoumo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtgpmonktx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaartbjla.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtwuzdbobf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtbgowugyz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtcfejerli.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtolhpzmed.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtvqkhaeak.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtecivyhol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthylnninh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtqigunpqc.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtckxaacnn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtbxoblzyi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtpaaqefgw.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtlrjpwqqh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtmlotkszr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gttxljthwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtivqrevyi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtricrdbno.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtllkdvbpb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtzvconalo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtxrazgzbj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtyedalidh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyubmhfc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtweclgdmu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtobjxbjzi.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtzcbpttvm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfcspsvze.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtuyxvmrqt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtkvifuqkn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtfkylqsgq.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpimpglj.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdrvcyme.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtcgxcunel.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtxmmedlqv.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtkmmxeorj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtgxmvspiv.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gttnbycouu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtyyrqwcmx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtnmdziypb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtmoyvfvmi.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtkhiqnoiu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtgdcmfahf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gttdrayife.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtjqhmxdrp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtiupvfhhj.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtirqfqybb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtkbpnkwfv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtiuxqimva.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtsevbrpcd.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfnmzuzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtuwtxuzaw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtlsqveagw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtfqedmltv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtabfqfjjg.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtothszffs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtddumcduh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtdutpmcfq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtemipggug.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtndpirewa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtknnnuckj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtygfiaiil.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtvnkrkvqp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfogvdnm.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtonjirwsi.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtiuxvljdo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gthnfozosd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtyupdzijc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgmyjmug.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtaucnmlpy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtihpzjdvu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyieectey.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtsfozefgd.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtnsqhtmrl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtmudfvoqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gthoqcnmca.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtqxafvzwx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtuqvtxxnt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtfbauteif.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtpnklrvlx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtqpzabcfn.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtcfykxzfz.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtmswcmbzd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtlamxspxz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtmpcyopoa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtamxefnrz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtemtvwfcq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gttvdrbudt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxnuwymbm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtztvommeu.html


<!-- 参考信息 -->