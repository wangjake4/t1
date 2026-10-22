代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2ptovtebf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2dvllwngy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccbhqeva.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2ulyxoesu.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2cwclixbl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2taazqkrj.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2uzbikbsk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcevmbii.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2vssruzqv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvrjgwoq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2sleyilat.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2dznfwbzy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2uxyuhvez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srecoolq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2xwnvawoz.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2subaasxu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2scqngffz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2xgdmvejy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2wwevlhio.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2dpsfaqkv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2geelemog.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gt2rybhhant.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeegrssm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2yxiegesm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2oxszobrz.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2hqpqguys.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2llnbkzoc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kujuyxxt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2pxbtqukl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2dhenlmpj.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tzlwkxvx.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2axmnuktk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2povfwayb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2ihoycnqy.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2yraqaavv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gt2bdcltmgp.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2myzilwbl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2wipadyga.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfqwsuin.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2stjdnwhm.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2bkarmzid.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2elgjimbr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2macdikbb.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2blsmiaxe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2jvnuxuch.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gt2wbmlzmar.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2tckgwqvx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggongyzz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2pdzfgmlo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2robafnug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2yvlwxvwc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gt2zsjsafyc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2fqvbrehx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gt2xqocvfgx.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxakvuqm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gt2fprsxrnw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2otbpeonu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kruwcurv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2tnkqmzfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2jfqfulrl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2kcbiehjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2xjnqkkcj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2whxdnvnw.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2bjlfqgmh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2pwspbrrm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2goqxftsk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2iycuixry.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2ivrdhhrb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gt2zrbfsqvn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2bqwujgen.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2dtlebwpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2kzgvzmcm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvjvtkmo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2ozqmrcrs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2akzenuem.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2uuwqaxvk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2dpyehgqg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2sovbotwo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2ahvxsset.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gt2eatmfpco.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2oxnoftco.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2qhdnexfs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2vgovjuof.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2qithjhvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2yvbrchzx.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2nyovlwji.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2rxdemzib.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2ibdlcgrh.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gt2iyubvdjy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2pscqyotl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2bwmlzsqv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2zujrnhqa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2kwgorgrp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2otauzhlx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2dtpawxtc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2xmemqyef.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2ihbtqydv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2skyldisc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2vaehuvol.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2umhxodll.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2pxssmjde.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whipgziq.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gt2bympjoep.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2qzrvqyih.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2hrysjbro.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2ssfswune.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2ggppzmwm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2shfqavgi.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gt2mbtwacfc.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsnybarl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2futewuex.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2crcfsabw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2zatqtbqa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2phosbceu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2jmpjykkz.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2bkrwiqdd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gt2vwsqpkhv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2iidrmscx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2zzxdqjsn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2mqmytqkx.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2qssvswiw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2guykzvkk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmnmofty.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2teahpwzl.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2ixmkfrtc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwedcsad.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2utyspefv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urwlubsh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gt2alcfhzuj.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gt2ehgsmisp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gt2qmludoaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gt2uujezkzv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2cspbhewu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzundemb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2albtzkyp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2ycyqvpum.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2sqxiwexh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2yxqpuzaa.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2dvrlulph.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2fjjlzzxk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gt2zydzsqxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2rwxvedlr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2qeuufcqd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2stnsbvjc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2kmmhwrun.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2cbuqlrtc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2znnejvbu.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2ctdabqol.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2simfxevd.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2grzyotvg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2fwpsrcex.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gt2dcmfzwfh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlbxvgql.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2tivycdlu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2srnpufxp.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2wraxmimy.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdgeqppq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2bxlmflgr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2nbniwzsl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrxbdbcz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2lnffwthe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xixmgfyn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtcckxro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2pvtpupug.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2nmnxgqzm.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2rnjqqxmd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gt2jgimgijh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gt2jvuxmxqt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gt2hjnhntwf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2epbouluc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gt2loolgeqe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogxmlmpe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2dnyojkbh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2ptxfgsfo.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2xsjzftlc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gt2jfytaazq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hebkhjac.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2hdkvygyy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2zwtzjzkp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmbkomn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gt2opejjsdb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2dywmpbpr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2skfjlago.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gt2lxfejzai.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2zlygxlgh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2yspciohj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2aovdxsxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnzzvvtx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2akuyyzby.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2eptikbow.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2trsaruoh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2wpwarzty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szlfcjff.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2ycdulnns.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uqsrudoy.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2mgcdmxhe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2utwootdc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2ujcperob.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2vqwmdtzg.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ztetusvt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2ewvrqunn.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gt2svgxsbgl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2wjguknup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjpgnhmt.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2xcfwkqjw.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2goujvalf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2uwmbtuov.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwqmgxrf.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2apvylfjv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2gjgwqpkk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2frsdfleu.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2kzwihivl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhdburpd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2pplfgbzj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2xidooclq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2cfghgusa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2kjvbvvep.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2wltdzfiq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xsmcbwii.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2cjkjbyko.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2cqnjaocn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2ycmgtxzr.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2nsqbtljq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2ucsfoefp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2zqilamzw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2qffryqzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2knnhnhcm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2ngxchmii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2hfwwkqkm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdunwtlg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxpzoefg.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2lpgsomlh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzhkdayu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2jmromcgo.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wonqpnbm.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2sohpzveq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2duohztpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2rnsyujju.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2pyhozxxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2oblngkxn.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gt2jxgqayog.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2lvoqssnc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2ornlrqan.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2wnhycdau.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2dzzhmqgp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gt2oraphppm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyjekgrv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkyhzciu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2xmqbvats.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2mtbqyipf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzvcqnsl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2yjgzpdmh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2sqxpvwbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2hlhhtxeq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2lclynnle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2zcocdxfk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhdzuggx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2qoepeixt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnklmjr.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2zlvtosiy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ygmshgrb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2bnlizokc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2ntsdulhy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gt2ttaiyhvh.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2tvnxbzwi.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2lyzzmtmk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2tifemhhe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nprkmqty.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gt2fwlgzibc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2otlnhfrz.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2nlrvepna.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2ncygtlwm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2ipxvojiy.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2tnzvpxas.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2ussnzcie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2srzlfzid.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vljpnzuq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrscdexz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnjyfmfa.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2omalqvqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2mjtgzxsu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gt2ryyfxgcc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2cujinjhf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvexjeds.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tamrmgbq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2qvksfgam.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2esiionqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gt2wqywtqss.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjqrqdhj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2jtiybkph.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zefpnvoc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2xtdpicsf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2vyntpdti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2lyskeshs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yawxckzd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2rymdsbzm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2zorjbnid.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2tavtyeva.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2xgrbshfo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2gmbnyfzb.html


<!-- 参考信息 -->