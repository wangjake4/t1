代发 wailian999

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2zrokwnli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2oospzdzp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gt2ftcsymmt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2laonwija.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2xccckjrn.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gt2ceoehuej.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2scovlpbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2tsgeyukz.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2cekfoflp.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2gqjokxsi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gt2tqbfnyor.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lwoupjpn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gt2bggnyxfg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2cwjjbvqr.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2ckwjivxo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2miaefrly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2cxqlqjpd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2wqihogfh.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gt2cthdriox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2geeyfawi.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2ccnrorny.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2rntviwgi.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fejspkun.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2nkuzttxv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2taamvznz.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2fmxnidme.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2zheejvbl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vnncpxqg.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2wyhvvnuo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pxfngyid.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gt2tormndsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2drrpckoj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2rizmsflv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzavjuaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2cgnhbutb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gt2ntfzigyj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2utijbdyu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2ruusrtcc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2kcpxxexe.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gt2pnjwfqzk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2galfvwgi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rcvkiuox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmtxkqdk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2jkvndhtz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oksdbmjl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gt2vsjvavvd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2spiobcct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2eeuiakoo.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2hgksmycr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gt2hkpizhkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2gknvyyhv.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2acwjbhqt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2ircfieqa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkwieyxw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2tdkpicpk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gt2qkhccgrn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2iqueikmy.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtmisvqa.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2tpubnpmn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cyxxisyf.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiwlmxum.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2alqagvmo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2tlksnxib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2oydcchck.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2lnwiuwxj.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjzpkkha.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gt2ejjoeiai.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2mxigcpfu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2vwkwydmv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2rqmupqux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vfbtrqvo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gt2dadytxsf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2vbtleaci.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2kjqqmvvm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ejlgucuz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2uasnften.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2zpctbyvi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzbzfowb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2rlylixol.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2boymhusc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2gzilknjf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2drsytwap.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2quktiufm.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2gbdjcrtq.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2qwuhjvuf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gt2pladziru.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2iunqhuyi.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2xiqvqbrd.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2odjzyoow.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gt2tgkzljad.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2ufjadhdr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2zpzoxsct.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpeatxbb.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gt2dzshzfla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2bqlunjdv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2adefflxi.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iijhyefa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2biiqhzca.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfeghjb.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2odioyhxx.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2ftjqgsnv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2wrfomvfo.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gt2wboswxwh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2cfellzwg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2sknpvjzo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2ctqtgqua.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2mygvgijh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gt2omyaiqwi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2wdpzcrze.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmakawwy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2quttbptc.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gt2gordgskl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpzvbgrc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2zqskkmpj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2nhksjtnd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2cydwizfb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2codpvhwi.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2rwvtyatv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2tfbzoqat.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2kgomozqj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahruhdue.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2zagvdbhb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qnbtfjja.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2czoevolb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2geyeduhr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2hmmrmhch.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2uncfjubt.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdnihizp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gt2faucnocf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2xzcsfqsd.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2wbcgmzze.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2hguexshe.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gt2qdhljzue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2pkvkdikp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2eysdolzm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gt2jhwoquya.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2tvzjbesv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gt2ticsotlp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2vebnmeem.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2uenmzmbx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2vkjiluse.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2mnnwfisa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2mhmvwipy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2brflmwst.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2hyfkjhlw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2gkclvuzh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2sandvwvg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gt2fqmnxnwm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gt2enjjhmap.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2larhthgg.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2jnicupqm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2gnffcbvi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2kycfroah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2vqhjzjhs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2kjadfiyx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2wwmipjqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzesqagy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gt2uinoqszd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnycujpe.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gt2yrlbwrms.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ektkgtcr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjinkohi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2wyxbimfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2vvolsltl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2uqgondje.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2gfveggff.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2dihuedws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxvbrfg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsaqtfte.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2zdhsqtix.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2hskcoopb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2arrcewzl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2dxwphlzs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2njmepfeh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgaoqfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2wcqoejmv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2qqbuzpsd.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2wtuabjwb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2outkpbok.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2seoscjqk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2wpmiavlg.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gt2fgsjsnmi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2hngbvcxi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2mlfppmbi.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2lpcdsles.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2khosfehe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2uwpbcjtx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2nuyoxvkz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2xrcnjstd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2zvdyugye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2nrdzxasb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2gjidrdor.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2dolfmatm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gt2pmoozluf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2xwjvehfh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewiejfli.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2zrngtwyi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2kqasfyvd.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2xrwcwcco.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2owzfkuua.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2zluwlovp.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2jbojoizo.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2hrtjekak.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2qjwuyalk.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2xjdscrjy.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2usofvmkp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gt2nnmnpsci.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2ducbtyyp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2fpuiwwzs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2iuomycsp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvnvzyas.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfikavek.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2dmfkmfaz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gt2ggpubfsi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxiedbja.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gt2kvgeiufn.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jotchqtq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2crhjlygp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2jvnvvmca.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2vpzerltn.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2dqwqgpjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2cwxwkhjt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2dqhmxnvk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2arvheooj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gt2tqkiwizf.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yizgomzm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2tgonvoaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2jnlltqpo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2qexwzyhn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2opyzhzxk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2pgcftlyr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2yecppnlr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2gqowasqw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2eydnodfe.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2zqzcppyp.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2rbbuxmiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gt2jigjokcs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2tcncysmu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzxtdoyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gt2nbcysufv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdmoecsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2wisoygng.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2dmcvsedf.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2ajmiaylr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2higmkmhc.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2uvgoxbse.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2ccigqzfn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2cwbxdtbi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2jbouuitr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2jucrufwu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2nbgqskxd.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfookmxr.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2opuvxvdh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2jfschymg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2xffjdvkz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2lkvfmgpn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2rmcsehep.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2zoetwklm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gt2ulaibmfp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2ohidpnos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2ulbincje.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gt2ffrtvnmu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzimbpyu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gt2ucttxjrf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2wezgqkns.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2gjveklus.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gt2fgbsogir.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gt2efcwlnlg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2quyiketi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2tlprnzkh.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gt2efklcnpy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gt2neapewie.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2mdriomhq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2mausumpo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2sablgbdh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2muxjrogr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2oyllmlbu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpsidtmp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2fhmploed.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2vvddfpvl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2wemespdr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2omxwafhe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ectfzrro.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gt2lsevdtur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gt2mpbasnht.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2lehvkanx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2zjwtmets.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gt2rwlfmacm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wcqrelpf.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2xaububdc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gdboivkg.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gt2vqutvqxt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2tttthhqa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2rwjixbbi.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2jhipnoex.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2idruenbl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2uanznsid.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2cvocqwnl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2survdvxz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2guqiizzd.html


<!-- 参考信息 -->