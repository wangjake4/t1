代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aecxkyjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2xytybkio.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2mczzntbs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvjmtock.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gt2jptethfv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2yzicywhn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2hadultkt.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2jezpzpoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2zrlhtpsv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gt2vnunpxck.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2femkttxt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzidbkro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znehrpsq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2jhksubjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ahgigohy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grmxtpld.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiboyzad.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gt2hsjadptd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfvujjyx.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2zellynoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2iwasydwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2rxsznyzg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2mzosesbe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkhresxn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2tjuwojhr.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2qvlozpdv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2ecblaaks.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcnakamd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ptdtpfpd.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2itfxuwwe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2symzonmg.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhztknlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tkpysqrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2unpzvenm.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2enmihpgo.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nlaojfjy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2lkrzarqn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2iqctlijw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2mtcwpkyz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2yzdztjwp.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2mpplaqbu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyinbrrl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsimbrgv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2ydcepnzz.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2chsqdnzo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2ypwbapwg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2ldrsqsbt.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmulippw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2gwazgnij.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tadrjapg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bahllazv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2maxeuald.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2flpsnazf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2vxqahacr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2forocelu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2kuopdskz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcrqmyyo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2ltotzghj.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2hbxjagte.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2hbgdbfhp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2xtlewfub.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2vcaejctk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2hhotualb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2rlgxmbex.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2irqmenqs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmxqrcfj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2tmjvkvti.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2oaltnjoz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2ppvucgwz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2punfduyq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtrybgxq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2wgvntika.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2miuefgkw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtqenniw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2eosozhzk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2wfddcrwa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gt2xayjhajo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2bzvimbye.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2ttrhkide.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2biemzbwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2qzvcrhmj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2vvmarzfp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlawyzcu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2miarnbdg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skprwjtl.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gt2rgwbhngd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2oyvilqxq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gt2bdtllmfn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gt2zlfljfpd.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2oqoscbpc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2xrzzdggv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2jvagophu.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2dgycdrha.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2dpomborj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2avjtszyd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2whcghcpy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2gqhzlrrz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2wqkdaeuv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2wxhdohkk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2cvjqjmrx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gt2wllztlba.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gt2tvkvaxyh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqmypjho.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlmkpqbr.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eraelhcy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2agaxuciy.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2kgeqnzhl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2akfzwpqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2chirdfxz.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2lquqhxbg.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2oyjuwvdr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2spbpybjt.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2bdaurmjy.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2qztlaiue.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gt2eskqmstj.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2tgwcmijb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnnyrrlb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2pazsqfrs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2kfuzrooa.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2jbublrpf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2ymdcctcm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2xfmlcfyq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2fzypzwlk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2zqeglupp.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gt2bzalgmin.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gt2paffpwiy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2hpuvvsph.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2qlqnorqs.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2skacmkqv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlmxmirv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2jwydxksq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2kmmvnxfs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2psolswkz.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2wouflmoe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2ickzhsbn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2ibhluzsf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2aipuufcx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyhmtpjh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhboghvr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2dgodehbr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2gfjelxkb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2xestopwz.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucdeyfla.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2txmgfvap.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2huxtwduz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2slhhiows.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvlxnjjs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2eehroyxb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gt2ukymzydq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gt2cibpeahu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2pvhomnyh.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2dhvwodlb.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2zhdhvtcy.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2kmhaklae.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2mtftbblz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2nfupgtiq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2laugimbf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gt2rrjfxopy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2mpqxoqrd.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gt2ppphguie.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2kabykepd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2wthfgfsq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2vzjrdpqf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkewuxhk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2jssqqlqo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmbthzqj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2orgitriq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2wcxtampy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2kqdgodjg.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwoeerlr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2xrnjicmt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2wdfztyxt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwheetpk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2mmjzgflr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2dglbbwon.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2zcasppim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2ymngwhsb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2eharigvg.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2rueenbwq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2lbhladus.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2aegaushw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2wqafurmr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2gjtchefu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2ovnwfexl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gt2qhcffhdv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2qlsylksr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gt2cfcuegpc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcsyrsju.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2eirlbkhq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2shuffmbk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2sqvosifv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sejdhjhv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2xvfhgcwn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2uyovxilu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2iyalozbp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2zqarudnv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fgakgarx.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2kpzdseet.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tliimnwb.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2beotvlff.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2yrbjlcyk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2yddansed.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2connaepx.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2wkveijde.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gt2qmtedrga.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhggvqca.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gt2mvxqykcj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2jggludnf.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gt2fhtuteud.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2axtylaja.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpedcyqr.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2tjpbhdfz.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ykjtefxd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2zdzjghxl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2oqjeufqb.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pzmoquag.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2djtwhkzo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2tfbwafqk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2jjxbheci.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2zrfxaqnp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2aylzoepj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2itntczen.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2xaetftex.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2jqytuoim.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2nubzztpz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2yzcxamdt.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqjdkmju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2wyuqsqlz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2hryjcttq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfrmgvt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2mqievoso.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2rtpjxlek.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2hcsykwkf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2rmygyqqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2odbaqqgy.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2gvlppeio.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2iykwhmkj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paufbyrz.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aebwnueh.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2pzryhsll.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2fqdgjkob.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gt2ublqiebp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2xkncvakg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2pzgarhbe.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujtvewow.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2lmnzdfej.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gt2gaajomjn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2xcmcuqwh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2uvnidaul.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gt2gpzcgnpl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2mumixjfp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ztbenrgz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2mfzujfui.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gt2afmkqivg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2elbypkbr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gt2toinalaq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2ivhkgxqa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2soxcjhir.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2jkmugxko.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2ubnxxbeo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thffzwaf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2jvkvcorj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gt2junmfugd.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2ndtmynst.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2crumyaso.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2wltckdri.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2onchvktz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqyzcqfk.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2rmeugyyb.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2vitqiphv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xminirli.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2watvuqyu.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2gpkpkdhr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ccwjfpiv.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gt2nntfpyct.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2ugvpmplc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtggqtuo.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2ohqjevql.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2flafsspr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2stagtoxr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gt2sqlcrfgv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2hmtinlnl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2wrlhrrhh.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2dxsnsikb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2hmeueuvo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2qdfqlhzt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogdeuhef.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlyztccp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2vahmlneu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2fnndgles.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okfdedbk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gt2hzefvaal.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2vjmnunpz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2cfypqbmj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2obuervfo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbpoxjxe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2itnrbaau.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2vmqybazs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2qqthusfa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjpxczxk.html


<!-- 参考信息 -->