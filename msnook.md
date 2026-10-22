代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtgevcpzzn.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtdmcnsptw.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtsrtrwmrd.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtsydedhfg.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtxwkjkiiu.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtgnpbxspi.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtwlvuaezr.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtchrdbxgc.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtnavswgse.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtdvdiqerl.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtxkdpprub.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteoxjhsq.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtmizdpnza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtivjrjtnt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtzrkbfepv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtwsurljsr.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtfoeifscp.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiftliynq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtrdxumsfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtxzohavim.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtuacghrdz.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtdlsvnhtt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbhrtcry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtpzoytinn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtihtsrlhv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtwzrkfszc.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtaxygkzez.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtnwyqwmng.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtjgxwjiks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnsggldjp.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtgtmzwigq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtgxxtzuea.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtqvifotwa.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtijncucyj.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtiyrscjet.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtjoitcuzv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxzlgexh.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtczctfipk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtufnxnhiz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtixwyxahd.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtqdnrqmno.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtoibzxeae.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtqozomqjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtwguyvgyq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtlahhfwui.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtentqrqoo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtqkiybvsp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtbkamwdnu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtidkyqmsw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtzvuwvaom.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtmhjocltb.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtuajabqhu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtsnqjsrpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtglkwwknu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtixggdhjq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtaarnxkuj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnfrjktwp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtjfpufnxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gthkjwxgaf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtaiagaqnn.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtpveoupwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtolsgzhau.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gttvwrudwp.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtwuexhpqh.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtxfpwyqvx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtxkhqajpi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtqgejzruq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtokjlpoor.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtwzvmafsk.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtvesagocu.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtgceiguhe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtohbpcqyf.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtonzbtdrr.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtexnvjfwa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gttanqabwn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtdmhashgs.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtswptqobo.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtkqqimavj.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtmjrkccxd.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtqfpqhmss.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqcmmchp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnhpvveka.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtkxutnain.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtrtfeuamt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gturuoaqyo.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gteuiioynv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gteyamzdle.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtruwtkqwq.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtwadelinp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtaxifqvgg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtrjnyxijp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gttcfnmqcg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtpbhokodj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnflcpcno.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gthippqapm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtnwxswuib.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtcknbeewu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtbufanbmn.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtecdsvhmp.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gteawayoxi.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtdnjwwljs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtnavsehom.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtrxjmpvis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtrtmqzvvp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtsmxmppwj.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtvufdntgh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtbsncimxl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtjpdtlvom.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtbuofzhtb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaqiruai.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtjquqffal.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpotdkej.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gthlgigzoe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtdzrqctvt.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtsmrrepzk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwgcnaf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtzyrbhynv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtjcaoxsao.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gteldklnev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtomhrocfb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtwicbapyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtkwkrrbia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtcikftows.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gthweihjxv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtdulqabxj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtrkgsxsdb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtznhsxjyr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtacwbqqjd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtyjuojejv.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtxnhmekig.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtxyegpvyp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtoywpncxb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvbzzakwy.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtdwcamijj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfuiieykg.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtnexlidxm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtxmolfxon.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtsokagvlg.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtqkmorgjw.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtpglpprhr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtwkwwhrtl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjrqhqzvh.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtznvzrnus.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtianrpdkr.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtrqcuhlzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtdzzuanqk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtefqbpnlo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtqsgawumn.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtphauccqh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtesfjcbee.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtgofsburw.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtpoklyiru.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtfieernun.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtstethpgn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvusrlaa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtbeclxncq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtjojdwnaw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtcuiqjhcw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtomgtnerh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtfoanrrlf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtjfujsvhr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoyonvdv.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtfzgdsoum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrwqdvonp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtasugleen.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtbikrolfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtvwiltvvc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtlrxsycle.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtnxgrjeok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtgeqcxdej.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtgycawijs.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtwdymwntp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtcoilxwox.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtynodbgez.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtipzkhzvj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtrmdvedao.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gttaqacfcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtvvdollzm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gttlkxzdre.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtyinstapm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtxeqdgylc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gthmfovoxu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gtjtkaxzes.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtxiqiveme.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtyrtsilbl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gthixbozgo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtveehkztc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtfchjcjwi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtsgogelca.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtxtexjkcv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtnphgnioc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtckcnlhnv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtkuarhbxj.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtwvycvzgs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtwjqrmdpa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtxucrqvdl.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtzlejgooy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtslzwwson.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtzevucfkm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtvxyuhmhn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkafodevn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtanpptyuw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtjjllqwvn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtwwvjpqhr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuggbpcv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtmjntaxle.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtrscijmvr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtexjeimog.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtzurvmuza.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzvhnthxc.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtpgbjoxmf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gtdegopyga.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtdxsflsyu.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtaflshhqa.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpvpjfvh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtqxkqylgm.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtseylpfbp.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtwqrbxvug.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtflojergx.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtbinsgsyk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtslzsmvjw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtkzmmnkcf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtrzxtrheu.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtexwahzhm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtvuznvwpq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtohguewbq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtmzoclves.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtyuwxbizt.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtslxixbuf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmhxbkwh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gteuavcpeg.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gthmspgvhp.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtuffbzmym.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtaqemfoku.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtazugciad.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtbyezxybb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtfivmtsqx.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtbrzddurr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gttlybbpps.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtlmifrnba.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gtldrnpskc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtyjifhqpq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtpcjskgai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtjmyrtgfb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtyhobqxqx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtyqndiajm.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtdxcsgpcd.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtsbdbgrid.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtkvobkanr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtyctgisyp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtxougvwjd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtjorjervj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtwwljcmov.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtbpvwzqrx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthngsazvh.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtqnnwxemm.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtunysieqc.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdnypiwb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtejfbyabu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtixnsmqfn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtujrbzlkp.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtysmqomrd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtiqqwfptj.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtparpreuc.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtnzhgolpx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gthmqeqvue.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtjkirzeby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtouxuatkg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtjkijduev.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtjeffxfij.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtxafrvtpn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtuqygvdpc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtankxgxwy.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtfquiesyg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtgfwbriqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtyznluuxw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcapkivjj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtzjimthuo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtytcgwlzz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtisudblne.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtwkpejcdk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gthceiefud.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtuxtuzzoe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtejodxalv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtcdvdvpcm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtvycqxwbj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtkokyistg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtkrbogshp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtustpxvta.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqfmdukv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gttlqgrasu.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtxwlfibjx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtkjvvfouv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtholxduqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtobsztssp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtlasjmwey.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtdaimaiuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtiwoogbsy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtovyswgzx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtnkibrjyz.html


<!-- 参考信息 -->