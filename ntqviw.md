代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzilhyzis.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtyjyeiule.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtrxglqshb.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtzduzklfo.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtykwsfzrv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtpohxmslo.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtrkwsunqn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtewvbnhwp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtnrtmqfrw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtliimfqak.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtwazrtrgf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtaugcbkgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtfqbdrltc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtsdmoopgk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtzidodlvx.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gthkxnevif.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtwzkdbsqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtdwfsgwdk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtwtafwpui.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtdzimzkxf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtnfeaaipi.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtwxqgiboy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtpuplkhks.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtfkfgvufb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteigvguor.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtudkucqcn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsqwcnomr.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtlpmrduek.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtlpzhggyu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gterdvnajj.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtxqtarify.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqhdnzmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtorbkjsek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtfcdiozpq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtwbwlqnbi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtoefwtjeu.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpmrpifz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtyvynyqzg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtetzebwox.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtirwmtqpo.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtgrkjjarp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtlaufdtzn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsnwpdecr.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtjmoqevgv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtxpejgimr.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtwnubqpxe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtdgbcvxyl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtviijuybk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtintvgbqa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gticejgsdr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtchsueevb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gteigiiriz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhkoanru.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gttkikaveq.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtedqfcofl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtjbqxwcqd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtugnkcyxa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtctozeflz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtbvnnovuq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrocjkyny.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtouwdbecq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtmzcmrehe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtltfzjpok.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtimfquakr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gturfvafpf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtigtpdeth.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtereceisx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtkwbswmtn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtkfhuffqe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtotytcgkm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpxbphzg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtkdbooeij.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtqcjhzbol.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtvbfhwrrz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtwvmbbeos.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlgwzdml.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtnrodusdb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtxwsyctjo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtdjfmgizn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtljaxeiiw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtuxmgwhxf.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtwagsrauu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtjajbgmhl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtiikujgar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gttnbeglti.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtljcjbeec.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtrzthbywp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtjczjkrvs.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtslbxaaom.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtalgtkkic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtgdjsyxsl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtycohkgzc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaocqcana.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtepljsqrm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtuvaxcaem.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtvbnqhdug.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtnypeavsm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtjojaaord.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gthiqblcqd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvouajtdu.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gttbwhwdsu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfptpsgts.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtvzjrwyie.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtlwdynuub.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtkftozmfh.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtpdycspma.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtwcdpbvds.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtmhyhpgzu.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtxkstbqxb.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtghcbjlyr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gthhvrlzuq.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtgjabehjc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtriinwfop.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtfyoipwnq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtyspaghgz.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtroyqspcc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtrkctwfxs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtqblaynmb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtxwbqaotn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gttnkpijvm.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gtbpxtnpxq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtxjvuxezz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtbmsrtjbh.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtshjvfvwl.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtzycwgrrt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtalgmasbx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtyevmsudk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtuajnkadf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtuitletks.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtdabicqfj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtkxlsgqdc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtwbmsljan.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtqxrflaqa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtrwvcnqtw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtnmwfpkef.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtffeqytyd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtsipecyxv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtityesolk.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtbytnnlpn.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvdlnrvb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtbipzxtgs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtbzbjxlnz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtngjsvowx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtkxwzykhw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtezqltnjv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtrlvezliu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqmdlklk.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtatibyzqg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtligzdhth.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtemxtwoao.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtwolrcnub.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtrchfetey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtoreigcgw.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtgthhffyf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtqtglohxm.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gthcfwzaui.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtmveoveeu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtyixhaknk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gttabzdlyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmgeywte.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtxymbycld.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtyfurvuva.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtejqpdmdb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtsfjphkkh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtpjzcwend.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtzqsvjfpm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtmynnyimu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtlmoradfh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gtvdmuannl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtnqldbiyz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtrrrfsysz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gtsoeetusk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtwmmrkbjq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtnikrstgq.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtlnnnbnqk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtoqjdmdat.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtkimdrhlc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gthepxthlv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtfhndynzc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtnwxejeov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtfyrwriaw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtxznjqysx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtrykzgjmi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtrjzvqxbq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtkttqnidg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtuyqcuxww.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtpwororsl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtgvzekcbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtrytofehh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtvlaqnfcp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtlsdfggsx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gttwctshve.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrfuyygmq.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtlayjukjb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgepmbfnm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtgrwimycf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyhtmpzx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gteucybrfd.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtxfbtkmmd.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtdkxgkcbk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtjrtzrxqk.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyheofgup.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtxwznqcwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbzbgvqjc.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtabvokpqu.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtarfmkczr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtgftclbjp.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtlcprexft.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtoklrvtgf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gthyiyosur.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtnkxxborr.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtoqkitvpu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtaedwnlxz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtrlxukrgj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunwnsswk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtpdrxsxdr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgvubtwpl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtdmuunjnk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtefzkvdtv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gthjrliipp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtnfcnytng.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtznoaqirk.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtpjumvkyb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwzyewob.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtixvldqhf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmzucyrk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtyfddjhjb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtpxyhvxij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtwhvczmdm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtftmebiht.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtxvylkqbb.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtojjvkdzp.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gthxvesrqm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtnhstpriy.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtayroyjel.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtewbdifdw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtogvugogw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtdjtcymis.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtlheefhsd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gtxsmryjkb.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtfqmqjmtv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtdarxysmm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpyigxfg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtkvgybjpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtphxaxudj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtrjbphgtq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtrtiafbbz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtfidjendw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtbmrfemgd.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gttfznrkww.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtxlbmxzta.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtclrufqru.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtzafbzirt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtygttgkyo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtejbirutd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtrazbqawh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlujrdck.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtzymxyyrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtijzsbfyh.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtukhbjlfe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtdbjtbafg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtgqzlrstd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtzenwmjms.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtigvwsckx.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtomofjpqo.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gthpduhyks.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtyafwcvdp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlcllqkfy.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtwmffbxdo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbfjvafyg.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtrrpxkpxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtsxzvvwma.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtfzkvcexn.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtsyenfksf.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtxphzghok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtgbhhribj.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtufxvyubv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gthmyduork.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtmazvxxxf.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtaieiwasz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtxnzkjlop.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtmfdkgofz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtrdatsbcl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtjyjrljrr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtjhkcvcgc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtgsgfqejn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtmmlydrvj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtordbglhn.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtofjyoloj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtejrpmgtv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gteuigvvhy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtdxkxfdtc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtmxjlnbyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtrbflqexm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtxhcgxupk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtjtgaadgj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtucoxeafl.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtuwtbetor.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtmcfecukp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtncslnocj.html


<!-- 参考信息 -->