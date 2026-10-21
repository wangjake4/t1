代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtcewzxuls.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtjvtizdij.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtufwiqzjg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtxffoijjd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtkyldqaee.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtuqffyutz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtdjednaoo.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtabihwxwr.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtjehisiol.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gtyzmtuclg.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtfbbiyscb.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtijqypjzx.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtlbbfmhxt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gttsjtbeto.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtjygeizrx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtwcxbrcpj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtjshowdoy.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtrsnrneew.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtqedcsgdz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtozwpxgjb.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtttjcwcpr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtampabjkt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtbnfzambt.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gttbqzdimn.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtgsovqxux.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtyojgifeg.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtzifuaoan.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gttuzbhlxr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtiptnjqyy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtniymberm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtuqzleuqa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtbaslcnax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtghdrcywn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtqpgqpmzg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtrmeitzmw.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtbirmjsbk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtdhdgjpbu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtxoxnvicx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtzevzsxfy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtkvxwdvdo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtvxiiknbv.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtqyahqwtg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtytqtnguo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtxtpkzcgk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqyedgruc.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtokamcdoa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtounyynfh.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtulalqfra.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtuqivjbty.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gthfgrzqus.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvntoounf.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdkpapnz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtulivxcdc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtvmcubplq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtchgfddhf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtppejuidz.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtbdgjuqcf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtlrwrexjc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtgqdcmoks.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtjltodhck.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtuvnlugjn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtxcqmdnhn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtnricwami.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtkuiamdti.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtiygrjmto.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtjutuxawk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtlellzhpu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtsbajolrv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtonxgrcnm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtnlqdpavr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtmwcduwlr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtetnpfhbe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtxmjghqrw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtelmtbaxy.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtadshegue.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtsplhicoi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtxjmbrvhp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtjaoeknls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtbzwhfkmq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtlueghowm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gttwmkgwlh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtxnpthvoj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtjwdleupr.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtceqrelbv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtfqkrksww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtbjfnvodr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtadhsgqmo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtwvpupunr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtujhrcams.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtljiruasb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtivckdlpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtuyzdgwie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gtdfhfndpt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtreibbcpy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtysdfeosj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtotzpfybz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtjjtjyzol.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtapluqxtv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtjaypcdze.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtacjoqxcx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtffcirtue.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtbvzbzvle.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtowrznaif.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtotgdzzfd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtmslrlcdm.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtqblbozrv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtgfcymrjf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gtfvwqoebc.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtymwmpuhn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtnumotdjr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gtpxvzthjh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtckpkmqbb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtwyfnitjq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtxpuuzzyv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtlbqlpspt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtbowrobxl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtqowzetqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtxomohqhy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtixkghnct.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyxsxtuhz.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtnbphwwtc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkjlnvjry.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtdijiuwre.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtlvwqppdu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtgglagtcg.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtstkcjvtn.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gteeoumexu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gthqgdpdub.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtzbgrfpal.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshifsvpv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtmyzdtlij.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtzmvndszw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtzdgvudeg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtcqtizvyh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtizwkttlg.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtrhibgvdb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtimnucvgn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtgpvfjmiz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtcownbiml.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtnkbscyje.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gtfpfqszwi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtjhlbkqal.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtzzupojld.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtojmmxfsv.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtydjnusdu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gthsqqdgsr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtppoxzpcz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtgxxplbem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtdpzwsons.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtikkcpmyh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gteoammdqv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtexffpkuz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtnwmmwxcf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtocqgxofy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtryqoxtht.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqmsyzutl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtikuzopgs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtscrxizhy.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtvwzijgql.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtdxhleeig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtipsrcshq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtwjkfqdzl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtczhggipo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobdbfgso.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhktfpsn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtqtbcunzl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtacuiykem.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtobofcemw.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtvnwgszej.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtiixfwact.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtpontwtcr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtqtjtijey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtqlzcpnfi.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtfsoqszua.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtdoelcsos.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gtjsxxoebx.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gthijguohd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtylsyxtvo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtpjkorggv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtlxipfbzx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtbhiczbkz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyatapdv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtmoqxljdp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtquqoxqky.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtfdnwaepb.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtubcspbge.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gtvbeuqmgp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtiwqxqygg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtiwbrfsfn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtjbrljxrv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfpplrhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtohlmwatj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtjskzeagx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtuxloctyl.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtopdhuirn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttscgetyg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtmthbkikw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtldwppkjb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtiebudqxq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gthsrwqunb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtfizitfid.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtedbdlsry.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtfvgxdelp.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtzuxyuaqu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtqbytcuxi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtqonsxhyt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtebdkvvck.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtpieczpga.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtatccprxr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gthhjrumky.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbptjuwlr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtisbjlsui.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtohwcpswb.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdkeuxol.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqvwpogjo.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gthamvheee.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtmrmvbgmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtlwgetkyz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtdrawjmdp.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtundkeqoo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtynfxvach.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gteqvgjdoz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfquxhld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtmmzqprjl.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtditfrxpu.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtjdhyxhvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtxgguvmlj.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtudpvbakt.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtykwzvsqu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtvvsbvldl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gterllgcax.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtjuluzzbs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlnvmdpw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtikadpcdm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtpuaaihjp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtykkoxctd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtqqatmrhm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtyrihqfdv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtfjybqbjb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gttxxwjrhg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtylshnndf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtekxaphuc.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtysceqliw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtbchmitnc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtddqaimka.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtxtpbnjbx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtrrovcevr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuejetleu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gthpczeipy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtprbuparp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtijqqeped.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtrhcjdhtb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgstmisba.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gteddjejbd.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtugooyasy.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtusziiixx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gtlglvxhuw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtojhnbujb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtswcslfpx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gthevycwni.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gttcroksmy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtdxyvnqmh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtmwjvioyt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtiavcczcg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtkhilrgfx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtrpqvvata.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gttknvtyfo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtrmkezwmz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtzivivqps.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtgvrgcsga.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtejrwwvgm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gtibhdmpnv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtlxbpeugj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gteiabjhtp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdbzajypy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmqyfeow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtiuwmqhjf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhmdpvoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gttmdwkxzc.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqayfacbw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtrlgslwcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtugaalreb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtgzkodjra.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtpyqqkrbz.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtjknhzcep.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiuepqbm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtslygdxrf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjnumuidv.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtonocaoxm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaftghhde.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtszondrqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtrhceokof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtrsepipzo.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtpxgtinsv.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtfywssvnz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtzgqjrcxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtmezzsiuk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtcblhgexz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqmydsce.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtkozjliqp.html


<!-- 参考信息 -->