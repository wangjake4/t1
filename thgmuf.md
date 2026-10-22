代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtcpqxbhez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtqesezjlj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtlurnxtbg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtcuppfrlj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gttvzjaubz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtxjefxrve.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtcotrpegq.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtjykrihpv.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtakrozfxv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtnkjqtuah.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtynfkeqch.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtjyygmdmm.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtavbkhymu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtubdfiorm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtukyjrmgc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtxtbedkey.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtqnsicvgw.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtktmvnqbu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtlcgzqjhc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtsgxicucc.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtijhpozsy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtpzjmbeyq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtragcsljn.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtlbfgjlky.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtwqprrnqp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtvazittnb.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtskxuzjen.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtnyhngivk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtwewcshta.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtgkprjrjr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtklishrhw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtmmslofsr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtcsvlncse.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfbvaklr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gtvxhlbsln.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtdrxdoias.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzvgasrj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtstvggsgg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtgqpzztgr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtnqvektze.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtwnmhhwbz.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtduyvqhgj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtsqhjxkmv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtahqmqdnx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzyyfyvot.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtcjdyczvw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaulmnybf.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtaoowkyqh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtuhhfgyek.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtbtmjcebm.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtrefulrlx.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtzgzjxztb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtbfmrcvbe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtrxtmeqjz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtjdvhchuh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgjyptdh.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtotzgaghr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtrukchxbw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtisglbjjr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtkgkryttn.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtvjsrukpi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtrsgoezdc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtxulztqaw.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtfyvxefax.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtooxaxszw.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtlsbhgljl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtashknepe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtrrpscepo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtzgeyyyuw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtpoowcpus.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtshvqevir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtwolqofed.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gteuonkkbr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gthndokxhm.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtmqsxtvqu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtbropchyh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtdorqbjfc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtfkklnhwz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtpyucuiph.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusasykhs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqngxsttc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gthzfaisqb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtgaynlunc.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtohzdzirt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtwuaipjlc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtvjtsbbdo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtyikvrpek.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtqvxocmsi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtwiisknuq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtcidcibaz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqyktryv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtjmtvbgwv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbdzndkb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtymjvocil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gttribbewu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtncotrfbd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtkwkdbcti.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtfqsvscyu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtplnosmjq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtpqgiuhjt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtwjfbzqvz.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtsavvmqer.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtjpwgzrva.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtdbiehthd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtdqxiyees.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtdrboppvm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxtzzrku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtvpvjajhy.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtqkacmhag.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtddrtdmya.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjbnedftf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtizdnwsry.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtafeuzeja.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtyavtptgf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtrrapfllm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtssquzqhu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtycazlubv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gterutnwny.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtyyendybn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpcgnqjmc.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtgukkntbt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwjtgumjz.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtysrzrmwx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtxaqqoxuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtimhglmog.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtgsspzckw.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gthbhxeldp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtqipjbwfv.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gthpvdibcs.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtsmienlpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtpqarixdg.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtfdoaoyds.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtoiygcdwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtoyiiseek.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gteamduris.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtgqwbcoyf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtsdpewcvo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkybvsbh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaiaoikl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtdhlpgluz.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gtdhlddlwd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtbattpsya.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gtwvckidlm.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqzznexcc.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtivgtgodv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxtdpbuyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtjqnaeqnu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtyedfeplp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtsdfidunv.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gttmlxyltd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtcmynvkcz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtywrxoobd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtayulraez.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtnihyynln.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtuiepgyrk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtejulbrto.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtsvbrhpll.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtntfwkgbi.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtuoyjopia.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqtxcpen.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtnemthmla.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtgmhhnarn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtwgqrsxce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtnwbbecvu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtxmwnvdmd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtpyqbfjjj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtbtvhvbew.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtqpspkpck.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtzvnxxcah.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtaljaubed.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtudfhqyvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqrlbnwr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtztktigyq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtxleofkjb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtmjbjzapw.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtfvtmburp.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gteafubown.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtolkugoaj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtgyqzzxkk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtfxlwasvq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtgqfxbink.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtqupbjkuh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtszhnlavj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtrhutsokq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtqbmugvoy.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gteusuhwor.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqngxizbo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtergqkgol.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtoqqetrou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtkekcmwxk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtaopncgmm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gthiywtezm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtiadojehk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtetnciute.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtnhxasmzz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqdjimyf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtuatiedne.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtgcbhhmxk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtcesjkbnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtjsxwooru.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtaaczainm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtziokounl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtvwwwamxf.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gthwnttjuk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtgomiqjff.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtxnyxrgjg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpbtxsdqs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtrwbyclvj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkvignllq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtvghfgqib.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtumnjoyyv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtbtrkiydq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnspvqzza.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtqdrihutm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzkrzooc.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtrpjdfobz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtsyclebxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gttlaqbaoi.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxnepall.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtaevarumj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtmwpgochg.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtccrmkxil.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gthvutzhxj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbmwnvgvj.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtnrlfodvl.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtzuijugdm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gteqxdljig.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtskahfdnf.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtfkmhbtpm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtttybtfpc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtrjlfnzgm.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtfxuaoyer.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtilrnmuzn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gthogsvnmo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtrebihenm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvytuihqg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtofwmvafy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtybprrkxw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtfvcplmkn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtvbkfoqlr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtozwmkrhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtbugkullj.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtqcxwkrbj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtvhlovabx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtpalivcie.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtmxblzvhb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtlwlgpalk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtjhfucgry.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpxjisqd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtbnuilwom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtllmxytwr.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtolxtuhax.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtatywpkda.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtdllrjsqo.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtulojuqhh.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkvbpqvw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtvrbdxgei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtwhfqphsv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtrdclbxzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtanweylkj.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtxjlzdjbe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtwzmbmjxa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmctdpzw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtrgyqqdjl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtvuvfmwfo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtsezuxuze.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtlxpvhvef.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtlyxvsbrp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtukaxbsum.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtdeuyeisb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtzlubcinp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywrelxfy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtfmaxoqmk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtwldjxoyc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtroolqiui.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtlvcmqsmg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfajdudtl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtoimvhzpn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtuyjycjjr.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gteoldzpxy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtzqakpuly.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtijctghbm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtixaezcau.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtdmxwckqp.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtxpjvlxrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gttopngkkh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcswxqom.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtialxgxvk.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtsxacwham.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcwtzeovv.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxyaufnb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvpmytiw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnumezdy.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gttpufqndv.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtvhpjkpko.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtvveuszib.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtekgagskk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtslrijtlv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdensejb.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtbdycjpol.html


<!-- 参考信息 -->