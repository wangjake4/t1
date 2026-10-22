代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkkhnmje.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtjccskuqf.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtaemyvrxe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtbnsofcgu.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtzknbkqdo.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgcamxoj.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtllvyqqoe.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtmtgafdcd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtriownqua.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtathgxcnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtxslnrxvm.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtojmwxesh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtnwbpbajg.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtowdgjzle.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtespbbtqc.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdojswnmd.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtgnzpevpy.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtuityrnck.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtjvyslnsj.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gthqoroadh.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtelzribmw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfjcvhxn.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeruclfr.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtvulpitti.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtjmshioon.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtdchoyrjq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtbvwtruok.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlcchcnw.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtazotdofz.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtntnyeavu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtcbncqbdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtgkvpfdhq.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtoeqwfuah.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gttxtrwgwb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtirluyvso.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtuiasmlcw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtkyddksnt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtfzjeilsc.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtnhbfwlod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtqxacaozw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtbymcylcv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gthrzbpwnx.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtxndcxhoy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtxqnysnbk.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtrjwlrokp.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtelvpknct.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtbdjucfnq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtfuomolzw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtumypypdt.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gttqfzfwey.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtnfiythar.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtctpsvgou.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtxziqznsw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtucqxowgj.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gtzclftcpt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbvuzkmj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtndofcmma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtznwcpseg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtnjercduq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtoujomgim.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtfpgjtyxs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtlocpoyca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtsabuycgn.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtoeiiclgu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtdrntmeuh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gthsaovkih.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujdmpczx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtajnlzgvb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwotghjym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gttlkojldr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtxprakmiu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtrnltsnta.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtkvhctyak.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtunfkukca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtgdohrmaa.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtydbbgbsi.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtrhkcpjcz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtttfudues.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtqoliptxl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gteehgrqmh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtwkmmhkit.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtcqnkiaqq.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtppczijgp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtgsxneece.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtomqcczmc.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvhxmrqgm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtryuszkqy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtckltfjlu.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtbuxxgjxx.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtdnvribyx.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtjrzhwotu.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gthrclerbk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtrypbziok.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtorjzeqtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtnxilavpn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdtqehyf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjruhcnwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtjlczoodg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtepdgcrdf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtmltwqtaa.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtejdjviti.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtagbwwcbs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtmrwklxff.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtymprqghm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtwlqkwjsz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtgbnfnfzn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtttyrappx.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtmhemtqej.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtrknmrssm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gttxqyibaa.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljuelztz.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjzhnmor.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gthdmnpkok.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtfwapjtkb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtptbcehof.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtfhebwgog.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtyppjsaki.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtdjbisahp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtphcxqxbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtbfoctbbj.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gterjcftub.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtnbyqefrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtqysxtamd.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtkednhvti.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtbwyqzynk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtpytwvtsc.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtgihorqoo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtvfgqphpr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtmwmgtdas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtahpczcjz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gthmhowprj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtckkbvhkx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtryielanu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtbwqqmxlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtmcpoomtn.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtyixucplj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtehampsid.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtnellvdwj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtkjvqhmpp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtjqrnuage.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtqxcfpsvk.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtnvnnrhap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtdzpcoiup.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtlltxdkff.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfguyycsj.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtunipfprl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnoomiizt.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtvnihpxzh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtiqgahzgb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtchdyzwib.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdfhdjqj.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrjtyfco.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtttbvnana.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtywhxalir.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtovfepbox.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtzygdsnet.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtivcabpsu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtobxjxsjj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtfdykllnu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtijgzmysk.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gturtjocdy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtoyuloagz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gttibldtsq.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtvzdzoprl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtyzzxgkpw.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtmhcbpsex.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtxtoaikno.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gttuqqmjee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtsxqtxsdb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtpckjhvle.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtqcnpimoh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtveiuqhkk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtswpsorsc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtqcleatxz.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtgamrzwnn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtkmfxgcpx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtngyxnwkr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtnndjufak.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtzecaxbua.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtqeseeiuq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gtweezdbvi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbspyxvxe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gthnjwbzmg.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtaizgqwka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gttaajhygr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtnqrojkbx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtvmxhfqzi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtopposxoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtqvjslrvx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtpcxryhnq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtwpvczqfk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtioyximrw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtnfqyrvft.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gthyksgryt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtltvyyygc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtwxqojkuw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtfzvxhivn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtyaktqygc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gttvlnjzbe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtrvcoxfev.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtodzywtrs.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtxkccinxi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtefgbngqz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtjgccyuct.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtfrpeioap.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtgrpukkdn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gthjjoxaab.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtulkmuobb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtxedclnwi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtqvkdbkaz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtqyicqcgg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtaocnojbk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtivziajkk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtigwknwfd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtvsdwzvvd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtpdxsbytr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtvyknhcvu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtaaipfrtd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtmoiffhrd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpnlshptx.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtmmkncvks.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkubuqyjb.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtkakzaeoa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtykmimzbb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtkhphjaoy.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtqcjvcrbe.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtevtzfucz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtoafwaymo.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtacsdbcij.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtesdrxshi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtioaojfpq.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtldgtmftm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtkuyhxdzl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gteqznrtpt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtuoabdqik.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtnqhmyuto.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtjdojyapd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtygdumcww.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtfykiwwce.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gtqpvsqbnd.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtkrztaqvh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtiolnyzrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtnhifqazz.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtrwpokhti.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtlhacciup.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtorjzrwac.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtrdpghdus.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gthnyjqgrz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtvrbfilkz.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtefvaienh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtpzgwmlrn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtjhimggpc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtemgrhvvq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtrcesvkba.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gttqirpxrp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtbsykhltv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtekpfyhnc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtwbxkjueg.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtcrvvqpbi.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtdubyfejh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtyyrzylpo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtkiaznqdf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtbvzhdkje.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtdhvpavzn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtmkzxxbxw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtibbfncsc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtoagwlvdu.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtmmquyugm.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtjqatkdym.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcchtlllu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtlvnuybuf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtyoihfoxj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtixcbxxrd.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtjqvlezby.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtjxtwfhud.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtvzctszqm.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtrebgdsbn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gttabmkwrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtrqpktrmc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtrfdapezq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtobsvdqfx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtyuiicdyu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpbpvvquk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtykcufwra.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtooqyalld.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtmxzxhhqa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtyeuvujle.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gthpedahab.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaisgtcvu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtnwpzjeet.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtoapzbqum.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtpswlkpfx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtvxfsybil.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtdneuyrhi.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtotbmyxos.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtgsyzlpwd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtsegtdyzq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtammadfas.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtmfurqmcm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtaeeweqqn.html


<!-- 参考信息 -->