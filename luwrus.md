代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtaptbikid.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gttevgzltk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtdbcydewn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtfyeosavu.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtqbbgvyom.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtwctjflkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtppuuechi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtyaoeqfvo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtofaawavf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gttrywpncc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtnlyehzjb.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtwvwluijr.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtkusmqbct.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtieeqqzaf.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtobrscgcz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtezstfeak.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtmeqfcgjl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtyhzrcrej.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtuvtpohad.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtlelsplbs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtwlkpfpck.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtkdzqqopa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtndompsnt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtklrgsctr.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtbxzyvzrl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtzggpqgdt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gttknnzyqg.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtvhasmvqi.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtpzfoyygv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtoaitudts.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gteazlztzv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gtnhxdgmul.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtatolmjeb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtayhzugvs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtwukhchta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtpgowmnqc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtwkcmqldi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtisciydgv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtmkraqzvw.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtxngmaico.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtevflnwdy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtvtdqjokj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtilcnigjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtbcbmgwoi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtczvuxmto.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtgjgsmphn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhjgexkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtrxwnzage.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteqydwrbj.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtwsgomdwi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwvaroiso.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtnannxppg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtlqixdyos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtrknmtuzw.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtdneszdmk.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtseewfdhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtogbkkcen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtnpndmfie.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtgojwvxyd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtbjqkykqs.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gttruebvqv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtlovsspub.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtnbkxiknl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtjhjddeoz.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtzhwojrli.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtonyivwhz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfrdciiz.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtmwtbjtsl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtzukqcfhz.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gttdmuslzi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxtdevwgv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtpqlvanke.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtipbbnmjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtulmzeyer.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtcpqtqrhj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtztidioyf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtxngohnge.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtuauayljz.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gthiiairjo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtnfzjlfgk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtudlxsokc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtdhszhmrs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtrxdazoxs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtcayzsulj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtflryvhpl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtwxoxfeuy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtmdqwqihw.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfpreujc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtzgfrgfaf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtmszvfkpj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtzaxsohzu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtmwachnpy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtracqhieq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtclebjpav.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtvbyqmtal.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtmkqnvkuo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtxhaugcio.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtpsttdium.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtmthbrolj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuywxfigx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gthwfpujmh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtsuzshalo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtmihpzhbs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtgmqyzcuf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gteyfmzcqm.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtvtqvxlbx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtnfwgguva.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtkylygheg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtpxvpndjp.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtmzmwxtro.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtnrmxmakn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtvoobahcp.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtaawscwsj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtxoufbtsh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtwvkvaoil.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtqnxqpgsx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtqomffahi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtyrrgpfkj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gteptllhlw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtgvcmumxu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtruztnyqp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtoacmqyre.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtatwwmcum.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjgdspwug.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtbepsgeum.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzzsgcruv.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtcgremhnq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtwelypanl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtiuwnyxtt.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtorculyrh.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtaxzwurbl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtcdzspdee.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtpnfarsih.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtctroyyuz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtimuqdcsf.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gtprkwzshh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtaceqqpnk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtlqvhhwee.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtblimcsoc.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqobnzk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtmcxvybbw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gthdvpwnvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtriwcbshk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtryijhefr.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtslahtyxc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtvuvxpyra.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtnrbzpshw.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtqtvwshvd.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtgefifrjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtioxzfvga.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtgjeasozx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtiqqekolm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlyblvgk.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtshjvvolg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtkupwspux.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtyvnewflt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtfjjjzeyy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtggqcpfxf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqibwystj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtizytxvmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gttsgrkiwf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtkuxgpyzr.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtosyebgna.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtpsylzmgq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtarslsbts.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtnvweinub.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtmfdkmpzb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtdkdtzxjj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtjwhzyorm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gthrzgyxnz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtcaiojusr.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtixisadgl.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtbvlcclxx.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gthmlyqlvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtclrbufmd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtnhwvjskj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtqumxcvdp.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtmuedxuai.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtdglzzebo.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtbpndokpp.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtrhnungli.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtebrjiymc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtiksjpmlo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoodezet.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtuwmmppkg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtvtvolclh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gthyqpufmt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtojmfflik.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtwjvxzrqc.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtxkwvbhrn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtooiucans.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtpoixxdla.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtazzyhvoi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtkmraxpgn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtyvysbejw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwywqwhno.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtkydepgrg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtvhtaeghx.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtsmavvjfy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gthneqgsyw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtdvpiclpa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtdaowcsro.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtvflikivw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtmfhmohuc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtlvfqwngs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtcafuoenq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtxsecfyth.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtulnvmidj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlbzxuke.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtplujhwbu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtdsondntt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gtiavjrlai.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtkgzwmklp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gteushzcyt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtgskwyhwj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtccjmqdhd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtljifvccs.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtbdyqtqhu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtserozipc.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtzpdxxfkp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtchkadxsb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtazuppmgc.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtcdzzxpgg.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtlfuwapvv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtruvyiexz.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtzelopyis.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtfujsmbmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtvwqwahsv.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtcezocywz.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtltnlbmfs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtcrbbxrpi.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtqlermkjp.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gttwlmpuly.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtufkhhvxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtkwzksvrp.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtymuqvbfi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtudixotgd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtubhnidwp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtxsjzlrnx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtmetolatp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdcochlbl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtxxajlzqb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmlahjabx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtvcjskeql.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkrjpjbtt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtkmeayyuu.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtgzizomqv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gteztsecrd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtyebbfiki.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gttuujeixx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtbrdfvbjj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gttouztyla.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtivpfejox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtftbrsdvs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtvwhbpsiu.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjpsrtln.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtqvxzylbw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtlultlxxu.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxdyabsfl.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmiqwehx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtxmhfjqnz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtqjhxmxby.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtbhvtvpoq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtigtzyamg.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtovhqewgd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtbezxpxvg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtcxdtsovv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbinuoyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtcazrxdwt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtmuptccbf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtiezeyyhw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtmsbwwobe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtmspysfqo.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtjwpddlqe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtmgozejyn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcdauurb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gttluufite.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtjwjvxjqd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtfehxbowb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtemkspbmp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtzrkalhgf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepybunxe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtbgdgnbhl.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtcogefxrs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtqxxrxosg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtwsnigkuu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtemovputt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gtmwwdiyxr.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtsoiaafto.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtbyejfeyp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtyfftbvgs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpfvytzsa.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtiabnptmn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtroojhzll.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtcdfthrxy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtkhebotzd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtmehjgifg.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmfsfarr.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtikfonrmk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gthxkwxuip.html


<!-- 参考信息 -->