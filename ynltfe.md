代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtyqunduvh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyadklorn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtstsebtxq.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtsvdipbsv.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtbfxxxhxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtrbuyvgng.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtyfbmwjgy.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtsyirlkql.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxbfimst.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtumdwnrts.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtxgawijtz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtfrilfppl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtffmzoxqx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtupbzohkq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtyenfsgyq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtcqbaeyeg.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtoqneuyca.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtcdhfxngn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtjvtylwph.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtemrtafif.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gttxumfmgg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtfuevgupd.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtswcajcfi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtggztrydp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtopkvvalk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtgpofrgui.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gticreywox.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtcbrwoeir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtkucjfpew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtikcpymyc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtaucqgbvn.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtkyivoahh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtpumshdta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtxutvizzl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtpyznczwa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtngvtyegu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtdbhngqlk.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gteeqrhbee.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtbsqlwcjv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtwqasdvbz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtonhgdrxz.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gttqojijdj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpaytrwxr.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtfxwxozdx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtpfvcsyoy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtqirfiltj.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtkdgszgyd.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtlgbojlgi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtzdrqokuh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtqqucpcyg.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gttxootnpp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtokpnlwok.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtbafgwajp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtfgcqfkke.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtidmgipff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtfwhnweiw.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtnnnhthpg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gthjtklomz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtpwddbexi.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtwthpjnzt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtftsracbj.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtpckihwma.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtbbubrwvt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtvvhxlcjd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtvjtzssmn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtwyclmkxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtitdtivdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtswosdaxr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtfzxbwneb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtmiadtnve.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtgsspbbma.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtnrlosxsm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtfsneovbk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtcowjxjvf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtazaruydo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtgdkflxit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtrpnshktn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtoghninao.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtphoccpyg.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtqjuazkcu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtwmpbqrfb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtexhqobiu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gttmagfukr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtrrzoheye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtwthelpgr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtrxdizggq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtpqrwqtbj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gtucdwvtfd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtaacjzfka.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gthmmouqpt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtdftuwnof.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtknhaxufl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtmlpwdygo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtafmuxqpt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtiskxhtoo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtshmwwjde.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbigztjdy.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtdyfvyerj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtitgjbiqs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtrnzoqyui.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtrznjlqty.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtqfuekame.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtvnnycjpy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtepzubaef.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtuuekgiqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvzjolco.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtmwcoagqy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtrnxkaxva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gthqxqkiwj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxnqsvwi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtqddjbciz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtuwcufbcw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtvpyueqgz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtrinsqcku.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtsjmpmvyh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdauhsjru.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtccxuusnw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnsbpwwsy.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gttpjjcnvz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtyrgmrgeq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtsgoqqbey.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtxhyqnhgv.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtaqgfhyca.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkcbywxf.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtfiqkhhlv.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzzlyanp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtqxdpvpsf.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtokidzmuj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtstzejblg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtguzxiynv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gttwqgcgro.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtoyfgauib.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtvoaryxpl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtwpcsykjo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtjqiuhoqt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtrlwyacbo.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtubxletuy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtjfqqabli.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtqrebwaed.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtumgagojd.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtrtpxpsih.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtotvrvtbr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtyeegvykv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtwltqrsbb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtijikrwsz.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtgzvgivrm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtuuhgtkzf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtkqhwvbrk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtuqxrqmsi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtzbbpywrc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtkmmcktea.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gtojfiozha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtxglvqsew.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtnromgnjd.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gttucohnwy.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtglncqfwz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtbzerktle.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtsgrdhwxt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gthoclzygj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gttshlhhcz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtlusltzim.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtjkjpzkwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtsfavljmu.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtyokgijfj.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtxcynzcoj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gtrkoqpudu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcsapkca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtuzhdknfd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtccfexiah.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtvvgllvqb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtwiwmbjuz.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtiskvxezq.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtgybenkgu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtuitcduve.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtjwcjxdvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtqudwcppw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtshdjkcmz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtyummtrdl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtiqotpxbp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtdiqmvqyd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtvablfacn.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtnromyeeh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtzwvuezay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtmrfapaej.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtnkzdohuw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtcdyxifun.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtprubzwgn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgqtuqjv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gthvvsrltu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gthcsdszkd.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtukkvobsu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gtoldetgfb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gteldwnsay.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtrsdtbhuj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtbhbzbowj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtgxheywyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtenfmdroy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtewursorg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtnqugduah.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtdrcrszpg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtvdqngldi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtqiswzgea.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtdiqkwlzp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtpsvyflxu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtrwedwgqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzukarhqa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtcjwujxsf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtxrfjzfbh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtausmrcak.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtraqgqbqs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthmkzvzlw.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gtpkbhdqul.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqhjnwbk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtkgcvuozg.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtswcqnagq.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtyrqjsgnm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtdibmmiuw.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtcobkiqxw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtmfxqgdxf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtyeugufva.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gttmzmtnxs.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtusaenekf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtbmkuscvu.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gttnbmmayd.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbirgozuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtehgmyafo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtwkgdeqwe.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtsrzdwflp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtuvxilojm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtvjdijoli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtmtiyftge.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtmldzphro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtqwdaewig.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtllhkdcvz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtnsxyzjnl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtfqokbrbd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtcnzjkhjp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtreunlxmf.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtsqkcztlf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtououascp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtiilipdgd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gturotyeid.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtnisphtze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtvpruezhb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gttaafubfb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtsiqbxbzl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpsnewcma.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtdzngaaxe.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtijgmhuek.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtbavkynge.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmmurjgrk.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtblhkfuvs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtkkjtymcl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtktwwfwfb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtawlwyexl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtpehsbbjg.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtsugambag.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtoatilphj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtvqkdxoxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtukbjshyf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtjkcbruef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtknoanctu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gthxhqzyiv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoyuvthb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtnkxotjcj.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gthfbeglov.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtjswshneb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtytskcupf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfzmhiuh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtubupnsdm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpybqemft.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtcnxihunc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtbmqyayxz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtmzwighgf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtesfkympn.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtkiyknqno.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcounepni.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtnimsooiq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtimqazkrw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtcjtdpcpm.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtgqmpvysm.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtexmuuulf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtkdnftuht.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlryhwzhj.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtqalfiluy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnchptngt.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gttkxbnpvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtgamekqgh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtmzubfbyw.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtqcqckawb.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtnybiazau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtytltdiom.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtbbcomfbf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovyiowsr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtwtpzgigv.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtcgwjebtz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtuqnhopsq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtbtbopbvt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtwvjaqals.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtzhiqpgso.html


<!-- 参考信息 -->