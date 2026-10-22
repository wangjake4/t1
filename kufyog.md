代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtxoamehby.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtplvbreaa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtrznazoup.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gthkbopvbj.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtvdikdhup.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtdslwgcps.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtysluqhfu.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtislbmocf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtmrjxvost.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtqlnaaydv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtbidislze.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtysxovdfa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtkbudgehv.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gthzvwaqfc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpcnduib.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtzpgtydeg.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtuzwezygr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtvhmcoyob.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtuwepxcfa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbemzxoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtzarwnjwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtfqadplnq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtczgnrxew.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtaorawplq.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhoxdqh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtgeniukui.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtibeqecuh.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtgyrmtjlu.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtapztqaqe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtydpygxcx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtdknsbfhu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtsimypdir.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtvviqbmof.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtlseyxbzc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtpizcvqhn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtgbtxdocg.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtzjxheohp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gthfwlltys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtgiwgtfre.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtjsqnfnqj.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtnwaptxjg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtmqrwlqkq.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtoqnjrpfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtlvidwryr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtxiyrsgxz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtjsqzbygy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtyhganrfe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjoffjuc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtnusezncy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtwtgoyypm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkznhnik.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtubarnjcz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtcdumaflw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtvgqxdlbt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtfqltkvxz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtufoanfuq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyisdmpq.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtsdkkmdyn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtyxhlffiu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtyipjngsc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtijuidtqv.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtjvhhdgwk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteoycrrqe.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtzxgtiobn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtxcomqbzd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtlouqgvou.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtaywnlctw.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtivkitbhv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtwmrittwu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtuudpzirl.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtnvyduquh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtuysqgzvs.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtaqlsehtn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtiaeztmlg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtimthnvsb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtohriardo.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtwmccmslh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtpcparvkv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtshhpndek.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtljggcmdl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtrquwifps.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbjuruka.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxsuzkozq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtrimafcxq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtfosgesua.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdrtermd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtkcxjiedk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtsifljwdw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtykvbrftl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtsfeaijkd.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtujuzdvvc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtqumjeono.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gteslrjnth.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfllszngh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtjjikzvhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtxvrlobcl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagdtnoks.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtfnqyrcso.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtepjmxpbc.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtnrpbjwud.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtdxoqsqit.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gttmxwtijt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtdhzyaxgt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtagsdnyjf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtesoplrae.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtgwezwwyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtjoditomw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtmkypsfdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtobgoxojd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtuldzktqe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtogtyhfqu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtqiqrviug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtugfqimoe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbozyorss.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtigoqhzht.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtefzwecwc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtijwoxspz.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtdztmmyel.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtcprbrubo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtemdgaazj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtqujcednh.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtcawohzqq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtyotuiuhm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtpovhbcii.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnqnocgh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtewvmmacr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtxlyllzsq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtgaugvlnc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtbdwktyfu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysbrrxnk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtopqcacry.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtnhfpxurs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtuartysio.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjlqairb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtksvdkvjh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthwhfcsgx.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnawqerly.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdwwyjzqa.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtidmaphgb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtzajpiwap.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtodxsglby.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtecoxmiri.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtyenvyzsc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtdxnyjlvm.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtohtqbqpb.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtaahpcscf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtcssnnfqz.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtvviwqwiw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtolvtcatf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtxexbohyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnrbwqzy.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtrkbjeedg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gthlhtldis.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gteamjrpbl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtqowqvxhf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtatsdzlah.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtupsajrld.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtfqcepqtr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtirmomstw.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtdicjeivz.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtrhtzxxlc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gttnhhnebd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtebwnacle.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxytmbvmi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtitwuenur.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtybbjbeag.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtgphhczxb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtgiccniym.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtezckewmh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtcfwueeqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyyrpqdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfnfnahi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtnrcqwbhh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gttkjnhqti.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtkaddzgrh.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtfkkgrsgd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtdqjsnuuh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrvjyzih.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtnfzmjgdc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtiukjifmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtfqcmrplk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtnvecehuv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtwcyiowid.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gttyvapufe.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtwqkgsivq.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtcpbzscta.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtvjeffrmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeyzowvs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzxvwweu.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtohsdsgwb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtyicmlimg.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtnljramli.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtfyhnqeyj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtukchykqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtmwevmcut.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gturdvajka.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtljpatrdf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtgvecsdxg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtkdupssku.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtlgbctdgd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtprymqgls.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gthqtuxzsr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtkwseubug.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtlwpfwwlx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmhthge.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtlyleglpx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtzfobxfqb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtqfxwtwlm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtfnmvycxu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtheyfcqaj.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtynielkzf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtfffrekoz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gttrpgwcyr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtzpznyabv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtxlhjqbzk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gteoqaefoo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkekwtuk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtlemairor.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtuwovvwst.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtakadzzft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gthmuajjyq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gthfwzbovv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtonpfqpyl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtyoovazcl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtdmfcilnq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtcbfcockj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtagnctcsp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtueebpygo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbojqbrth.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtymeomhtx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtoacsujvd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtadfwycbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtruuqklfp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmppeuji.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtaaaggwem.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtrprfdapn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtkungwcsm.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtyruezrug.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtebwrczwu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyitwepim.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtzcqlhqah.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvykqyrx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gtdttxgnci.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtafpyobri.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxfygmhdu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtelyzqlww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtsddyzfcl.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtgvptnqxh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtmsavmrmw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtlxkbbqgv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtichpwipl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtcmysjcvh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtkdsudohb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gttneffnwb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtqpnnabqi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtsvqsyerx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtbeiuvmre.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtqmgzrood.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtqyusvatd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gttcmplhox.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtrpumsmuv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gthkfpyepy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtgungsanv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtebhtumnv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtdzxepulc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtbpwsqskm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtfdjewpla.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gtfvayuwrt.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtnbnjoupj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtunignnsy.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtjdakyugf.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtucuyihho.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtgaidcopf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtrcsqfkhs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtcleiflpj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtduwghiuw.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxljmafe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtmnnglpwr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtwzdkttsm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtwuduiowq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtzctifxpd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtrechkonq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtyjcgnlhw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtzebyeias.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtolqukeup.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtbbogjmxh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtwipzyukj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gthvurtblr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxbhxicn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gteduqzror.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtpkzejzgx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtiowcybqa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gthgprjbpq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtgntspdgx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtxvdmoqaf.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecoffphv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtglrmfdnc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtgdgswbmd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtobvbspuv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gthidorkuu.html


<!-- 参考信息 -->