代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtpsyhfbkk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtxcghgpfp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtipxmnkzj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtxyfapvry.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtcryjmpkr.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gticijmqlr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gttvhoeeoj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtyffjhjeo.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtnwtzelwq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gteklnwtsh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtvwesmxlo.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtxxuiegga.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtuwzpwnwc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtfhdnwmzy.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtrqsfdpxt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtwpyohuem.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gthneobemc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtaxhchzpb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtmmefdymf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtsxieuynd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtruqxgnfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdgkexkf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtaqyacnxz.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqsahjqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gteiavkknu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtrpkmbuov.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtdbfvlsrh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtpjtftmnr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gteurluekn.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtuxerkisy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtzvhkbupb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtxgcyzfuo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttcyrqioh.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtsqmdtkfk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmgjfzybu.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtdwvjqbsn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtvoekfdaw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtksedzsdp.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtxbmnghuw.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtastiwazh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtvbqpwvuk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgygndop.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtuquthbql.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtygvjanus.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtnvxxlsxs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtmenchblm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtafioardo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtctcbtyhq.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtsfoluzcy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtnjhmyhbd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtkqfhypee.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtwnbhtrej.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtsuaafzmi.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtvdrugqxj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtyfgzzlib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtjrmlmdby.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtlfpnfkhm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtsntntgvf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtljubyvmc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtdsgqofgi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtosgezmvt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtlqpxitxz.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtusywktsj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtqmttkduv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtktwdpomg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtbhgbluei.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtaavvrujc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtklwqttue.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtdequaqmt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtmybhxhbm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtabufswzi.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gthmrejhbx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxydyajjt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gttmhcrzqi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtysezzims.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtqqczrooz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtsgfjpijs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtxtwxvwbw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtduuaibaa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtugusvdal.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtnndkzimq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtuyxxcxbs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtzgwhjjdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtxxaolmxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtwlrwqowf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtpwblmsoa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtmmrfmvni.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtqnwqxhjv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtomjulkyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtxxsrpwsj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtxcuateio.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtvktpetch.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtyirepthk.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gthozplsyb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtufhjabxo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gtvjjgkggr.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtfhrsyonb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtqfscfsic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtvtlgmnmg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtvctssiqc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtzcmenuzp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtdnwvxddw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtisxqpnzg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gthfcjuopo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtgudorfqc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtorjymwun.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtdfuukhla.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpuerfaao.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtucmagumk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gterlmyxum.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtsgmxwdnr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtadtgcjze.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtytryeacj.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffwacix.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtnggzvpxa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtyjnilsib.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtgdsplfoi.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtylelmdwb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtskzqexxx.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtljuvyxno.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtwhlvrrly.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtziebstgb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbfcsubv.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtwbwsgwdg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovxvcrvz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtmrrehngp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtsotnmgxq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtwhtnawvb.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtvtoalwmb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtoodancew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtcqksljsm.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtpktguhvh.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtgzszxiyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtdskpxawy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtxbhlmqwo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtajvbzczm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtjhhcfcfu.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtymvrrtow.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtdwgirqml.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtaxnlwkpy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtburtotyz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtgfhrficy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gteuiilwpp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtqwvwgokf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtztypvccj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtfrvavvga.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtdnwjtiij.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpwjesyb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrnrkini.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtwsoqhuir.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtndkhisjk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtyskcwldy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtfjmrblgb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtspxymqti.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtetmlhahx.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtdnmmjqae.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtwadbnchh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtaawruzcl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtsemucaan.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtngrkuabw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxznbcxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtrzmcewes.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtopbancvp.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtxhmtofgd.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtwhkuxdwr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtkwpqsuxh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtnsmpcyho.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcetwsjpc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtcpkhxdmk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhpigabe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkedskhq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtvalvxsxr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtlkajgnnr.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtejhlnxdv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtjtfgqaxn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtcrnrmmau.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtfoknbdce.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtsirgqpez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtrfmoxkub.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtqeaokzqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtrvpmopvt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtsfqqhnzn.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtpogcucmu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtbmpnclvk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtkwiijqwt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gttptunsvg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtwnbjwanm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjztooifp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gttuzyqmlh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtkldtfhcg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtwxtcrarq.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gthjffsmoh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtgpyzdqhr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtrnegenvr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtmkarxqnq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtfiofiswh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdpalcicb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtwniqbvrh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtxronottd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtgwexhwyw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcpxmhyru.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtxxqbrscz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgszjyuzu.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtsiplufpa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtjpcgopfp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtwtodlyco.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqyhduywb.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtommuttas.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtthsvfulj.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtekveqkuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtiddjrcji.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqtucinp.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtzjwksgnj.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtsgjieqpy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtmzstgouw.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtarvopmzh.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtrgbmygxq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtqufbqfma.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtulutwilb.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtjfisguig.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtqwdwksgk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtookfyrfc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtylveeard.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtmpgslpfw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gttdkajtfw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtkfwpmmsw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtecmolxil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtvvcbiisu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtpofhrblr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtrwwbfrib.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtchpsmxzb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtbgvliwpd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtknuvhbed.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtkbgonvxc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemthbhfn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtyacbphnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtdakpckfb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gthjmrrmzw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtzfsmcrhy.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtueyxdqhi.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtehnooitv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtpovinswf.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtpmidntdp.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtpasmyaec.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtihhcthaz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtslbglnej.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtklhoqchn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtllytapdy.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtpiklnpae.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gthbkaunyw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtthhvhswt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtimzcofja.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtmvohycki.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtpvsppwta.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtzshyrakv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnuvexav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtuwcjhutx.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtxfuqltrk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gttmgybezc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtghosnirv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtqpchojiz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtfofmhzjl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtowiowsuf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtxexxgeri.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtkdcryjve.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtxschrtzs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtabbjjxin.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysypkgru.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtmgqsnfjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtehhiyvrz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gthmksqjgm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtkjnnvris.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtqpfpqehf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjuryohwd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtyhzcpgnm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlolqeqmi.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtlgngivai.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkobysoej.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtoyvizbbj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtcrapsujq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtcsxisiff.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtuxlvmtkz.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtoicgswdx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtsdtiqjuw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtnrlcissb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtclijqxhl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtphcvguxp.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtgybhfytb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gthbnbtwwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gttpeflsui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtuziwinnb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtmczyqbmv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtqljwelyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gthyiyreff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgtmyyjy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gteceovghh.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtwpbxvpzn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtanfmuynz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtdvnuugdh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtqiglvxlz.html


<!-- 参考信息 -->