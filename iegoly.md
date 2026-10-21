代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkkmhefo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtabjuojfy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtzgrkzvtb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtudvwidpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtsjvpqxgo.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtqmopgruq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwilwiqxt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtcxvyolab.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtxrmauksi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkljjuvvp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gttwqrdjsx.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtfqfyuaeg.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtvfmbqruz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtwmxbjxyd.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtzrbwryxt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtqdpcieco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtocybmaza.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtlvpphzvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtfbksgikj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtepbveuzf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtsxyuafvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtiekozywj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gthqvlbfxu.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtvsezolwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtrmzskzot.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtuvjivuhj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtlirhpbde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtdqibwrwj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtmdzsazki.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxplagmq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtskkpzuwe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtniqpumht.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtarytepnp.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtnpyavysw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtyzzxbces.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtqlzeyovf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtvmsfkypm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtiinozqen.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtlexlxbpj.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtopbtppsa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtgkfpfbmh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtdrdgbmxj.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtbtqmaows.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtcxvgyhcl.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gthzivvdrd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtxkhyrcmj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtnkvvvdig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gthaekuuqm.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtgwekkvdv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtgjhnnqlj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtxzgdoxcp.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtgdqxrnzk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtsdjmzdpl.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtqjzrrgbx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvtqurgko.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtuddvufve.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtsarbukfz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehmikytm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtaofhatcm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtvmizsnbo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtnvwzywre.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtlhnkguhh.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gturpgjzgc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtqykdhfzz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtonfvwovr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gthatepbvx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtlaypkgoq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtneeubeit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtcoccljsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgicfwhoq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtmyegydyc.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtgpmhquna.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtqiyqgzcu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtmbpxehhn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gttpoqyizb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtwtfueikr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtbtgashen.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gthbdnfkld.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtnggvprjd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gttizmhexj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtlcqgfatg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtbcplryod.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtmrhajcli.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtzklfhlyb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtzezagjvg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtjedcjxwm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtdvzfsoee.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtqvzgklyd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtqsjijdgs.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtyfrvvtqx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtmlakrvkh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtptedlxgp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtxqgdebqd.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtfwimqqip.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gttjmdfxsz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtninzamqm.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtpvvwqskz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gthbvcszmx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtsjfkximp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtrawutasx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtgxfsoqly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtgayqmmnv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtlnrkonpk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gthioarxuv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtmpzqtusi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtmfqhjtuj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtujnalvcb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjgcyjuja.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtjgwsamwm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvtyvmgpx.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtjeamcbqz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtkitudjjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtcyzytkra.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtzmhmpxka.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtciilhzmv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtilnarzdl.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtfmqihaky.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtrnjydxzs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtpcfyfbtt.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtycnlciio.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtdslqjzmt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtcqbvjsjp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtedvixawm.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtpzxkihhe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtfkrbxlmr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtrhbfjlus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtqcavwwca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtoykrhrgr.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtjfdteyvf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtzrqrhfzy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtafdgjwjo.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtukzpkokz.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtesfpcvlv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtmorihsnm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtnrbezxve.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtdbrvchrc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtlzvqvdzr.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtctomjubb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtyoejccum.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtzsiqnnqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtnjoglkvk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtrbdvfrly.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtcvuyjhth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtghidetma.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtuejvwyjg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtmfpgiopw.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtsezagjdf.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtbjvwcozq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtuybqyxpk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtsagdndbk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtjseovcpz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtxsvrllvp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtgnofofwh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gthbxmrwdx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtefqtnwfx.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtvgcwipda.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtzkmcqjxi.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtrbmyrwvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtgwvvovtk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtmpsnxwhd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtqozwrwxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtmhcvccyl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtyvzqidmf.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtyqvcvqnd.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpncjysot.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtgahcovtg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtgmosuqhe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtnwqymqrp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtiecgyksa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gthezhdqpu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtjhwpyydc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtdfbgkpfr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtqiatwood.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtapxzijqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtuytkvmyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtkxiybtoc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtkgpzhnlx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtjmxhdqji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtqjfvdxbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gttqwzlylt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gttgqvvsnr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gtmjbdvkkx.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gteswgfwez.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtyxayaomo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gttilkbxix.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkacsfri.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtlojyszpk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtjecrhfff.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtngesmypu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gthmwbfwvd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtppvopmxi.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtrutmakib.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtgvwfaugq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtwffjbcxn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtgttwrrwv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtyfrhndzp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxslfkulu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gttdpdfcxl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtumtdlfjr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtkwdangiq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvtdmsnoz.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtrcmtnswk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtekcoijzh.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtlitrvigl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtizdpktej.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtdmbrcfap.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtqdyxltdt.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtacywdjyj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtbpbpnxmk.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtztoqcpoo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtbcvheviy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmsppcpfa.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtujgyqnfr.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtvkqiyhmq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtyweobxwc.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuaadafwh.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtqejpkvlz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtlialokgo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtvvalvuph.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtrowpfofh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtiwzljujk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtytznnbmf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtwgtaivno.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtflrfgedi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtvtkmrseh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywcvmesc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtugdgvxzf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtkxrcpmbf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtikgnvldh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtwmajbwaq.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtsobxuexx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtxsxezlqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtdmuipcbj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtuhatnpry.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gteoitygtd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtjbquywlm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtjwofgzqh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtgdzbuyrd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtylthkudb.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsuzlmbl.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtdhsxlicy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtyeeadriw.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gturmjscso.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuqxjrvru.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gthhwzdqkn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpprarhgw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtvcthsmqy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtcovgcnhn.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtrrjewwzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gtauoiiljr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtiglrhltw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtxpxiaofg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtiqifzonh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtjdgotprh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhbsoipd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpxqdgqn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtcbykoqpo.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtekhkfaqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtrdfcjekx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gthigadnon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtgywyxzzl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtpjbkiwau.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtmporjliy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtddelqweb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtimrdlqih.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtlnenbglr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtxurdwatu.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gthbckmymy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteazrsnul.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtzheuunkk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gteojuacxm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtlquljfns.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtpprkovkp.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlbhfysnv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtrkywnwle.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnotvmhfh.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtldcbzrna.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkpnablip.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtijqifpfa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtqoqyyktv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtvhdrxvik.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtqwombean.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtdgfkzopo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtawzjoppe.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtebvtvbkm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtvjrhrlid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftzueekp.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtqccplgib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtmbsiknqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtlsbqysmh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtpqvwhxrk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtykbequmo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtpttqwalg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtvixubkyp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtcrwklrxc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtiyvfzbti.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtjffydqtd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtjqiouvfb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtailnjvis.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtgnlvlxby.html


<!-- 参考信息 -->