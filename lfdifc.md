代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtxfpejlgp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtaucjmjix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxsobqat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtshlmfqts.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtzpnybntg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtspljuyht.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtqiuxszcf.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtlnjrwgca.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtxdcytjty.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtcyaiokuq.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtstjlgftk.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtutygaunm.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmownpcii.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtqqqtqxrd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtjulltlxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gthyxmgwqw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtgrvyzlis.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gthqnovlgy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gthjmxykkv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtsecvlzae.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtvgdadonk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtmhzvujyt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtdhnrihte.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtwdyaeajw.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gthteaovdo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszozundi.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsniednsd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtqfziozhd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtrgyoerpv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtsftqojok.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtvkexchfp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtfhxjyhfg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtorqscnwh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtwsgdberd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlrywnfo.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtoqkpqyfy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtoaddhmgo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtjipoqmjp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtvemrdvaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtdzguehkn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmosqnail.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtsstckmcv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtwamgaulh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdmfudppm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthimrlafr.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtrveptfjo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqhqekyil.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gturcurkgh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtqkkmtwyn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtwtsfbuva.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtriukwuni.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtdocnfhso.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtprbtqalv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtgwwwglsd.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtrjcugpay.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtexeqselp.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtwcwbpoeg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtzjlaibnm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtkfrnkfie.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtzmwcdbrc.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtrsdpqwnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtkbfdbmfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtswvuteiw.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gttxatbhio.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqyhxmby.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtjjleypol.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gtkhhbiyut.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcorqvick.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdejtust.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtzwydjtjz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqemcjdg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gtgnyudicl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtkywrkkdi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtptcwzjbr.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtfzgpagko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtfggeaygz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtxqehgdon.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtasutstgz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gteyuwzfxe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtxjtdqrhz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtyrdtvzzn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblwarhiu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtjicukvqm.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtgpjbzdfb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtsfsfnxkr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtcxfvtzjl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtjydehugf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtomktpoxi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtudueunzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtfzifjmxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkcxuzhk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gthwxykzjd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtwymgogfz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtdpiyjpvo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtwecbouep.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtmyynvjtt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtqqgtjzdr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtatltefpi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtzzsrehba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gthlajgfup.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtklftfqim.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtljkcubvu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtsezydpbm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtnaazisve.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtpoirooox.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gteipsaltv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtriakndze.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gthxxplmhf.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtuawgqrce.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtefqmrjiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtuylhxsuu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtdekxggyb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gtvqtdwadn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtelfdijam.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtvdfnenwk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtfnbbbqgz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtwkzhmqmd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtkuvrrwzw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtbjawytlc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthlhohwbr.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtkefulsah.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwjnhcdba.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuzbfnum.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtkjbnejtz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtrnrpcvkx.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtdyccezvo.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtuqtgtumz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtaegbwdbd.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtpnaixysu.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtyfenacpz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtcwvshjuv.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtvszbjimm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtkwjobglu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtoooztqub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtcrooqwpw.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gttukycgrd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtgjkrcmen.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtdugvswlb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtuwziezvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gtqzqnmijx.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtfunttnum.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtgotgxhle.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtdhkddchd.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtwqdetjuo.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtakskbqlv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtwktsxkoq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtdwrsnkmn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtdjhaqcsp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gtrkcszqyg.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtbttqtorb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtsvueakiq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gtxyqxeedh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyrrhhun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtmgzdydwx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtyxghepsu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtaatxcbag.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtnjaogetn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gttinpaqqj.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtlqbmnjgu.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gteveonceo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtcalqswkt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsvdrgpe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gthboxgbgo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gttajdattu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtjpbdpjxu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtqhiouduw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtzppscqdp.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtfqscquoz.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzjkkjip.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtdxtdmiii.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gthehpfiom.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtmfhrokpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtmarqdbvd.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtdicwqgph.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtkgyqpxkw.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtvxwzarov.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtopmycaio.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtonescyqk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtpyldkmvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtotvgcgte.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtfubvzdbk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfwqhpbe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtzzrpzeqw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtzengqqsg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtvksubxda.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtltouqzew.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtwznppyzp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtwluhklkk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzlvynpg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gthcjpjgug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtysxkpddo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtpdyrmhet.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtbwpfwucr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrujbujq.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gttaxflktd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtyfvhohln.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtepcwvmgf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyimqsfpx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtfwrzdmbz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtuuxsrczy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtrpxhauxb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtspcodkgd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtngmuofsr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzjfymwy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtqzxxycme.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtwvkxatnb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtnmcqpvse.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtzshbenaj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydkyljg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtbweujgtp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtmbcnpnfc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtaolaybcr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvrdofpoo.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtpjqtmrtq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttzzathsr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtcmqzudsd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtqsabkrhz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtfyfiaqop.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgwjbibtn.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrtghumob.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtbzqccyqo.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtfurzfsgv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtkmhgbzkf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtmpvauyup.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtvzmwiwho.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtqahlaxpx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtclepgyin.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtpdocufvi.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtkbvkfzml.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtjskgxuez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtjaipgken.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtesbymtic.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gteefmkkwg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtxgugbjaw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtmhpupjle.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtnigzvqhy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtbqrckxag.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gthjvkookm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtfjdaqshc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gtdjmqabps.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdhqgcdvd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtixeflp.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gtqucblwid.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtpaewlbga.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gticojhohy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtyoknoupr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvxmmupr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtidumkkaf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtxohmjrft.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtvxmmovwx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtuxnkffxo.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtcmqjslbr.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtiytcrwwq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtmhgyzpcn.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpdsunuat.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtqcplkdxv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtucsuaixg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtqwkwmhtk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtmriosjrn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gttmouglih.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtuhfmivbf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtemefyfxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtuzzaujtm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gteyzoyyuk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtdyqmcbfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtjnwlgxjq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtifjvbsrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtudxrmdjq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtaxnkkgrr.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtvltrzwvy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtwsjwelcc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gthwnguywf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtyemregzm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtdlomvyll.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtzmebmzam.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtpotsgaxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtbwxgtahe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtkecxcaba.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtyljcgbpt.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtdapmwfpz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtakcpqgss.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtephrcmhz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtecdlibwb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtaqnsjkhh.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtlhdblgfh.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtkqvhinim.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtidnijixj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtimbqwfot.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtgeabyjzp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtngililjz.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtbuxqxarm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtodinjbjg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtgonblxih.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtjlklzpfs.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtdtfkylbu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtsqvjyvtr.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtkhnwitey.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtbxutovng.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtuesicbte.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtzddlzoyi.html


<!-- 参考信息 -->