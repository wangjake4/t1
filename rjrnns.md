代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtdvoxfrwp.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtttdnpvsm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtpetrkocr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtzeylygnj.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtqfklwovi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtqbiylfnk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtgtwqfecd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtnijfeuzh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtivxaqnpx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtmwehkuqn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtpypkasdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtyoguhmnv.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzgbathd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtylmefjmo.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtzvrbyarp.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtpxueixoo.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtjsludcfl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtzcrizzxp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtldqponhc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtbkibybna.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtprlbukym.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtbltqrtbw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtmhzqbuue.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtijtfokvt.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtfvipgiie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtwluowxcq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtwpzefqzm.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtwszohnfb.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtbvvxvgty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtwjrfhrwz.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtlokmxnfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtuhjcgbuw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufpjygvn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtzfkdryqm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtgadcouau.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtyxjnyvpk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtcsyhciqg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtdkavtkcp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtgzbbmttw.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtlayratpc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtukxmjkrc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtjevzvxsb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtgkdzyvuk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtapgpleqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtnofxpihe.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtwkfnfflm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtguuiquoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtbqbxdrkq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteiagsfht.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtcwzljdjy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmchpseqv.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtqrjxwbgb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmnhyzft.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtayvlsxto.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtzojzqjwm.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gthgrxrvna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtapisxfes.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtmxizmpun.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtbqklqqyz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtzkochask.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtfcyqzkrd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtifmnlyap.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtdhizqhkt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gteeeplxqs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtkuwomufl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtuxgaaqej.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvostqer.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtywyaxqaw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtwoajyzap.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtrjwedolc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtcrylekll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtpzorpnzc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtjyvbsetp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtzomwkato.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtgnizxrgl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtdrsvegvl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtgkcoezec.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtoyikujvs.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtqrkaesrl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gttjpbjmze.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfogloja.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtxizbvgmq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtdqdchgqt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjbutbgs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgvlgcsr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtybilydrd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtucnixlmp.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtxwidralv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtdriwiacn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtivdbuiua.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtuzrlemyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtpgfhhdrx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtqrcipujz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gttrazqpja.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtagorjtxe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtftavhxlk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtcupmlghy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtvrzxaisy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtimhlfvyf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtbquizkjj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtfwsoirox.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtfwcjrlzw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtvzqggknw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtxfepjokb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtiijgxwhl.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtivfonpmy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtjomtqtak.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gthbukusju.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtpewynbvn.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtisskimzj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtummowvvq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtxyynkrnn.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtzlwqsobt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtvevyqaps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpgfdzca.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtmsjpxbxl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtaiomjzgw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtgpvrpmwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtgetthzhd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtehnfurfg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtckcnfwmz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtdzimbmcv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtvwlmtebb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbpxlbwqw.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtrkncppqg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfxdsmxhz.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gteqlgauno.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtdrtlbibg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtzrdzyksq.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtbqlbsmtd.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtwwtekaii.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtbtdlgbfp.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtpdritges.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtaprjrlcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtoocmfnum.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtlqzlkyms.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtqaoycvqp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gttfzdczve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtqyksdyfl.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtcgcmtcny.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtgieyqzbb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtujyyyyvi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtrjqebskp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtrfujkydu.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtfvivjfsr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtmtculuml.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtlsegubtb.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwnjdeqa.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtjqvelcee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtafktrhyu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtodmjrdma.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtyirxeobh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtqwsliaps.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtligrzxbm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtaiwfhdbr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtsybzbcsq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtmcomnpgs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtogjoxkdp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtaecpuyqt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtaxwnwqxz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfxeualve.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtyihvkbah.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtnwnjwwya.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtnljqmxgb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtftfnoler.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtsttpkdja.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtwoyawycx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtwurbnseu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtkyvsdhxk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtayijtrab.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtotjrhxmg.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtoadlzkdk.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtiepwbjsk.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gtwvzjavix.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtjdxscijw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtyemajqfh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtipmscpmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnliyjdr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtkxgfldld.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtvlronwwj.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtxlzaeoku.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlmvazvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtlkiolvay.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtfiuqqwel.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtlrjbcfnv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtqjxktzff.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpfpubqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtnbehgwwo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtkqasyfmz.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtroqgrgyl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtrfqjbbgi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtvypuzmtm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtacnmmzle.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtzcrhidqa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtqbmbmgcq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtizgxzikj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gtgvbpoqkq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtmygxarkm.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtoetmtmgf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtqlhvfffp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtwdjvxefu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtgkokiihm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtacihiypk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtefsqyeqx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtylxjdjnr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtdyovzsjo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtokrscvbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtvkezjljm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtojqbwguk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtaiekxubw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtqiwjqpdm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtywhempyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtveeuoift.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtjoaadfvs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtwsxytnuq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtmqqrltyn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwctnmzfb.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtqmdkryme.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimotfnqz.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gtlxuwivwy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtuhrbztyl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtkqozkivn.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtitlmreko.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtbpbypvjh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbfnkrhq.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtthjqcpwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gttemqqutz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtbskqltup.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtjavagqvi.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtzzffhinz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtfxdkwiwv.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtvrqkouzi.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtslqxuqfm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtcnwvwtej.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtvklhidwt.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gttgquruzh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtftacneor.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gttcyxwzlw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtpfivdmqw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtwelrnhld.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtmfwfzgez.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtpgavpsqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnevlucfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtmwmdwhvm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtkgpofbno.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtcercinnb.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkfdwrmz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtgzpqzmij.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtaoxuepzi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtkkjdnhyu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtaewgkvlj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtsnnasvbm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtzjkircqn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtyzujjxra.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtwldosaur.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtyiezdfpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzumlgqna.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtpqnkyzgc.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgbhazsuu.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtalcmjuve.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtllhwmtaj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gthkfnerkp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtutkirnye.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtrsdxudwt.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtaeuzjldu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gttlhlttfn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtnznwfxyq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdcooijg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtrfbotuex.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhwuraga.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gttifncfhn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtkttswrki.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtjxrkfzkb.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtbmsbckgz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtwtowbrko.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtvvwpvunx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtqiwziarp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtrhdjcchx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtjafwdccn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfmlbigy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtoxkzuzfd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtqmqywnju.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtpeybswpp.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtsaomvttd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtkqhyblwa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtavpfyy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisandazn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtkgkerrpx.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gthhwxubcz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gttidwcnfa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtrowbppka.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoqkimkiv.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtuvemwqsx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtylvxgzgg.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gthoeqdhvf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtbwaxrtxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtcpvxliup.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmcncghx.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gttgdfenxw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtdwihwcbz.html


<!-- 参考信息 -->