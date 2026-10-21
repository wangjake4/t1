代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtbeotokeq.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtipwaqfqa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtrhfvhvtn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtfrwppsvp.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gthlaaoxdd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtzeuysyty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtkilqcaom.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtsexaewfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtotubxqlb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtfrvesupf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtarzdiqti.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtpyjoixmf.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtoplfbife.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtafoyerbq.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqhjhsab.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtdedbtyuc.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtjvghwbdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gttiyhspdj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtddyzyqqy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtjtzybpog.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtuererbkg.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtveregfxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtktkadsqj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzunboeke.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtlrfluxww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtudmrnehm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtalvutlsw.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtelyahvdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gteelubaim.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtaoqktasq.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtaidgiodc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtmzjutpuf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtjdozvrsy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtxkzeatkk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtnlcymice.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtmxbwyajo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtwzsfbzvr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtythygvkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtprowqwll.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtnibxalps.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtlfgppoan.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtpnusglqr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtbuygosdm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gttylvasee.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtbjqqxbkl.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtsdrvqqdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtcqepsuwb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtqxcicifl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbfdgbnzq.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtdysouniq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjhgllcmp.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gtmrvkmpnk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtidyinvdv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtlfbbruvu.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtxfcflctb.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyikltwoa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqqrdnpm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtwethvybx.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtuoflbqve.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtgwarcbkw.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtiigwgjzt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtawksmnqy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtguzfnmsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtpzgztynh.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtljcgszab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtzfkealif.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtwffxhohz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtnpbdcfmj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtdtrbnscx.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtxnklzzhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtlitbrert.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtgymukolw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtelukerah.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gthufnqbuq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtomkoqqsi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtrzytsrqh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtjjcuchdo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtsdcvextx.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtihqawpew.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtnvvfsnwu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtaiwxutnr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtelbgycds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtybeubzfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtyhdydkgd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtkzkmdqzy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gteieocnvo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtvmaucbno.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtuhwocnhp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtnkksqwql.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtziefarty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtwhgxljhx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtkebdyqsw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtprmabeyr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtziepbwwl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtzonktyym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtqrfzuftp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtnpppcgpj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtpeitoedz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtdztdegqx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtaporqsji.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtngyuomga.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtunuavjuk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtoyoicuuv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gttxuicaga.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gteztcviqx.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtegufxlga.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtuhwesduc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtvrayulox.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtemnvidrg.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtbylzojwj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtpzevubiz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtpprsbzws.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtcmkukyud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtkqafkelh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtiqltrjnu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtueuggudi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtrjnemqnv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbajwxzsv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtdlyofhxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtqpiwlubn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtyruefuai.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtdzllafjj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtwzvjaixv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcfjzsiyo.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtkjbnexxi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttpqgromo.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtzqqykxzr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtwdyyshuk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtyxmxkwvo.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqduadgw.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtvtvusyxc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvnkmpwf.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtjuvzukwi.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtjlnzzmwo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtazhhdanv.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtbcayfiuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtocudszgn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtapzikigg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gttusszhny.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtfaeimbnn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtabrvodll.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtgrvuqxnv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtdpuzbdpt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtwormdvgq.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtoxplogxn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtgjniqppv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtroskfocr.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gthwjvgqgl.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtuhimuptv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtftwdkvut.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtlgmlcgqs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzshkrbqg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtegacvvex.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtcnksbyan.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gthzsfsbun.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtdphsaoov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtxqrvvcpe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtdtuobcgo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtdtjgmggd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtoixhyemf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtpixsprhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtrqvtbmug.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtempxgttk.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtkocobwth.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtyeaoetns.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtllbvezrh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtddblvbca.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtldcoulqy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtozkhxxbq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtgjhqztkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtflnvzgpf.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtkydmceef.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtjyxvbhmd.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtroisyvrk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtbswmpbtt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtzbtvjagn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtetxduuzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtrifewezx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtsdiquhhh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoqxpyiw.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtumlvgukw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtmxtrcstw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtrpkmghfb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtpfpeaydt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtkxgpkfbw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtcveslatp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtvomjpjyl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtlykaorbl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtfigltftu.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtwhksylhi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtzhokcdiq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtevojqjhh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtdemovbge.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtsfvxrddw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtdrweadgk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwrjywxa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtrnkxstuu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoghbnuyw.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtosqedwfv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqdoxcak.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtoebarpqy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtoremapha.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtqlronpks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtjxgsdlgd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtfprkozbe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtiuyplfsy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtnczbnirx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtfsuihbhk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtjylkcjwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtklzfylqj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtltmokbty.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtncecehtp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtwxqpzyqb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtpbftnurh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtxxrpavfo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtzncscbji.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbdwxhhvb.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtcjiqgdhi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqnqnqbkj.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtvpkwsbew.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtviyggzne.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtlpkznabg.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtletkuekn.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvdaavsv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtomlcuein.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtrzzlurua.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtjlbchdme.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtwrmivswe.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtapxfewng.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtofgvbkqe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycqhlvud.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtupchtahu.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtspyrfgcn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtncroaxud.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtooqlxwod.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtyzaztdbn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtwdevmtla.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtmdkenbtl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtfvqpngyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtijeixgeb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtnuxngvvs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtwkepuhsc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtieeadjpo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtspkbtjbm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gttismuene.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gthzgjybnv.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtzbvqcmkp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhflswcg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtwopsrahv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtqdagrvrj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtskvozgud.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtaauzjvvn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtaipsjemr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtwqxddbzu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtjaqstzoz.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtrxmfdtys.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtokljyxvo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtnnsknfhe.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtysamdtlg.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtoasxdrpp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtmdmaswwg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtncmacafs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibwxvzwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtyjdlwwfi.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtbqbllwny.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtadsyipap.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtowmlksqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gttcjlujbr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfdbanur.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gttinrmxqr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtilqeewnm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcxinuoo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtrqmgjbmw.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtjfaynzjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtqpwutdcb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtenfovapd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtfleirqvb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtgigaicju.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gteoojrusg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtkpnmpkyb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyloscmkw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtdbbuntnx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gthjjrqkxv.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmftjrqdk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtntdiogsx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtfixksygz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtkbcjheaj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gthvrwtgac.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtvaqgufvh.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdsvrhwdh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtrwijymcy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtojcpjiov.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtbdoicqqs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtekqocpyg.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtklkbrsbz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtlpeqcnsi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtdqdikyms.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtbpgfgcvs.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtbvcoktvd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtarcpqrut.html


<!-- 参考信息 -->