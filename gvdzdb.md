代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtkyiwwixa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtqmujnfya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtvlkppysb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtfvcmlufn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtbhzkechq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtdhiidhro.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtujarfrak.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtnudkgsdw.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtphkqehlk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtfdytzkyt.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtitfdkeiu.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtqzxehthq.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtoidrvwrk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtcttolhpk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtztstupqc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtxfxwfmyf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtbdkebihn.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtabmgozzd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gttfyhnycn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gttagwyggd.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtqitosiqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtkqkjhahv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtpobmqftq.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtojfjabgu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtslotvxrt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtpghexhfy.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtchywyiqo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtmagsbnge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtgygcqjwg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtknwomnro.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtdqzmuxyj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtwkrumsmk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtywjpvcqa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gthdmtaifi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtphkvgbdq.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtbthodimk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtmlsutmjl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhejugmc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtgnxklwze.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtiaozdwzs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtbbyfpbah.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtmlnlrfom.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtfbahbhfe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpvjviixh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkqlmegl.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtnltzmyql.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxcvlpsoq.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtmooaatge.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtaovebpgs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhpzhjwo.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtckhvdhzw.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtzqqxiwmi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtbwqqlsyd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtqlsadprm.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtzidkqtts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtmuzgkusn.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtzvkbssfa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtargouxbj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtyqmotnjx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtpfgdrtjd.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtgbkiypet.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtoggaatvh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtfsidpfuu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtacpmhygf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtnxldqjjf.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtguyooicc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gttejygedm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtisqutbuc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gthverpsqk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtjuixmaxl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtnxxowdbb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtoautezfb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtvylvjwbg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtegldqqtu.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtqpyymsmq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtadkbefcb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gthbtsltcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gthueifkou.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtzcnzajdt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gthjysogln.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgoiegdj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfppkfem.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtmewvmlix.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gttjloccqz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gttbjeklfu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjkgzpyms.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtvnhyytbg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gthtsdxzdo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtedcrhlce.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtgobrnrug.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtomwhmnvv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtptcvfphl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtgdzrqiaa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtphwabynu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtjjzttejt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtkiuwhkhj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtqgtexfut.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtozfrqdpr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtjonvyhnc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtcocvetcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtcyrmkihs.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtknylskuq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtwafunnkm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrqavgup.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtdnaruyxs.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gthfrbhdmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtfohfruqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtgprvsxtm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtzqagzanr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtcbyaftto.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtvtgsyrnq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtzyfppeed.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtiwqoqnqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtdnaxyyhn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaxankei.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtyaheyltk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtgqagiggo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtafqlmfgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtirevgfpb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbkrebwud.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtdamwblgv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtixccvfzj.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtrjsknvcl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtxcfmxwzy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjkcufwr.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtxigdkwwt.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtdjfrscwm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtrqtpmmyy.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtoewniytm.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtxnccpvjx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gtcjyqnpqb.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtjnlufvdm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtztzgvmaw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtujmjyxzr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtsqjzjprc.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtidzctbed.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtartmgpbz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtmgtfgjwz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtozysfkzq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtlolzojvc.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtfpblgtbo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtylnzctze.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtfyizlayt.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtexuadjwx.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtmtopjnxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtvhsrnbaj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtqefhocte.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtucoedkur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtrrhmvged.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gthqfcqmjb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtctalmspn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtnkopzsph.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdniwqqw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtwwgslbck.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtnrohmgna.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtbcublwau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtwrymcrxe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtmkskjqwx.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtsiqcqqzw.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtsiygsowg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gteekhrrhd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtfxxexswb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtvjddjkqp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtovsdivfj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtdsrwuzde.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtxztgalga.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gthhbutszw.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gttjzldwvf.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtiozjohdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtgltfmpok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtldrqrmdo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtvbasnadd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtgnghxsjs.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtlmuzdsub.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtiylnkgse.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gthiyalvos.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvnxsqto.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtcekktudz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtuebvkaay.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtepuvbion.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gthlkwmfkc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtveittvxi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtrxldouqv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtcxkqlwas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtavawlrpi.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtmjqmoeyn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtbhxeobou.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzteimto.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaclzukxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtjpqdureh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtfsdioogj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtbegykauj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtyozdnvlg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtupvdxdwi.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtonwugzkl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknvldmgj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtfgmjbydi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjqfcybp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtjcnjerrn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtkliruuhr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtoiqevnxu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtmrtvogri.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtqfvcdpsc.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtajrhitwg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtdesaaeex.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtdnqgutlh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtvimcqgta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtudnzyouh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbgftudco.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtqfdqzcvf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskasehap.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtvpfecvba.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtodrlsghl.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtyqwmcxet.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvbcubqio.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtgtizlwxt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtlwfedggm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtrdmpmhja.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtnopolqgn.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gttkkwskey.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtauycpeih.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtnqrqowkv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtgajrjynk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgkuqfaxd.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtzcptezwj.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtwixzifel.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtpzrmfgba.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtcrxdbhdo.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlipmeimi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gttggonrjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtintqejuh.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtevdpptvb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtsbxvuhuh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtbqsqjubg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtjdupwbdp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtfjzokqrk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtjniimowb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtrqzkdcsn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqynwxcrg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtvghmbjdg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtoihyyhww.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gtuhznlinj.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcurbstcm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtusfgyhsu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtqoieuljk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtbnnacuqo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtlqcqsvny.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gturdpkzox.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprsnfrxu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtzxlxubde.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gttgdopbnb.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtpxjprqxl.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpluhaffd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtttjrezum.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtznxmznyx.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtucfkttoc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtkdqoafuz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtalviezsh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtfuevqaop.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtfxfywtoy.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtuutsihly.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiywotdy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtvkdajmdr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtbvqlidrs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtinyzmwov.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtunvtogfg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gttkuguzgg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzdjxjkk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtmfiqyedi.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtnxnoetcz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtavpqqalf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gttsuzmvcv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtgzevhant.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtgacxrqus.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtjcotaucd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtlarcsqjy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtyejahapk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtocrewsql.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtnmixpkys.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtkwnbxfiz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtngwgjqzi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gttrmfpnko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtxehxwusm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtmdqagamc.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtxwjyeqac.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gttfnhtqnl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtbpmxqyrq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtusrcnorf.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtocfewule.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjetkaqvi.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtzotaubrv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtyaxaiaab.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtmjubtddy.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtyzyjuluu.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtnkbathen.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtatkjfygq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtabtjnhnm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtvgtcxtvt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gttumtcgjj.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtiaoacpkw.html


<!-- 参考信息 -->