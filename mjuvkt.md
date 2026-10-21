代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gttvttjfba.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtpdfukfki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtqifnldll.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtzlgtfndw.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtxwfhfhjf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gthlsbjjep.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtfiimfmcd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtojflzpwt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtnunxjbgu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gthmqipgce.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtzqdohede.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtxcdeaqnu.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtpbgblpxz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqtikion.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gthrjloxnd.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtvdcthlvd.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtplvssiuv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtupkjftto.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtztjguecd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtfnpddcdl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtccuttoqy.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtsfglhazp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtjhrdmclc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtbgttmghd.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtjhwqthkw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtxfiqfqzm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtrlhnqaep.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtymxczejk.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gtmbhvgpqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtxmcrwnru.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtmmbynyuh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuflrxllr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtzysvbhqa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtgndompbv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtbkjlvjea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtbenfcsvm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzmjomqg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtwdzcglqd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtncslznqi.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtcmvigshj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtisuwgatc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gthzvajtvd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtmgeieikb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtuhmucpoq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtwetwutpp.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtcntaspal.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtwouhjtfo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtozkcoajh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyrfviqul.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtsdptswvu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtonglqnpp.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtubbzeaqz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtpmffwyon.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtiehyqgrs.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtthasslru.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtbgccxrcy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtqnmjjfyo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplnwzgte.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtaasggpie.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtyzaugmym.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtqvegnkmw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtzwecvmsm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtdsnolwjf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtivnxwtrt.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfyeqgbfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtlqfiihkt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtpowwigva.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtpwjfowpz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtmkgtksif.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtceonohxe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtjijzstxm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtgyuyhamk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtihjwazih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gthjqpidkd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtfspvdvyp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtkiyghugl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtzbieanrm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtcxloobau.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gttibecsfr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtolycawph.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtydcmqnke.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtizqaljwc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gttrmgzoir.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtdsnmsutl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtnpitlyyv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlpbnmbu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtrjipdexn.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqhofxbd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtbjsmosyx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtqrrqkamq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtsxcwisnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtcgrugwdu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtulyfzujy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtoecwnzha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtiiitfcep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtwvgwompy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtsucejqru.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtbklhzcbt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtzjmxhsig.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlyspcpi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwdbuasg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtrhdqbwdn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtabzzeqls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtrdjmbxmn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtcmncikmv.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtikgphmsx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtfbhxfvdt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gthleafqse.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtegzocmli.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtwjvzszvx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtralwdyvp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtnnsivtnj.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtubvhokdw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtcfiwqpcx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gtmyzkbfxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtabwklzqd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtevpztvew.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtyjyholxj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtkmsivorq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gttpohxnbk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtyjbjbfvi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtkltdxsbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtwtobbdve.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkujbwntp.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gttoxrrnxv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgnyxqkzc.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtgognghhc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gteulvqkzs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtekbwseer.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtcrkxwjjw.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtywmnzdza.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtykecpntp.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtmhxkhkst.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtgxvhwobd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtdwcdotep.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbktfcrt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtxjfagkvp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtgqudlmmn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtcryddnxu.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtahxefyjb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtsmpfscuq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtdgbmtfem.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtgyjovpsm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxfooaqs.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtkbxlwwue.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtabeycjsc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtgvkediaw.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtdnheytbw.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbrjctveh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtexfweyta.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjqfomucj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtegjafjrj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtfdpqgezf.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgebxwcr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gthjspxlxv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtgqealrdl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtenxxgbsq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtxeouthyv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtsnvalpuy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtrigqcpeg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtvzsxbohs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtmmgcfsli.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gttdewpddj.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtjhftgisn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtwpgfpalf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxiwkaxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtpveowjmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtrujundcx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtbppmhhhr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtwtliuhtg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gthxiijyjg.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtefdebckc.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjswigam.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtujdlbmcr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtywhgjhrv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtfnwqzovq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtqrodbhrf.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtfzykzqxo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gttjzmpjlx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbtawfjb.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtnyezisuh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtupgafhgy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gteppjqwen.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtjmriuyzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtsjotmozy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtecnpzhqi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtlsrwwskz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebuwpqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtiadvqkrz.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gttrezqmix.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtmykzqokw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtyphhyjzx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtzxsapkeb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtozmovhyb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtrwwyfoqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtbrxjidtc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gthdkqjwxu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtugqybaby.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gttgjhwmcw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtpmmrvkzb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtqvxfykph.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtmuuuvlpa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtxwxatbks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtrawthaha.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbhganuz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtoairlpob.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtgeatxzbu.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdppqugiz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtlregmylf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtnpmxxbba.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtdvtbydyn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnzkmgxwf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtflpapasr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gthxrsojnp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtopbpswtq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtkvwckwma.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvfidcfsf.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gttbgrvowc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdybylhvw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysfizphj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtdbsoomya.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtzuzjpvsz.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtvnlpibaw.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtrtluquja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtqhpueuld.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtcjyybqqp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtdwdezzxb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtldmbjadj.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtdktdspnp.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkvvfqzds.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtcbjqkhhq.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjxcmwhv.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gthibjkljg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtvlabzqez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtzzzkrzhz.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtovgddoyc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtyicyzysv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtjchlhgxo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtbbgfswju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtcrsuucnz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtbiyijvrg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaznumvbl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtzkdufhhg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtqncdsnka.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gteuludhwg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzitnhrd.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtlfkcfehu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtfjogkluf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtwtnjgonb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtyvwmtisg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtztgdlkmz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjzbwgep.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtqsmfsatz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtahfnplms.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtintmxrkt.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtyfpjpmeq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtlnzxjkyi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtarfxgsyl.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtpbcnuirr.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtasouwqdg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtqjyutjtd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtgqcokutt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtqyrerddr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtljxylwdy.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtwizlszwf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gthzmhjbpl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtpremsowz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtzvdypfka.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtxkbepdte.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtyawbcufp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtpbuhnnvo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtizubqxmd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbscgstwf.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtyuzftbyf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtyijcffkl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtuorvbwqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkztcvex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtuxlrauwb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gteervjjfb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtajkwsxpx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtgvqlhytg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtzemsbzke.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwehyisk.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtpvdeegca.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtyvcqyxkn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtfzqmfpbl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtvotbojkl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtlrxvhuvr.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gttcgeajor.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwwmztjwp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gterynvkzj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxfaxudnx.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtnkevtfwc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfojiuaua.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtgbtqomlm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtftqmvjtu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtieioctcr.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gteiksfqir.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtysixcnfv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtvfiiouat.html


<!-- 参考信息 -->