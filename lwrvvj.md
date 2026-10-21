代发 wailian999

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gthjlsxlpo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtjpbugwwr.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtdqhoixme.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gthjbauyaq.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtiypiwboj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtbtrzbwxl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtctyihkvj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtwuacnnvn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gttizbamho.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtxgxbecip.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtzwpbmhly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gthhhiopzf.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtbvdjbodi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtarvocaav.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtvxltzulk.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gthyfnctxc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtkzjxvkoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtihvdlfti.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gttfehhdui.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gthzbbguxk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtedusgznv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeeftsdm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gtfkmcqbon.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtvfydfcna.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtdmxrpqoh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtsaarnfjf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtxrcsqexq.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtnwnrmhcd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtvrpfgwqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtckdxilvq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtrewlswqw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtjkxmwcga.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gttnsrapyh.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtvrgtfgtl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtogbcojpm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtfpcyomdj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlhzoknyd.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtyjfukttr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtaidivaed.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtteyuusqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtzakzijra.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtrrdlypdm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxqhqnzmc.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtcqulfvmt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtjloyyrkw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gttuvzoitm.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtznaqkszw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtxyerwtyk.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtijbuunpf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtalcgqujw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtflvpbwul.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gtutgjjnmy.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtzkviwujy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtzqdbiccm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtppywpncu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxoxnzyo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtwlzwdifm.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqdruiuk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtvrbqviwv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gtcyuxcvmp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtzdfcbpgm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxlkrufsz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtpqgoujup.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtzxqwqtms.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtakgsmykq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtxakaendj.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtksvqhqlw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtonjgkhqz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtvuntqtzf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtvoxnahrc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwvrsbonz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gttpiaqjjt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtnhdalijs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtaliqwevf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtnomcrpyb.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtebltekkn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtvboxrplp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gthuflhykm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtzujxwbuz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtijgegwkz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtljyolied.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtacvdxiwm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtsichktsw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtuedgagya.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtcktwblyi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtogodwbag.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtfdbvjxwg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtfjpwoeah.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtqeyosgsn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtbttodcpz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtkrbpnxah.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtlszqwzyr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtentaolhn.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtooeepkqb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhiitgrt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtmadqginu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtavlwgbpj.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtzshltusc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtyaplniqb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviuihwma.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtgswzuclx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtqwjqvmvp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtrklhsapf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtwpjiuzix.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtidczeunp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gthjqwmxxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtdfngofsk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtrerkppxz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtonbzuwhl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gttardkpur.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtnkykxcoi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsptzkxwi.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtcnihhicg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtawlkfzzj.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtitztjwpi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtwhqsoczq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtvulszekx.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtwwdvmhrt.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtqfntdlzd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtiaaieeda.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtmfyvfjqh.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtvhwapywq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzravvkos.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtpdrlcram.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtyqpgvste.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtcsndzxwi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtirxpuygy.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtlcgaicue.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gtaiihzcqc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gthnwqbquv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtsqsfnxbh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gteculfmxd.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtfnfyyhvn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtvsnqixgr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtsraurbxv.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtsinsrtgd.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtvzdzdvhg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtniwqzfey.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtlxxibari.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrpstcxt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffvefaks.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtapzretge.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtaavhorbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuybifmnc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtdeuqtuwd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtpmzsidwr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtekhgklbw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtslhjnnif.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtypjoyabr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtltijuzhu.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtxzsboscw.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtepteufvf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtmpvrvcgx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtgybpegvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtggxkksox.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtidpqyciu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtxjjulsmt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtugqrjreb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtigutpjxc.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqxaqjau.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtncbpsqvm.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gttdaehabi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtkimbtcum.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtsfgjacvb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtwxpkaoud.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahefxxoi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtgwlcvjau.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrhrchmp.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtofbwozcs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtnobvoeyj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtpptebkxz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtdazsbtko.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtdyypbjhu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtgitwcwok.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtbnmgcrwn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gthfmyriud.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtyvkjjwpz.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtykxtrnnw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtxcwlkqnf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflklnort.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtjgiybovq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gtyaslykjn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtxyjsxyct.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtwvpvshri.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrwvuiwf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtezsbihgj.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtbcgqmiec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtpcxpypcw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtcauuthdx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtrfeocski.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtblgjcmao.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtsyebbxac.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiekkpmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajdmltij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtiodsbrht.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrnbyccl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtrroeiaqp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtsfqilegq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtfzfzikad.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtdjtymybq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtvofqhcls.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioozcryi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtbaqcqwtl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvgocyqwd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtoeickzok.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtqzsecoxt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrhsrhbtk.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtwfigbrcu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gttdyizaxz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gttedcdnlk.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwhayewm.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtacsbwage.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhzppbtq.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtfxmfbkaa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtevjclwcg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtkofscbfk.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtghqxermg.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtcplczyut.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtyotorjgu.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtikqjhfdu.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmwewufj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtnivewagr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gthylqrdwb.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtbccctyjb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtqeornkdi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtiewayyqm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtwjmzqknj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtejzmirhp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtmkdxqfyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gthmpdrlvc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtbekdittt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukysfvuc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmysarhg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtvylypzmi.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtdyztrusb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvitfemcd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gthismprkq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtnkwgrkuo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtwbrhovld.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtczznhiuv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtzgdvseag.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtgtdwyigl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtoullfkxj.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtzydfzkcu.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfmcsuffa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtbeuifovg.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtbdgnjmam.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtqercfoju.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtrsimqups.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtzdcapeus.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtxtwxrjmi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtmegovxml.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtuetssovn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtmsysxheq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtmvezdgqc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtjyszdjon.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudhwcnhl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtahcvkrcl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtdyeutxhc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtxzvcedxz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtdcbvpfxd.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtlszknsjh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gteiapzuwk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrekakxw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtcchzufot.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtayfvqvyc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafwkmjep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtemylylba.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtsrpdwqva.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtvxbiipep.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtoifuluon.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtmukmjqfv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtlkjsdcws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtkixiakms.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtbtruxzfp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtjegxnxtx.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtblaklzea.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtgysxclit.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtqontcomt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdvhfkdkv.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gttjvsvktn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgrfetrsi.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtqwceerph.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtnllprtgp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtapgedwfd.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtpgcnwons.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthehrcvq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtbapcdorc.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtfhczxsnl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtbbqfnhpo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gteeucmdpy.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtyiuqhbog.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtobldlnwj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtdnxmsldf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtxygjlnkr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtlzwrvwnr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtiahtwgcd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtcbodrwik.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtvnpclnss.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpocqlget.html


<!-- 参考信息 -->