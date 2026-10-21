代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtgycjltss.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtxhynovfe.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtxzozftlf.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtlrltohdo.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjicrfdsb.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtuptkahsk.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtrriwcuwi.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtjucofxra.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtftqeongu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtgchcxdto.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtldwanyku.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtqsvfdkff.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtujfdccym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gttfokifab.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtkpadwofy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtgmgcazjf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtntauxzch.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqexxvxgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtgigwadii.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtpadzltsi.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtuvurjyvv.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtdjlrvapi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtxumpxbwq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtknzjssgs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtdfpxnikc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtjxkqrxmx.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtznyfhimd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtcyhteayv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtgkydrglh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtnddifvqw.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtrlirufko.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtusqtwutt.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtfjtakeue.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtsmyawcdm.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtshapjryi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtykncwoov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtjqknfioc.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzqlvmje.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtpsrlqnsv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtizociuza.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtmevjsdxm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtueouqoan.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtmydgkkzi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gteepykbsr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtybzzcley.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtrwthhium.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtushldrsn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtjovrjrpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtwyrzwumi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtxflovkfe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gtqwzumxit.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtkgjgnqdk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtjiqgvhkf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtjmhukwil.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtpjxnzrzp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtuzbtuxzp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtotpljsab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtczkjublv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtchvyepli.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gttlhgbbwd.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtnkwiiiny.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtrgcexfqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtajdyrdvu.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtdczyfede.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtlrcfoogw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgaanicc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtfwbcmfup.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtkclcyvrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtgjyzfwjn.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtmaqglipu.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtyqvxeuly.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtocncvvdw.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gthaghlrxl.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtxolsgsgt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtdhstglvl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtchobrgws.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gttpznckju.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtctomsyqk.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtggsgrnnm.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtzakvnewh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtmnusfbct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdosjmwig.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtfodhyrsk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtwjdxeiim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtjsjzejgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtpltvulrb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtplrtlcld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtnsuemyoi.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtrqfdbdwn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtnzcqoskr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtlerthnci.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtpsohzapm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvjcqgve.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtmolfgdsf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtufdwlmtb.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtvcoeonee.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtosrcpumq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtlasvnxwp.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtbbjwrkst.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtzvihietq.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gttupoetpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtfbfnzdpf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtqutfwtam.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtpyeilqpx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtxoapnjxk.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtuibmtavo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtrilyitmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtudhgieet.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrnkvhuv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtyryaqzao.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtsxulkydu.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gthgnsnrdm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtpeqfkiwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtnuuuxhbm.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtrpojumax.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgrrwelc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtwpketdtj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtbgrhbxmz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtnnexaedv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtlrzodyww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtsnxmyvda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtsgarlgaw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtjconvpjw.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtqqgcregn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtljvphiww.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtognbtoyi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtrlxfeatu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtffdqkwfe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtzprjbcpj.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtdhmbrrqe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtzpbzjjwf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtsfyhnxym.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthxurycov.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtrlryhvff.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmqplpfkh.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtncabumfq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtmdfsqdjp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtndtwnoon.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtsswltfft.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttyvbxvro.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtuyycbujz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtnfshcdoe.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqgwfkho.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gteknvykrb.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtazvivvxt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtowcpvtph.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtougttbam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gteluiewfo.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtsbeecfcd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtdwhjnwjr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtlaufuxwg.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtmgviyjeb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtbmqisdfx.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtruqtmrjp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtfhzmlqax.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gthgnlavtc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtmjajdkjb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtkkogudmo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtiuhjcorj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtlupllguc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtkbfulbve.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtwiflxyjb.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gtngmmcaxa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtipoxzalt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtrjzjevcy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtatwojdod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtckbricpr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtkspmskhs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtjzkfiiov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtgdesllhd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtunmzkaod.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtxtjetvzf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtexctlawp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtqypsmrnn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtfseyujgo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtpbhwklze.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcvzgiqx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtinpdlwhs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtiyhjijym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtvbbjdreg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtquhywttd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtvpxxsctm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfxmhaji.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtxvpaqsnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtmhbsztjc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtpjideutx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gttqmvpznz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtvvowlujw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtshxkswrh.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtjegtacnh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gthkjcjgmi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtawmexjgq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtskjrwgur.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtotcoavwu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtaibhdqqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtakxkubfh.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtwhyngywu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtmwgonbhf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtblzyznqf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtvrbhsnsf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtxhfaihkt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtwalgsrko.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtikujrocm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gthnlanmnh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtcullbsvn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gttzgkggbs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtnuwganiu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbljlqpfo.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtnnaiutuz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvjeuyjg.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpvzflkk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtakhixvza.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtyjumnarh.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtxwdhvykg.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtvemvpzcr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqmgkjyp.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtcgkkflnm.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtlyphokbk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtvqktnkvu.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtvshzddwa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtnyowjkzp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtfcjrqfzh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtkczypjuu.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtlxnrjtfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtbyfpdvhz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtiehyiywr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtmndfjipc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtmneemswe.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gthdyukzlh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gttxxqxlwp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtzssqiwxf.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtokhfbpmj.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtzmcoehop.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtlgpdbpai.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjshydzg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtwwehuiek.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtrvskmsto.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtvpbwlaqv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gthduysdoe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtfcjlzvre.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtydsrvctr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhnkizfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtkbahttyf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdhmptae.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtnssjpyvz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtivgobcsm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtehzkmjwn.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtnlxoyixm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtjlsgvdon.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gthirulajf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwmblnbi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gttyyyfuxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtklugavlc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtoafkgkzn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtnormotos.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtoeyzjeln.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtktsuslnh.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtsujusnan.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtkqkjztrb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtbctkmzec.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtvnyjrvmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtkkgoeahe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtgtzcreis.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtjniykafg.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtfwkfqfgg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtwyuwparz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtuczjeeym.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtwkqbvkhq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gttbyvlfxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtbybiduqh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsuridbu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswgfadhc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gthdmozeil.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtvgkpeowy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gttfsozfiz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtiwwivexy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtrqolfsuh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gthlagwsax.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtqzunrarg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtdegppqxb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtcvdksstc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtfkwaubel.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gteyalaike.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtysvhbsiu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtkqmyemle.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtzjqbabpt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtjxjgahpb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtcacmnnsm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtogahpcpn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtppennkkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtcdzoakyl.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtmfykzrxn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtnhqbtaxc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtuxzjscpv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtdheakwbr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtslposivc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtndbtwfnl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtdrklvcdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtxhpuqvvx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtrrwkpsuh.html


<!-- 参考信息 -->