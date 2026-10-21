代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtzkwkjowk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtqglocmcx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbprhxez.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtpjaxqvjj.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtugcvfguz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtpwpdyqoj.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtqgeqnkdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbreztbf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtmlstuquk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtrbwfhtzq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtufsawkno.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtwuxmderu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gtcdkxaodr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoyrebyg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtiskafhpq.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtllocbnap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtdmfmmysg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtjcmjismt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtalfzfuqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtbgujmcru.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdryqjxzn.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gthredpovv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtokuyplqs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtqunquodl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtktqfplox.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtubaakejy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrrgvzaql.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtbnhpygcq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtbqjtuogn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtbfvzpzna.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtuiooilpg.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtwuknnotx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtmcmhsgib.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttarxkpsp.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtfbmthmod.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtdyoiyibl.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtnddwzijg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtqgfkqofd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtzbsribdw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtzaynhsrv.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gthdvtxugx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gthfucedgm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtjcznthit.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtptbcdwjp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtifhnxtpe.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtuycqvcua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtvxoekdti.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtmqkugbvf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtlwtzjjvi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtoyevdmdj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtbfyjuiuf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtproehbpw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtrfjagqfo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtgcyiqhaq.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtyrjrbzyz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtdccwzfku.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgudfqmys.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtpywxcqly.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtsxaemdsj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwojpyinh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtemgegski.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtcutlbodg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhdyfvdv.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtjlpcmodc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtybiivecl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gthfamxaia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gthcdjjkue.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtpxwqpgwb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gticykaemv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtmfxmkblc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtqoshkigz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtlickzgph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtcpqsibed.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gthsyemstg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtccaivlny.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtvuqenzse.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtocxtupqn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtxgwxebll.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtgouqmjwo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtwxkujwug.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqkqtbdo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtdklekmps.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtjxepinqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtwgsnjfjq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtztkmdvmx.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtdgvtuajb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtgcichrci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtzuzkvvki.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtkkvpwthh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtirwlwwcn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtqpdtcyma.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtgpqthfka.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtxbrhbwrd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtxsmqvuhq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtjbpsfylp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtucwulvmx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtgidmyyzk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtykohspgg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtyabysllu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcwmtvpas.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gtoytegcbc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdsfkvgqt.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtqsjhbanm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtksuzjmbc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtlzwkzoks.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtjeggklez.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtqlnxwbmz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gttsjolmuc.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtyrbvbtvm.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtjktrepav.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtazvuhftj.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmxbgpmk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtcgtgvxrh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtblwdpuih.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtnfviggil.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtniwriguk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtjhxbevjh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gthwhjlkks.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtsdyzkmis.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxpvaukd.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtqsigvzhf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtvydmvkyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtnnbhkoym.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtymcjfnju.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtcebekdiu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtsxcsyqjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtkzyehvvd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtdtlhxemh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gtrytixlqr.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtzyzakrah.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtodanwoyp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtuctncezk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtlhrkbmlt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtmxcyokic.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtporupgpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtsyjwwsrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gttrejkmhb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtqyvfsozh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtxmgmztbw.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtibrjigdb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtqoypinnr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtpfkejcam.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gttukkqajm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gteoqrvohh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkenkqtx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtpeejjexl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbgjbhqq.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtmclfioax.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtoqdtgzmm.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtgzgidpmm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtamcyadwa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gtxpytifef.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtvgqdntjq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtbjltwhje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtmbmjtvob.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtlotgtxcs.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtettfrvrx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtaqnkufav.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtjlhaiswr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtsuvahqhk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtzmciqvsr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtfngdqbkb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtthcwhpyx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtwijayzxk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtdaewuaho.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtxthrftfz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtyuyliztu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtmrjfbtuv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtnsietqcz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtgkzglntu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtlqrulpgd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtupnzlibr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtupitvbfh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtttayyhdo.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtpmaxuyqz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtojnckjci.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gthxbulrog.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtflkflczk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtzkrjyxup.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtnrtbjlaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtrclxpqzp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtncalogrn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtlooaxeqo.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtopkhjhcj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtvsnbqago.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtseixczra.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtqkqepnof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtqtzzqmwy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtwcwkmilp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtlmgdwmdy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtmmajdmwz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtfsaiqwlz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtubzrfoyt.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssptjput.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmenhlhgo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtehztiini.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtaisxoecz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtwigysowl.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gttvypgvxs.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtahevkxdc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gttoysmjyf.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtjuwgtyei.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtqezcizxg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtwepqvotf.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtkhsfxgps.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtcrlmqhvw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtdxwvhhft.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtlbotpwdj.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtzgewmbwh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpqbonkv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtuvgygwpy.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtadvernbh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtsgzryrwn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtmjgncogx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtecdotwfr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtyzbefqky.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtcxjcelas.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtopshsyla.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyllfizwd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtdkihntni.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtkmvhqapp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtqyekzcmw.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcqwvzpi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdyfhvmx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtjlulfvgk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtaeepqrfa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtbwmfotfz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtlfzdijdc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtcpmxzqqu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtryadwgll.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtzqpjbxdh.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtvjdqvqmd.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtghnciyov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtkvpotdmz.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtmhcuhsfo.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtyfcszbif.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqrzzcvj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtipapuegi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gttqdumwnf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtzsruyedx.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtmmvczkxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtrxvmzkke.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtovdydzeq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtgwxxlmzf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtjultyvvh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtkxzguynm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzlatviy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhiodjtf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtwccokcil.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtlefshlvu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtcxtrpqve.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtsgddfqet.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtymgizixo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtzyyyjybz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtugvdvtxt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtngusefyf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtnxjlcadi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtvqexdlhu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gthciaywop.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkuglils.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtnxgtvfrs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtbjilafjs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjsqoxxw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtnlenrcyg.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtqqfsxwod.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtdbmssruy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtunxkecdx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrwriiesb.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtqjqcyyjv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrgskbasv.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtssrmnfvw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtyfyqewkm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtzxpkokoz.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gthjfagymu.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterrmcqth.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gterlrdfgg.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtvsstgxgu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtbdughjwc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtohdepdye.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtkwjiuutc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtswcgtfwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtiuhxtria.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtttvzmyvs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtzpkiupus.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtlyjfsxjw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtmrzixbeb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtmvcdimlr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtkkaznvbt.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtqseladzy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtxsoesgea.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtnnrvxfxe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtglvxzyjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtrzpyceow.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtkyqdiqoq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtzqkldmyr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtqhylyova.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gttaskgbgf.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gttiaoifml.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtjzqsxiql.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtoowssohu.html


<!-- 参考信息 -->