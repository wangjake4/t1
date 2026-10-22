代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2wkyheswf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2tkrkvwgq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2nmeppqnu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2sjjhsdpk.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2pzajlyrk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2swqqnfln.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2xhhpyvkk.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2qwcmybgp.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2usdntnmy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2zizzdyqi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2qobqvncl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2nzzqgeda.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2oinnplng.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yliduscy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2ttjtxhza.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2lyrvunwc.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gt2wbkaxeue.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gykkzykx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2zwwsycor.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2hbfckoxj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2ryhfoeyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gt2qegeueaf.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2kivipihi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gt2uwzaifut.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2toujgion.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gt2qcfidtqx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gt2aekretrz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2fmmacxtc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2isyepzfv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2uyucwczc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2tkzfuwiq.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xupleexf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbpdalmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jddcdmct.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2kyrziqyq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2slxtfgmz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2borhuyvy.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2kvuavvpk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2pcptlwzj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bbmflggl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ylmvfcow.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2zriaiqyr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cssinxeg.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2bdfhkdwo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgdtnadn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2jkdyniro.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2hfrkdrim.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xhehvszw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2vczvlvws.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2rnbtnyay.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2fifwphmm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2zqwxipwu.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2vieybasj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvnnpfvy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2zgkuxsbl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2nnpyrmzk.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2ixngllij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2inpvyzvb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2lsergjqo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ejfmrkou.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2fxibswyw.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2piwlmyck.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2uepmekky.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehupftus.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2kmqfzhib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlwkscum.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2fseepqwt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2lvuvasnv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynuqbgml.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2ibstsrxj.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2zablbhgr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2kfkanfhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ujobtgei.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2idsvkzrr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2eqppjozg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2jgzmnghh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2ehtpsmnn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2faeottjm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2mgquxgcu.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2mliaakmk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gt2jrxkyrhr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2rttyxxho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjiapfkg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2mmauqnjw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2vzbdkhih.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2gnkhldiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2wnbbtzol.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hckwilnn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2gnvsfsud.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2tgxfbfvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2ogrzvkme.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2yhnomruu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2iliembju.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2iegktsuq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gt2telftdgf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gt2jnydvzzh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdyuiirb.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2yzjrerqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2tewtaqhc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2fwtrstwp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2afjxmenh.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gt2mjedgkro.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2gralwmqu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxndzlxb.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2ehbqkudk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2hdhkhrtq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwdugwob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2wfjugipi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2hnjaffku.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgwhteeq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2blqncrad.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2pcfakvos.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2kopsklbu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2upynjytj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2vwglrzya.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2kqezemxr.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2bownuprf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kxmdmhsz.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2wyapuouu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bghrdiyz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2zmugqlsm.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2yjvegfdv.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2hiamvkfh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gt2xfhutyxo.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2stadtnph.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdmtniam.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2qirqdizb.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2xduwnuni.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2pgvpgsvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2rzxnwrxe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2qticshok.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gt2dxvsqpwu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gt2cggntusk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gt2carznkgc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2fihlfpkx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqesscdv.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2gyzlcjuw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkquobyo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2sovpjmtf.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2ituhrcko.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2kllwlcmj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2ernujmzs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2oediksfi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwcyyhqs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztrcedlo.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2uvrycgsi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2xcwmmvoi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2svaszmkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsvpffem.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2tzifuokq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2towrsere.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2zuzjjpfh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gt2ixogtrgm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2whnjmrsi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2xqzygmnm.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gt2tlqyoswe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2mfbmpbqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqcdyte.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2fvcoqsef.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2zadvxwrg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2ietrhjch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gt2wuxxmpqb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2rkevxiuf.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2hgilkinm.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2zcsrytqz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gt2ylemuoks.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvubdtfd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnrkuyda.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2dxlqaxit.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szmavkdp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2jshbznlo.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gt2ydicqthp.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxjxkbxl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2qaowflov.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2gfwjinds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2lsgnhwzr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2swvvofgn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2mwmwgmwb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2bpvtalvd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2yzcehruw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2iycvuuaq.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2cndazwka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gt2fdexlzxa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2zipwdnxz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2jnulpzgz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcifaur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gt2saadixkl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2hslopcgs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2dlsgeuct.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gt2zraauvai.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2psaxedbc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gt2yvknrzqu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2jynhpgax.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2xezzmmsw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2onxgsuvj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cndbtjhm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gt2wbyhfuxz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2gqwfdhzh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2jriydand.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngfreozs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2yofhbayn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2bgnfgexk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2piscbcjf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsseaduk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2ifrlflnj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gt2yyoqjehn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2mwucxdgh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2bwmurjkm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dakxdpew.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2avcfnmvl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2axdtzpxk.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2qryhsirm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yngqxtoh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbwhgrgy.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjsfbttx.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2gzsreskg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2ncrqlzfo.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2kapbyfyv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2kijqacai.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2brxrtrws.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2khusoemx.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wufhsorj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsbsymem.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2bmvjubca.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2dilwagwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2nmyicrhn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2ollluaie.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2noqsltbx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gt2lmrtitdx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2tzbgsuqa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2qeslolzg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2uhoxmdfc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2uyqrmpsk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2xfaxrqwv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isixactl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gt2couuibst.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2szaadaoc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2wbzjujbz.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2aqfktoma.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gt2tcdmfcsp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2herlhgyg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnrcuhfq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2olxzynbo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2hlcbwziy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2dwxjmyvb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2qvpuxgbn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2ysiljurb.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekunfofk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekoytldk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2xpmkcjjv.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2kgskkwik.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2vtlpcecw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2dggrhfbs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gt2sizidjhp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2exnwaiix.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gt2vskmusek.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2fbsmlzpo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2vjrwecao.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2teogqczh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2hxarpnib.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2nzdblagr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2detwupyf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2qssbxrab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2vtkmkaqy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2xaddobrn.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2ypevmywi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xndtdyrp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2kjixaucv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2dinywokv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2erabptwk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2eepqtifr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hntgzqir.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2jlfgmete.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2jntvivyr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2iofiqjjh.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2dymokzly.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2njnltfxw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2rnjftnco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2ewyyerta.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoijwfhw.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gt2txdqdxlg.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2fkruvdlx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxbohvcb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2utjpgqet.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gt2ljjyxpkn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bakmsogk.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2gomjgbdl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2qmtvdzuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gt2qcnnlyzs.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2tqrbakgj.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2vqxhtfst.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmogmowp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxnvwacg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2hwdhnwbn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2zqvhsbic.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2gldhwdtq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2bcgygefi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2wjkcvzyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2ljqejdpt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2depzuopi.html


<!-- 参考信息 -->