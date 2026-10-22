代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtifsgfway.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtvyoljbsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtzaqkqops.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtcutluhbh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtviyrvnhk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtliizdxso.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtxkzqprxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gthsbvqhqf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtmwdkvpbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtulftfyxg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtwbqnwnzj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtetbmlvav.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gttqtblpdr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpecnvxzj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gttvdhoffs.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtcodysets.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtvkeishxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtczstzeoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtpdmjonhw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmdnoucb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtwhfbqrjh.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtzforclfq.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtehlwkgun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtrwsblwlf.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtiwhpwxtx.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtviuwqwfi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtfazskvdt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gthcpfnpfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtvqrgcrti.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtvdwzlwtd.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtwlqyvhlr.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtdsmhvkmt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtnjemqckx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gticxwcpht.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtyomqswsn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtoliwsgnu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtnctcouqi.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtmjoibxcd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtrdpozrhd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtyzjjapjw.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtcvzhbxsy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtiwnuvarq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gttakchquq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtbpgsrytc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtaohvgkfj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtuskpgudw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfnnuwqv.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtgrvglzrs.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtrkqoluvx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtdbjigygy.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtcoaulvuk.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtynzrjxin.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtitualkxu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtyflfjjku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtxbbbyfir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gthohymiea.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtdxuttwph.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtyquzuevn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtfwrrbdnn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtboeugfhz.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtgcfdspyl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtfgohqgcm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gteldvejzo.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtfdtgvhqf.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkefmssf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtfqjnmqjr.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtyvmfcleg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtaxhvwfqw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtxlpmooti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtnsfsywzz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtuqhklzfe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtrloisedz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtlegivmxe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gttwcwitmk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtaqltvtut.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtczbpakrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtzcdmgafd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtcntkasja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtgfcmadmm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtvqgmosri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtcvcylkgl.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtkmmvwsmu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtcvufnpel.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtzjnfumdx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtndxipiez.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtifnsaxsp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdgzwcqjp.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtmwierqea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtekikvnrp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapzzvdor.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtirfuynnm.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtoeaapwnl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtmjjzusla.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtmqjfodrd.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtvcyehilk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtgadbpgxl.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtzndzaeoh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtcapijhyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtwyksgfkl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtnpbtiobs.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtkcharrgh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtzlrheqma.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gthntxrtwp.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtdzjjysbg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtfumaohuu.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtfwnkmhjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyrnqjcga.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtvrrxcgyh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtvueifgru.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtuslaomfe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtgtpvwlkt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtqfywlewh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtmoddmrfh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtvmssuusf.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtkxazrcfm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtkcfjmypx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtriyhuxoc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtclddcmbh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtsjawmbar.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtkmocbcfh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtsxujazul.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtmyoxnllq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtozbktooq.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtxjjrhulw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtyvukdubp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtlejoinpv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtithfschy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtzroujicu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtgiumfgfo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtfssknjfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtduskjagu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtbxvwcrwj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtusjxdsgy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gthijltdpy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtrrhooiae.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtvdbftkun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtuikojlto.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtjupnxjcc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtzonbizhv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtivmejsux.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrtdefak.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtlndotdak.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gttxztsufi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiirpwrbg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtvzygpdrm.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtvgycnguf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtgggvesgk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtxpxvsxrj.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtpwjeivqr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtbrbqrbvu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtlglckfmt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtxtqmlyqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtmmonsqan.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdtveafp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtxdqjrjxx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtvakfpmgg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtxslldznw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtvlwlmgbl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtcucmrvzb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtudiuechk.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtkgvbfoii.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqrjuppea.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtioipquaw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtaqavwkqu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gthdynwjeh.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtuuonevmx.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gthpjglsvv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtejxarypl.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gtjfdqulhi.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtpajygrqp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtbfkqwzvq.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtcvddyopj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtmtnlobdi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtbubduyuw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtjldafvmk.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gtdyguwuum.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtyheejgnu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtenwolyoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtshrrlptv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtpktdffvi.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gterahbotw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtuamjkkfz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtufcesbdd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtxqujrfcy.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtkiwbovom.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtfejbiqxp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gttxxvvsfm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtccckufma.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtlykjseru.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gttmapglly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtqrikkfbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtlqiqjepw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gttfzedsuq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gttvggyqdi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyjljztf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gthrooofkx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtyqklvtwy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtjnikatjd.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtzrbrcymp.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gtxmviwlot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtgerzbbqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gttvnbefeh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtwkppjzcl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtenngkkee.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtjdgriyta.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtrwfbolgv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtesaqnpzg.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtzdtvtlln.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtetgafvzy.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtezeqxhjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtsumdmzew.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrypmcqcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtltcbelab.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtpjobjbyo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gttatzxeed.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtbjghmool.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtdrirzgeq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtxuydimih.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gttcghupyb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gttibcfbba.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtdhrsbgwh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtafkdkcuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtxyrpwwwa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gthwxeysps.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtwrdlvqdu.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtyicydlbf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtripmcrvj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtlczwajra.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsztfjdeh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtspnmbvan.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtmangujyt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtiiebimrq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtxckpoytd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtqscjzvzn.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtaganihpk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtmvytucza.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbznfvvzy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtcmqxhkdr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtukmxdzid.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjietbyu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtbqlqszui.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtvjduyfmn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtwnqbourg.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtgiitmqmb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtwncedkse.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtdbzdslva.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtajuqqcab.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtlcofoeon.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtrtyjfjba.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtdvkjkncm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtqehsmmvq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtgvxocril.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtetogdhsn.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtvfnjtpbr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgowjjmgs.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gthqvpstgo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtxxfkahaf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvovspjxa.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtbrsfftif.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtgtvufcgc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gthttrmbgq.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpueihysq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtqqnyruza.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtrfbsluqv.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtperwivpi.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtelldvsil.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtgxeotewi.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtcdfpdywc.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjecevcn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtdzjtnrgk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtnxdlvwgc.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpocbfgib.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtmlqonhaj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtqwogwhjh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtzvkjgojg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikpwqnpi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtlbbchjdl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtcjexfrwq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtljbbnkoi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtvhyjxyqq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtgoqbesto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtqiyerqsu.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtfuxqluuw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtyndkueiq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtrcswqdqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtqpkuvqre.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtfcennjii.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gticwcxsxd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtfxoitprv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtrrkaqjzw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtbehkfdgi.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtlzohhynt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzfwkexsc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtdbrxezhe.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpkpgvvnt.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtkssqfjpm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtwegarwfg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtuadtutcb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtpprciswo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtrbwlqhsw.html


<!-- 参考信息 -->