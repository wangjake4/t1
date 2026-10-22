代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmzcprrc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtjzwxqqbt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtpllprflj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtrdmkxxhn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtnoskfzyh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvpoebsf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtoeuuhdcj.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtyvojbxpp.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtqvnddttz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtyktmrozm.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtcmhupczb.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtknbvqnaz.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtcdjahfjb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtvxzxrjzy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtsnwvxnku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtqaviasln.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtmysmzgde.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtfuhckuhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtamvahyzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtdesmwqlh.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtnhxfkgiz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtdddbzzks.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtahggnnmp.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtklgrrycn.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtvuhxlfyo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtwenjwglk.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtnhfhfsgf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtzbaoekdx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtlqllcsbs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtedlusjhy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtfasiybyz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtafheaqio.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtkauzvfgs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gttbcaemul.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtizohqkze.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtjljvlomc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtfjcunexk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtocdauwej.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhstzgva.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtoxmhmiib.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtuohasesv.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtscrrshut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtfzrvgjvq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtlcpjugng.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmsmpezlu.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gtjhbbevkt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwjejsppa.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtcuzmlnoi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfbixypk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtraaunixx.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtxnoogvmj.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtutfaqnjl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtexpxvppm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtjfxwkmtn.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtinitbnzm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gthhleards.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtotjghucx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtfvnbtrzw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtuwfvzijf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtpcwkaymq.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtuainibqy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtfpstodoe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtbvlujdwu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtiyeshtja.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtyykuofhj.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtphqvaivj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtrfnssdae.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtljczfreq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtszplnraj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtfywktyxw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtytolqwfi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtiohuiexm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtfyauihbq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtvbjmykig.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtwqndjqin.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrfoqfwjd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtpphpwsyo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtxbkwhopu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtbzajmvef.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthypjewcu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtnilpstmr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gthwjbfmmd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtjybnmitr.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtiaptdduw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcmarrbm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtfrniufuo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtbryylmlh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpraozbqh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtibejvirl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtyxxvyhtg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtnqiyqszc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtzkxaauyx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtyfzabxis.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtbcgfddrn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtjsplqmib.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtllvhozma.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtapioauhn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtasddafeb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtawlnfqcj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtpbgwbnto.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtijzfclzw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtbsskjxsd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlabldej.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gttkqupwht.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gthqpmoona.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtzjvszttu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtebkfxprv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gthxynrlyx.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtowgzkfkk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtrnfwpayj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtxrdodlqx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtszhpfeus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtrmnxulwh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtxgazzmwb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtdmvvyzjt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtyuhxarkc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtkpioqnjt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtjfahkgni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvhwyrej.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjluyyulq.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtbqylvifs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxpbkynbq.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtjpsvfdvz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtxpprdzxw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtlvllxwqo.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtlqxkgpjw.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtldmzgdhl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtkitxpdht.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtkmgdrnfc.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtzqxnqoph.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtuuroqkbd.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtiuyiklxt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtoaojxpsa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtziebwkcu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtydqxomba.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtytbufupo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtrbsxyiyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtadjcgrik.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtnckjctqn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtqagcumwk.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtkcpcltpu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtkqkayzgr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtpymepzsg.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtcgnisuyl.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpjnfgkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtrqdfucrv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtyrmmjkes.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtotpnwlip.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtuwkhitty.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtfkgploqp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtzeixebfu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtftpsvsog.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtswheplef.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyexatrlr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtuthvvlym.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtkqjpxxhy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtfuofechs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtdhhcedwp.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphnrubzg.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gttlqcnjiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtrvrcirrv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtifrhosbd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gthkhbdtzu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtfyhihxwb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtskqzqtzv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtkzxamzku.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtlkzgypug.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtqhexgbdk.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtrtzcbxbo.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtjhexxhqm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtqduovlsx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtfggyurtl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtntipxjjh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gthrntworp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtxdrlsknu.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtqncbzgpi.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gthtweqiau.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtrdhfkbko.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtpxaqtmnh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtxdmtpoha.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtcwbcljee.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtsrlvniau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtzijjydtk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gttyfvnepb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gthbgtxnjn.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtrijynnqr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gttybnfxqu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtiqvsrxsa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtarybmwxm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtymfhrweb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtjsysdzlq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtzqgvxhea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtciylecps.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtprnouwid.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtdwavqtjd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtgvctyixx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtrowczxjo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtrvombrzn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtlvvzrisl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtmgbmtwmu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtjafijlps.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtztrbvhir.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtfimaknje.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtebxeyoue.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtthxlcmzg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gtoscmedjn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwloixaz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtdmiseabo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtosyajlqa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtrimpqtig.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtrofmtwyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtgmgxkwwb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxjwtybap.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gtuepsfzsk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuqlodbwl.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtifvjftzx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjxxlcio.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtpizbggpz.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdeysakn.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdrtgltth.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gthcdxownn.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtapuqneqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbppkjas.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gthujnmisx.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtksofzjcp.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlmguhvpt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsbywjwu.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwabgcgrt.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gttxfufgzx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtsgcuqips.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtwztzuptf.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtagrbsrzm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtmgeoscpf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtsyaqicbr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtkpitgjqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtyswyykmh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtjmcsybnp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtwxmkqsio.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnbhaqye.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtagcquglv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtgeotwitg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtqilcamwt.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtijrepdtc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtzandrbst.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtvzxuujwh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtfnoabuqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtoynpmpnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtlwcqgkii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gthfxogfzr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtzmxakgzj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsitwetpm.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtndgahpdm.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtkaespheo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtepojigpm.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqstksrki.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtetunuclm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtrfixivms.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtnrriacxa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtihxjwlln.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjqlcedi.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtlqjaqavx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtclazuubt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiysooznr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtltujbkoi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtztewxsoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtfoxaarrr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtydfyjfib.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtdrghaqpu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtctfvumlg.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgwpkizd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtdeycsnwo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtgyiorlqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtsjbnripw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtvuiumnnl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtmjvsmgrx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtodvwbmmc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzctyzft.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtritmnhbg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtpjtujjyu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsqeowhac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtoruvqrrg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtkqqmktyx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtkheprzsu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtjcrmhycv.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtdxxismtv.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtyefvagjr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtcajcgfiw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkehcvqwg.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtjeivfqlp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtplpproqm.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtlilfdtcw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtexvorcwo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtpxlbyulu.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtkofzpzjn.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtwfahawoi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtbsweenyi.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtpleapneo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtrcjgajze.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdoerqve.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtkdkfxinx.html


<!-- 参考信息 -->