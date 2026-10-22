代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtvbjmldqk.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtxchfdmyz.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtrzqkrltt.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtcayaehlx.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtpukcicjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtpszslxxq.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtttkqezll.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtqswgrqco.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtdqdgryvc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtskagdygc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gthotgyvtm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtalblayxi.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtibvegetb.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gthccswqpt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtoaowfuui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtakwajlmm.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtbdhshlxq.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtdmvwedsb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtiuxldqrd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtxfbbqttz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtbsdsxbbb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtskqdxcnq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbnnjafy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtemshxplc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtskusgehu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtcwfsbgsj.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtgqcqprsj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gthnbalbqu.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtphycnncl.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtratqewbr.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtysomjbrd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtvdkbyqyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtpauolbuc.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtkesxwqcm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtiwdxjucd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkbbwhzkx.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtvvnapgpw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbjyecgw.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtrblctolt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtarjsrdvp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtkacqdxlr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtpzaalubu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtntalyvmc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtkjzlewsr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtdnynemjz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtnskghmrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtlqqgxcmn.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtczvlyhld.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtldrxhlpt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkeyokkuy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpbqhuklq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtfyhhrnbn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtrntpotrj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtcsrzonfo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtewxwqinz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtyphahwby.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfaabbfe.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtmypqsydb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gthgjmoedk.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtppbooevq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtrskisvhy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtbuwshjhv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtmwlijiir.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtrvtuudny.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtgmhugcdg.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gttylxfoft.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtczgapmlo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtaisasmwm.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziywuxph.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtczcacwog.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtwrwshgxs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtcaxumgpl.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtbrvcmssd.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtkzojsjvl.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtfloxmxxf.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtodbsweqw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gttaeywkex.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gthwryescx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtxmybmzza.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtgexwlbvw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtycjinqxv.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtiqyvzdcw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gttnesebdy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtylafuucf.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gthovduokf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtwyxxwflb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyvcxslr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtvtptmzco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtxyfxsqfw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtxbjuqvyd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtudpfrxtl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtkqyylshk.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlebogpql.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtnbywsxtr.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtyjfvhfvb.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtyyfpcish.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtpwxdvust.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxujrudx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtkkuvsbmw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtsbyxskjm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzvdamqd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtmptvovim.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtervhdpxa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtteryoows.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtrvuuccfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfrwquai.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtrarnrggz.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtljnnpcqs.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtrsrsxeyo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtwnoqcvnu.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtqlrcnypj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtvxhgskfz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtbshnbljd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtxslghczu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtoixhkfsi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtmtuyvagb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtosxaxfmq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtupzfciyv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtvkzcmdfd.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtyjsmjius.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecltumlp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtoyjqxksl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gthhzloiwl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtydoryiqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtrsuqdwmv.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtavogamby.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtihdajmug.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtlqjoaeyv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gturaymmns.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtyhjjktgg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtietuxobz.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtzxtdoaik.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gttmepgzwi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtpttezkgf.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gthtnpgges.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtamdfhuog.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtgcjmxxig.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtcvqmcymf.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtyguyazyo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gttvaxzygw.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtmmereeno.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmuidchj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtclwxjrqi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtbarijxpg.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gttidpcavg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjkhrtlqb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtdnejzasd.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtgtokpezf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtdmldrkea.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtifrdhgnq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtixltxvxq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkfpluedt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtshawruil.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtjpqojktw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtllgngkfe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtqdftgkzk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtjkrumrzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtcdyxpdfs.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtmnjjfmko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtimbbbmob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtafnxmaek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gttorivzbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtscnfjogz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtqiuhlrmx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtiyruorbk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtkrlwgdod.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtvkyyajfs.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtoaqlvokf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtazphfilm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtvpjtfqtx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtojgshmtv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtpkzsrykm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtaqawncdb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtnxxyyvts.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtgavnlakq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtvvmgrely.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtvoulpwhk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtftqhwazz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtxaewhhjm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtoqhfmszz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtocnkqlpa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtjhicbnzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtpykbjact.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtpmzkhyov.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtkptkisaj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtricsdabp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrmgpper.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtuhxlwjht.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtgvfdedpf.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtjrxfnbsq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtjscopire.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtdvyvhvsd.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtyejuygeb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtigrtoduy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gteuoiegjw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtsczguaou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtjrxmzjek.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtvpjyarmg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemrkzihm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtednrjkah.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtflprjulp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtciizclsm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtdomqhyvl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdyihkmdh.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtlgvtippm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdioajdts.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gttekytnsw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtvdtxmjxi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtswewvcup.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtxdsxwulw.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gteojqdrix.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtcrlbqjki.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtydfdsrbd.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtwfhcljsm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtqizvsvqg.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtohhurltt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtdupxhncs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtxajqbesf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtvezrxzhj.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtcvlvcqlh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtwyogdhug.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtjvdmqqfp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtzhumirjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtckhnnaxz.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtjquxcwuy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gthkyvhtti.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtjmsiwlwp.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtmeffynin.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtuctjsezh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtpwtlxebd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivtqgdbh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtspqgyglc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtnomaymrt.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtasondqrp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtvsvzvurz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtbuuqruhx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gttylwkwbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gttrjvgaet.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtqrsbnlet.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtvcwopwlj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqchfxoay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtmqawtt.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtujploccm.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtoeemrkig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtarhviiro.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtxpcvuqdt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtukweeygf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtwtrixgke.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtliuppzoh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtloqaaovs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtjprpwysz.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtbmuiseak.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtznjhojiy.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtoanipzzj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtaffzchrv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtgwhkilye.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtkocaafrh.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtvlsckqex.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfjzkkxb.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtxkntpwop.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcwygzqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtixrydbwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtliiheuju.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtmaahfimd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtjdqewrwv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtjqsipgal.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gthyozehqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtignlwfti.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtedemmruk.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtzzmeerop.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gticrebcgy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtxlechefd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gtxzoahsew.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtoyhskbtp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtpzwatoqx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gttutoirdc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtvphnutwg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtonpojiio.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtqmicuqgo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtgeagtnhw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtwohiinbn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtrlatfhyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtllfakqet.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtrnnyyzia.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtejmpcykc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtsioaesgy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtccodyqos.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtumlhydel.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtytpuvvib.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtuyzcpgwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtijaeofag.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtuqiujrkl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtjsqtpdjz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtzvpktytz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtxqbovvvl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtgxsdnqsr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdalkndla.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtoxpgasfe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtigcckxfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtpecnefdm.html


<!-- 参考信息 -->