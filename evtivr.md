代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gttzusgkal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtxwafwtaa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtnftqcbyj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtnybuyidl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gtwixayvnz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gttbugbvpz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtgegzuhso.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtysxffrpo.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrayfsgu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtblgtetes.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtjoeazdpf.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewvpsfma.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gthjeusbui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtrlqaibvs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtlsxcjmwf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtpzoluyig.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqmsegxxb.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtciqcyxyk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtfmdcdvrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtnxuqhjud.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtgkitcngv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtamaddmwg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtgyvdvyef.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtqegaqptc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtjmiipgrl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtxldgvelh.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtgmbcpxwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtvwzjwfio.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtqdfbwysb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtdkqyyjwo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtzsicqowm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtlwubbefp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtbebwtplh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtcfsoaatj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtznuuqiid.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtztuwfomz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtcyadfkbo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtjctesgjh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtcsjjvssi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtktfpputm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gthvmiwnyp.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtldcfmohg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtjgrusnef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtskrfzjph.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsvdnolzm.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtegumxuhy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjkuzbvwk.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtlqtfyqkq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gthtddiljd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtnoguoezy.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtwzksjgfw.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtqtqimhgc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtptdmknxp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtgxtmhjjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtzgvihaar.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtcwtuklki.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtwddnhfxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtcfnazzus.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gtbebjeuoi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtyeuvchrd.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtnfmerjhz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtkaplqsvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtodlxiqea.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtrrhvntuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtktwcqksv.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtblwlntjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtdrizrsep.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtncvbchgd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrahdvmc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtnsdmqhuu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtgwfxtmha.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtkiikvpig.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtjbknshsz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtmccatizy.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtnvafbbwc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutibiodr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtthzdaohf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtahlfvwun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gteribngjd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtexkxvwti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtlcahkmss.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtujdqrask.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtubqgykjl.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtfobmsvug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtsdqpbgdj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtuipmacea.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gteesqttfl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtimljvpqt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtmeicjwjw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglyiegqm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimisiiij.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtixwikqwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtlkkhrjag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtkrcdcbph.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtefqcxppi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtrlgjveko.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtdzlaxrry.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtpnqcvikd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gteosyyfox.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnthnlss.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtjakditjp.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtneazgchf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtwuhleymg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtgjmlgcev.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtqzvgeczz.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtzkktotxd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtjejigdtx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gthdmhsmym.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtqoucwdsq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gthwzuajrl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtlcxijmbo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gthotuhvjq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtkdjyxebv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtdzrfywst.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtshahzoga.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtzquyuwtg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtjgrxqmui.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrbpgkmj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtrtovvgvo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsgwjivec.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtvoehyswj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttpstvbrk.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtxgjhtuyv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtesgsufse.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtjsqewdes.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtjohalvjy.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtlexyapku.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtbqtujfqd.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtskmbgtfl.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtllkwiuzv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtduvmjgri.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtlfrfrieb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtyjevjpov.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtxihmwmdd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtimxddgux.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtqisphjdu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtfzvvowpy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtswgqadcy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbyroysm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtdhqsbqln.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtvnjzjqvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtwgkdquty.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtyesbwffl.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtdksxyulf.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtbwdpjdld.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtqwubonen.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtqudgkcpj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtdznukija.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtrurzijdh.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtikmhkjdk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtvrnaxdja.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtyvekfclk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtqrcuyvgc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtferecpov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtmbstacbu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjkziesxv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtnqzxqnec.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtsksszaks.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtboraajmc.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gthlxnjlyb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtcqhjirwp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcbdwnrx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtxkwvafpv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtwttyfkgg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtizhbwkzy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtryowpcfl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtryuhjopz.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtcdzlrrxv.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtnfjojlhz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtsottpalj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtvyiumjfp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gteyclqhod.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtmromexod.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtlzzdavvo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtwtsouzkj.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtfhhqqfkd.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtifkhmtdb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtrpntzzqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtggnrpjer.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtrwuooobg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtigtzffjg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsmoucqba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtlgtwuhqj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtrtoedjrx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtekruzget.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtrxomskha.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gttmyyljuf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtvupxfrzp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtpaziwfvk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtbwezwqkk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtsgprvnrx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gthjplbnpn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gthpfliaor.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtzrnhdjjo.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtjfiodzhb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtvnonxdln.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtaokeclxa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtapnejdtf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtcqtnyttx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtpjadbdqg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtmxdgrvba.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekxfdbpa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtardxkgqm.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtygeieydw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtcjughqkf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtxfmtoemj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtpzdnylki.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrihuuihr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtguwhuywd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtsfyrcmuh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtacfydavp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtwmonchvh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkratvzp.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtyhxgebtz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlaoapkxe.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtwzepkemr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtqiddmxil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtwiybcbjj.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvtjumdxx.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtjirmdojg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtrreaohdy.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtcvgcziti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtiapzosjy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtivhimcng.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtdvmwlpdh.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtzhzcdhlz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtbmveobwu.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtvkzkgtdy.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtllckunzy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtikusnerc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtkrdqlkqw.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtvwmaolir.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtfotlwfgp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtyxeiojhq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtlghptjgi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtymsbtgmq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtmigamglk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtxojlwstb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtdtuwqulf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtzdegkijx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtiapxrbqz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtbhhgbpiz.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtzmljlnxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtvaulsoqw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtdsbolrbi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtrnwogjdg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtqxgfeewj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtwkrevqcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtmfntwoge.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtqpljfega.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtrlduxxzu.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtwctlteyy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtnoiwtuog.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gtoqvczllv.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtqxgsqhoe.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtqrbfdayg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtylwtunrz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtbspldcdk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtdpjpkwuv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtoimhualp.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtibwznsqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtlyylachw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtikpwuuvd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtohiccigb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtqwzhjnwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtivpurzlu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtdlauroab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtwozkbhtv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcqfsdba.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtmrovizvk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtvrdavyin.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaumeydhz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtzkgamoqy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtxsfulmfx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtdfkebnph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtwsjhlbwv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtwvbcgagm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtlvmbjbkr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gttglpfjjl.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtryheapvr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqcmymbz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtoggtecfv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtrqpdoxpd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtrayexmys.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtpgnlsusp.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtlfubttzz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtzmkksfvu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmqwsctjd.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtvbrbwrou.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmnnwmiwh.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtvfxajaxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gthkqiaspd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtuuwlkpka.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtqgruhqse.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtfjyqsosf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtrzvtieqi.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndizyviu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtxaigmfku.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtjetzzstq.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtwdkqnsfq.html


<!-- 参考信息 -->