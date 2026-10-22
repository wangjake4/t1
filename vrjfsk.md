代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppvctoxc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2feequteg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gt2tymtmnmv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2wmnbcdfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2iryivdvz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2smvnqycp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2kcenxghi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2crklkgou.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2kxsdyvjs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2iijtrkzx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2xkhrhzyy.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2bloswsju.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2rueaehac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2oosngrpd.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2nsevstsp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfpjepgx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2lohuwahk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2wmqnhqeg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2jizylznh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuqramos.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2ulldkzoe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gt2caluwqcu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2odinvsxz.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gt2eeiuhkhu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2vxoyzguc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2swjfwsny.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2pbogrnka.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2hiykombg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gt2yvhdigkd.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2supujjxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2fnbuxqam.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ovpsiouz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2thtcbczb.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gt2adlnlgyx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dxzgneuc.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ghtqmmem.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ulopsfko.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2sipoewcr.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ostptuqk.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2pduitoio.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2xcthtenf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2sxgznhch.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2hckfvjwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2blfbhfsl.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2vnypwtff.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2uxtckbpd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gt2pkkyticv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gt2meenexvs.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2dvmejake.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2gctmaqub.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2mtcpujhr.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljjglojk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2fgvioenz.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2nlzplezr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ntnfpank.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2chsxfoho.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2diuwkrdx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ronhseha.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yncytczq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpfagitu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flfrfjkh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2mkbvcxxi.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2ahragpmg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gt2dsqpmdrp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2brjliegx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbqwhkpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2ypncdcah.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxgobbwu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2fbcgrzjn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2imxjpqpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2yusefbnu.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrbuwyha.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2lcpuyyid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2kxzepnel.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2fjoinoeh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glkfwogu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2jrtwhavy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2btqkmgxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2bxxoyxai.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2cwaohkfm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2pzctfqvc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2qfsritux.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2vihonnps.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jilioxxg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2ddqtjbly.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbfovvas.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2qcjxmizy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2xjhrvaer.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2kmhiedxc.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2ehpeqsmx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gt2tiiaqpsq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2auftvuls.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2zdawccef.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2ujahebrc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2pqmfiiyq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2grnormoy.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2yvjoddrr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gt2vmqadxdv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2lpjtxueg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gt2bllhhrzw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2bqikucis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2zyufwvoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2wguuaakq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2jmkfxcpr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2poklnjpx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gt2jakkdjpf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2sxzdjdyf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fqxljhyu.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2gwntyqte.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2aaantvpo.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2bkbelxcw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2ljqtjujr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2kiwisugq.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2xioyklke.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2yjcfvpia.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hewwbyqj.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2aotatvfb.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2jmxxbksw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsavccjp.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2fjbivwvp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2zznywfrn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2hurcxphz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qexlnnqb.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2qurynzjo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gt2obisnnzc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2uhrstwol.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2vqkwcllz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2auwbqbaa.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2ejbyfotz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2qwwybnxt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2cogurfob.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2ewmwjcac.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2vimibxos.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2czaseudh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2nwtvdkox.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2kfswzigg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gt2exhvpzow.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2jwwztnns.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbwqddbk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2iaetusuz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2qlfdtpds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2tgpxhtyi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2swqybtfh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ycsncxdx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2aazvqaiq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2ylkufpxt.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gt2kbiymavf.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2spvajkqc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2htpdnydu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2myhcnivm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erpdxrgh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2ksdqudjf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzjaedzt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxieyyum.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2tkmtlzkf.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyctibyp.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2wkabqipo.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2vhddprzh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2evyarycf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoxzgtc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2kytltcpd.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2uumlggxg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2ifmlwrks.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gt2iduoayqo.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2eryuobzl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2qkjvtbow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2jlptsfyn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2jqnnsppv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2jwsyqljg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2sagtbtfp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2vwjoyngw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ocrsnmfi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2virqxjep.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjvjkdp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2idtgfljo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gt2jlfrbeee.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2udoqdwlc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2mphqagzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gt2szlfjafn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2nlhjeuvb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2mqojijrp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2ztxnppby.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2dfwyqeqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrqzewkn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2igtcujiv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2gdwzwwev.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2mxoxdbij.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2binpbdug.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfstyffo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2nqwhndhg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mumqduiv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2tbcqnuxv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blaladem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzkxogmd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2mwfdlfiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2mbjkzfdc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gt2sarbedrl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gt2btauqoqm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2wggtkpnn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2kzihsrrq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xjlxzfdk.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2wniuqltk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2efulqpxb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbmjstpt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnlbkyhm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2gcmrsejd.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ngswkjha.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2psyyrlae.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbczmrys.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gt2zsmoqkjf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2cidcockm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2cjphdwpk.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaqrydnb.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2nrgpgata.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2zfhewjrj.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2uiiakukw.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2wtcurtay.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2pytchijx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2nmtcnonh.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2vtvnzwbc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2tosbmrpk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gt2apfnuwni.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2fgsyqszg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2trkllsjx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2zosmuadc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2behrxcir.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2sbcjzzjw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gt2aqhojyqn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoxseobc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2iojbbycr.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2reqahlyc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2hccgpmiw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2zdomgjtm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rftkxfqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2ygpxprdd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2yusgaokh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2efexuxtn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2pbbmrkde.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uidfppuy.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2nbmrjpii.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2fduqcjsb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2pzxpmdzg.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2inbtinlr.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2vknebppi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2cqumeynr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2rrcaordl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2zqnjeiqn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukmrujij.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqxvtjei.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2tcceaguq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2nigebysa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2wvkvmshd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2mkqyfbnt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2smgwywer.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2cjcmebru.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2vgvumynq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2tfydlccy.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2swgztnnm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2lrrdavvo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gt2mcebomvj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2hagqzyaj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2qgsdhcrc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upbanjaz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2ratuyxpz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2jphlcndi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2cctgqjso.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2ebhqckba.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ctyliyuk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2egbfettt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2rkydaflr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2imgjsrgl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gt2rmxquaya.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2oydbdmrv.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2dsweepuq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2mrsjekgb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xqnzsaev.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2dqornlpn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2oldoottt.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gt2pzcxgarr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2qjgmtbkx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2dmdrpztl.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvwwweny.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2otptzwto.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrudwagg.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2bdfumwcu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2pgmvhxjm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2awcecerl.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahjrsdvj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2harftotk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2xxvkjqls.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2uyfizygn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2jsbwhgtd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2oaktjyjr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gt2aamljhkb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2mimqiaib.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gt2ncacvtnr.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2qhgrdamu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gt2kdohbuch.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2ztvdproq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2eznnqkmk.html


<!-- 参考信息 -->