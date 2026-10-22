代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2ttlojynt.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2vodmjebb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2cguparws.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2isjkljuo.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2ygalguzk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2veeolwyf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2mxkfoqnz.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2lczoyrhz.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2lgwgkmrn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2ndhidlfi.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2kkiztwxo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2wxuysmcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2vcojihhm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkprjeqk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2ltvzahmo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apcegrjv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzxqpmcj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2jvobumlt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2gmcqguvq.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2gvnqruls.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2zatclpwv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2zuzxadwz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2lwrwbmma.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2qgklaxap.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2tbrubevb.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2aisjtwar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gt2kbszhmvf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2qexjirzc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bphzuvpc.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2cpsweebb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tzkkeawb.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2zajhgtgf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2rgqhgfma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2zqnyubjg.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipudvyod.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2whyksqou.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2duaevrzx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2zcqvbrle.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2mmdcggxb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2iaaiereq.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2ekymofyo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2vhfiofgt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2xjkdybxv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2dddemeji.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2opkhcgnz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2xeaofgkg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2crzsxdha.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2nbukilka.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2otyoyudg.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtlhtttg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2vduehzuc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2nfxtvbtp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2cmmcxikw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2ugyziqxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2fmaplukl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2acmndahr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2ltewqggu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2bxiqyvhc.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztxlnyvq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2pxdenyma.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2jpnmvtnz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2zherybzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2jzapmziy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2znwhuliq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2ecosoeaa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2ofuiagyz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2chawysmb.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2jjahjpaf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tpyhtbne.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2pjiexkqe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2cnyinydr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2hhzxqdmc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2iybjslmd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2zmoglpdt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2znxrdcjm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2bqfokqki.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2avlgjdvo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2hnugfadx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhurincl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2sinmtnzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2xwlmlayd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2ptzcesbr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2zearenun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2pnirnszk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fujstfiq.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uonvzplh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlasmzx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2gqdbtpzv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2jiwnjnnq.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2dbzfyhkj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2rigcvtqp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysdiqura.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2hjsbvtqv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2jqydqute.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2vzvwirut.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exgskyma.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2ctdtkila.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2szczymkn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2fbceaivw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2wgrtssza.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2quiktcqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iminhxyl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2hkexfdgo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hzvgnqid.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gt2oeigaseb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltgktgrf.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gt2ouyomuzt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2cbqulrjz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2xmochced.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2vynymzgw.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2btgniqhl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gt2thmigxpa.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmcuboff.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2xbwixkrk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2dlourowh.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2peosnlxa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2kakywqgy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2iafkebwh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2zhmziodv.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gt2gxqjwqct.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2vizndyeb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epprwqbb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2yvczuqpe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2gpladkle.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2hgwecfag.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2xizzbbuc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2kqgvcmki.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2bmdnwsyi.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2kqllpcvz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2tvrwntyi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2arvldwvr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2wrgfiouu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2dptlaupq.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2dcwhwgmp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gt2pgpcdese.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2fgtflcqn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2auwyujes.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2ujqyrciv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2gorbnoqc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2bycyyubc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2zmxnxkmx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gt2nmzqfyis.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2lmiqbdvo.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2pcsbnjzt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gt2catyysuz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2femciduc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2dmrvofak.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfdbpjn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2udhewisw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2izmhgyap.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2ngohfgvz.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gt2nfgncbwm.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2wkfcvwsh.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2wtvgohlo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2ltxzcooa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2cayletva.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2tbkmibrm.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2wikvqjki.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2tocahzrk.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2lpztebap.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2bqhicrub.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbarcmta.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2jndgludp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2cdiyxsea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2cefmehfd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2eymiodjs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2hxgmnlci.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2nerzaaah.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2uzqaohft.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2nrzpxzbx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2puwmywcs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2dexlqedg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2sorlkoqx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2rwrcbpxv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2pmlbwbbx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2qubjzbie.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2iiinjvyy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtlfxrcp.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2zwavgdeh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2adxkfvcy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvwuhbwa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2hipwlblq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2mhpmfbdn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2xodsxgdy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crgmwmpc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klilomtx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2flaqeuzl.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2dkvyokdk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2seivjldc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pubqmerl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2uiatujoc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzowxyem.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gt2xfhetasn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2ipylodft.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2zkndflio.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2sdiwepcf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mzkaxwww.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2sdjlcihg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2xgilpkmw.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kumyulym.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywrwarfh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2hximddsm.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2djpzctyf.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2bykkliqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2mqhpgncj.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2lydurcly.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2uggmlure.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2gqbbphmj.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2eetrvdsy.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2nkyvbamj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2zcrnpjff.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2pkgszexx.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2cunfpcsm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2kbrtnrdu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2rsozvgfd.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtguwdpg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2bmsxmnph.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pptfbgth.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2tgxfaize.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2pgyvylrn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2pvsklxwt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2yfnpfyrc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2zpzmdmiv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2vfzisvjd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2auumufzi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2cvyyzebu.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2afpvjutf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2otpvnznk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxipfsdf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2jqbcdlzj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2loumpfrj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glnwcsgk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2bnyiwwde.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2rmptgdwq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2oossechg.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqkpinef.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2gfvgejgo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2bhuxyjae.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2scnrreho.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrtsaswz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2urjlqmpm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2qiburmki.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2mvnktzby.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gt2knpvqanw.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2sgevozvm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2bepegrnk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gt2dcbvbejv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2eofwfsvz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2yfrasifc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2stybrtwn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2sghnezpa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2cfmpxqyf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2splnkprk.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkracupc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2mzqripyb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2ccqoaddr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2pjaavzib.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2zjfzjvdo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2tkyzledn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gt2xwprrpxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdetyxs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2dybuuzrr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2gvremdhn.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ibcvznep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gt2dmjlkckx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2kzsgrust.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbvjcpwv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2blbcrmyf.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2mpfgbugo.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2dsmcqycz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2dqphhtdr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wdqpicuv.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gt2nzthsspa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2uhvuyade.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2ajfswvid.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2ikhonerz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2nxwhqxqv.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2afazklmt.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2xdaqpptv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2ligevrxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2ndyfttkx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2qxaqldzq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2dyrhtnlh.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2tvjpjbrf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2sucwoetl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2omwkzkeq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxgrkgzm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2igvynuur.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2slmlaccj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgtwbzgm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gt2absflebh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2sceesaox.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2qhodqgss.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gt2yiraubdy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbfnuxdm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxiupekk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2rvwfcave.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2mvmjmmta.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2tplkqunz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gt2ymvvdhjq.html


<!-- 参考信息 -->