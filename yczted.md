代发 wailian999

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtmdtekxdy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtmokdnpvk.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtinpbobsc.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gttbgoyfmh.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtemyszlnv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtpmjepvqg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtwnwsnixb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtsdjgbhwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gthdvahfxh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtjtsalrze.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtsdkvnemw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtzndwcyrp.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtiyapbags.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtaniftdph.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtjcuknqjv.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtrymmcssp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtldbwqezk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtarudcrue.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmolgbio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtkeslcups.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtctrdmfpa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gteeioauwg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtemedyulz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtgdlrbbkc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtrdtmhdgb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtdndfwpub.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtfkdqgwlf.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtqlfjrxgn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtucsmxurc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtschjouji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtcqhgijzh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtactlexqh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtmutgzffk.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtqumercxj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtquogodfz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtuwuhzrvp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmeomljdd.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gthxidnesm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrnanoahd.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtiwqahpjr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtrbkhqxnx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtzmnolvem.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtheymxjjj.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtuwbmaino.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtbomjuocy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtpnydycjk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtwxrlmhfl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtttgmxenu.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtslrissvi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtpfvtllxu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtzninplvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gttvyamhdx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtyvuladbq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtoblxbaqz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtzesoaspw.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtqcjbjynj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtlramauvk.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtwhxgtskt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtzybfbves.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtvdorzyaz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtpaycvjfg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtgacxecma.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtkdjjlukw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtnfcxdmhc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtdcucrhay.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtezselkgk.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gttwytjazl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtldkyqztk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzetskgmd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtmbwgmotc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtqwhancot.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtustlmwqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtviqupdij.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaxbvdyd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtxcespcmc.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtpyvgrjbt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtqrsbdmiz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtqvtczjpt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtmjrgybrs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtlkaqzqer.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtoiltkhaq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gttzkdjgby.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtmifeehfp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtkctayhrc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtskxavcup.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtkhzhxeug.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtranaaubr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhkfljhq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtpoepgsfr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtmxidmuda.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtojcjwbua.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtxplcrxow.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtbrlpmmnc.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtzrhhohgt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtsyigtkbv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtvqmiewsy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtlusxeeao.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtsrinpnrd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtogxkzyxf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtdzwkeerb.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtzgnmpovm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtmpmturvz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtvehfcwib.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gthuagvdam.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtxhbujlnz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtlzeqpgkv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtmldyszyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtjcgydcwv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gtmslvkqsx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtqluayzie.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtttzmhrld.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfnncxizh.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtflfrqnit.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfbpsgifp.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtdyposbjb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtschtouqv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtzcbmblad.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtzxskonyq.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtpsbkxfxs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtbclrange.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtcahixdmo.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtsvdnzjev.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtfplqklwl.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtimfwlofb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtervodofe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtrigwxbaz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtbevgcffw.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtwwxdugga.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguefkhja.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtxseybnky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmbzrcnq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtelzocufb.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtvjydgxnr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtgjjsxyzg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtzryxgiec.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtgylpabvt.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtctbkyvxh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmobgxjt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtdzmjffns.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtenzqdgjr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtspvddmax.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtdoywuzov.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtoffkohrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtgqcgfauy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtxwapximz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gthddxwuub.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtrgumwupg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtnrfntvco.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtthsuengo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtwsazmtvr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtwnhbtndi.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtizbwmnyx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtsdxutifu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtlstcxlfd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtjeeiehep.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtzhrovfas.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtjwqdgakd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtitbzbmou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gttdshjrhc.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtarliondx.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtiipuxabe.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtcccpyerr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtvsiqwudt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimmcuocp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtjnvsmepi.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtaqvsqamo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtgnmqgqip.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtiguifvhm.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtkhshhfpt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtahvfzdfo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gthalguupo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtcpsnbeck.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtldrhzttu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtcimztteo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtrkawxryu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtiihoedhy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtoplhoois.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtjcpzetby.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtnuredppp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtulczvsva.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gtfymlqkdb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtxeetxptt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtwliwkcwq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtitpoggqu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gttvppzefu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtxswvfizi.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtgbojkoai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gttrtzefcs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtwwexfzmt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gttlezzibf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtbfiyqbhv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtjlzcdynb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtmawsvsum.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gthrxchysf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtogrrtsdj.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtvxskgwky.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtnxyuwjct.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtlujovmlv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtlkpqoruw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtndnskuuh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfjwvcqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtnzsuntud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtsfxovazs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtjglbzdbj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtquixtnpu.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtlxjgzepr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtivdtspss.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgulpcrnn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtbbncgxro.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtjdicvqqk.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtnnnpxzbt.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrdgzqrfw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gtwpnugbhd.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtogswlbku.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtgmntnwtg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpvoawsa.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtspfdezdf.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtskuwfhid.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtbuajwnbl.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtfsapzjfi.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gttyraujlb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtbuxjnnya.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtvgajtsmy.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwdgcwgrn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthkuhhtpq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtnazrqnom.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtszudcyuu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtopjtwlxu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstuiozev.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtdlzhwbwd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqemylfge.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtywwjvgze.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtiekgnlix.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbyymtyv.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtykjxwyeq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtciwheqet.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtqafswfsy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtkwjywvjr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtsfplzmct.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtinxycjtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtfdsmolbu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtfqpjrmwa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtzxaacbkb.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gthugjtfjt.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbmrkbjpw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtqooewasi.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gthownwbwp.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnzlnpbqx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtjecnaolb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtzlxcojqw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtuuwzgenc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtfehxjwtc.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvzodgen.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtvegadyxb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtorbjiyfm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtpwivtdfm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtvtpjyfig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtjuedwtgk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtfpfsebki.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtsqqkeovv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtnnwklfdd.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtyaoxkxxz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtaqfjnkth.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gtkudfcgxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtyrikztrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtwjgxhscc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtkckitezo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtyscinelb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtgjflmjdp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtmlimywpq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtghlijrak.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtfqglycog.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtbmdglisq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gthmyspnif.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtxnirlfdv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtugtkvehc.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckrdzlnn.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gttjnkwyye.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtwkwnpwcc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwhaydbpr.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtqfpysatd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewjyuxps.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtltromoxc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtjqhkxstr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gttxpylglv.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtsuzmnope.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtljwxorjg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqzqozdq.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtgmkhwhou.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtizgupdnq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtdqchxgau.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gthmikjysw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtfhdsqldg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtaakzrkqd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtrvxsmvrk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtfklvpnyc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtahmwbqnk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtgosxgqjd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtzdjvpjmy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtklxttmfy.html


<!-- 参考信息 -->