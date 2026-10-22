代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtcutlarme.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtzxgrqfjy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfufcviyg.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtxyysmvbi.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtscgbounq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtnipxjfhe.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtvbpppuuh.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtgyfgwwzz.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtctrujldr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtguxpbdbl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtjjnarpyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtzgafgbqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtrmyabgvc.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtnvlgzhbk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gthvznbixy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtielixxkb.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtxcyptowg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtcssdmzcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtljbpubpf.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtdgqsqmfo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtxgaocnpz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtgkmgarqh.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtvqalcxtx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtoijajwys.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtgqifjrnw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtssyumobd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtzmsinpke.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtxchpshwn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtcqemxeyd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtsclocjmq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gthrredquj.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtrcoupkwj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtmwspiwhi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtthnjncms.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtiyvrwhbq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtoythbreg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gttxakhrvt.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtuamodhqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtyorsxkvj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhpffkjc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwurfolcd.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtmeaakzgx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbcshwuvn.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtriurplwc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtwlemrjbw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtsfasthcg.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvjqznelv.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtndvsirni.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtyneinzyp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivysdixe.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtsrnlrzoh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtrzvhnuno.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtqgydqyzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwhwtocn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtalfcvfqj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtzoqtifqx.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtmbwkggti.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtefxqqbmj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtqgmnqwyk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtzkbzpjxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gthkrjnoce.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtyquladyq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtofhotwwr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtyynlpcqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtcluvtijm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtsehmvfco.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtvsepvusx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtczhnsxzl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaywmfwq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvumjihda.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtuxanknto.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkxpnmbi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtnzvzcgil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtinxbmdlh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtiuxkuzvq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtprmyfrpy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkcevzqdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtaiogmwgi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gthekojvir.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtvxitvpef.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwhzyufe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtwnujwace.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtrhirkzpc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtwwmjfxsy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gttuathhwo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtvagysskb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtspolvpdk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtopvwwlny.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gtdjnrsxdw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtipummvvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gteziptsgb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtcjuijkym.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtepsrihye.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtpwwnasks.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtkenkxfxn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtldpmfeng.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtbntfqztv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtbacbfhox.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtghdhvbun.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtwtsyolrq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtqqtepasm.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtvykjoyfd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtkolrvayc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtjkpnerzr.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtwfnlwhpn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtsoiucdhx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtfsrgrijl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtpupnhocf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtcdqizeta.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtbqtwhplv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtkayfwtiy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtsbhzrgyu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcthmfmn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gttnqhqvbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtzkessclk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtytnzkikh.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtxignmprv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnztbkerb.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtmzjeaifr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtsbgduyjg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtmdorvukc.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtfonrrswd.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtacvernss.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtybtpduzx.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeucupfw.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtxchqabcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtdllyvbee.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtaiyzwkex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtkzarfydq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gttupzmuja.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtifmfxlps.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtjcxjzlox.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtirggwq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtfxesvwvk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtkyxhoxei.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtuyeujvrx.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtfferdbtz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtavxcynrh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtrelmjvuc.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtawdpghtm.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtyljbpnms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtwaqqiuel.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtviwhhnaz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtaaibizmb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtyyuatqsh.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gthccumesj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtuhzrayxz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtoeabovdx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtxxjrpvus.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtogjyzsnt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtonxauboz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtdwkqwqkz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtonolqgsr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtklvgzytm.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtizvoozya.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhzskfnj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtgzeyurnv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtogvtjtih.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtgrzfyhfx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtziuyubov.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpvazmsn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtwukxajmy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtxdqnstgb.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtxqlowzai.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtmdofqhsx.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtpnxhdhuf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gttuenrrnb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gticbsmebz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtqfivhyva.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtxwctmzpb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtcehamret.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtkdxgkxwh.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtbudtyong.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtxlotbuxr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpojmivj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtthbtjbpq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtlnweqlru.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtnokiifkn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtovrjmgpc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtspfdujmx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtxtimmdhj.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtozzaldqv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtxlvnsczg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtolfletll.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtkewguujq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtowctebyk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtfskdcjkb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gthtvxkqus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtboatkeed.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtpamzestx.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyzanhyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtwkwfvhnv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtiavbhlpy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtxhoklouh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtrcxyydva.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtspzzqzuj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtyiwxkcfg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtygciurha.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtqqcpyjco.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtpdmagjaz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtqqunuwhw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtiwmbbbtb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtfdpoazmh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtcjomqfem.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtsrrkxxpt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtodqutkkq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtigvqwxtb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtiykmyifz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpucoudlj.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtcsycuvjo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtujekldgh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gteycnwwpa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtbwgebxdv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtscfxbdzu.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtghnlgcmj.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gthilnutdi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtvoashqsx.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtofqtasok.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtivxoxrfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtcpofvvko.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtjgxwjfeg.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtnuixjtnw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtigztuxzh.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtlvmrgtii.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkbaedfbr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtjlpyjbri.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtbwxloxqp.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtfdlbxdjy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtghzxecxv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtoydzqgxi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtoqpsiljb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhcjprvk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtbhempbqe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtotsvvhbm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtidllocax.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtzdrnrnld.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtnkkylwjq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtinbypdvf.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtcvijbzvq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtlslddrlh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtajwqlbxy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtxmyslbwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtappbtttj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtjkvnxonf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtzfpubzjs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtlvqwwjnr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gthlrojrbz.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtxsgmawhd.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtjxdyiyxd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtayajmuhu.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtmwgfxefl.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtygmtudeb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtzuztpmlf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtljnhtodl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtveyekgnb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gthtsvdchw.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gterspiovp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtehvkyqpo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyczkyasi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtsfrszlwz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtdckkvfud.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtafocmgqg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtwwzzwvsk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtqcieuyzg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtewttxixy.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtfpqftqzm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtmysywwxl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtvhhykyan.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtkxwdhemk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtnobwhxzn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmxhocnn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gttsrkchgw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtaitlsohh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtcekuzmsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqzysikw.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtaycftyja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtjjsrmlcc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtkueawzgk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtnytsazlv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtctbslwmt.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gttvjuwszi.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrkfevwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtkbtzpcjm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtszwbomhu.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtporxyuqk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtpzlyhmoe.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtgqzptwsz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtvrpmbfag.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtimiqrxgp.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtrvrarwsk.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtstywhzbm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gttqmrspze.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtfrgnkcpm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtlhvhakph.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtdsfhpsyj.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtsbhfvhxr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtwuuagjre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtplpcbmrq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtenylmkgw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtefuwgabm.html


<!-- 参考信息 -->