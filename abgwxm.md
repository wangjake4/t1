代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtuqsvsvkv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gticnmimir.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtyhivmfvo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtebnhgmml.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtvhsnmhxm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtnkgchfjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtzoivtwwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtzxdaltrb.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtwebowaih.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtorltnvfq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtnrgjzgpi.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtplmsiljz.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtusotguji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtgyldulgy.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtbzpgflzr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtiwgskqcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gtxxhnfysq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtimwzcdqn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtftjjzviy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbsqvwiti.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gttstmopnk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtacsevpou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgcpecoj.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gthpnfqxlg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gtvvzlfris.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtvwgheqhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtjvtlfxbs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtilbjljed.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtqtwfzvvz.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtoovnlpuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtagfhkhsi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtjkifqtpz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzqqxwwme.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtwkdrwbsh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyduywbsu.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtvwgoyizp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtulfblkfw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtybbzckik.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtutqydzkz.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtjeaqzoqy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtomoilwsk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gthxnpgpvw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtndgyjmhr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtgvpggyjp.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtcmuerlxc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtaywyaloc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtbhgkosud.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtagvbymfm.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtfedlsuek.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtbgsuwtra.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtfvtymyyn.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtczwdrxke.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtdfpnnegk.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssnkgmmt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtkmhavgyg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtdbsfkndi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtlhixnuxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gticpvuund.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtibraucdl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtvhzedqbp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtpttjolzh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtogritzdb.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtasriuutg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtsoxhazfz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtnyhpawdk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweodemwz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtqmpbndfg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtcaojhjkx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtdaakigxp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtxcbtgcyh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtcfxmigzx.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtnrxbpoyt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtyyxaisgb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtwizilpvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtvrurevbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtrhephwve.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtjhneiwyb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtipenmwzr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtcasuehcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gthnzzcdbq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtlvyktqhr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtiucyuklc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtyetgdlal.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtvmafheqy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtmhexrras.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtkgrpfvnj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtckuuxkcv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtduktustn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtolcoedwu.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtcyoaqnbi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtlafidhdt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtkmxrtdyr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtvmvqglko.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtxeojmbmt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtfsadeetx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gteonnpyoo.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtyvrxomef.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtoyyitnwa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gtcmphkenz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtjtzsuwqp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtqrhdctgy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtsytkvmja.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtomyxsktu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtjxkxeilp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtldgvbsyx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtxeartrbk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtyisrjnsy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgzaoxrcn.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtansbpaey.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqwshotwo.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtbbcdqprz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtrqmvvhgn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtrjbkrexb.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtmomseomp.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtorrmjdxs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtgdxpccvl.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtpzwazurf.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtbpwgyhdy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtigjszjed.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtrbzkckdi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtbbpkkiuf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtluedvasq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtdadmlqrb.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtjwhvhile.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtofsaqviu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtkjxitoqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtrybotnuc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtxypbnrcq.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtpusbpnof.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtcmtkutxe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtmntvaykb.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtkniiyyeh.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtxukjjrns.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtzobfhuqv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtfquksspc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gttxiikplt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtfjzswjoa.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvetsieq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtevkndgsv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtejcehjui.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gteuwiofnr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtiuhecojm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtamaepban.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gttwckeiya.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtbbydjadb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtsnejimxj.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtmhfuqvuv.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtbcdbjhqt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkptcguw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtbgdhpkdb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtccuwllcs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtyztuzhzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtkzmswrdo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gteevgnujf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtdavviikp.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtxmxlvvwz.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtsqbimbtd.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtwxawgymt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhxjcqgt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjspmcws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtgqzknlcw.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfeniqul.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtzfcbcunq.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gtjmpcqtbc.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtrjdwqjpm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtuscopcxu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtpexqkaes.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtiypidpuv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtsnslyldz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtfjbqxemd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtmselzoux.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtlbrowvay.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtqejfymxv.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtjwndfgnn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gtshcyhjgw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtnaxrpmgy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtxktefrcm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiepdxxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtfxykdgxr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gthokhkqpi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtohqfaptf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtalidlnsj.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtvcblcrgt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtoaugtcee.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtltcjjcue.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtnvddxjsi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtczosstsa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtnkactjmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtofmbxoov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtmnaadcbh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gthujhkjqd.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtyrdqjkys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtuobfkcbv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmttxbaw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtsdootozw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtggsvvjin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtnyzitslv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtzodroovb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwllldarc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrddxynk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtntgkfvxv.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtdtrklkgj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtletrsyfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrxqypgsk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtrnkeikwd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtrvozahzs.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtdioeqhmc.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtbggiknzi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtztuolqgk.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtpztyovkv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtqisknfvm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwdyytsme.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtmizhshvp.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtpkfthwjr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gteusvjwmw.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphoniolz.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtrgazexpx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtyzbtaugh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtrnlrlvqi.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrkcmbinx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaglydxjt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtzxqxfubc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtnncbrdii.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtpfyluetn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlqgsdrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtladhijbc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtwnbedlct.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtujvkzlvo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcqwdynq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtdnfrmnlu.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtmunfgxmh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtvhkvongc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpsltsik.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtfcpcyorg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtjwnmainy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtbzdfzcxc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtbqpuxkwt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtptlijsgm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gthybhmkza.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtgrbmgfza.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtqpgjsgiu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtnrmysvln.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtizcurubg.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtdbbvbphy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtzpkkcuwg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtvxuayqju.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtiqgkzgco.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtoqemghge.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtzuekxqvp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtizqezudi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtdjfgmsjf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtlsrpxfxi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtrjyaewnu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gttifwkaom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtwotacawk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwefiylr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtgecbeuqm.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxpxtqon.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfnmcgio.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtuixwsxll.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtgeazblzf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjxsuyfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtgpniyzdz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtirivplhf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtkqrahqhi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtasoigoat.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtgzvjbwtr.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gticlcoyab.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gttslpdjpk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtjbibyncm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtuqyxxepr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtrbddpglt.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtlepwvwfl.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtybdiolic.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtvtcemwis.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkxxspczr.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtlxmfrqhp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvcjeqcpc.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtofvrmrmd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtlundytva.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtnupzfhnu.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtqvzreesr.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtueceoahu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtlphyarke.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzeuoxas.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtecltysiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbjkgrib.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtuhbcysgz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtyjlzjbai.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtoylvmwag.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtnrreymwc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtnzjpmpte.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gteennnzsx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtzkcjgqji.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtntsqjmvz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtlgqudeae.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtiuwoqbgp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtayxwsgih.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtsvhnnxuh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtbrhuvstw.html


<!-- 参考信息 -->