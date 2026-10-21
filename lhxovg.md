代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gteqjviuwd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtjyzbynxf.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gttgbmwurz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gthbqtbacv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywlrlmhp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gthruaozes.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuikudjup.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtpxtvzbgp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gttbegqdwh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtfsqavsyk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtgualrohu.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtlmoiedcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtagokyjlf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtfgzkjsri.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtotnbnwiv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtvtxwabht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtbpsyaasy.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtkinzshvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtymnxmder.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtecwuzalz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsmtrzpg.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtaflgedpv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxvntwbxk.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gttpcowrzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtdehhttch.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtrdhnbtpt.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtzsgghtam.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gttduglhqo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gteupzuzxn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtertllirg.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtupqpbyku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtrdbewfcm.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtptstatpt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtckgnjkrh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtxiapkrwd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtqaaqyzdk.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtwnwwmpee.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gteutcbolb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtvnhjbepv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtvlkucijg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdltgudg.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtuzvrozlo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtkucfxrlp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtyyriujza.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtguwciubd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtgihdpasz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtezixstxn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtzdoffany.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtkuvxvfob.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtwfvexxgf.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtylfzppqm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtaaggngfu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnohsgjb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtwxhxxaws.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliccntsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gttuuaixtk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtgfuxcjcz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtmsegciul.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtnqkxxzyt.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsspexikl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtanuyhljb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtokinyizp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtptgqmfid.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtpijtgxkj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtfaggxiuf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtterchkiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtgvhkhdbm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtxsxpebuo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtposhqopj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtwdqmiyft.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtvqkovdzc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtpjxjwdts.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtpkmuidvb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtvhfhvlhx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtutonysjj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtfexrombd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtymacvsbg.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtvnzgqpqs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtnoidpurf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtgrwlpwut.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtgpewfwtr.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtndscnurw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtpkvopaks.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtfekiiinr.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtyhzlecky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtmokbsucf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtzpckyutx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtwbtimdqw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtpezeaixq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtgbgopcci.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtyytbhvlq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtnrdcipux.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtfgxzuwho.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtgilcotio.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtrbhrtgcn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgfeeipey.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtewzfnate.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdmrbwzge.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtlafskdna.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtjxomczta.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtlqkvefbg.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtowjawhnr.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtdeutthix.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtpgnwwfsj.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebomhqb.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtrwnrjpyj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtutzuerud.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtwsyzhdjd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtguffyris.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtptspwleu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtifbcsvut.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtcbalimnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtihxchxjf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gthqmltmab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtarvxlqza.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtivwkujlm.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtdubijgpg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtbjtnkzxi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtzcgceyke.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtldcqskgh.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtpdveohjp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtaeypykhy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtgazjwels.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtcjblwmmj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtmlnqbuux.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gttijdumfj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtbejknvos.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtiqbowcti.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtcocdfeam.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtynyqymgy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtbkivofej.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtpafvajrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtsxzqrjvw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtcjupzwkt.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtjlnsimho.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtmraqukjk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gthvzycytv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtytrjpevy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtxcbxuwzq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gturnmvewm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtuwpzpxzk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtfnwedioi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtjpjrlugz.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtiaqlywkr.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtogxnbusd.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtoqpwfntb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtsfsyhkzo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtgeqgtuwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gttyqsinfs.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtvkefezmd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtedqvgkam.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtfdkomqqp.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtojbvzxtp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gttcuxlpiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsbzduoq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtxjjnodxy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtabsmvuek.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtvlajgocx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjrfgdfe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtbawuyu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtixfepvog.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtozyvwnan.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtcpdzurqv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtnpaicapx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtwbxhmoun.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtlvtpnbhd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtcvgridzv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtyfrwrugs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtgtzecryu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtnzcbqsht.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtpacweodq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtjreovwbp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gteohcbvnv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtpjapxfew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtqmieicbn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtljrknoeq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtpznbbpnn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtrusffncl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtlbuttvyc.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtmszkciwz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gthmmwsdzp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtqmphowdq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtfygjjrxa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtzwkxqngs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gthaptwfmr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gttjpcegub.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtrtxmfbrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtlbkscuvx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjkbhern.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtrqtfnias.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkkulpnux.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtbmlkdkrr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtfesqxzmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gthvrhrjli.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgqmypxo.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtcfgsvbmh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtcfewillm.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtorbgetcm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtpgduujwr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljkjtonw.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtwllscetx.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtdevxndqp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtimnguplh.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyffvrkws.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtahylzwmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtrhafvbfb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtccdgnsvh.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtoicatjuy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtowqvazht.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtbdpnoctd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtgdvsuaye.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtbfpdaisz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtarndytks.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccyzrlpo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxljznsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtcdcxmmwt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufmudsuz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwyyqpds.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gttvjvquqs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtrvmtfihu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtdkvatjhz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpeeqsbsl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtmkckwxyr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtgcbtxsav.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtxxykzdue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtlccmtart.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtafsdrjvd.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtwwtbieol.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtyhtghzqg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtijzwvtbb.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdyjqpzrs.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtnaecvxpm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtqqvoisxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtlpzrbjjf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtbdyieozy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtxkiltpaj.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtnyedtwzw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtonibzoea.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtdxqlxbav.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtifpgamcm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtqhjswoht.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtqefvigtg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtnrlvbqqc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtwfyhkukc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtwjvofjtj.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtakecdaot.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtzrozacgk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtlicnxjof.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtxikucpjm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtrioslonn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtdqnjzsux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtrjycwxxr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtgxagojbg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtotaxnfib.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtkjptlllf.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwiygnosv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtwzfpproc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtmzxmbvcx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gthekdzegc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktpviqpn.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtibnvlxpf.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnvmzqfmc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtnjexqftw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtewgheaxy.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gthuwepxsu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqacmgevg.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtuowvzkcn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtuoqswcsf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtbotnvgrj.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtsvxwyxcy.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtnrgnsbai.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtobktbrdo.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtztsjcicr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtpvesprig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtzdviwhmt.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtmrqtepvs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtysiwfiiv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtceznlbys.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtmcgtjmpf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtzfiwuwob.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtzbrtnrlv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtqsxuqnky.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtlyxaofsr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtehhpphdp.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtthrrjtlz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtrdetdoih.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcliyepox.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtmubwluqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtphambzlf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtgrodmvto.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtptgkoeha.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtsmcebzkj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtrlfujtgw.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtuyywzdbt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzijypjlk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtpqfixcnc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtvejowniq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtpgtogjfn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtamrikoam.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtgoyrcgdr.html


<!-- 参考信息 -->