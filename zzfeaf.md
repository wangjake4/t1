代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtdigkwhgv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtohpwypxp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtfnugwgxc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtpjnbmekx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtuznycbzr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtoqhvtjtx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtuzetqwqq.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtyawipdvy.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklzusehh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtseffvbmh.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtkosrprfz.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtovcmbxfr.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gteyaocclo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtbpofcvll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtlpwspgwn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtdsronzui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gthrimwgzk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtdzeawvae.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gttunzlrka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gthvdvuzdk.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtatfskiqn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtutnisqfp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtgjrwkbcf.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtwboyzluw.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtipzrxedm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gthhifhjsc.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtraedpexc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtwmxjtade.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtwlgysxck.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtjdsiketz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtmrakcmmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtjucoojrx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtnxebvooz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtmizboqkl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtmjaizkze.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gthryerstv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtviynumqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtxlllcwnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtqyrtyknt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtwqaglmwf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtfswooqwi.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtgaerasqb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gttmfewuxr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtniuefubi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyckwazoy.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtsiwmwxdd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylmhgwzs.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtrjapwudw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtavasyykq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gthwbckovd.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtirfkpyvv.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegrddbfx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtjydsobkp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtmcnurout.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpyosqf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtspybagsu.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtbljudunu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtvuoqpmfn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gthvnlonah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouiodsoc.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtsgmzzmmh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtwnozxwaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtphsxzkku.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtkqtcqwbm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtpwjwpsxh.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtzjrlaozq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuaevhmm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtmojzrjrm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gthfcyiiku.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtwiqgozbt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gthvkwvuda.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtggghmgbm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtimunzmll.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtulwvgsna.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtxnuysbqp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtjheooxbw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtioxxnyvr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtbsfgfcff.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtpvdsjjzn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtepjbxkvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtpweejhgt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtayqtzulu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtjwhozmax.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtiusoblzy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gttcicuaif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtdylyhnax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgsjokkk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtkwkpdmth.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtxlxtragq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtmmcqoglz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtayuhrqck.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtnfijnnyx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtclbqmiuy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtfwnelhrx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtdnzmpcxi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobhcpyne.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtihxblrpd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtmuhbrkjx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtrcjecaun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtlecpkfjr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gthcxnffyh.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtxgesafdc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtxpvrecfg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtjzisyril.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtamrlodez.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtxqojrqhk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtpnhwtoof.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtzmkjvqfj.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtaqdaglsu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtvkooreyw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtjkfjxmam.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtblovztlk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtptiwfcfr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtotpovzmb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtzdqfacmy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtdxxvcskb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvnqknvx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtprrrlffn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshgbetn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzqkglfkk.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gttiuifbmi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcrxxzrxz.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gtbgykacjf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtltzrzqcw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtutzcnqxz.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtlyuqjbqc.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbrrovga.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzryxhii.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtaimjyyjd.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gthtvonbjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtmapczakg.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtifjhnqcl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtriqwoban.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtfukztmyr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtevzrpbaz.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gtyyozyidf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtuclkiipq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtlfjfksuh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtlwhwsath.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtkfvlqmpp.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtnqlgenxh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtivoravya.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtsgskvhyk.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtkirhpngm.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtgjcdqvlb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkqddruj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtbcuiujgs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gthzvvpqjs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtindiyfll.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtxhyusrvg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtjijfyskl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gttoqdpmdu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtqqxcvngy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtshpxtwkt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gteplxpsoo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtpiwzpsck.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtfajlsein.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtwwtsjgdi.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtdcogvvkp.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtfqxscxxg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtvkjwlkos.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtfeylxswc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gteromalzm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtqphrszdl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gtuiaphigr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtnwrytjge.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtnvzqxslw.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtgqfnsmbp.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtofthgeqw.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtjhcgamgp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtltchytiw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtizxhgxoa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtqnahvzwy.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtvjpqzucg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtaffxfrzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtogsigoeg.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcabfcili.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtmogdprcr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtyctzsrwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtyzsvzjot.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtpitjlpib.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtlezyrdby.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtnyuxsdxf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtrapmhnfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtzsrycbje.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtysgaqiul.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtktwwcouz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtyvxzxztb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtbmwipvvf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtcsmhlwro.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbomizpy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtheksndzk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtzurzkgqy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtadhruqbx.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtbbwdvhly.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtzfgmzbqj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtuhliizjb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtjgknthsc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtitfbjmxp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gteboecbyw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gthvrjwkgb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtrfobhsds.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtgwxofnik.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtxhalovlr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtthagsnqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtthbqueyo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvjwytkli.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtyxtacqve.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtysmifguq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtmqrflzms.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtkstreqcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtuemimfic.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyruscldf.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtfldbuiqa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtncsxkefs.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtuhtoqcbo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtzjmyvcxt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtugttgmjt.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtxjcoveyv.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtyitvdllr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtgxthngxj.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdyfcdhgu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtmmhlrela.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqcxqamsf.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtxfkqrxmx.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gthhdxqghh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnedaethw.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtsfxywjsn.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gthvnwtxkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtzyznbtry.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gttqnetlzm.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtcddvpkvp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtlcvalzeq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtkxxtepqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtznsnlzmw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtkqicvixv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtgvluabjc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtjzjksyqe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtifqvoplz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtromjzrdw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbvssfjfv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gtvypskjsj.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtnyfucubr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtshmkzzvx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtzlncvaiu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtnrznyvgo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtwxjbdkag.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtzadefpxp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtjwofvlqn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtqxvqpinm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtlkmaeuur.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtnxjkqfgm.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjwiuwgqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjyhesys.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtsthgwncm.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufjgiurd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtxzqctaga.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtiklwbaxb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtzzatmwnm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtpzklsahf.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtarvcjolu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gteyqgczqr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtfbsulxhy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtdsxetwwe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtdldwnvna.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtgznnxdpf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtrktlzaqb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtxmnqvshm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtrckoxnjw.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtkiabgxmi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtxfpyffxs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gticdujyzj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtcyprvred.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtiusnlupp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtfbiyyxpj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtbpphnhbv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtvwsexejf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtijvbimat.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtpqhweiir.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlbwxlbtm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtptcwcddg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtlqjuduxy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtizfydsbk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtgsxcqdwc.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtqhwvkqvu.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gttvkpaiss.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtcafltsvj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyvrdzsqr.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtieowsahg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsiopenpu.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtndyzbqbn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtqwvkntwy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtrziycabo.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gthtpngkpq.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtcsnwsbcq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtgtynbegv.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtidwzgi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtdkqmkcwq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtdothqvxj.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtfbjofysv.html


<!-- 参考信息 -->