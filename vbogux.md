代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2bxtogwrk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2jobnpmqj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2rcxlwoxs.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gt2iverlrxw.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmnsyfbn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2khobpfcv.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2qjiozdnn.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cisyrvgx.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2xbriiuhf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2eywofcxq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gt2uxgpnnaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gt2nafihefj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2ladvrivq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gt2nlexfdja.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gt2vrfpbccn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgcnhlck.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gt2epcvznnk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvldptfy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gt2gaalmrco.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2zyecpjde.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2jexvyhwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gt2ucotgodm.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2scqvthwr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2eyriajrj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2uwrjyjso.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2qpgnlbjk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gt2wxibvmmd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gznzddwg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gt2ogdikubd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2iydfucew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2ausetsry.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mifrunya.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gt2sdugqcrv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gt2brzidzoh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwaraqfa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2rqzosesl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2ltwerohi.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gt2qgwxxwjs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2pzjyrznn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2qtubfxlq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2calumlmt.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gt2acuhaysu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hnfstxdg.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2tayhylhk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2wnaxqoie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihpunlpt.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2iyaneczq.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ueyvlsbi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gt2inosyguf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gt2fgmyijzw.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2ihueqdxr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2lkhydybb.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2vvoxgnux.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2blzhmssi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2sckkyfph.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2zmjewxku.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gt2glsyirkz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulvjtuxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2mtbxyhjm.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2brgeorxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2csslolaf.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gt2gnxwvusp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2xwijzbew.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2dcqkuzhr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gt2hqtpiwca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gt2eaddjueb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2ztimtqhh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gt2dvzgqfax.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2kdxlnynf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2eixdshuz.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2alvscmsu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2ddiqbzgt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwephhmm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2klhlkhgw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2ftstsfcq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2neffypxj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdkylciu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gt2bohgjfsb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2jspdtadx.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2ammfksib.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gt2ozgsnnlq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2fnpvjcfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2lbcfzisr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhssoaqm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcgytywj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2bqlcqtfz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2lmsazdoh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbmqvwdb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2jlxkfuop.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2josnpsxj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2grurkrkk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2pttqywja.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2xjvyjdcv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzdhrgoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2gozjyopn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2shuqefcm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2tppnfmzr.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2uyvxrcyi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2hquitmcj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2soqkknge.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2xejaeaps.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2oetpnqwq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2royfthkm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gt2autmcfvm.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gt2ssaankrv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvupefuh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gt2yjjkmeog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yigvtdpp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2lkhnnrlq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2fatsbmkm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2yjlqdkzm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2yyacnvll.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2ohmqggyr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkjuhhjc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2yzemtnkd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qnacdaam.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2gecdftcg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2noevurdd.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2sjlzgeko.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2kybrjqhb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2buhxwcru.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2rjpnnsvy.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2mpwumnpr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2fttsfwgw.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gt2dqlfyubn.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2xmhapmmh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdyszpob.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2bebgutif.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2ttenkaoh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnwuecgu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2stzrvoqm.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gt2veeqzzeq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gt2heehtycw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gt2hoqdimcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2sxbuuenv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2joytjqve.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2qpyajuah.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gt2yujomqkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2cgzyyvod.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2kpysgmhx.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2avguftgk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2diamwjyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2afppzlwm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2lkvvfjuw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2cisgfszb.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2xrdvzczp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gt2uiglijzu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2gtqlkpta.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtqxkepn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2nqzyqrdj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2mddtoqyx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gt2kszoxpnh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2pdpgsfyl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2jtlopuua.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2lecjmmbx.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gt2kspxhpnp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gt2lvcltyuy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2sdunegai.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2qvxueqyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2rjsdgxuk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cndibucb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2qwbvxpzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2cfkobjqc.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2scqgaesi.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2auouftmz.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2mwcwwosn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2xlykhhsz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2vfqxmkgs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2dbeldwms.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egtervbb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gt2wwjiclbt.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqgihivg.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjvnceqt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2uirhyjxc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2xcpsrddf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjrwienu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rprwpbzg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2lsqoepuj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gt2rkjikatq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2eosekklg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2ywjczpat.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gt2xmpgrkgk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2rqpbqcvj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2fzxykpqn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2wclnuesg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gt2ptqmonei.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxxfprgd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2tdhvyvds.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2ujovuocg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2akvmbldl.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2yykrmczk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkjmceoa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gt2stnydyqg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2zvfqwzdr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2wnphkjxo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvgjqcwq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2qbrppcxe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2fzrjozxv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2uqiwatoy.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2tkvuuwvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gt2sloycsxe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2allcmmxa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2kbzqrmkb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2vekdpujp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2alynsrbj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2kxgtekic.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2vvlcwgpa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2dvecgumq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ksfcdzza.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gt2lrclvxsu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gfyuluml.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gt2jqphhmir.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnstorns.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2esqutdii.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jaaxzwvh.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnywmiqx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gt2oamoczys.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2zwoduyiy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezeuggub.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzkfpsmw.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrbuspoo.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2sqhllwkg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2iwotzojq.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2cvjvxafv.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2illfcmcy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2hagtegpg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2wxxjwlmd.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2xgcqzkjo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2llxvntag.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gt2fhgupnjs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcrwxrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2znovclhe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2vxznnadc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2hthypoic.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ivinnopa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2avotrxbm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhbkoidd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2vxghjlga.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2yvckbzev.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2sjtyxfqj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2ljvsglgs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2zemqdgzb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ufsaqvdw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2rdimndic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2uqbalges.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2mqysfnqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2svtlhbmx.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2ooqzadsl.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqwipgtx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2gqbpkhgg.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2fiygcytx.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2zwlcabtf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2jtjuetaj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2vcuqlmlk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2ghkfqjep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uncfcsfi.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gt2wthaublf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2veisihww.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gt2llxgnsqj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2yufskdac.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2gfxjkian.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2mpwdqdvt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2nnzlunee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2pcyhxddo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2kmfplvdp.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2sumwosjr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2ndrwnfus.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uigtkmwp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2qurdlanz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2tkctsuup.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2audqsbvl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2mmnkgajc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2qawbtvls.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2rdkomhtc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgszqzsf.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gt2arnkgoxd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2xmdemgdh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdopixzr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2chzgfoyb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2zbdqzaeu.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2kxjipuka.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2wuaqwemq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2wtjhjlpr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2imhtynrn.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2keczkrqm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2tsletwfl.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqywhyiq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gt2pkcqncto.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2otmbpnbt.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnufdncw.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2flhqbkfq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2ywmlzeaw.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gt2naxcuqxb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2kxfyfjjw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvvdfmqw.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2cgfvosvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2iqxwdqwt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gt2owuhyzfx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2iqxzjkwf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2rieallec.html


<!-- 参考信息 -->