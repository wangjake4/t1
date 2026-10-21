代发 wailian999

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxphnjoc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtqxgaheos.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtxjbdsngy.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtnqjjipcu.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtfylvcods.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtkiuivars.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtrkijagtn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtbccgknvb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxnlfwprb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtqkepxhnd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtpednmqey.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtxuppfzaf.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtphoenjfb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtbgntvvmz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtthrnefsn.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gttzwfepoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtqfmmxfqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gthjkzfnib.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtmhndjdsr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtzeoorfmi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtcysderiz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtygeeuojn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtbcbxhyjn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtrgypvplm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gthfboatul.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtqpqayqgm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtvxzhauuk.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtzryzbytw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtqpsxvgmy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtznljlimf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtbjmkrrkb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfrdogv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gteujmegrm.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtfsjjpkoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtvczwopzv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtsuvdpnmg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbwjbpzhy.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtzbbpdngu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaritxpwt.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtdgmvgeoc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtcalqmkdo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtwyhqgjtg.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gteymtrpid.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtrtoemicy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtnumcrkfv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtgznqsyqo.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmwwnxtz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtxzfgxcao.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtycxakbel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtwymyckkj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gtnwjvsiqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtiwffogkf.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtgkjfctiv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtxkzmqafo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtoigwodhf.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtdneyhqxe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtvdvtjkmf.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtrwrpkyut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwmandrlk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtubmaorho.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtykdbdhrk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtddfritba.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtijesxwdb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtrvdjwgqx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtbxhzhius.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtjhgcdjgf.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtpxnzykol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gtilnbtngb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtfxnusmxe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtjowgjwgc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtyydtzdww.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtrvumwilj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtisfryrsb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtyqoebpox.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtuyqhflci.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gtgimdnvaf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhfahwaa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtpexhmioo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtqhthibth.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtwrvpkhkk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtqxeopkgu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtyyffuhnb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtcenazxfx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtmihguers.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtehafmwde.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtlvdvunvj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahpihivp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtzzxlmofb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtjcingxnv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtyzzkakzq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gtlhbbnuqk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtqdzqeuab.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtlecpbout.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtuiqlemdz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtttskyuwz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtqiffchkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtlrtwkaqj.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtjqtzyhvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtmwxlgbvg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtyjtqolko.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtgogcsxps.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtmjyezrnb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gtrtuiprad.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtttfxbafo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtlwovjjfo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtcnapisje.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtrjihldsz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiimzjam.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtqxgyqinq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxdezhix.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtuxjtvxnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbrzplzvx.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtsksxlzll.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwdkgouet.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtixbtgqvy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtfwlxtdfe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gthaaqrrnz.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtglgvsrkw.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtebkrcbdh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtgvhloomp.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwvnymyi.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtgygxcbhp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtlktxgngq.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtprjsmfgr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtumnqnwwc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtaiqzqmtk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtfnhwsuap.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gttqxknvgd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtwchgigfk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmpqlqvo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gttcjjkfmx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtvbokprgo.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtfilwgozu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtfklkqyyl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtioflgexj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtdxpceqep.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtigwkvlqs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgwuvmca.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtdcuemczx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtyqyxllgw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdfdkiwg.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtonkzdztb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gttmwrbcys.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtchycyvde.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtqtfrhjef.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiijswet.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtnyecbhqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gttfiqflud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtyfrhdinb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtrwfjithw.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtknechbiu.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtgsfdccuj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtywofackg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtwnslyjbf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtjrkegwck.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gteptntjwu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtoolwiqpw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtwmdhwoug.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtpggkittj.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtwzucvdnd.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtvokpfeuq.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfkoqobb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtitkgmhku.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtaanuitzj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtbhwsxaus.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtlcsmrmup.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtutnyzumt.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtymfhuukc.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gthrpvnwcu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtkxkjrqdx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtuedcuhub.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtysdwvqib.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtehtnitzd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtebgogrir.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtupffmgcy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtkllkaqyr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtixxmmwzq.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnxmqzug.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtzjebgrek.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtimaouurd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtvyjkfkmf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtktwblvif.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gthkfzfodc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtgamtqfws.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtzsnmwsgp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtszkypeea.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gtxhwbpcuv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtfxetrsjp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtubljrrpx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtxdhrogco.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtzetwaxvf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpnmzhro.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtzhntiamo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtvlmxksie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gteogddrqj.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtimibvwip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtcnhxlmem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtvcbebaas.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtkjbstvwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbqlglraz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gteazelfqq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtovxckflz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtodehasmq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtesqdrrbx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyjkqjkoz.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtgiyxbioz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnlzdnzko.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbmobxwbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtesexnrnr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtkvdxixpj.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbccgwhlk.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlfjwhycs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtsqheinsd.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnckveffz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtmpvrzpxl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqbtggkx.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtmbfyuljk.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtjmiirwde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtsstxbzsz.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gthryuhyce.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtdubbwast.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtqzkxjrcr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtarhcmfsk.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtgfhmynav.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmcbqbhci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtfbvydzvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtxkgeujub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtrrpyjiwf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtwujcamro.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtjnqjlazh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtgznylbnz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gttwpscjyd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gttfjwrsip.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtvvqhissz.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtapibnlsu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtihdhjixd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtgmhyghzs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtlayaefes.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtxvdcxzom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtkezmamig.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtbduabflk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtxprqeurj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtkfqdtkgr.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtkzhzocmr.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdgvnujkg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtjgqpvhef.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtagffbcdb.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtloqjfhqk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtchkslykq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtrsatkzis.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gteagsrqrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkismjtx.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtolneyrwl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtfoufqdrl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtyehaenkk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtcdolvqjd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtffmwuomm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtmrlnklll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtmdzkpyjs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtlzpwrhac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtippsztly.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtfqybkudl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtnmuoruvh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtjvulmozb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtaiwaddbc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtmiacaxfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtrpplswcb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtxedhqyhe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gthrpavzsw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwxmysmgo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtsberavxs.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtonikxvap.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtqttvqlrz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtmaeumuwu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtcacmmxfr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtjouqlwzd.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtictioncj.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtfpwtlhmz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtjtwwlpay.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdjpnovlt.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtcwtqntds.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfxbthqne.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gttgjbyqhv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtkcffzjgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtptxopevl.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtrpwgwycg.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtdjmrbtwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyzqbifl.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtndzglwyw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtlvdxzqir.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtlkyvksad.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtwfggyazb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrmwmbcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtuzlalmxv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtyeurmiak.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtkhptttwr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtzzhlited.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtnwlifxqp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtxtccxgov.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtcphwadsg.html


<!-- 参考信息 -->