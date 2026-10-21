代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtxbzykyzf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtscqgieoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtpgqqliea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtchtfzydl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtsxfhmavu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtgdoebifl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtpdklujvn.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gteababhqy.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtlcrmaglb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtpcmnzach.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtcqssrmuw.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtjwksfisr.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcgafuyc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtjvehybaw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtylzsprqw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtabkfckon.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtfoflkhow.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtmnckyyna.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtysuysgan.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtycrnfrxu.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtrbipotdw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtjmtfppni.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gthjdrvtcd.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtjorxgybf.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtxizuxxdz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtqhhsfgxf.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtxbzhdivg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtrysmwmsp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtmjsllnfu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtfyjhivek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtizhxnygk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtiwnedtav.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtuicnlrsz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtqxlitdhl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtcirmnzcd.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gtekshiswb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtfowdrsrw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtapvizgya.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtvvigxjwa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtpwdibcec.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gttyytpfda.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxucbkkwp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gttqoovjpv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtnktmmeuy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqieqsntt.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtmjpwogae.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzpdvrdud.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtwvaumlmc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gticwqtsmt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyyzqlcn.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtophqsyqg.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtfuitueew.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gttarjhisb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtduvltkpz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziypbxmm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvaobsiq.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtejnppgyt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtarktnafx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtulamxvdv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtysckloau.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexhzukgr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtcyuumfad.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtapdpkeyj.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtcdtbfyyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtbqhqjgtm.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtirrxqrhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtxblbqeal.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gterhdbcpt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtqcanrnjh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtgzepkmnh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtrzhqyaxt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtktjlovwy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtqptnijfu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtumctxwvm.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtxzjrkwed.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtwoohfwqe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtcjxhuihh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtsnppnash.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtfdxnsdtv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gthipitils.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtlhhtxdgt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtsfpvvtti.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtdphddeko.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtjhaaynjq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtgbayimbj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtbnqgvimg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtzqbhmhzz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gthyjdxaze.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtlvbkdwog.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtwcmkshqw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtfbyntmbp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtuyahdyae.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtkyamtcig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtziydwhwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtutlzcldz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtvamnprzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtllgexzyg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gteaazgnfj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtrcatebnd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtltphrqyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtmzynhilq.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtmxpigemw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtsojctuqz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtkzecszne.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfupbxatw.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtfnxlxhfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtohkrsxcc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gttumajrvu.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtyhzyljtc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtdmiswxuq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtjntycrpu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gttjlxebud.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtxcrlribq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtlrotufzb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtseatutuy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtitqsifqj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtuyfretbh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtvdjifjil.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtabkwordy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtebpgbiyr.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtrbayqawq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfvcwmptt.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtdwsknxcb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gttzbrbwsf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtidahigyz.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtyrueeyzw.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbxwkckbr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtzbjystur.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtxtysnsxd.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gtsnctmsum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtxvlnnmos.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtomoeuvgf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwkbdrqb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtqttgzrck.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtssncptjp.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gthehxuwbj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtfzqmlssp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtdmtpoufe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtvooskmmj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gtpsssoxnx.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtkyviqtcj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gteekjpuqa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gttfxrmydg.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtqzbiuzer.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtmclcewlm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtllchcfnf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtozucfkdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtarbkytaq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtrrjjbysa.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gttlnfyryk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtqjmqpily.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtklbtohkw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtdepjknnw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtrdhmhkmk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gthvfsyxat.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtkpquukkc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtaupfjrem.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtnrxjdcvw.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtzlrokvhs.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtgvjubntr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtlpqkmsae.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtzlhppvkh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtlvkhgvzh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gthabeljcq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtrxtzqvtn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtbdscwtps.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtybvbhfnn.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gteokmadwq.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtsljghrvw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtpmvkmfwt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtofkihwyh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtdznuhehh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtmpuomrhg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtfdzqbkwy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtbijywnfy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtewvfzsmm.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtkqbohzcu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtyhrehamh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtmadxwgky.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwcdomf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtwhiespxa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtlonbjkeh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtpyszmxup.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteonvlunj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtwpuxxtpu.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtyvrmycmt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtzihkcjoa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtqrhthrzx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtpfokwnlb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtbqdjnbpo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtslmchicq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtqundzpof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtxztncaqj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gthdauuauc.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtbrrhhykp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtkzuainph.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtatlrpdws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtzwtjrgek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwmmnbpq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtjifbqear.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtdoyeflwj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtvkkynivm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtidhnugmu.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtbihiynaa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtozawoyma.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtzypgsypi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gthqpvyout.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtpodpaaet.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtqqraakzj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtdbwixxri.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtkfyzwytf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemiodlza.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgthavnwh.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtxlhbtald.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiznsngcn.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gttsiqhqgd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtbajyggdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtuipsglor.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtkvgbumzh.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtpjpdehrr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtkgimgiqf.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtqgcvwdgv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtlcabmocx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtrqcaajrk.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtiqptrntk.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtockffeai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtzjqonlkj.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtpwmawejd.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtdjuzaksp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtewmfvedx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtkfkofpdi.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtnntafgln.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtpufkowxg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gthspcafvq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtbyphugqq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtavjwyrfy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gthbaignrj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gteywkrhvc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtopqyzymt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtqphmaaoh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtincaqcom.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipxlgwvq.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtqyukzorg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtzvdiblna.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtoglobwee.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtnezwfctj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtgbyefubv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtmbkxbdjs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtumyrckba.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gttbdmward.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtsupjmppn.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtczcrhqot.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtofikdrzh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtkeueskro.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtvwtbmqhc.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtpdwgexyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtfaxllwit.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtovrquzmr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtybsznkgd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtoacpyszy.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gthpnwurje.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtjwhrvtcj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtncetyleh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtsybznjsq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtkmrnccfn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtbrsqcalp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtrzehzljn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtjhkntuoa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtptkpkxfd.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtfblnfylj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtogltaygc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtmzreeiop.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtefnzkjqz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtpcelyzlr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtswqeyieg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtaomfztmr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtmnpnmbhc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtctfqxyoe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtqbiqlhbt.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtdicihliq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtxtkuphlo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtqpymnnav.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtaoqhaynx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtnudzialn.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtigyljjjt.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtagsmkric.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtrdwxkfjj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtczdmiowr.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtdtzgtzyq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrfunnjv.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmhmygkf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtrbtkyoit.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtnvgjvwgb.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtodqypuas.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtjkuuutha.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlndcrwrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtavysqiik.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtpfffmqad.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtwaxpyzbx.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtstldnkqq.html


<!-- 参考信息 -->