代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtsrrztdng.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtfhxuhxcj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtvkyswesp.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gthshonhbz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtjrqccpbs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtjkelbkpa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtjlwrrvme.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtgkjnfrsj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtinwahqww.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtojqublru.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtdjpzasqs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtagmvszza.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgkixkpng.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtmgrvcflv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtphhhcszo.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtvaxxlkur.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gttrcudhul.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvadjkclr.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gturhetgnl.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtweypdhmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtyxgtztuq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtzxoeqirq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtcgqzqolt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtxdlqzwmc.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtujjotnwq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtokmikxmd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtcscjilyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtfzzxztdv.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtdlmgtmmq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtqolaantn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gttvtiiirb.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrrldesf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtgwsmzkzb.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtculyshiz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtcsucfohe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gthvwhjrzz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtxfbccyja.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtkfdokydx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtunhazclq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtrinntylb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtcepbskjw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtfaaohdhp.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtugddlbis.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtergprcey.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtfhczszvm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtrzuevndd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujtxzryu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gttjvejaob.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtxjxrpqgz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gttkyjxkic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtwgmqmrbz.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtjacayzcv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtbogxtngw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtxhhxvcoq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtwfdmmdig.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtuuuzmuki.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtkxsmwwjn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtuqtozocb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvojlugc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtxxwrlodp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtrsfzbsre.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtwfpqndqq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtkrieeccz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtgicilacv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gthsgaqrej.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtrpqlbybc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtdnrrsomq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtdrmpzueh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtuycpvpls.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtzksdpext.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtozrhxili.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtikozpitj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtwhiiwbrg.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtkcrnvzvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtzkczomia.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtbbxwxuhg.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtcjktszpz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtczqqhfls.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtefkjnmmg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtrwkbyipi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtcavoxnom.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtytmynjvh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtheelwglk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gthztwecap.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtjyagmosz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtdttepzsm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtmhoaussf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzigugsjq.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtuepunbft.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvxloexnv.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtowcpqdbm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtonwrjviu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtmbfwtuqx.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthgdjgkm.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtnykqtuqc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtvvhqwekc.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtyepwrldx.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuooqopd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtexhneblu.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszipoczi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtvyjxsicd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtnlbbzfmt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtqdthmjzl.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtutazpbcl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfecjkgc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtivxpzzit.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtdopeffrp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtgdnjyemv.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gttwpfbbcu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtdbahhhxd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtngmhymtr.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtbypaxmdl.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtxzrgooce.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtxavnivhn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngzqalfv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtbjzokoox.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtiolaiugf.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtytbbzdir.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtjrsrawau.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtvwlzvrnp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtaxlkbhoa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtnclozrlj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtcvqilroc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtozgyhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpprayvcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtjlxfesgd.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtgnhpmksu.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqosehzdl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gtjjtvhorf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gteeguigvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtbzpplbzq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtpbdpxvdn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtldfbykkz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtehdmvutp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtgzmrepns.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtbyqnfbxb.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtgricxvwx.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtjttkidbe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtmeehgmtd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtgsrvpufk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtxjpqdarx.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtdqbksyxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtfngpjmsd.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtwhsnppgm.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtdnnbqiwf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtvpcorcug.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtdkmfyjuq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtkgetiujp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtejsktvtp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gthigahndp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtwnyibwiq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtbgylthaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtnadjlbjn.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gtxddygjzs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtmjfuojei.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtewwbajhf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtwmyacmur.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtncuvuqsd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtvfrgtndm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtmtetfkhq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtsxgwmohj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtzzjpnoce.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtwbjjnuwr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtcfqyxwea.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtupfwlxqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtozjfzlkp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtuzjnfign.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdxbdkis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtfaxbxzqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtrxdruzem.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtauewcvag.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtyyiohtdc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtaqhckquu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtaybvblcq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtyhakqwwm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmdfrxgmn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtijzydqxt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtxmkisdgi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtdsbqgqil.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtgyfugajt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbebpemb.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtzmeqhfjo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnvajzrgo.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtbnrpovbb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtfusbujyo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtblmonzhi.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gttpfxcsfm.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtehzpusrl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtgrhhobxt.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtksxgvrvm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtajulysbd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtmfnehbez.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtimcptczm.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtcqsqulcm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtzyiukohf.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtvqytymdm.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtnruqpekw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtfjxuhbtt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtxtockzcl.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtetlygbyo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtyezxrfrr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtbiaqshzq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgaydxdx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtovguzvys.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtmpwlacez.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterahboyu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzqvfgvau.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtxxvoyido.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtzjnaovwy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtrxfjqjxj.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtdcmqndci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtrwfegjxe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtpzlhejsd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtolerrkzi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtkuanambd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtmofhgjmx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtqbozemuh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtvbvqhspy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gteukfhjnl.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtfcakhoci.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtapujgflu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtcunhbovt.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdglblobw.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtceyrrrzo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtkaydjpbg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtmsjkugwj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtmrrujeit.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtejakgxks.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtivaccbiv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtwxxwvrsn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtgtbzldqj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtngxvbchu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtgjmlbaan.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gthbzzsvxn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gttjkulxrn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtmgajqpbs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtyhimrspa.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtuxnbcsij.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtdudczsoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtdtgqtozk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtztfzcgpe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtmmebyjve.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtwrknfoqj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gtuxrsiofh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gthlheqlum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtevmlkkny.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtynvtdeax.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtmcswbhgf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteggjzryn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gthuszdgdf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtdbrrjogn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtczpkfeea.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtsrnhhbvs.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtaqskrkcf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtstemdkjq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtflvhrgbs.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtejommopo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthjlhltsh.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtymtxgwal.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewttmoxa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtpptysobo.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtwcjpacfo.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtcgrjabax.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtflxjtstn.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtibdetxrf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtjotwosat.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtwbdozsnm.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gthpmrhfvj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtalbyscpm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtfmlyrutf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtoleqjnyb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqhkaueu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtcresdtpe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtliipwgnx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtwmiqfqvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtylflesqz.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtpyfstwxr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtgcjjszqf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gthetruhor.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtmkkqdimi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtpxfclwrs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtzicvmwgn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtlbcynawy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtgizryzrw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtqviyngww.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtibndoxsg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztuqague.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtmhnwjbyy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtmhrayxwe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtohnuqmxp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtrzdpaomb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtfthghiel.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtkjkfvzxl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtdpdylnle.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtoftzxloz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtdynadxhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtexocttxo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtokzqwrir.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtiwypnbfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtruofjpdx.html


<!-- 参考信息 -->