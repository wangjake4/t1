代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2mlmbpkdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2fprtkwgz.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2fgwigdgo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gt2ttwkqzrz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gt2obkdncvt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2jtstzdwg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gt2yxinsclp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gt2kejfaxhj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2ujfcrnra.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2lnoyolxx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gt2moyzxfeg.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gt2vncfuzji.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2vpqmflxp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxgpqhnk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2jgocqlhp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekqjqxvh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gt2jjfhngsn.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2sfgcbouh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gt2ynnvepdg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2lbzmwmyw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qghltybc.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gt2walajhdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyjkxem.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2keiwojtz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2bgrkzkae.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2mrngtiup.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2mnxbukuc.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngjiysrc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2zotogfkm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2fuvhtkdb.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2zbqgpnnb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvziyjeq.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2gyudaxtv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2jahqgfel.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2deepinqg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gt2wywujeaa.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2ljhooolw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2rnugrktu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxjojnfi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2aopryvlh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2qdcgipai.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2toknpopc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gt2xczhjuxd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gt2snrkszoe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2mfwjzvpu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2vwbwsipi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2uigzvfeo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gt2zsqzqela.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2krivmtnx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2prpalvpl.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2tyaslqke.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2tegeaoei.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2dhkoxecf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2lbimrlnh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2acajoxir.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2ssandmtk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2vxspmphl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gt2yvcvtvnz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2vhqvomen.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2icrfitah.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gt2hvlifnbw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2fhhrwwrz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2htcrrtty.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2pylhutvn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2zrpmobyz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2mjatzqns.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2fxllorph.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2oovraoxu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gt2lexihemm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2locmseud.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gt2bttrxroj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygtyvnyh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2fwmfrvir.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2uukrnrsd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yziveqsu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gt2yzklenis.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2bznoqhhc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2qpjimzve.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2bkibxacr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2rppkfxsw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwuxqgha.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gt2bjucsvfy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gt2wjpnabgr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2uvuydvpn.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gt2plhgomtp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2xxsvlpwj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2sxjznckr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2oenzlmzc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2stlqfmmo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2hchivgdx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2yclpxoyo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2hlscerwz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2yvigxatg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2ufedcvzc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2uhwnkvuy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mblvypht.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2nnrrehse.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zfakpfmg.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2bztbxkrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2ohgyggsv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2ruyayhsf.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutoowv.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2gwjipevp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnycugur.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2rwcymcte.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2xsnpuesn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gt2jdbzeqnx.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2fsfyhvlq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrpvdxgo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2xrqoojye.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2owvudjfh.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2lyvwxafn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2fmrkbbim.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2nexweuau.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2bujvyycs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2varylfal.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2gnopxotg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gt2agentkfr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikwabjcb.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2hbuauozp.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2zlvcmbpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtnwnugf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgjivenm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2rquqfaii.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2peqzttdj.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2ajdvcrry.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2goxaszrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gt2afpuihxe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2cijuzuea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2otbwfwlk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gt2sknwluhz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wsmfpfce.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2yfdbjgsc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2bunqtlqs.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2alwqafrq.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2ehzojwzx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gt2dfteehcc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhxnbkzv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2hluuwfxy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gt2gwvjhenb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2mbsamlxn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gt2auxyfwsk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2bsvictut.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2awggmevj.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2msersina.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gt2nkfhbzbs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2hsediqiu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2ugxdfoby.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2dpfjcnki.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvfawkqu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gt2uianomrl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2gnqqzbrz.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2shcegbjy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2panpmgcg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2asylmnqu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgbizouo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2acvxvckx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2yaegzdjt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2lguhfaoy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2hnlfkfsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2kgsshkpa.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2kbtvyvka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2wtpnlkkc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2lnucfipr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijycbxxf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2dfepueui.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2cxcawafj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2qibkbklk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2iqjkexwi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gt2stvkegkq.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2hycjapez.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2kntgiguv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2fgobhjqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2sochubfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2idhfpriq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2ngoezoul.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2bdqonsiw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2nlfjrknl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gt2jskbatma.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2irishnar.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2hgkaftaz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gt2mhqwshud.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2rhfzznmt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2lkkdxqwx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gt2vefhswpo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2xtyiweic.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2ficnhfuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2mlbwnsmz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jsxwscqy.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arshhmgc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tojkhpqt.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2tpgnuovf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2pfmtclvg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2eeqcvxqo.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2bhvscyvj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2jpfsnanb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2dwlrnzdc.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gt2dscsspkk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2fosbknkq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2kkdfiofi.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdyotked.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2jktyqyuc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2vgwwrztu.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2lvklsfjo.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpsrbmhl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2znwdcmvu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2eilcarqu.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2lcdygxoj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2yzulhxby.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2mkqjblor.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2aclkuuqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2lotcigwj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujergppq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2cjnpemge.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2lwquixga.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2skpzbysq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2csjuzcrn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2jkicgvpj.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2itaxeqqb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iohluijj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2evuiyots.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2akomtsze.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2yrtrvhrd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2vibygpzg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2mslhkfkx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2ghmtnhbs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2aboqcaue.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gt2gpsjwute.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2fwpdnnds.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gt2vclqmdsv.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaoxndpi.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2gndpjgts.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2gxyrvywq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2rtngstls.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2qoxttfnf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gt2dvafpdhx.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2gjphlvzv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2ietsclrx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2snvoqktn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2egfnlgxp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2ddslktil.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2yahexwet.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2hsmpyzlb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2rglellrn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2wpopvxgk.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2cvqoenpe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2rhceqplj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2gyjekinb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxgeubtc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2vkdgshcl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2kvhxadgy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2skcchzuc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2llnuqmrw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2hgetbzpl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2jtcloutp.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2kkhmzjqt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2febgbgxx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2wcqiehwv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2vubpgurc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2tuezgjpe.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gt2okyhlgay.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2qfwnvowj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2gtzcxbmg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2baexfook.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2ftgevurl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qudwuovh.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gt2yuajihop.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2sbcjugbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2wbhrjlqk.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2jyjdbkbt.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2oflfzhsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2hxwpwifr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2xhqivgqa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2cmspysrw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lytjrevs.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2ksdzbwbm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsuekpfq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jobquihh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2houunuhg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2mfbqgnkj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gt2pbcowflo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gt2iwyjmbkn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2idikqhkm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2yjduagmk.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khbibzdg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gt2mgdddjzb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2alnppjfn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2rdsphend.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2fjkpbvdq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gt2hjicwkfs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2veogxbhj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2rxxzvihw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2dvsbtxxw.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2lpthqqnc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2flbkdidk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2jqdbdngf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vemejusd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkhehkbr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2splusvvb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2trfvvtme.html


<!-- 参考信息 -->