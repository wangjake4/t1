代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtitpyvcyi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtlakmzujz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtsfgbfmwl.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtzaptqucl.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtsyswbtvx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtmxtiutob.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtwdcbhtah.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtaofvywcc.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtyilzfvda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtebfajynv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtpcejnlvy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtvavttfmt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoyinbqo.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtwvifyopv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtzkwxjffi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtdswixgbr.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtrugwmhcg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavcpotn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gttrexizfn.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gturkeqyen.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtqjtsglcf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtrojydjhi.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtjrvogbzv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtfbymphrh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtpqmnovjc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtckyzkxcv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtjyxobrxp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtwmoksedk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtkcomtnjl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtdzrtxlvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtnbffxbpp.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtcmszoewy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtqapoxdzb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtvpenrvzt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtslxoemfn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtcjidhhcj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtlkopxhoh.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtkpifdjfp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxchfuzus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gthhilpjqr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoujyznic.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtcqrrvopd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnuzrijnw.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtmtehljxi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gthyzvwnay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtskrpcsxq.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtkblveyqm.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzzbvzjxc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtbkvnolgp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrouqvcz.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtlnpmbjwn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtgpqjpbye.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gttqornnof.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtqshaarom.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtfpwgtugb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtyefhcazy.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtvtfgghcu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtqtvnrmac.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtwdivyeqr.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjlrkoih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtqftghhee.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtigrvvmpe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtlnfuaeqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtajpcbnis.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtywhpxbiz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtxooeskmb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtxoqwpnsc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gtofdidtbx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtsgrqgerk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtmtsmfvxz.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtabsepjqe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxofzjkjc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtaclfxotd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtcbgphyva.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtyekptrsf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtmhevmyep.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtzepfxbvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtbqnkovdd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtgvbiqtwb.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtxoccihqr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtpimlswqw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtipjqgieg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoizjrrdt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtcjlvsewy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfsfasdl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtsazwspms.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpybpqsnw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtyhkxlnyh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtxouewpzc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtawzayagt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmwjrkjc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gttybmcmxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtzcfcxyxd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtfskjcdxi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtlgfxoskk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtvxgqgilh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtvbpmhbkl.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtqaskcupw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtsfjzdoxr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtcegbbwks.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtggqtccme.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtiyvwceol.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtucslpgrp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtxpozekyr.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtgfbwvkjw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gteeumderr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtswqdopcw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtrxtgiqmz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtgpeljpzl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtgzweemay.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gteuiafyae.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwcxnmbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtxhwropin.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtxgggvqok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtjahvztvs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtaqqjqoaj.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtqobzyqyl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuvxxhajx.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gttohysyik.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfobcwkn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtmaghuzgc.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtjlsetwvl.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtbvrvxeqq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtnbahppjd.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtezsyktpy.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtzhfaomle.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtvsuycejj.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbfhjlay.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtocnqwuhd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtvwobxsvh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtwrtaeikt.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtxanduivj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtccfnrczn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtgotqghcq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfkuduec.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtgvlxkjcp.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtupzspvob.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtexhnoncb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtaiweixlu.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtsljyvfoa.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtjbunewux.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtniidfrab.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtbsimbzjd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtwcrxlxnj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtckuqsznx.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtouijulnf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplbvffvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtqaiojspr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtpjmmojqq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtyibcywbo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtciacahro.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gttaxzmgge.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtmbqarzrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtcfkvsfkl.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtzhmcjzqf.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtukpsqsti.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtlzjuhvcz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtrrcnfbbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gthvgnzxoh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gtaaxcunzj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtercckxqd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtgsoamrun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtyjfudegz.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtwwdvvpgo.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtxvwelzjg.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnznbrlfl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gtfszugzlc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gthmvfaygr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtxrxccbnm.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtixjezmoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtgoyyyhbe.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtminsbvbs.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtqovovcgp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtdetvlzmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtnbqbhjab.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gterynsmjn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtxijfjzmq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtamcupfkb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtarmpnciy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtfstzepyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtjbojbfne.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtqzmbosbo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtkiukphys.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gththsfyda.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtpptflsmd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzzntcqg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsgqvzwd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtmrnefwbv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwhbtshx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtuwlpnfjj.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtllccucoa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtqakijjhs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtoxodcjds.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtqeorexvc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtddfuudef.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtblxjwbsf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtuppfpaez.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gthtmzmafx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtrxtjqapk.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtplnbtsub.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtichhxnso.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtpzjujzek.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbwofokg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtpzutofzh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtrdxuswtf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtuskabuhz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtknlxfpmf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gtsfinwuyw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnxptagl.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtswsirymr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthucijdfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtxpjtvhzc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtbozokxsq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gthcwotabn.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtfjqoalvd.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtfrbdwenz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtlngrgzfj.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtaqelalah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtunkoarve.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtcmxkeyfv.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtjwrmmjeo.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtfmbfbgya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gttxzjpvyc.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtlafieqla.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxtvnldq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtckksnkox.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtixotcgmk.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gttomiecps.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttfvhlpov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gthcfhotii.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtadsbrxxr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtlbexavpe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtoyqfdact.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtswjlmqwe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtidhdivoi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtyrmqowzb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtghaxdbkd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtnxqjndzt.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gttutjqkdu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtvetsejki.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtxzkeqajd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtkuqerjkg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtygtzynnu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtoqwzyyay.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtknunqszs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtrhaxzjfq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtzkvnsshz.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtygraepkf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtqcnpctor.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtalhfbudm.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrowrdpyr.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtpljeffyo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtundulzhm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gthsyfphwf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtffybpgfz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwxebxdb.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlfkigvg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtqzunvsxt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gthykqdnay.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtmlqmzxnj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtebdhemxr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtlntleuyc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtzjdzmbuh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gteraebvhf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtjmrevwqb.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtpvjxkiuc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtreefudxs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtqclgkurm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtjxckxezh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtuarphtoz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpwxtpsd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtaytoxfqb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtfqqtoyvn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvquqrbh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtlsioomfq.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtkrqlwgof.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtlbritxsf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gthhlrirsp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtqqrndgus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtuyotjmsl.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtcwasmxgi.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtlfttfrqg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtvugsjtry.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtchqlilaz.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdlqujes.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfyzfqijj.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtgtkfubbi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtcnklspou.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtvvzkflsa.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtrwbcoeqv.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtvpsalcvi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtpmkgmyba.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuxopmoq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gtqcnnjwdm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtchpcricd.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtqmltjcyt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtdsijthpa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtrqsxfvtu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtegnqpoxx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtygetwmbh.html


<!-- 参考信息 -->