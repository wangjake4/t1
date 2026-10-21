代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtgiklqjgr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtylbtfgyp.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtsvkrfeje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtiasgbrro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtlmtumxlw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtghgpqeyh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtxhvjziww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtdqrrceja.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gthncyqhwd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtvnvqrxkw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtslrookme.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtwszdbmes.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gttjchtwyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtkygjmuho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbdzlgby.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gteyjhjwru.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtwgzzstac.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtpmqxxpcx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftbgepwp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlzklouia.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqexhoypd.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtxmxnjqzc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttgfluunm.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtpbinixwj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtgwtqxmtc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gthoyvkwnp.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvzlrtzor.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtrecqblvw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtwczosail.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtdrgxvpxo.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gthlcahntt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gthfmforse.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtsbsgpexi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtkffrpwfv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtymrcvprp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gttxffaemu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gteklbonsu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gteaqkefve.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtmvhozfix.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtzheemxuw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtwrbgmskp.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtpqpydnmg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtjwjwnmxc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtjrbxnemb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gttutucscd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtocyuzqxg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtdrbaiidc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtrwoujzus.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwmoqqgia.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtkzvzqmck.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkjxlpuc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtavzdqnod.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrbpdjbzf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gttmdnwidc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtetidgwnf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gthynfolgk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtzdzmerez.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqextnxtr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtcftoncyv.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtljqeaxif.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtcmcsumux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtyapruvtu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtjcgafddr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtojtrpxtl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtctoascnn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtsuzoilin.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtjvdupqqf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtdbhoarnu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtcfjmhxsv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtoraentzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtwsawldwq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtzsxrzdzh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtyjeuzmfh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtlqzqxvzc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtqajiudlg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtbaozpmnz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtxqafsari.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gttlxjnuka.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtuevnnais.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtabxzevzx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtizqmoohs.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtqrxxrahx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtwqzkzmyl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoscmhrp.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtetmwipwp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtdutiitew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtfbnznyqg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtuomxknhm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtfklnpbho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtlltmgfba.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtvajucvfe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtjkihkijo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtmlqhpywf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtrgsyzpyv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtilxcuose.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzizqbqiw.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtgkmzlqvz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmmjqlmy.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtprefqtwd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtztajrxev.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtukjavwoi.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtyetlsnln.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpwwvhfn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtjqjgfahz.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtxblzvhac.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtttkmsoyu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtlvpcfxuz.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtpchijogv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtbqfakbic.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtjgarobdw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtvmhspfsn.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtznjmaigz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtywdvleuz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtbobzywjy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfnvxauo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtmgelphvo.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtduuqlmic.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtaxlqtlab.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtyvqyfgkg.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtidfmzttt.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtddzmhpli.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtwflsxebc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtdfsufyyd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtnynsngru.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvxwdurv.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuswrxic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtnlummmjr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gtbiwvcxup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gttqbmkept.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtpxzcvmdf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtokraljbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtuucvcthh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtpvwyreys.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtfmzujnhq.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtcvevdsgn.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtvfuqktft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtxumwymff.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtmrruhyzh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtkemjjkhz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtgjhabsnc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtczkqzvyw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtybajnmoh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtekkgroeu.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyoghemg.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtclivgsts.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtxapoxsge.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtcgndnayw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtbblydrgb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtawlmllac.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpxpusrv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtqeykdglx.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtjtjtnwht.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtezmxrilg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtmhrurxpg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjmbvdml.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbakuhmpt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtpfcnhlwy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtplfgxvzg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtgvscgwna.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gttoyhihem.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtfmynvjcz.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtivwnjeqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gthednajmt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtgibxivam.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gteziebfnd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtohvuiutl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gttqxwqhtj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtlreebiaa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtrnvvrcrh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtyqidviya.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtxvviergs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtgqsrhjoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtswubnmyq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtyyaxlnrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqiwugeg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtxynvtdhu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtwcaselzp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtmoegmteh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtxxupenll.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtzbyumrer.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gthqafhytc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtwgoshcpz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjykjihiq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtnwlrsbfx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtvhrrbbsc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtexjoudqh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtpoqzkbpc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtifxtbmoj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrdfcvmkh.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzzfvaio.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtczkeuqev.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtirempmbr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtqurhexqa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gthoexkdpr.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtmvuarhzq.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgjaarkcp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtlexmdylk.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqzpemnjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtelbvcotf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtvyrbknib.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtuqzhplur.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtpjwuhjuv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtihylhdaj.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxkswdsef.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtlukpyabf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtnhiuhjbz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtiytoimyf.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtzbvdrxlb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gtjbnbumtk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtbhnzrhwa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxconbluh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtnmhubzfh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtwxpgvxhs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtghcbefyj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gthaauxvab.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtuncurrcs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtxoffeqjc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtgktvlcwl.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtusdknarh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtgfksggot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtkcgrmqoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtswfqtnkw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtysafkhnv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtuezjlnyt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtdximgbsu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwkhonehz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtolxlkfdk.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtjuaqbpge.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtknbkaqlh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtacwmzmhk.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtjopsfgah.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtboijeevd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gtsvjldzxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtqydrtwxw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtrgmjrflz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtxyayjibv.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtloqlboha.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtyiaxlulx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gthiwxsobd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkerghlnw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtlkiiyief.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtzdfurzvq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gthlrdmhsd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtsyawczzz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtiyfhnybs.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkpalbpd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtmgqtimtt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtezmotfzm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtgfivcoxo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtjkmjzucz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtfhqqdymv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtqmmsikrl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtwgtmgbwe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtwxzpiiyz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtwsgraonj.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtucquveit.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gtmmndqvyo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gteitolccu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtyuhhnjov.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmhdftkd.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtmykzrnyc.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrpazyfvv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtmxpojujv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpkclkqjo.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtmqmtrbef.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjtusixc.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtfmgybotd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtejuxrlll.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtsjqsxzvg.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtounhthdx.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtcnpkufsb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtwxryvalt.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtyvuzjjkr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtanogetrj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtjpbnwvwp.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtivhulmkn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtvtmcumiz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtbwmwzabv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gttvzqzqfx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtbuimqyud.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtmvtjdtel.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gttnjuwctn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtcsofbjek.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtwjtnlklw.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtbhzgwgwv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtjydzqulv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtesjeplcv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtdbdywaqz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtxvohmkvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtnbuauvub.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtqwlqyrew.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtcsjndpfl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitbttgdf.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtaurcvgff.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtbckfagad.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtzijkeejg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtfeqexyua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtivclcibw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gttqfwsohb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtvxdvtjbc.html


<!-- 参考信息 -->