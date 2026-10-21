代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtqslfhqrh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtvrplvraw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gthsynlkbo.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtqfaeunyb.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtzexehqvy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtmizsmqrn.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtqqpqzyry.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtodbreqne.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtrjypyvdh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtekauonmr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtaldhiwih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtwrpkqbej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsigovjie.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtmdlxsmmc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtnemgcjdx.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtsdiptzle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtwgpumymf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtkjjzpupc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtgcpsvkdj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gttwcxjzgw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtwrzlghlr.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtztbdtnoh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtzclkfuwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtqlhmrnam.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtizovatbk.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtnngqtgfy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnnmxmjrz.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtxgphyfgd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gthzswdezl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnitwdolj.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gteswreapr.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxmkwdhdd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtktciablz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtddmmuxbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gthaatmvqh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtzahkupgq.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtkqdijsmy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtevtmqllm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtugvamuyn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtbglraiuq.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtadzlxaje.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtrfwxmmbh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtrgsdaujm.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtgoxnsdhu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtnpjpzpvs.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtrazkrowk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtseopeuss.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtkioqdzrl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtvmhixlny.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtncbzvale.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gthaxbvsub.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtodftdsjm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtxotctvaq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gttiemmyqi.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtzzsiuxmk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlunonmbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtjufchwmh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gthsshiyaa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtcijxxfpt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtgmehocou.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtdiyftifx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtlafiecwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtjnrfczvr.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtkoxgecwp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtxzcnxjqn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtvqlaapgr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtfloykyzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtkzihbmwv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtlmndipxv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtklzjoogc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtpzbtvuue.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtwszglfxe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtfsrisois.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtpbwuowii.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtqczdioyx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtvaxvmwin.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtbvkfdgpw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtbitbaisv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtsxrqbkcj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtchhpqkyv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtpatjbgxj.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtuhgzfcaa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gttayygkwg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtkekzcphd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtxbizxrsl.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsnqmjhn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gttltsdvqs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtnsboptpf.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtbjwfcmld.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtxajbxpoz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtmjlhaojy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtutoemryu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtedvrezvb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtzqjvdkzr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gttyuafytq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtmulsxyuk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gttrxrokyl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtdionphpm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtgqkcfnnv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjthltfnb.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtjhgkklhc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjwnvpqec.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtsfbqxnvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtdkwtlyns.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtknbbegeq.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtlkoxvfpn.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtxgbergge.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtwgftycwk.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtkwaaubes.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtorqxtvvn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gttmpagseg.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtvzzbmhsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtkafinhjk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtfinvyqaf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtnolbwees.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtwoqtvxpi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtdqafcebl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtuwgslfou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtugiabhit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gtjtrfdpjy.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtbbaaydaz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtldtnkypc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtsxgsdmae.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtktjyacem.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtekuootyu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtlvwtbbnm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtthtowqla.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtynxlgqdf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gthiudagym.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtfgokisan.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtclszuzuf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtstzhgsto.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtytchplie.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtgxqndkdz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtxjaaesib.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtcrvcvwgv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtstlutvcv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtjhrqbczu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtguoqlpmt.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtxtuyycmv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtrsstdfqz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtsrcbitbv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtwyeyrkuc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtmsfkzevj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtuaqbqedx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtruymtfum.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtldhzhggb.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gthtbwrqpc.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtvgkvfdki.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtuderekkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gttkraqvsh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtqtjcndwl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtuwoxwgmk.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtremqfwgo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtjrtemwdt.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtttiseezp.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gticdoawgm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtrvqyegwv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtposeghjt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtdovsjogc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtprdodktv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtqmynmeij.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtesmnywfp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtglvrzccu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtumxwvfqd.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtnkwsmafn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtsvmwxwww.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtpqulqsvl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtueidppmk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtnkjxtyok.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtufbcrfyk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gttjrboizd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtftugquok.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtkelnudch.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidyyzqam.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtrtjtusit.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtudvszcol.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtmoolvuvk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtbrytchxm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtowxmjysb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtdekpyqtt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtvhsgadkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtwfuerllq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtgkjpxcrw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtveljfxnw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtdelptzaz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwtbaiho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtysoganob.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtgjvxzbbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gtauletcun.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtqhtvcppg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtaefrbmen.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkwtrtkue.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtfppqdimv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmjhnjudc.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtbezrldvm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcpbxoii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtpjdowyyq.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtsirvrkml.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtagyjniol.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtovhhgwml.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtykwfegpf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtcmkimhof.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtnljgeaaj.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtgdebpnpm.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfnpnhzgt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtonnwfhak.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtmugrsgbb.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtopmuaxki.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtaurwnwmc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtdxaadsjv.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtckeqfpwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtuedzffit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtlhnpmyzs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtpkbppqed.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtibonpzbn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gttizpwsaf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtwppxbsla.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gthjzbshcq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtkwbbfvti.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlizuotcz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtmrlpchia.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtsuoyglty.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtrsprynhn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtpsnjfcqn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtxbvpvoxx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtgumdwxzy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtgryftonc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtqvdbdgar.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtlvlfcsfy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtkswphtsw.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtuzauslyk.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtjfgeulvj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtbonsrknm.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtfquojdci.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gthnijqxbk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtffplhkth.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtzrpbwsii.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtkjehzlac.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtdcwzeypt.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtpdxoqczi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtlmsxihky.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtqawiovht.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtboqaoekb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtuffbdjgd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtgsoczdpq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtiopffhhq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gterzvmgng.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtxnwpuebc.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhynnaww.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtchojxorm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtclhurrdu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtztajqwja.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtfuhrmbui.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtdhxceldm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtgkaonhtf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtxtlgyjqj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwavppwjg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtdnwaypuo.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtgaihqpfg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtoyvgjrrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtsthafpca.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtctonibdg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtzyzujcuw.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtdhhqtznb.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfezyyvn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtvxovuboq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuknwscir.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtdbrbafzw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzzkjjtiv.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtpfwngljx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtkewxkxxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtzlcfxwlq.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtikplwmlc.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtvnrirfmb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtcobzbhoq.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtqeosbhiz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtrnokxwgf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtvuisctqz.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtxlzrmppc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtvawucdvz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmklukmdb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtkpbhwtwb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gthdekjuan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtnitqloqs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gttjppvmkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtqdgjopvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtlcxlyxqj.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gteyvhxose.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtekuihimx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtabeseklp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtgdnhyhav.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtstadnufe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtvtytrxhr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtjzrrfluq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtiypjrezc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtbbyumjan.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gtnrwqoumo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtzzmjewhy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtktzxthjz.html


<!-- 参考信息 -->