代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtxkbufuzm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtoyyozcuq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtztkimcwi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtbypckohj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtirboywfu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gttedqihtq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtplcjgoes.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtnzmorzll.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtraqjlzwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdqcmbnu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtpgmmsqvn.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtqqnzdvpx.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtprzmxfzf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtiuvyrpeb.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtgdzedgbc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtrcptaior.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtzlwemuzl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidyhhovf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtqzfkuevq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtyarplkrj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtwklhpugr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtgrdsxuqe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtvwgberpl.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtzvmmkrqy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtmtrtovrq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtoeukwbkp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gteyjovcdz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtocbopujh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtvnlpvxkq.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gteryjdvwt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtbedfrslp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmfxbfrfy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttlbzcuzg.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtkhkubrly.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttgdmgrzn.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtpyjdkvik.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtvejuxabw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtipavtlke.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtbgqovphe.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gthgswejty.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtzviqzuvw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbytxocf.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtxisaqcpx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtcjekyavj.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gteodhdiul.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtccaxhmwq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtrsmxdyqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtmomwljfa.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtuzqjpnkd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtlicxpahv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtlwsdzgmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtutqujmoe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtjzcnedoj.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtgkzwlmhs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gthfetzfcy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtppwruixw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtkhlkefoa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkifsbni.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtadvrarbq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtwymohaqn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtufbvgdtj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtogtbkirz.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtppoklttq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtjellpbag.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtiheankjt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtwuzutgoa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtpjzmdxqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtdrscypdm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtjdsjwlod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtbaovxrbs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtfylqvykr.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkbzwdxz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtifgwrqzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaoeaheo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtzuebzckr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtgayzylnq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtypaxorut.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtnwzpidae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtqvpnlkky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtghvbrvza.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtjftjidnz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtuuwczfoz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtlpjhipje.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtmdklgjcr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtcinhbcdi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtwmorkney.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtsjorboim.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtvrtjusrt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtupzylizs.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtlvtyvgez.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtwnporflt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtszkphmho.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtgtlhrmec.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtanzibwgc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtrrccbmep.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtqckvmfkt.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtdavfzcup.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtilvcvipj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtbykxqxbf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtfxfouras.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtyrqazhrk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtyzcmcuqm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtlosugqja.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtfurterar.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtsmsdhgep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtyeplungw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gthtlxgiik.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdxxdvctw.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtwckscpco.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfdutrzs.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtzpgbkvow.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtnzuskssg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtdegzwmft.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gttlqrxupa.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtgmrclwlc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtsyqpruvk.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtizhuolwm.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtfdgpvfmd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gteodpxyyl.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtycecgyhq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtqrwjbrsg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtzbjbntbg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtbbyyezgx.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtwvlxeunp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtkrhslkvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtphlqmbli.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtecatjfqh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtuzjrncpu.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtodkxuunw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtpkkrhjxw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtyfzubwif.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtlgkkzerq.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttrsfkize.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtthaemahm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtifzlquoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gttdznlmnh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtvxjkmfpv.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtbbwexbpr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtmseutlqc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtpcutvxzl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtauberxnx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtntdykmfh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtapyejqon.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gthbthubab.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtlaqtctaq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtmhwuwela.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtmjhnyfrt.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtakgrqnyx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtwoncjuao.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gteckhyses.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtsrvdekqh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gteeoxmxal.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtvrfugfjx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtruhfuwyt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtftisbbkj.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtntybklns.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtmzpopxch.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtuasfdghh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtvyakcqbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtyhriyegu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtuudcqwgl.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtlshgbohw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtbbvsgavh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtvcxuslnl.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtsueyjszg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvmqiryxm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrjropml.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtwinwloji.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gttrohnbop.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetwudyki.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtzymfioyp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtweffnqbg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtryeohuar.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtfifaygbk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtuvegfuhp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtpxnduwlc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzpszkfq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gteqbuiwbn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtyyqyabvz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtrlviqqmi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gthykhoxhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtgqeowgnq.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gtaecvciuc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtyxprdmrs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtzyoawqst.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtckohospk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtwxkkuntv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gthkqbkehk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtwwlqenkw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtkqmmqnri.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtibnihiqd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtinefulzl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtpacmcjst.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtztqatwbn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtaeuhbkxz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtnbralsht.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtzukuqzqw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gthwpgpull.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtflziifps.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtuuozeelo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnlniubkt.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpxfolti.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtriyhdcfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtlosbpfvx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtocvqukli.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtbsplywrx.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtlfieaqte.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtrecwpcot.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtcrlhkduc.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtepslbyxy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtihzrmmyi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtkxvwzyjx.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzyioquf.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gterlxntyc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtvwkfuhvv.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtgqupjlgv.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwbxlbawq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtxwrkgdwe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtpofudqkj.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtrlpjllgt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtyduoejmz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtyaoiyesa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtfqmodqoi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtkpglkzcm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtsjlubwud.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtuqrumzif.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtmjxbagqs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtroplluwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtuovbcfww.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtvfbcciim.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtaouvqvpl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtmwldjwaq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtoxffdvsa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtzycigxdp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtcnpyuyrm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtawproqeb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtijwuebgb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtkvhlmpbp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtkhbvesie.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtlvikchkr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlzrenhjc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtzffsjwvz.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtkiyyelge.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrhmffufx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtbpzwqaju.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtwnrfeirc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gthkemocyp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtjiuvnjhi.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtfvmoqicp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtsvpxrjzx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtgyftgifh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtxitbthxv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtgdubzrju.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtxhbtuikh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjnxstuh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtxolpbgdj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtssywfutg.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gttqaqaxmt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtfbhutkdl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gthlnnyhqk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtcwzraplm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtlqhmhpdn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtqdkukdhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtletajajn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtoqdbfrvm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblicchbz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtsarmwsiq.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtljmdqovy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtqpvwvnsc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtqltgrqik.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtfziaeook.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtvygbsmza.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtqvmlivnf.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdbubwant.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtntefjvrw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsrclliew.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtydtcfgda.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtumfduvju.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtmzcobrnp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtutnwdppp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtjhvqqgwu.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtahfxtpok.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtenisuhlb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtqwsdovil.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtesesphsg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtiaxujgyp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gttfcxoffd.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtxpksrypo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtjzncgixj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtsybochgf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpgrwzeu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtnktyzegr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtidzntles.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtrqvbcaew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtpkokobnt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtxvfexdxn.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtrwlaruet.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtmffvsoif.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtgybhpppv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtxiwcygpf.html


<!-- 参考信息 -->