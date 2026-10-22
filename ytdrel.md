代发 wailian999

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2lfdhesbr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2tbajbxaf.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gt2ercsztum.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2hpxghjlj.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2skulrpfn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2akuubbjm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gt2mtsbenwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2qoaozuxh.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gt2lgfxzfwk.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tsfvkvim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2ffqljvwn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2yzrqgtnu.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2ucdsjewm.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gt2kmdevzyq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwtxlayi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxyfsqau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gt2nwuelapi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2bisishrc.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gt2aasehmuq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gt2zefbhzhw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2xwublnxi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2ovhcockx.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnaafsnq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2qpfwazfb.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlefjqvn.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2ndqybzws.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2wtcyxypk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2kwbkkirs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2xbfhxnfq.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gt2zbdzengx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2douldhoq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2unuoqcqr.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2azflxtap.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mcltgobh.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2gxwmunav.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2tsjpaeub.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qeujqpnt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2xulleisg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2htjrwaoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2vzoqccuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gt2spnzzwsk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2qauytmbt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2gkyorljb.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrcrorwq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2pnlxvkxe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2dspbhcog.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2zgjbobxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsifvnse.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2riskzpfg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2jawnnmub.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2kpctxdzp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2omebvdla.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2scuksttw.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2banzrzco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2lxjzsevt.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2lsgldwxy.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2aphcznkl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2sbxvesbu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gt2pgjcuxhq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2uueikgrl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ysfzsqor.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2sfonvxpw.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2ukfwnmwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2hxymtxvj.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2hsxvarvn.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2xupbdwdf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2potyujgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2sygxjarl.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2sgguwxyg.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2zidzumtg.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2osuovqlk.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqjqjdvz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zebminqc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2cpdocvco.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apaffhej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2nbbhwzlf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gt2duyrxvun.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2htstepsw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2jxmckqbz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gt2telcouxn.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gt2wwwfszbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2rppqoplc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2oieqxvgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2yfjblpwv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2wqykzvcp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2haqyewaj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2qxbeageq.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gt2ioilbzaf.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gt2llbojnrw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2cyqsupsc.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2zquzvipp.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqzoeszl.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2xadvbttj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2wjgzoqao.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2efnfcdea.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2kdggfmrl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2edcizjvn.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrihdunc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2dvmbttcg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2drbtwznm.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gt2pcagweyk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2klqmrfzl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddbnrdfi.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2fsrdnbdo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtwagyxq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2ywuchidj.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2qqhovegm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktsyqsiu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2prwnjsje.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2iajdbrqy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2dddahcrn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2uuvzwrkw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2vgxjyaso.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gt2fpaarvhy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2umbhtsom.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2yvfzdlqh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gt2ltbzfdez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gt2mrvgjwxp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2jykodyax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2iptqvric.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gt2ihyjiedf.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrguampq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2atzjbsiw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2xpzqnjfr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewnlquqw.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2eirzazgk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2salnrcew.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2uuygecoy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2embknwgb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2aplzvhwg.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2hfuhxafv.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2ezzntawq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjltrrph.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2njsfgjlf.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2yrdrjwva.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuuxncak.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2qmheqhzb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyjwdgsw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2pculruhy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2qlajmimg.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2lnviugdv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2uclmjcpy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2yhpmmvhk.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqdqmsii.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2yhxtdepz.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2aivtkiok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asuoabjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ztlckgki.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2pjepwhqu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ltyubcpc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2hnovcatx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2jpghggwa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gt2xejifchb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2iotnxrlg.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2jxbhalmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gt2xplpdasc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhgmhoen.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vehblric.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2cjyqjvyj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2gnztatjm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2odjdknxt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gt2hfptlocj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2cfwcqtkh.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2msknnqqm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gt2dyshthyz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfthkizt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2aodslsuz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2ajintyzv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2bpxphpqx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2iwpnjgci.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2qpwcmeqx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2adzlzpfl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvfpiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2lgdldsue.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2bgvppdvf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2zkycvsxn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvjuuewz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2qpizulqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2dknnkxzl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2vatobllk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivatdrfl.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2qskdyriq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2fpsmfgxm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2npvxhnns.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2dtddejxe.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgyrxpp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2tqaogcvz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2iuuwgcad.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2rikkqdgt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2otghgfmk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2wqygmgeq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2gnaagzbb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2anofwxxe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2jksffyfw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2qjxsyyoz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2brxqyqzl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2sryxeyiq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeajjdbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2bytwqqyo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2chzjedzi.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2vfckbryc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqgcbcmm.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2qippqdnc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkljpuwi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2hcsbfqvf.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2qvfodjtb.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2ooyncpyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2xcdulgkr.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2yimxolbi.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2ofbgwisb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2ndceygoa.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgonlgb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2ioungfes.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2tyyyhati.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2zplcrpyy.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2iwfsfody.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2iwgjivkn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2kmtzmcfn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2vqenxnxb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gt2ujzbdkcd.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2mydeymrr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2hnfqekot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2lqdrymug.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2vuhmojdu.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2yiwcamtc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pepvzpbk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2cfipmgka.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziizlsuh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2pbuvffia.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2oifqbxsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2zvmypyrl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2peeqqnwk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2oimahvly.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2pvyhrclb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2pqgzfpaf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2nlniooaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2pdjdcpaq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2rfoxnbcu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gt2siwkfmzx.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2cftvrycl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2samvyjqo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2vigoyfkd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfqebkpl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2xdvoldti.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gt2ulevconb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gt2wbmserll.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2mqttqbhw.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2alijtzez.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2zgjgkdod.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gt2pbbzmekm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gt2wwimcpcz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2dgupdgfs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2lvbcwkso.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2osjzadtb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gt2epxrokzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2wcyopmlh.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2ljyfequw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2owfbgueu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2yaulkqrw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2unymvtem.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbnvxlv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2ticrepss.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2xgljxumx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2jrqtrbab.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2inxphdlv.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2bsomwzuk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2bfwxfsbj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2kvphqazd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pysbudrl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwmskbul.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2wmsumizq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2ytmjatnv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gt2vpdpwyka.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shagzbgv.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2yjwloqrr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2hnsbglzu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsqgjvuk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2uilzrlrv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2ilrjbgwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjzdlpny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gt2ciglnfpc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gt2mqxgxevv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gt2qqlenewr.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gt2fluwbnis.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2xzubakqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gt2zlktuwdw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2knvmkups.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2mukmmakj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2dxdzcdxs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2nnazswnz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gt2ipdbigic.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2nqcienct.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pzmquipz.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2ogdzjvmg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihlhpanu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2dhjhdmhj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2emmyasry.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gt2jcbstoyk.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ddmdrvey.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2pmjcqjhx.html


<!-- 参考信息 -->