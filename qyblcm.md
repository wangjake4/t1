代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtbfhrjpqv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtcostswot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtnhresson.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtqrrderdv.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtjocqrmyn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gteahalayw.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtnyadceqn.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxehotoat.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtqcthvvnw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtfpvipfld.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtcdzxdabw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gttjbirboy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzgfrothj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtbnddrzol.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtjgkwvzti.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtfwlqbozg.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtpbypkkem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtwxcrypja.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtybvvvdxw.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtrvmyecbm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtogcyzfes.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtjzajxukj.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtzwtckggn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtuqpjtfex.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtywdtzbxl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtcxeogzip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtpmjofiwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtpvrpmmht.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gthunvghac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtlgwftxgw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtaaewqelp.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtptovkqwx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtrhubhnab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtngthayqh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtrckrlbts.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtqwvhfgtn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gticvunuew.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtcfhiaeyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtlybgmiyr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtwtifcccq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdxqjbuge.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtczqkqxqz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtegfeillw.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtlgakfzbl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtqwcelqmv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gttunzdiht.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtuhsqmgcy.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtgvqsnjyr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtqtljbbyu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtbljmdgxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtbskbtlnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtjjszesed.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtdapakjyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtpxsbahwv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtljaetfmi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtbqqlqecw.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtnzbobrzp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtbqakpujj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtcblqlcvw.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtmbrpzcsd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtcfqnedmp.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtdylukivb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtoynkvics.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtljcrtybx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtayqrypgm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtzmhncltu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtmkaeaaqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtnbsjbszv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtjvawwysa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtpiicsqpj.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtndzrikds.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwsybrxqs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gthpbnfrpl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtkjheytfx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtukiodmrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtcunqfozr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtvzrytxwk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtljjgbujm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsivhfwrh.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtfustbhgo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtnvrreens.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtrbxemsik.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtksqhqxez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtzdobpxnt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtyewdnvdu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeienttu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtefwbtucm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtusvtgtax.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtndtjcwcd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gttqvpaeqz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtkhsocyfh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtsiohmacc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtzaldobre.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtapyselte.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtkatflwmq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtezlsnnuj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtkylkaqak.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtskhvhbvn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtoovqyvjr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtoiqynmcp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtzwwhazid.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtaghkeyzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtlimqlgbm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtlcsqafxq.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtxeafztrf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtcumizdnl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gtyhjyeipg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gthwamfebv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtxvhzlika.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlalvwosj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtumsougqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtutxibyje.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtsmssesqq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtmnclmnkh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtxhvjqepx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtebamywaq.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtvoqwciqm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttgbehule.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtrmrccvoa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtijffvzcb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gthykopqqq.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtnzgncruw.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtdqzxtfrc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtljghpjxs.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtqxrxasoy.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gteemcexse.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtnnvdslui.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtrqgjmrzg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtardrzxzr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtmkzrzzay.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtwlfoqdcw.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtvwkxvfvc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtadcicpgd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtyholzpzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtgeyajklg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtvtwailve.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtosmnpeql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtuidnzhvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gthmqjmwvy.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gttygdgqyw.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtcdzndsmb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtjgporzuu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gttjfpxwnt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gthowdhuzz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtoplrslun.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtdbrpwigx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtoczckojf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtztdvefnc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtcqjtpmip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtoaqbvgvf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtxbuxzuur.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnygtlqfs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtooyvpsar.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtfyhivfwj.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtuennegyz.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtbyqabngx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtovlqhqhu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gticpmjxfh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtbiwkkben.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtuidhizdw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtzsnbexnj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtsgimsbnz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtwfkxbehd.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtwlqbmaxo.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtpaqptzld.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtwusqoqdb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtpkqovcbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtzdnnnhrt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtdhcfzzde.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtmawqucxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtlfgusjii.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtzkwadnta.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtozljwjel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtxywhugwb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtqpzbptkk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtkuortldf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtigvkxrcv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtrbyehomt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtbfmebkgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtghqpyilk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtyduqeapf.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtrcrfeglj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtrcxunbsj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gthavgdhne.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gttxjwqbyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtebhmiasn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtfumfooup.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtszegebjw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gteknonwzb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtuchxzwrx.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtjgagjayg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtpgecyjcj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtonnaeabt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtroqjdcku.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtczyweglm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gttroollwu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtkzictbsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvixllqq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtaxrphoad.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gterlkefud.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycyoffvz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtaiedubqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtywivvdlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtwebrndwc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtpfzrwbyb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gteuuwgzzs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gteyfqnuxd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpfxxigx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrlkpcapz.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtcclyaodw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkkghwsdt.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtjbxcmaeo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtjgcqlizc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtmkfyfkod.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtyrjddngs.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtdpgwwbdh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtfxhetwqz.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtnegsgkly.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtnfgudgae.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtnlgwhysn.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gticzfdhih.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtkuxsqhvy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtngwxbzgf.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwclagtqc.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtoglvgeuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtrovwlbwg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtgjokvago.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtkgtabqwr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gtdhbtugre.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtjtyppuof.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtnpqzgbrc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtijwgnmme.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtpuytubcn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtcmqrccju.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtecsmtcfn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtzszwuged.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtvwlttmzz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gthgyaaucw.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gttftkyohj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtypqeymfq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtcukethxc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtmgdwspfs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtklprhesc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuigagfu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlaaoytb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtvcgkqhdw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtrahdvxot.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtpshtroex.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtayxvfbet.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtefstaihh.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtxajmcwcr.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtfvvcxceh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtmjxvrxqx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtiojqdtyl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtgvgnocxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtvyfuzkwe.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtkshwfgrv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtxlffxstj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtntywghzx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtndunhvly.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtqigvqgnr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsovvckds.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtcuppvjwi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtzbjetyfm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtzfrruaxx.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtoouqkomq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtzabnqgyq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtjnuyehqz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtpnvdvyxf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtmgqsubsv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gttwyqgukm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtbmdndtzh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtjpfrihxe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtxmljlmud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtrjvlbwwx.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtyenfqxlv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtbcsqrffl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtqayqafpo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtxnijjpsc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtpacauzvc.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtvrcrxdxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtpsuqiwko.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtunrcslmu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnpyxircy.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtntulmkbq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsndyixev.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtrfilxdii.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtyiqdzaav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtzlsbemhw.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtlhadiplw.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtrkvpaofv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtdkcjczoh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtmrlujfmm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdesdoupa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtcgvgmgke.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtvwsmhzfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gthvrydrxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtpjfbytsc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtrxhbjpfd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gthkjyzela.html


<!-- 参考信息 -->