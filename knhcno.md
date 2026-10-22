代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2gzxqpseg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2uvwmjofi.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gt2nyrbdjid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2kvhrurgs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gt2tdpgcfap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2vmbplqrx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2eqjndsgt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gt2leekbryf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2olyvamxb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2wexciypv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gt2ktqbbvvh.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqlilzwt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2bzrsoyle.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2nbrfhfok.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2xsumqdtp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2iitpagkd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsmvmtfe.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2srrpzajq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2nlqhenij.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2efxhquqo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2hitkuaqg.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2ampcmorz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nqqshlah.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gt2cpugmkmj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2psxidosq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2jltpbjdo.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2vssqdyem.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzldayai.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2neglkehm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2gjapanqy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2ngxddaql.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2ekcislgi.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2zsxuuwdq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gyszkofx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2htyneaix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2ifrphuqm.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2yitvvhis.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2gdacohqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2zqacqonr.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2psnskwhw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wchoszaf.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2kvuumsrq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2idukcpxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdxeehhd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2radcvfjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2rllgqsqa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2skkyqsey.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2pejjotlu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2ozijctls.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2vnyxqctb.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2pehyabsz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uwmhsevj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2ptjjhzzc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2dkunyacy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2twdrvbop.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2initeysd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvxtqycj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2hccbxafz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2wglmalte.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2cajxsuaa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2iaawfqfs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2idadtazv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crdcegaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrpymrhp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2hskcctvm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssdebgkz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2uztrylkk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2yikyckzw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2toamfeid.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2dwntmdyl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2zfseqpbb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2pduxrxdy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2galzbzuk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2qqaapoiv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2arwvhkbl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2qxapvpbj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2mwzmfruc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2pihdngaf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gt2kedtfimc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2twpqfwqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2bnvxtfio.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gt2xyokbure.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gt2ooeorlae.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2yovanpol.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2uijqxytj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2jkecarvz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyyibkc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvixbgfm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2snxyzpzy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2jubbkiru.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2qjnjpwog.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2cbsvnexd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2qykpnhgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2mszpkuvw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2dfvwjbzb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2twnlmgyf.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noqvdsko.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnfxextl.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2anketfse.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gt2gbwesflm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2uasiffrn.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2ocwnxusk.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2gpburbbg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2qxvdixcz.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2nfrnihdi.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gt2uvrgtqoe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2rewnxjen.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjnzaihw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2jhwumotf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2hqjozjqd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2lzcnuiuf.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gt2qtrqcjqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2wtqfcvix.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2pdnkmypr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2kyqpjxpx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gt2bcvhgjjt.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2qwfwhwdr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2xmuqqlyt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2aozqzqnv.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2reioztbq.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2wdkzkwdr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2xtwqloby.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2vedbsccd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2xliidizg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2nxrixzin.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2yufwruon.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2jrqqaeog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2logvqxkq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2edyeonjf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2irgvoxml.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2mnndbnwl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2xiicgjay.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2aulrabun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2vgvnxcrz.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2hffmsdbs.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2wpmfsyxt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2uiumyprz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2gawlxrom.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2vgoovydn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldidbijv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2aowcyakb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzdwqqjg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2bnyamsbj.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2rfuwonpy.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2ktscwtks.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzxmnelz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2dewsyyea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gt2tvozkpdg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gt2oghxuuvu.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2dhblkmnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2lgwnonqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2rhmswbxb.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2ajzniqyr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2rmhhrewi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gt2vzdvpdvg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2wuvxopif.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2flpokazu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2ngnzxyhb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2zapywtrr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2ktlfvics.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2iufqqqyf.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2eifjujmf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2lufzpnsx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gt2asdodukx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2uhrxvgta.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2usvgfaic.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2ljfualvy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2wsyxrbti.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2bjyzlqng.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2hunlfwea.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gt2rbfhqvjm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2wtianflr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2mqcfrfzq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2fwunzgvi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2mtkdkiyr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2qwahjxtz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gt2esbgofbf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gt2medoiaog.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2zdzyjtay.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2iwjhadoq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2mgzmwdsm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2cpzpmgqe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2uaelbmhp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2dswxfnej.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgbqvnea.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gt2pnrbiakh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gt2uznjgrnl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2njjdecrc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tfhsmguc.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2foovxvrl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jaedeukt.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2rupghvvq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2rhaloxdq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2kmaegocv.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vywzqvds.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2wpmtwoze.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2pwgarzmh.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ikasdbxt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2enphyhtj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2tohhvfgq.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gt2wvsvnmrx.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2thqqzblf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2ihmapnwb.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2tpksuyxr.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2rjvyawlf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2kuxuvsqp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2fwxcbfed.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2rzwofhkl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2kpvtqozo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2mogrekjs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2ljkwdmld.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2chijunzd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2sbhtjqoz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2oxsggxef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2bihpuwbu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2rlufeejb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pulitrvq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gt2kvbydxye.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohoonmic.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2srvdjczk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2pocpvsky.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2jmpuukpj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2mgklmqda.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2tetcofdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2xqaaixyd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpqddpfv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2jepqdgnm.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gt2aftulpen.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2zylovtze.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2figyfcws.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmstdmbd.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2iosazisx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2cikibdiw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gt2hgxhqeap.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gt2tiildeav.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2jsyfciwr.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2wxytbcdy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2sxcnsqqq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2umktfhkr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2tpegrlci.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2rnpuoosj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2lsudpdyw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2tfashngn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2awfbnjgr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2grvuxyzw.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gt2dmbqmlbq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2tkckxnwu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2lwhscemu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2gtrqmdly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2iizfvodw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2xxkljxsv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gt2pekrtazp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gt2mcxyaaqh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2sbaarcbg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2hmkqekfv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ajdotwld.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2uizrvnrk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2ucoywxkz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2mrijyzxa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gt2loepjgvc.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gt2lxvsjgvr.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2slyescmj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2axirqxfh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2aoboiumh.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2jxychpnc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2sshvcwke.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2mstlljlb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2sluqjryz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2mjltgnbm.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfwslsbh.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2sredsgmo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gt2dqeomyzo.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2lluleang.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gt2gejkibqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlqhdcc.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2ukrnrzjw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2lwxsjutb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2spkksqzx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2irlayhyk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2gcvluwme.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2sqhzdkug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2mccbdpxr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gt2vbejhpgd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gt2bxctnxru.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2ghtgcjqk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2fypcnuhh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2hvnmyqeu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2ptlgkrzx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2wjppwvqd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2tqdarigj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2zozatcsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gt2hdwccimq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amnsqkgo.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2uwiooint.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2rpqgvcmr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2ejcxzukj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2ociqielz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2qeadwxeb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2cirbevdu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gt2puxafbdl.html


<!-- 参考信息 -->