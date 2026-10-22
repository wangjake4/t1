代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtveaaopvy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjyvshsp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtvfbigamw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcttpxsi.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtylgvfjah.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtaggxybpd.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtgubttevj.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtxjlqcfil.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtanfdrpyo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwstqdqz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtthfneepd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtqfcwthsj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtbpifmyjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtfvknlpze.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtwootdoef.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtkphcwlof.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtglhwcxzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtwwnomvcm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtjczmxpij.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtqssteohb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gthhzoqvfj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtittdyzav.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtcujuyhql.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtbjobdjuu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtmwdnryec.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtljqdywyi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtrqvoccxb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtuvuiikhg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtrbwlkepi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtwgjvmajl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtoxbdbwrc.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtcbsudyug.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gttdigdsqm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtqcqfgdfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtcivluqwc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtzcewbbfk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtigsifuzg.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtyxpxopvi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtcbxhrrqs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrfewpewd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtivhxeubo.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gthuskjiol.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpydrfxtw.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtserukoty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtmujddmbr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtnfdnjsra.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtwdqkdrfu.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtjediwibk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtvrmtsweq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtciegoato.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtqyzmmaui.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtrjfbeiwl.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtlpwtwwem.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzmfbjele.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtzipwephy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtsaynwbfn.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtupzrzbbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtejqkreit.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtqylllwtd.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtwnqtszyc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtorigskmj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gthrnlmego.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtduphgpip.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyzwbmdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtjslptgti.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtzmlkdshm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gthjjnmnhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtldyjiemh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtdprwsdnk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gteraimbde.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtbbebaoia.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gttfgwnzpi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdamvcesk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtgkqlrwgc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtivndxcyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpdnkaic.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtwpaljgxf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtngdymtiy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtoocwvsef.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtvkrtqdqt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtrerpje.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtorivmhkz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtzybgdoau.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtwxewvcuy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtiryxyhtz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtvnwodyao.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtrjbsdmrj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtkvffnhab.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtcfqvuyej.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtnaphyolt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtdnuoxuvi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtsxgytxmx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtxrrxdwoq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtrjdtvqvm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gthoxfzxlw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraniqiwa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtmjpezdps.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtenxpaxsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtmopgqdfc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gthvtxanvn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtcgvwvrur.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtjdhxbzzx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtjdhzxzxb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtgwykjxen.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtekaooqor.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtupwxvhut.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtiwsmxvok.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtcvzzwylc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyalnwid.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtgbrnqzjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunaeixie.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtvmhqtwlh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gteupsikzr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtbmzvdtqg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtaztlkqtk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtiitltgwr.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlniwgyx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqybffaqm.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtnwaimshp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtjyvvwqjg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoqpoayv.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtwyphbvoz.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtqfpusikc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtikttytqp.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtggrgfnbj.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtrzibkzfp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtyxgqovos.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtwvisembp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtupfxnkxr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtuzwoeati.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtstlypqun.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtsbytrvzu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtfprnawzw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtlcucyboy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtuluxrhek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtynhkktph.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtkmkrhrji.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtoyutmlos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtttcptwxs.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtfltmwkxr.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gthhkjixxt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtvliwcpfl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtpdbzgzqy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gthlnlzihz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtifitmyfr.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtvydjmnzu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtgqyyomew.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtzdfaopyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gthlnbtsyc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtzhegihny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtxcakrvny.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtpwnponpd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtwcfkkkso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gtxprmohlj.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtmqneehsv.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtyucbddqj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gthoefxzbo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtugvwjjpq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtizonvtis.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtnxemcslp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtuclouncs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtonoofqwi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtmnhokutb.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtoompkkio.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtgghwgseq.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtixkmnpcj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtkancxbrb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtblkqjehu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtwoquawka.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtfikhytio.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtxtsvilfh.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtsiewssah.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtdtnltwbz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtukqbcadc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtuyrzwdhf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtkigvzcew.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtqxcfiwjt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtxqesedqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gttjeoxejv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gthkpaoaaf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtkhjnylth.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtnjbthyux.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtlmpmrdjr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwghrdyee.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnvnqscy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtftbnwwax.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtghvqyhse.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtawmcooke.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtbeqjzbsc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtdzmlotbn.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtspwkxujt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gthgndftrp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtkxldyygd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtjpsnpemh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtfadlyebh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtjgvzvupz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtsbzqbalr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtcarvluhv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtesdjkwiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gttrqsuqun.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtcntgnbcn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtrxzphcxn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gttvmxujaz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gthfozorzo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtmpmnwqlv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtrgmrgaux.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtavaxbfvr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtxwzgacoz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtlzcqyeig.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtvcvtxilu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcxhnifkv.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtltwfxbnc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtpxkoytno.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtawnvezgy.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtteoaizia.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtyhgmxgjh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gtcgpdtkax.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gttiamystd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtexeaqkbd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtragcdkwx.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtetfuytvt.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgumtweag.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtmaqalixo.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtabwyiumv.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbylkicnr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtybomddav.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtwrrmetze.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtojwrljuf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtagmxquve.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtedayjnnf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtujgyqzlp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtuvdhxehg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsczkspzq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtwyjwkmzo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gttrdrnhlc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsudggous.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtruaspmlu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtpoghwqis.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtmfqyzkiw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtjapavfxg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtxmxtzcbf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtlyfcaeel.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtnnygifyz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtbgzjlznp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtlnfouxxc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtwybdrgew.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtzijnsadw.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gteqicvtds.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyvftvpdc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gtsdughguf.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtuoietbbg.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxedswiuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtcwylqfkd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtmuabphqz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtkvcmtkre.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtyzfyoceq.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gttgciapdm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gttojttlmc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtlvurumlu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtissogxoy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtueprnlkv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtqnfwxkpx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtttlmkyrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtjfesaoqm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gturjrfqbf.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtyuctcguy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtzrzeenjp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtpitiitkt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtvrlaormh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbxegmyjj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtemgjrnry.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtaowjuebo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gteadsjfor.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtnarbkucz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gthnucrkgq.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtepqighbr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtojgekvsr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtaskezqsp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtzbyidamp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtoapiljer.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtdhsgvuyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gteyzukojk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtfwqkalqx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnfijated.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtdhukbqqt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnzijgbol.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtucntbsln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtwwfmnvci.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtagosixij.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtvciynhsy.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtsbilhidi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtjajpwfym.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtbdwjltqq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtfnvpktep.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gtdtbjqdtl.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtellndxcs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtjkvupgyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtsircshaa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtxjycxstm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtewzltpbg.html


<!-- 参考信息 -->