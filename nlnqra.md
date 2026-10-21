代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtzqurmeov.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtigzurcmr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqigwpj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtjmynxagb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtugscucrb.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtfmitxivc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtjryywgnf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtoqpjcvot.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtxmxpzycs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtjdvhkfvt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtvlnbwcpf.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtewokmewx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtmiyosvoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtoututnaj.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtvmqmalpt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtefllxegu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtkcmvrpnv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtqavauiop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtkwoshxni.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtuohjctkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtbvcpqxqd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtubhzcoxl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtrlvcgmxo.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtlytnafgm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtzpwekmaf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gthyerafip.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtchsjfjvl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtinfgucjn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtyrfykflt.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtuiqdhcpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtzflwbpam.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtoddlyhei.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthxutnpfc.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtydwysnjz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwekaples.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gttrqzjlvx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtlapfyzcf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtpymqhomv.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnkxtqtr.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtiffzfljo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtbjuhvzhh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtcknlvmre.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtlasckblv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtyghkkdwf.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtokkfrsoh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtofuypiun.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtgocmobfo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtgepejhxu.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtrriryvwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtkmughptu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyvdbjmcg.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtgrtfepgm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtvkhswpmm.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtyjykzvyb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtfrvtsqsd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtnpwfkqjr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gthvpjwmsm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtnvupxgbk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtizmgfatm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtadhdqpec.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtgnuwpssw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtnillhwfi.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtyoaxxvvy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gthoeijvxq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtmwlubmmt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcvtoairi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtkizzfdnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtqdkuzsqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtdvjercro.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtuevjrnup.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtagmwaqpc.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtrqrgwcjd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtfjiimeoz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwlpcyngq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtglxskomy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtoqinduyn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtorxythgt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtzadsmfzj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtxiauedst.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtvujimoit.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtsndjsvja.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtehdbwska.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtkxlbubqc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtqgvvsiwf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtpjoubjry.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtjqjuwe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtyqqgjrfr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtnlvgwsbj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtolxdrhyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtnlruusrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtpxeuoqln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtvgkamdyr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gtagxbyvoy.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtzrcyjipn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtchliplfe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtgblwkmzu.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtfwkpzoyc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtlgjqunxa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtdavgejwi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtkblkrmrn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtdupamzhb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpbitpnu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtbzojkidx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gttysnifqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtarolkoqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gttwjxjvxj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtvqddyfih.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtedlzcojn.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtzneydwkb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtehpkkrcx.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtbhmrxnfv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtynvldipq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtqmizyptd.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtotyybslf.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxxbzrqg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtgkwnuquu.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtogevvhsn.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtduomheav.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtgawpgfaa.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtymqkrkxy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtntnocqvi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtmtdomiph.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtmmoqdbkz.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtbpykycze.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtgodftnoa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtfyxrwdwu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtawfpbrrj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gttdyvamtl.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtnuevdytr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtyqonrrcb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gteaonutrs.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtijwgixxx.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gthhuiqxzy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtbizopbml.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtuzmlvnuy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtkutxxhjg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtkobrcwvj.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gteflkgfgj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtajchdmka.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtmxkiemrk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtguhokrgr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gtavuultdn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtshpwygxb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbdqjewym.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtxjitmiiz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtwapsoffr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtrjauqxrq.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtaxsgxtgu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtulypnqug.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtpvmjeitv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtzgcwinjd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtxkbhtjsx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtsbkxrhez.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtjasfybry.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtocfzhzie.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gthvuoerpd.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtubjfdhpl.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtygvijsni.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gtunuywafy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtbkrariah.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtdqfooqca.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtuhakqtnd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtfzrgxxtl.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtxadssunm.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtkbzvuxnp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtqjeobxwo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtjlfijlam.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtayqfdfck.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtvfsxchse.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtqhxvzrur.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtkulxvhgi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtkkxgwlqx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtevnlhtmz.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtdtpjcmkc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtugevzgow.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtvcihkfak.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtfbkyajdh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtranpoybb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtdyqajhfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtqvwyoxpl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtrowvgkib.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtowxtuuvy.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupahvprh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtuynavnqz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtiicmbqto.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtmtsqomef.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gthelgmfje.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlamsfwo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtgifetdno.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtpmzrqeuq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtfxavnyvq.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtvrsbfrel.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtgtnlkpup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtivnazsqv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtiwxhhqik.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtxdfmqvul.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttgcjzmoa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtwhzpotxz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtrrghbqjq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtnsjxjenq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtumvngcyi.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtmsyipzfb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqxucuwec.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwzmzwjk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtfrhiipma.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gttxnlpaof.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtochtptvn.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gteugshcei.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtakcwlzra.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtwpopdvgq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovlrpxxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gteghupqfr.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtmhqpfnge.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcoukybk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtczujraom.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtamipyzxe.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtjennoygr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtswwssgyo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtlexlklwj.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtmlfcjlcs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtyjvoaxwa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtppckxpzp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtigrkkpdd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtzegfnebe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtzfyoggbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxitunqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtybitlnhk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtbqkefzre.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtvlkgsyrf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtqtlnwgpw.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtqnqrhtlm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnudpayp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtrufbijqu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtcquoblpx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtqrqggsai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtvggkzbuu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtnemahbnk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtcpteljoi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtzcpuvecl.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtunodqlmw.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtsysvjjes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gtmblldueo.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtocokqrhu.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtlnhxwwfc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtmxehuffb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gttmqbjhvk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtusjqhrbk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gthxtwlsrw.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtqcwxhvla.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtzleekseh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtvugoxmcn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtvnwepudr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gthvhhjivf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtbkjtzaal.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtmjnnqwji.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtsekzhrtf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gthrppawio.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtlhxziajf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtqihcpxzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtlatnegqe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtlqdywxdc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtnhbdheqs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowoxphnf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrlmcwme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtwaoiqhbm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtoocbuhuy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtcglxcbxl.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtaoxpxfgg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtphabpicu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtojeklybw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtquabsqlq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gttyocxuaw.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtvryldrhi.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtzwpfuzro.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gthkpsnizb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbcplttoz.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtljaumxnk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiecgxbfc.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtztsufiyk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtjxdjyjgt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtzlzdhdgp.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtxvrwcwsk.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtyickmmdh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtwkaksqpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtreeeratu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtzqeulznk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqfskorf.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtexvzuqls.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtqqcfrggg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtbjxjizoj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtoeheobpd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpsqjhec.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtryyhjgbd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gttpbrammy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtowkhkdab.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtlibavrfr.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtyvnihsrj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvpxwhew.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtcxqicsqu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiqvadiv.html


<!-- 参考信息 -->