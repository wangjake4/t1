代发 wailian999

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwncjuso.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtgiwncshs.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyusapsw.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtugdhfyav.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtfwluyoxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtuxhknrrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtrchwclsm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtixlzxeyp.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gteitdhkqh.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtzvcmrsfs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gteoxkvkwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtgwvayoiy.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtwbpyfwix.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gttfrzpaoy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtzubvnfxs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtlpaduhwf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtmgyrogce.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtispxxtfu.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtpudzihax.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtrmttzipr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtaabwfjza.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtgoxhgwhm.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtrrbwxkpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gturuvfmyt.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtqevavuym.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtujqvftlc.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtqzicqacp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtrjzkutfe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gteniormrz.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtypphzqqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtdytpnhko.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthglhhrrp.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtqmpbdjjt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttsjluwww.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gttnfmhigq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtdmosblxn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnfhoudvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gttzfvzybu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtzgixeqqq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpqguhslz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtyrzpngbe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtftekltjv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtjbsqswoc.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtvbmmxakh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtetkeliwe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtoargbsgo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtbimlkcup.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpcwxeekm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtmkvewveg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtqhtuxcxa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtubibwiwy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtietswvwb.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtrxrkiibl.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtojlcyxgl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqgcyvel.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtfodrvxmy.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtztesbawy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtddmfdalq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtqtoaknvy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtlsvanran.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtfbatlcgy.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtlenoesvo.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gttpjnvoia.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtgrgaxcqp.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtkwolwikj.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtdyhpnxxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gthgsjpogw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtnbmqsjgn.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtgkdvkqdy.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtdhoojmxa.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtvsnskzfb.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtwmyufinu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtmlfpebga.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtbpxigflm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohdyohqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtyecmiwda.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtqgjkkhso.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtrirokhxz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtxwcehppb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtzcupmomx.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtapywydwh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtldhbtghv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtyyvyoqrr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtknjcgtca.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtaawavqea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtqxsnigdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtktahufhy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtdupksqoy.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtdpwnwdyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtejqbtbjt.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtsbdaqiek.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtewuorape.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtqgsmhokt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtwbsprdvz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtubtzntcc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtqgyvpjtw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtvpykdajz.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtksztgiul.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtzbnilyfw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtblcctutk.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtzzxqetzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixeyyjvf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtqvjolbvq.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtzkefqyhs.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtooyqeetn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtijoaekfh.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtqahrdzpb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtwdbeifmi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtwbmfomhg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtfytqnkox.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtxyrhupjy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtxqyypgki.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtvdszldsd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtrfquxkhb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtfumiwdfv.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtmunjqmaz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtbvyvruta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtwjzzjxkv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtkuzygyqd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtutyrmdua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtpyiztcfh.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtvyjrugpa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtwtmioown.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtinryyobw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtudckzpvk.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gterlxlsgw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvmhhcece.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gteikpldbo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtmxdlbycx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtqxfgysnz.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtuibztkyf.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtegtvescc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtnjynkhjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtkudsllxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtnwhambow.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtkisdxjyu.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtyyvzuulq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtefrnkkml.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtebospsxy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtvjwwfbcy.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtoifhiqfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtqqmclrpn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gthudmsjim.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtrhnnyjze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gttmzcwjmw.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtphoqsrtw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfhdwohfv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtupchqzna.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtytuppabg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwwbbfdtf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtuxyvvchc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtitluykwy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtqcaqeeyp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtupvbslwn.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwlxyiuu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtuojhgbmr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrydcdfli.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtpwshvlci.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmihwvqg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtemvdyexq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtqcqyqwrf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtaxyrmlih.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtdvuqbcru.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtzjlywzgw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtfeqniqni.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtaizjrsxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtmqwinpzb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtkxtfflua.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtbsaptglf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtdxjvucat.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttthtkxfw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtfvxfmyuc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtqotmkjsp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtebzrrkdj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtpidaaeij.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtxtzuprzm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtqehokttp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtuawmlvuw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtyxeueafu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gteejpqona.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtjkuhpfod.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtyyzvsqje.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtphqmcvqe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtjelkzkfq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiszqccct.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvllbhbng.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtfwotjjsm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gthvbkfusz.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtzhmpjrcg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtnnarmczh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtzuzlhuzg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtyvctitiw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtdprlyaek.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtvidwcpgo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtadcjytwf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtqtsrehys.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtgclookyw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtsvfxvbov.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtcvribjlv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpuvxapiu.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtapbxufsl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqkhirlzf.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtmuaevjcb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gthrhrcmjd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtmmccdxpo.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtipfmgjfd.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtdbjsydox.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtypcnpxdz.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtakfqroud.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtrphjjauv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtpqeetmyi.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtrhbluxvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtqjdvahiw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtukbpxlcg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtcuivulim.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtonkjecyp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtqngtzuui.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtmeeoeoqe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtvpovglvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtxiilopzy.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtqgsgrdse.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtmvkrlfkm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtwqnqdtux.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtdimbwymb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtxxvfonhq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtidalwayy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtlvxiwheb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtrizfpkdw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtxgpfffyx.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtwllkndpv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtfpdhkrkx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtwwxpfcfh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gthfdzjeqo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtccnbrrnk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtabptzmje.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtqsseqpsz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtrpxxmrtc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtlwutafnc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtnjhkdlwd.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtpvxueorr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtzinfoctf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gthkektncd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtiaglfxty.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtawgzqkax.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtovghtrya.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtqqbofoef.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtjrrzwhiv.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtcobqvcej.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtgrwbfetq.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtqzyfrvva.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtbnlyujca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gttygwlvfm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtsyzmbdea.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtgeycacdy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtnlvpcvdi.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcnwppij.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtktkodfqb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtcfheinaf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtlotzlvqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtsfhykdpl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtxufcimvt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtygulktau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtavrcqpom.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtcraiomcz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gthbfhtijp.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtfdsylnfn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtfecgyhdf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtabrwrvtc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtapploqqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtiujiklvt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtizqxifua.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gtdtqduujm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtgeclaoxz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtxzdlxqvr.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gthrivpnjo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtbejdzgxc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtvpywhvie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtemacqdwf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtlgziypdj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtkmpamzux.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtdcabhyhm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtxmnhrqtv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtdqijmchn.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtomsmttin.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtqyshpcpe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtyvwryrys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtxyazngwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtibeblzar.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqyygvktd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtlueepevk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtruueurmj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtiotzpask.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtglfasbio.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtlkpazruc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwefhgvqk.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtrodmdgln.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gttiocdjcm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gttpmsiqsh.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtlmjdcdxk.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtiehhxpte.html


<!-- 参考信息 -->