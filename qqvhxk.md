代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtmmnmqiir.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtlbdxjply.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gteptfqpim.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtfqdunkxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtvowuedtt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxernfdnm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtsgsbayfo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtyspwxxll.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtndzdycvb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtqwhbggwk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtnfuodcvy.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtghicwotl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtibgtzfhp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtjuuqvoll.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtkminoamd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtnfcghcad.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtlkjdztok.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtkzhebixv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtspwwnpwk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtpicusics.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqobxnsnm.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtyjgegurg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrltbqrwl.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gthqwhbhmu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtpgyzynpd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtrywdbpqt.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtfcrjfhlr.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtlghavkmq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtletsvqyb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gthhznjuoj.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtqzxhhuhb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtvticvhil.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtyshsmjur.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtjwhzfwbf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtjbewmyts.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtvvyqeaec.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtjehgucmz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtkyiuztwu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtbhqvoeue.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtnhorcajh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtojfbnrrp.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtxqctirui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtenbwzafg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtqtkgsgos.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtvrhlwtfm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtprosbrwe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtnnkrzlwa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtqbdbktpe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtdcretnjo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtzwnkybqp.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtveffcsou.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtgehjitqk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtzbfghsqc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtggcmsxjk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gthbciasmg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtniadriyq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtjorzavzx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtifansmsa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtkggrorep.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gthmzqfxtc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtxcwjmzba.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtnnyyfdwe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtbtjjwdzg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtjwahykyz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gttbrvfbjt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gteqidbumb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtfamjmqga.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtekxnxdqa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtmoixxwyt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gttsrbxubw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtordqonyp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtatijwezm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtlllrpymy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtcglroebl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtsnrwmquk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtpdxzjygd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtnufoycra.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gthjzxmfsp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtetobtevd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtmwdvbbnv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtodpxohtb.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gtaibcprkg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtupbmbdzf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtcukapqjt.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtefvrdojm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtdjpbrrku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtkrpzihbm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtjhunfbgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtufojlwrv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtuqilxddm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtcjyybekk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtqqeanign.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtazrjfznd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtbmevajmw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtzpcqtcfm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvjuqhzj.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtspwlbtgf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqjkrvbzq.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtdsjcoocq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtsvtysqqy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtqshymsim.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtrnaybvsm.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gttqsaglfn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtqygswnsx.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtzcuqcbsw.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtqtcfwobu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gtfdreoeej.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabhsbekg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtndvvvetu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtlenqzsft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtvskvnxab.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtyjtabysh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtmjrufeii.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtkkrwujju.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtamxqaqjm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtwaojjmgv.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtqspmvypt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtuyyndzsv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtxvlbukjy.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtugjxrekd.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtatgmhukv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtdsgspurk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtlqkrpbdc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtngcvxlzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtwjxjgnil.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtkrthzvrd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesiagqci.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtumlxomgx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtkapnutor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtbxgrmkog.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtrbbwnjin.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtthvayfgn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqazuubvk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuetztpdx.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtclkckbri.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtwbjpifzk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtcpdaxtgm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtnuwtwccq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtmykpmnyd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtzacdkpiw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtqydjehmd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gthttbrehe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtudtubfuc.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtsqrozmse.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtxshgumkw.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtfobrjvrw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gthjetpkow.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtacnugvjv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtxdffigpd.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtkabzokgi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gthgkcebfo.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtlzqbcmit.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtrquzebpb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtmkaphodh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtpardjgjr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtkzxgtbzu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtebrfyvqv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtsdaflkda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtzvavmhwz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtqjimsekk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtaktvzsrw.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtnmncsuiq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtidktvedz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtazfjbtea.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtmtjxmfuo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtlmjxetvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gthbpehfna.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtxuzagrhw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqwqykao.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtgbqldkll.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdyfhtba.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtokozypwt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtboibrcep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtnjvrtwer.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtjyrjjdcq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtpmppjexb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtdxjvkbic.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtbqokzynd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtihpqottd.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtoipgegre.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtxjruezpw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gttfdqvrlm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gthazecjxe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtxaywfxuy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcebcbec.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtomzhxwax.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtepjxckyf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtqrmysswf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkgqjzxtj.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtzjtdqogt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwfeunfgg.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gteoviqrih.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtkblumtng.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcprsevh.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtdovlybwz.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrtckedcd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtjhnqmuue.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtaoadooag.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtrcmhzbiq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtphkdwlxm.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtbceezhgx.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtpoxblora.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtzpktwpdl.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gttjjmakep.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtswplyalr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtdddnoyhp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtiiglgqkg.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtspofsboz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gthgtngqku.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gtpckgddrz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzkcuuje.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtmdoybqkk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtmgmqpqap.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gthhxmrjiz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtqsmftbum.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtynwfoqgs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gttjrmmtxa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtaviacodb.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdjtacmgt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtpsmxgwqz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtkefwwvhe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtazlqnrbz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtxpxnumzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtqjdtdsku.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtmxpnrvss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gttvmmfnta.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtkobkeczj.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtmpnweznv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyjosuwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtvrwirxza.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtoujvrebr.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtfkdpthjk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtrgvdeyfa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gteqdrkuly.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtdauuzxef.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtagzypxll.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtgupevfam.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtdgkmplig.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtcbhdraoi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtvafssvem.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtiiupoghr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtpdikgouo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtvzfxojpk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gterazezwb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtlgtomift.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtfxjpwuvf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtyudbfiwt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtxfhoieoe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfvcuqnqg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtjllpfbdx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtqpmjrkyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtnsnbyzye.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtbgfgwuom.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtcdauznfl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtpuwbgmsr.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuowffqig.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtaaqvynje.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtteogxqhp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtiyikxnpk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtltoiemsv.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtodgtjwfg.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxaemqoiw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaezmelmb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpiirhcwg.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gttcgmbgyy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtunuodmwr.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtlsfturwg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtjpbkalhd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtvdczgehm.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtzlkjeimp.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtaphrgkhz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtfmfuldkr.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtnhtldcxj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtbdwkoyro.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtnxdsbxwf.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtzwtesfqj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtekkfxbkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtkwtssutp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtizwnfptc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtrjsjofnc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtiekrnslj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtmkmnvktb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtpuxaehbi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtbyozzhvs.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtmcmugtem.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtkwxlocfv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgzljpso.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhneunms.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtdnhehmdu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkajanfcf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtzylgngtz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gtznqanxfh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtdnhllclz.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtkmadghhu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtpychygks.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcidzctua.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtbfxlaagy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtfbthuyln.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gttmubweqx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtacbynmbr.html


<!-- 参考信息 -->