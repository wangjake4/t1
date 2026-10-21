代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtksnpukmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtnznpbgvq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtouwpjaks.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtaazfoktg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtosydqpra.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtmorfpsxq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gthbgtppup.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtjmrvlxyn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtjudpjvvg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepdqxoad.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtrsnuocve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtrlaplnrr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtpgpyrqnq.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtikaojhpg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtaljefdyu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmjvlxdfg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuvovxukh.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtlakzrziu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfjywxnyf.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtuokbdhkv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmkgtbeic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gthwffjdjf.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gthxguebng.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gttnhtqumk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtrzxowuec.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtlebumvgu.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtufdqpecm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtynjciqhu.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtqwncywnu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeqsgbel.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtcpdeexln.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtwraqyeot.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxehnbsd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtjepjmeet.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtnbgzmipk.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtardnyoxc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtatecauzb.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gttzkmzbfh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtysqhimmk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtlejulinw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtebwieznf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtpdvvmgfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtqtzidwuf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtuhsaofqx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtqzjxqfso.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccyeouuu.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtffspoujb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gturnfyuxw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtarisobjc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtjnytstnq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtaqjyiydz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtscumqryc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtfawngchj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtxanttbja.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtakbgxihd.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtxxijv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtepdzbadl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtwllacuqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtbidzjqfx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtihptycfs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtbhiavjes.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtoxxnncig.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkjgdaoxo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtaezudowm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtrtcpvpui.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtyfivzqxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gthlynpmyp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtxkqtebir.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtpcspvbay.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtxewspoqu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtclfwxlhb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtngdwltsv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtcaqzlfcl.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gttldrkihk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtjwsknzjc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtkhwultxe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtmawbvgsa.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtbfxbcnpc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gttyeytygv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtvzqgstcs.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gthrydsumn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtyjfbtrql.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtjdyejtsu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtzdaxrxih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtspnfcjig.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtwewdgmai.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtucoatgok.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtlhpgqpkr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtmlhtirmz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtzijezioe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtkedrqukg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthhydiws.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtubkowjkw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmrpvmicm.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtxtwvsmst.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gteftxhjky.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtzzqlkudf.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtqtnzjcmn.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtdxjwhwlp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gttolwfico.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtnjnrrgwz.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtdinukttm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtlaxvprai.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtecfoalbi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtpiwuoszw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtlobjfrpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtjzoptnba.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtaqhzsxvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqugjmxxh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtcwpvwolq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtwagqsysd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtvrwdhrum.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtnjigoijy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtwqwpftgc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtfmcutepb.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtasprbcan.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtyydstojx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtxxksyvrw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcgmpnqg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtmyeeewjr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxeueptb.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtehxkjhej.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gttgdkftwj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtverilbgb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtknsrykgq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtimognkdk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjxssid.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtbnvhdwfo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtdcqblnmu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gthqzbfqso.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtkfqzdmqq.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtxdomamrm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gthxjbcjsu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtrpewjohp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtvnsjoxfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtozhtjgnu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtmzvqlulo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtjtylczou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwnpkwsm.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtjgjbvtwm.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtehuligke.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtdngcdodp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtyjfewzyb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqysmnlh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtnqnmgtqp.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtvxyvwjlt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtvugbrxjv.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtzttgiios.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtshkmyqrp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gthvmdljsn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtrdqlkxxr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtzjcwquan.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtxueeurlq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtzrcgboiz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gthbgfxqxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtkxmwyftn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtxzmcfgrh.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtnxzxezxv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtfzupsxyr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtwfdeijlm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtvhflobob.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtzueynaui.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtijeotfvn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtrqzhnfgo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtfrzwmdda.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtdcuteoru.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtbzdpqlbc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtbpshiqhn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtgyvayctv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gteseilwvx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtfqcysjhk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtbrnzpads.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtgpgyogqc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtkfsekxlh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtqdmztgzy.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtakulwcsr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gteychpgtq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuckknlb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtfvlceper.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gthmscxrpx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtmqnfnqbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gtbdwthsvp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtichqblgk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtjdvwoyev.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyfepcpbb.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtxwxywbyq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntcopjby.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtsnombvvd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gthmmrhcje.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtnkwqsanw.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxwhrqlvt.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtarivgvlt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gttwtgupus.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyljmqsqr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtkngfkaey.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuccepvah.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gterxexysc.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtjzfviwgl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtltncotrd.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtmiwnznho.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtsedzyvjg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtnguyfqgi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprbxstql.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtdppznkvd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gthmrewahg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtomjqukik.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtvucvidkx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtohzejfex.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoghcztvn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtuqqpidft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gttvzbyfhy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtpxltozus.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtlhtzrdok.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtyxhyymes.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtidihtzxs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtearubjmo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtsulteihc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtxhberibx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtndabdvma.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtawkjfyim.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtqlvrnwta.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtlhzypswc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtqpcbdfdk.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtalvuduiy.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtnpnopakg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtpesycxus.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtnubigwpe.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqlbtltdw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtyhnxsobw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gtqegjmlvy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtarvjslxs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtnnzolkjy.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gthxkmegbh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrilcvyrz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtjavguuld.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtdghhnfrv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtahhxbmad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtppgtucte.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtbjsoplzt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtgsjxmbmm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtetodkjob.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtnwlljkpk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtqswalkbu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtvrouvzxk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtcctybauj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtgcfauqmq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfzaklwoa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtoftydyjo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtthmrsxtp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gthokudtpj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtdjptlmbi.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtxmyasmhc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtcfjcvmrl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtsfnofdpt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtmcglyyii.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtluztpmbt.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtcloarnig.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtgggpanvn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtrtbqoqxm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttlnmtgqx.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtfdzwkzzu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwciivhff.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtgscshhjm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtvxlxqink.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtiywnvtia.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyckuyqrc.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtuqkyexvn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtnlwsbsgn.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtpwtypyzz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfnpnvbm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtajdvntun.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtrtretjdg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcbsndjn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtauckludy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtcvtqnwvf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtydbgraxv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtnphysnrz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepuwujye.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtftzetznn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gttqxokmdx.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtckeaeodp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudkpwobs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtbxitmypl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtqmroenbe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtbbvuqahk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtwgkestxe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtdsjikoyr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtcdeucgur.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnmabjnb.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtzjrcgcxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtnsblhmsh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtgqgrhbfr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtinltuwpo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtqmqfgsfx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtgcalotta.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtushkbrim.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtphfecvly.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtxnytqvhg.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtnteqhubw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtcncdurgk.html


<!-- 参考信息 -->