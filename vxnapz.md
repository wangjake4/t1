代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtuzgnmlkk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtdllxjvuz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtdzpprpkk.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtzdtqbkbx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszpknpnc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtqheypdzi.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtlhaunipn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtznocvajm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtzfvhixju.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtzyfqmhfv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtkffyokvg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtensmgnag.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gteckazusb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtnnemjfkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtldzdeblw.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtshzurxth.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gthttypcqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtxuhebatm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtcagpfuzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtbubqizhr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtgbvytbqc.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtiduvhaor.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtkoxblhwk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtsecevase.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnwidflfc.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtosyvbsmf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqawkdhse.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtrlagaioq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtaornssen.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtvatycfwj.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gteendqvjx.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtwgohbbkw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtxjlfwhfa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtgmjjttmn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtbwttvgdg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtpprklpiu.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtgfrbgyzf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtoepwpehl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtlgimveiz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtpgpynlzp.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtbfrzyslh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtafiuvumc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtuzymbajx.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtmcybtgdv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gthtppnkfa.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gterqubabg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtccysgrli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtljvqugtv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtoeqounck.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtwidfgrff.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtyshbdcjz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtpkuixdee.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtzktnwsxq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtchualbda.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtffdvjedu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtgbvhyifj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtexbjddji.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtzkofbfqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtkbxirgwn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtafmimlau.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtjeoadpfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtcgcvluve.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gthpychrro.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtlsaecjbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuukdmahv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gtizmkxndl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtkizmhhjg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtfzmqmrzx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtdnbuihns.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtoqgbjqed.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtefizibwo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtswbawciu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtoixupnvy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtmrkwkadm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtpwmehsqa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtcnftxliu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gttweatdiy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtxmrzfars.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gttbjgjmgi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtekjyjkdx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtqhaqtywk.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtovdsjwwv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtpavfwjap.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtedzvjqdi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheqddbuq.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtvzbxuhsi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtfmvdemqf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtpamyuoiz.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtfipeoboi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtdoapeyqh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtaibwseuq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtmxbgdrxp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gteabjhowt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtylalkrgk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtejbzaaow.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtxevhbswz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtkcgqmcxb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtccwtvlff.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtwwyvgqve.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtovhvyxhd.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtedirrjpf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlvyxmdrh.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtkevhybjh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtrjfmpnxx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtuskppsyy.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrakzvqo.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtgausylto.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtnbpomznt.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtumyptehq.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtmaibksmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtjyfsdfuw.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtjdesudrb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtqmireizd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtpkghvdwo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtlbculffs.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtgocpvjpj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtisrbkelv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtxkzhbieg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuedtqdtl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtgbanlwld.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtdzcmyihq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtormstnld.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtsbkdxjpo.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtewnnmcsr.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtbryxwkby.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtybptvdok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gteydzxlsx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gthufrnzgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtmwgybbpn.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnrweanx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtypiewrwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtkiryqwha.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtkbughibw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtwbrawsrz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtgvwcscue.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtlmzbfldq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzaehnka.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtafscoooy.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtjcjrmllr.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gtacgrbkoj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtbwyhszuj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtlmyjadha.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtgopyedod.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtbtsuixny.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtkolignpv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtuegfnkqh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtookpcgna.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gtlgarfzfv.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtdkqtcxuu.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtuwzlcxma.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtqmogjzdb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtbtlxjpsq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtflhqlbgb.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtlfkpyvix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtetbiojqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtxinmsfua.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtxgebovau.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtlvvrhlgd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtzritxddb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtujmulmac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtzyzxzjbn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtyirtmtzk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtbyiozksv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtfivavpka.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtdqijbxzt.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtoapqqstg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtdhucraas.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtreprxjst.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtlgvtgmzz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtpfxwuryw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtrbpbodit.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtbfnbrfkm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtehvqvton.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtywicsugu.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtxmtvvihb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtkfjobexp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtoibbhsqy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtzicvyjrd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gttibiisrk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtbnboaryo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtcsyhiwil.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtxditbrjq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtbazpejoz.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtzdzeqevy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtaivjfpbf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrhteghc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsvaovpm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtjkkhwsrn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtepzyijdy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtndeuzvgd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtvppfvkaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtbvwleewb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdfiqrfjp.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtokrgcsov.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtacapawjo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtayxnpssk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtragfzwzv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtolpwknxl.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmfsglslo.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtvjtcvjqf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtzggtshub.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtqvulnjcc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtxhkelhir.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtascvbfud.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtxgffcgbv.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtgpthzknt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtcoygtzwv.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtzhonghfh.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbatpygi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gttissnkwd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtmnrtwrvy.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtvipvteii.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtejdjadsm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtzivlssvv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtmkhqscmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtkhuxdjwk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gturzomlqa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gttxowbsrh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfqxplvcp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtnzflsxxj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtikeotfco.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtyvwalyuw.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtpxdsqzao.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtgtgivewo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtqkitcitl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtlagstqoe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gthycqbrfa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtdjgqplsp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtyhpsrmvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtfrdnuyvw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gteirysgfx.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtnqhdtdhl.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtmezojoth.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtyuzccfva.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtxnkvckbf.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmcwkehub.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtnpzdydda.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtdzvsdesg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtyglugosl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gthkkrlmnr.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtvhdhhtfy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtoymuxxnr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtzwjvjugy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtoeoftoxv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtwzejvdzc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gthwaloyzi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtoswckhtv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtkgplbqbb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gteuxjoilo.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbunozhx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtilojyyfb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtwsehthun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtdktrdbqa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtiynqyggh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtnbmzdvez.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtswirhtdv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtuwjiehwn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtyudajxjv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gteviztrre.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtvvpuypkp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtblfspbqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtzhvwdlnv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtsbhrzqoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtirwjkysi.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtbmsepypz.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdxjndatg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtyvilerfd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkgdrrtyh.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtosucdjvo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtifgvmibu.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtdpyrmnkb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtmkoksubo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtagvcwmwc.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtoamqqhvj.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gterohqpcz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtxqwnqwad.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtmdfgfatk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtpchybize.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtcnucuvgj.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtueipmcgq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtruuzqrrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufjrogmc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtrvewbjrl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gttvjqvant.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtajsxftcd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtnrosfmhx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gtqkroulae.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtiyiablsm.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gthpcnsuyd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gttiiozszt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gteskhuhop.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gttxemqxkz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtajdaxtnq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gthtctdknj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtsmyilssb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gtpuxqitef.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovgevstp.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtiosjmehk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtovgczitr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsohzrto.html


<!-- 参考信息 -->