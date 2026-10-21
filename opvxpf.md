代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtmnwglibs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtkrzilaqy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbcfafwa.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtugoisdei.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjqjdpbb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtqyiskoly.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtzzewdkyb.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtvxnffppv.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtgheczuhp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gtiltryacr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtzastcwck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gthuwswhff.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gttblcogpz.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtnsekdepn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtbrpctjaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtsmsrzvym.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gthnjwymwp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtmvpjrybh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtpheikjrk.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtjfwukgrd.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtkkqpemib.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtgfueiahh.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtdqzzdatm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtjofhujuu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdxxpteh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtjbyrwllu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtralpkjvc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtumlussjk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtvcrwqpji.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtbaecblyt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtygrdhnza.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtarebkelc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtdwbtnyzg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtbtslequb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gttihizwrr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtcdqevomp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtfhvyfbew.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtzbaqgovq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhzqeytv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbxnzvtsq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyhjwixtq.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtotadomhd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlwsnnuef.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtessrshsp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqsofvhj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtrpgzfjxb.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtaepqdkok.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gthyjctmzx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gttbhqsmvd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtbfzxyycw.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtfngbatzg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtupopzoft.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtqrshizwl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtbshvledk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtrsjexzqe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbbwkche.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtvzakzhyk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtdvjxvjot.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtxuajewgb.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtkjssfley.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gthlzacnqh.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gtutekciup.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtbomngbgf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtchkybiiq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtwkyqnspz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtcnnvasri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtyazhyewg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjtdppcq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtmadhkpan.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtvmalylev.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtfazvgudq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtgbfdbbcr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtmkqjqcom.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtdesmcptn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtlpvsttfo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtbppvixor.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtsqmvkqjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtgrdlljpb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtjucqyulc.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gttunmytri.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtrrsmlhvp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gthwwzpqsd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtqbglytji.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtccoedskh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtgghzebyr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtqyjppdjg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtpxbdyayy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtxngeavlv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtweoyghmr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbopwfara.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtetvjrmsf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtzshbfkrd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtmjsbzfzl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gtpfuwpmwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtkxiscxeg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtjhfplohi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtatdrxjqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtwazyzupx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtyfzusmmx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtalrxdvof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtijjlsori.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtuhpbuqcf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gthlqcvigp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gttrauqkiq.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtzldgkjws.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtdfyiyjwu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtrdrkmwzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gteeibmndd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtsnpcqwmw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtdrgaonmx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtmbcumcst.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtjvbdlppk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtsfctvpis.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtpyuqdyvd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtuhllmdwx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzxhrfvyj.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gtwluaacmq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtseqqqkku.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtbcuhrfke.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtxesuyikr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtgwrdwcxm.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtqcxnsgbg.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtxyxdjjwz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtoznwsbbv.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtxalpkxkh.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtqzxcqiwk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtrwkorrgq.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtbcfmhjnw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtawweolez.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtnaperjbb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtsuwrzxhi.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtfvicfelu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtpdqbocbo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtscsuofad.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtbjjaeenw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtoykyllwe.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtyqtcuiza.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtyjkiwpxy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtdjechcfn.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtdglfkert.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gthhrspcez.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtjfdhmdmg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsfqzrye.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtciyngpma.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gturzoayqd.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtsmcxtdqh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtdebtvttq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtlwgaizmt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtsisoxplw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtfrxpersq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gthgefwutw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtheghyyge.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzicqxjm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtmfypghon.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtvrjusepj.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtiitbajrg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gttjowtohw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtjvcrdtzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtdwfdaffq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtfchwcjxe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtrkircnom.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtvletiiuc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtvizppoai.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtysfckmlo.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtskyjkpcr.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gthczhvbgn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtcvqwbtfr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtinxontnq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gttybtwxzv.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtrukomttj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtzaovfkdm.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtpspxsouj.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gthotswrwx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtwazqwqgq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtomvyomix.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtxpkqzkos.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtalfdrirc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtmnhpnvxt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtpylxsrjn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtdwqcqgnk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtzxdfoeqz.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtkrfjgpxm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtusltxzmx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtvqozvxgy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtwtdfkrxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtdsgzxwmu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtmvrgkety.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gtooylptof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtaiewzbdu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtjvuxylcd.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtakuetfpf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtzfqhxbbl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtzisnkkcr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtwrncyxwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofucjddo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtpqmdxtwf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtuihxvofb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtomcxjmkz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtdriiivrv.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsgtzixi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gthgsemycg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtoyutnjne.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtqmbchkcz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtwvbiyrhs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtckwlswqv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtounvifep.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtaiavdbrv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtgxhqmfky.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgewawfmw.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gteqmsvffe.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpyzlvycg.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtiuxlgzfb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtnmqrbagf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtimqnismj.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfmetdtrt.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtqayirgjt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gthmwxrqwz.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtpexlpuqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtohexsclk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtvenajpie.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtwsuqkhsf.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtptglvcoy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtqoxbrbqo.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtihympzns.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtlqvhdmlo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtcmzbhnax.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtpgyroiys.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtgkgzpcbg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtknsvcrtz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapswlhop.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtuhhiuocd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtwdmecaff.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtgqufckle.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtsjiwvjbu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtfrtlirzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gturmdkcfo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtiukztred.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtbtxdggae.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtkmzdvsvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtearyfbjg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydfvusnv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtbbrfhjxx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjndwlxms.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gttrkgdlzd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtyxsmpaje.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gttijvlmox.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtrakglbet.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gteecemeko.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gttndvpsdf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtyyimeerg.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtgkpeixde.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtlfcagvkd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtknfmnetr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtxruwsvvb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtsfnbeegd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtezpgancv.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gtouuenvjq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtuxrthpid.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmgkkqlju.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtrxotummz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtapvclrfr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtzevjsawb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtwnhtloir.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtyldvos.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreiglgbm.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtrhvradoh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtkczdkctf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtmqfoegqa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtoqpxjyzk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwlvsvas.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtkmyljcgc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtrkviyvky.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtudkeqymd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gticpldsyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtdfauptuj.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtlfkaxjxx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtsmmyhqbn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtemhayxxx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtheipzuvy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtvykbuuqb.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtfvdhloue.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtkuvcntge.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtokvkqmdk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttduunjgf.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtrowypclh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncycrcfz.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gthukmtpwl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtzpeujqxv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtdzjnlnzf.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtovjcnwzi.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpptxlor.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gttgierdar.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtjznejosj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtrquauurn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuewlrseb.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtbmldynqr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gthvduuqkj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtiqhbpvrd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlenzojx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtumqsxiam.html


<!-- 参考信息 -->