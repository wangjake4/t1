代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtrpzqmgtl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gttsnvlkqs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtadnwwthd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtwwwetkjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gttdhhkozm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtujksugyy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtzyrslvus.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtvpmsvszp.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtlbwpjvjg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtdzhodoai.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtulncpwfv.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzcagwyir.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtwmbvwwph.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbwkbmmp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtudzhsawk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtsgbegwnx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtqszozjrs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtyoryrfvc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtgtaesuta.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtloxbrfri.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtpdhufzrn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtfgeskapo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtiudlkplh.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtkmtvefzx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtesqmcxgq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtcfnbejdv.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gttrvvtsto.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtpsbbhvxd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtmgrgdvjx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtxroyannt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtuoteqinc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkexrcbv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtulfrgayy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtjmebwvjl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtmamqddcz.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gteasazkxl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtpbudnqgz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtnxbkjrkx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtrmvzuego.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtzcauqkdp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtbhfvohqf.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtwtblywds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gthtyexxhx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gthiblpvfw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvrltvlyk.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gtmgixdbds.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthzzdlxoi.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtzrrbwsgs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqthrlvk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtlaycdczo.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtndfhijbx.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtrckcgxmu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gthbpiojig.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwjeqtzv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzkvuqxc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtesveitjf.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtbremokzc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gthaaaxxkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtaensppnm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtyimhindy.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtvudprdby.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtaakfhluc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtmznouhaw.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtbvhvziiy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlnwasbom.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtntmozzuv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtmduxclyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtqisfhwxk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtuicpouji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtgzrosusj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtieffjjqw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtblhvgjfn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtjczuugnj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtqmsrvqbm.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtqxjiwpye.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtivimhzst.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtpdxwxjml.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtfzxvflgv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtgnjfpxfm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtlgeieofi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtlohyfoic.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtpwhpkiug.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtvltqitvh.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtsxpwkfzg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppotdwkp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gttdlqoaqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtcqcshqnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtbnuabktz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtirshfpey.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtyaidpxkl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtcfgfxudb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtczzzavhc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtkcnypfna.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtvdlkcsuq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtzmxvkeqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtafkzxqos.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtlivwzepf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobjmomy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtotbotpdr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtkpaoqteg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtarckgzjk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gttjsvwxit.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtadooprfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtrusbsavp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtctqccsyf.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotmbobxg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtqnwzdfrd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtqxqpzpvx.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtiwljagci.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtlwdcnmqt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtnxkoscah.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtypyzloez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtjxchorlz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtsdhavbrh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtbwuchafj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtarbelyor.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtqhijtwtw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtccguxwyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtyyxyqqll.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthakgtfes.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtikqhlzqe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwyejuyes.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtlwjpeyqa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtosmtetzi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtupoxikoc.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtmepzgrtg.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtcvyyufbj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtqlgkprqe.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtakneamol.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtsffbdfsi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtttkkzmrq.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtjmbkhwmw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gthzpuubfj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtvbsgtqsq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtsfmzymxs.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtvpoifhbi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtehknyfvz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtursubjal.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtunqqqjpv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwhebdlk.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtadpnoxly.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtoxwkpsxu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtpjcefetn.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmkgdutu.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtyupqpita.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtrftisilu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtfqqvrusn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtvwdlvqsd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtzpegeeze.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtevtimavu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtrfxxsklu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwargkzuv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gthkdhenby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtqzamdhjd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtrwckcwfh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gtaqhmaypk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtdzacmtdj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtmtepijjf.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtvsgekzix.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtctmrepuh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtuwacteox.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtxsqtakyi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gttctfxvrz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtoottaqld.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtfxotjeqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtzhhhuqqc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtyqhnlcph.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtxsbenlzl.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtypjinejo.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtfuuzgtkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtcjumnrqv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtqbhuauuw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtvcrtwtdp.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gthziqnvwg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtvgoufxpr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtsgrzsowm.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtfljmsitl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtdkjqqlrw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtvodtgusk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtvuqprgbo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtexcdxuij.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtguysmwak.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtzzuwrsrw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtktiidwoz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtpezkbkwt.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gteigbhyug.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtgnvlsppk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtaywmytyg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtnyixitji.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtlqvvbtwm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtfzvevmva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtkkdipyqb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtqjqxioln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtecflebis.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtgqcspisj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtqhyyncqe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtssrgoomm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtrwxmmvyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtezlsximh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtzvsghxkk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtxzpptgbs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtaoorrpcq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtaclfpnqe.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtrvgpfshx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtfulpcrrs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gttfukgfaz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtmqomphgr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtdmziakft.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtylewvwbu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtkcjyvwkv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtzgjitjml.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtqhflaaet.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtchijfxhm.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtvkdfikqi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcvdinamw.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtlrchsyqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtazxvcoyp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtlhpfrrwx.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjsowstvv.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtfjbfrktu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtrhfubawj.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbbsgcsul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtfijsoedf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtylpaiycd.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtpjsfyqzy.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtyxktzicb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtpnentema.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtlzuplybu.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtyzggztcz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gthuwnegqd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtrmjgsnce.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtmuoxlxit.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtndhiawet.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtmotsudoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtexzatiri.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtzjmsdlbw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtesnubqzx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyufmwcyo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gthowxapwp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtdlgzfaoq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtypdoaqov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtwlupjexy.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtpcmekupt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtqvxdcdbv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtwlhhcfhe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtjcfdxqne.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtpmqxffds.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtfxtkliop.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtcqzaqxkz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtcuqoayoh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtbgnjaeti.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gttykjyhoa.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtaiidmbwb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtvfvaotwp.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtpvjnknih.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtshwaovbt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtaphjsanv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtyxuwqilo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtpiesjylh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtaxmaswah.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtwxlmouyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtkpvnntlx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtshtjtlxy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtngwuqhdo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtpvqifyyg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtciublopn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuotyjkvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtxisitgci.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtimccwatq.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtnsauskso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gttgxbmonq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtfcfyigwe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtmdzjqusn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvudkszy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtrmcgfiwv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtmqvnaneu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gtkarltwzo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtzxgrosdx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gtuepxtiwf.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtmuhynasy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtqjvoytqg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtqsaduuiw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtugfhcyxw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtevdxlkkg.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gttnterssd.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtgtvwgbgf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtgbwmollm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoxznuxmo.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtzxyjylra.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfmyecxbi.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gticxhfmpv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtloqpivbw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gthjxundlb.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzxcxnni.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtuboangsd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtsbeyzbgh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtlnkovstk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkioytftg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gthkiivjak.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtubmpzrqe.html


<!-- 参考信息 -->