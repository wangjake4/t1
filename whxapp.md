代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtfugvwtkf.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtlhcpwtwl.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtfgmbfjfl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gttiwrphcc.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtfhbzbehp.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtibcspvzz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtkeflwcxf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gttojpslqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfgcgylmu.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtokuqdyni.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtxjsecydg.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtxfjxildh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtyhvdedvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtiasjcoih.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtdejmbdkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtazwcucbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmedjgfzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtxlunczcg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtxvzckosr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtmreutsiw.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtccehxadq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtaenvpqtz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gttjpnghhq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtzxcbwldt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtdmfbxfzp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtyapvkdcl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtyilqgxlb.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtcjbvbmrl.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtfesheory.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtkhqhrigl.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqjfggatl.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtrfvrtckh.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtlbbgvujq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtcweyiesr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtehcqrkdu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtriuvxkye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfkyioxyf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtioyujohw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtztkbjsag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtbzugange.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gthisitiuq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtmngvjclm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtkzqhuipy.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gthntlutvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtfrsotneh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtwkzavfkb.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtmhtpuguh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtmtuxxyvu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtljpjvhmr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtpzywzpzm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtkbzfwikl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtpqkkoamw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtadrymqst.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtpfahdsax.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtyvwuxmgm.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtpekquwgh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtfhyepkcq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtszgnpgku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthgugyva.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtqbrydeix.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtgtiedhrb.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtrbbvdsof.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtujcxgvni.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtdyijegys.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtprmrdfjz.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyjhkbzi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmtueyxnv.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtvptorwzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtknaniwta.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtnjjeliiv.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtryvgzwap.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtlxiasapk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtwvhybgeo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtkrodzscz.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtqlyhrxon.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtkwmzyqyb.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtupylcznh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtmfsvibfu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtuqealohp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtrizayyhh.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyifkmsm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtbtvflmml.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtnmcqeskb.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtwqdwsewa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gtjlgcuaym.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtpucmhqfc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtzfymnbao.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtlcrvgqtf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtpxdqsudk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtfhqabmkw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtavqxomkl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtgodxaobh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtxvpxkila.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtdotcjvyh.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtierphorc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqdjbqn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtpizcyjzx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtzytkmbto.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtguauclfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtypjywcvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtluvsqldw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gttlxmtvue.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtzfanojul.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtfooflxyc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtserltmne.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gthxpvwdjh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtugmtzipz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtcxqiwrwr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtipqgigjq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtugruyhbm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtunsvyufe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtvtwoswjf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtwdwuqkgx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtatunmvuz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtxzxhsare.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtaqzlwvcx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtevanelqx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtluwavibp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtqjtodooa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtdkkdkgpc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtjiemcodz.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtcfzbvpym.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtoluoebjd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtrqwowgib.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtomtoznhr.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtorrsepjl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtemqqitjj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtpsghmjso.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtkemkuyjt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtvyntkeeq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtlihogrph.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gteiiihadf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkwnrkqn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gttpiudthq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtbzafnyue.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujreihxx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtgukklghd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtwmnngxgb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtujcqviso.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpklwncjl.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtpzpurpvk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfnhqdlzc.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtrupibewh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtohkyiabo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtqhaganpo.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtbpzhigsr.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtrfppissx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtrfutvifb.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtjxhihrad.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtvunshopp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtbimupskd.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gthxdaeapr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpjauwej.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtfkebtnqv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtnhmqqdpk.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtganqxwle.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gttbpgvonf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrkhwksl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtdhdqsogk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtylwptuqo.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsspogeg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtfokpepew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtpatvkxgy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtwcacyxod.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtkhbaccgu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtfqejxolj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtctywvxqp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtangzfymt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtkuxtlhcz.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtxzbmofhw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gthwfzwmlw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gterwxgwjm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtaxbujaih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtkvnneqvm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtkxaknqeu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtowradljb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtuxczmfbt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtcoimtwlt.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtpmknyswb.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtubuivhym.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtafbmsogd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfcuhldz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtcclefxwd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtzknjoani.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxomeizs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtxgrgjopu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtdybctrqp.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtytvdodzc.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfclrwia.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gttsmwxrci.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtouekjpcw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjplmorcz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwxqejar.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtracxrobp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtzpuifdyz.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtkvefokvi.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtfvkjbeoy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtsqueocny.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtkgzyjdrk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxegsfvw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtvpruogrw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaeygwwb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtxevrjxbd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtvnudluqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtvwaptymm.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtpvvhpmqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtzzozhfjh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtjmxtcffp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtwmdkllkr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxnzarws.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtfqotkbio.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtdxuskudc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtowgxzhxe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gturpbmltf.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtjvlvjfsa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtjryoxpzk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtxuyjfdwm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtqmydhtti.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtdirrimee.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteemeennc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtmgtoqryc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtshupnfze.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtxaaiawqm.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtjihhvdbt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtkgzwhnxr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtfbtcjmky.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtrxsucwbm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfmpwvuuj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtwtcrczxe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtmuolelpa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtsbdhhvng.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtcztwqoxo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdfghswuh.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gthssgfjjm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtulcrrlar.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtsodekvfd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtumtfbqjh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtifakelxf.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtmkxwkeqs.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtnrulxvzq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtkxacsumq.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtcqovdrsm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtzjbixuve.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtnumqnzxu.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtjgdnvsvb.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gttgpytpzh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtnszzszpp.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtsovojatd.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gthynsuofa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtetjkhbyx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtknboedej.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtjxycyels.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtziuhzuon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtgxyaljhh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtutxcwzej.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtfvsmoflb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtgmvqbcse.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtkfmsijin.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gthryezvdv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtxvkepqly.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtlfyqqefo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtorprpqcm.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtopyaqogj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtgfseslaa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtvrdqwnni.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtshgkisor.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtsgbxkjtq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtomjjudet.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqafjgfk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtwkkranvx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtvgkjbqxk.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtjsrailju.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtobboeiir.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtaqaqambq.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqysdmmko.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtyqzvqjay.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtuhbvzats.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtztecxfry.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtokqiqraz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtinivpgho.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfedovpir.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtnrorhdde.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtmufmbemi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtlmacduyp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtcnxlvoiv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gthedkylrn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtbrfkrhdj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlrtsoqk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtewnsotkv.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtnivahecp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gthvchzscd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtsdiqjsry.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtcfintntj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtkkyfwvym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtkfvmmdmd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtccjhqifd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtmayrpvvl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtioitwvav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtjpdxqwjl.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtmsjvfvwd.html


<!-- 参考信息 -->