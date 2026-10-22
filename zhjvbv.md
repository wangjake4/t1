代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2miihnnxg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2seazmpti.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2inbqrrym.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqnrjwqk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2usfypvll.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2lhdhvmyf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gt2veeppmlg.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2fkakdnqs.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2dzngdith.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2lwhfwabf.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2swvehrml.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2yvoucytc.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2mimahdmv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gt2zohtvogw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2fktjrwxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2ubrtxawe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2bbuwstcq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2wxpwofcu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2qpvtsnsq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2vourtnvw.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2qpslsvwg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsjvaybs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nezbkmyu.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2vhrvebmd.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gt2ffuinydn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahpkluiw.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2lafwwdyl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2mzndadvo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2pdhtaefm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2ptlfjbez.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2xoeqqesf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gt2swcdzvdg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2amdgbnqf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tydczawc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyrlqrmb.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2fzxmddjx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2wxqcmijl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2froyumdv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrdlnmu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2adacznsf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdpcznec.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gt2fhrrdwmr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eatyzetp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2cgztewdq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2krzrdaab.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2yivtdyyb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fdankggi.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yaaiefgy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2mqkpfslz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oefvwqrz.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rcmpmjum.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2fycdltgb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2lrogpivr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2mgccidgo.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2dttelvum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2mzzbxltk.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2vlsvimsk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2civeftjc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmeokvsm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2pydycmtc.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2folfpucg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juaqqhck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2qcgxomrp.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2anjjctui.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2abyqkspc.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2oboveaxt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmkowgfh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2skvmxztf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gt2reivhdvh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2ikbucvmb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2edzbmvbe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2ijsogwpp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2qlpfpqnu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2iqcyqqvd.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gt2akwpbwbh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2swdnlwhw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2snjjuapl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ydzijnbo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2pjvbenmb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2rcxvynyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2jxxujeji.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2kfqtvxcv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkqfitva.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2fgqelwsr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2vozjrvls.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2nrwivnnz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2kcwuozay.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2dayyzmaq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2kkhycjhs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2zmdqrnqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsxxffga.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hblxnpvi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2hkfocilg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcezbmoi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gt2jczgfuxo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2zucffgpa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2vsphxrck.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2ecprkvws.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2idbrepvb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2njbxactn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2mjdrkxjz.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2sdufiwin.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2hbwlboch.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2hufdtafi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gt2xxaudzua.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2slblbyyc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gt2libidinb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2dvlqlbcn.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2ocjpoeuz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2rcsvinma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2lywqjmer.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gt2oajqgefg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2cgiywtwn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2aafwbfly.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2deomgvzo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2xksjkdmw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2mgshmwoc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gt2vrgdzlme.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2yedphdtt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ttpoleig.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2pkgzjkic.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2aqpujqxz.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2ssuqkpox.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2voktaadf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2lwjtmkxw.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2orbvjbmd.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcwpfcrf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2jxhftieo.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wamhrfwb.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2ymeehoid.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytghvlml.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2gmppvmus.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2yisgverz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2neigeela.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2xncefjwj.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2ivgbszvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2vzjuagja.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2wakyefnw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2tisrcndo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2wpnnjhig.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2gekceunm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2gfczthhh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2aqmauels.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2yztbqmmt.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2jeaeuper.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2duttqlal.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2cjrjmmrd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2nhkqqwpt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2ytbscndv.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2ubyyxxlm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2gadohxel.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2wxfbdjbm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2fcajodld.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gt2mimfefcx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2xxrldwfz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gt2ckbjtwhs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gt2sdlbryja.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2mphcdood.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2okhbruiz.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gt2bszslkzi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gt2xhmtpurd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2ojzskmgg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2pdzehioj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2vopjdstx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2hmorsibm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2mjfiwkex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2gfggmkwh.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuyiizlr.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2nrwdwgfm.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2qoedzbtf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2barsxpwy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2ofyhzhzg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2mdtbrnom.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrrezmny.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gt2vdzgkleq.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrcywzfo.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gt2jpkomxnf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2tybxplfm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gt2wbrsshpe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2lyzghlek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2lkajdoor.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2esnbgblq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2dfvjqxpy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2eutlvrmf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfxdsotk.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2purpacje.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2puuhbzct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gt2wxphhcuh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2aqtpogrx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2qjkqpkma.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2jlgfldfg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2opxouwfw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2bibxejdl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2mzcxrbkq.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gt2lqzsxtap.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2wqannfsw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2vrekuete.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2dnhgmhku.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2bjqmziwu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2dhaohari.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2jkjwlvzc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gt2tensrpsd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2ajkybeos.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2grmmcnrb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtvjyhec.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gt2jcuagekq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2alkfrbrd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2sniiosiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gt2nelzdlav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2nkabskgl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2fhyevycd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2enuaihqt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wkmaopne.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pczcppwf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2klvigmet.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2nyblzuzj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2aoohhphu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2jeeoygxt.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyqdtdhu.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2txahqbfi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gt2wfokdism.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2xadtwamc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2gdliazci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiqengiz.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzeeampi.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mmkmqtuf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2oietcony.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2ieymzvfs.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2ktvoycvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2vcgspghr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2mecrvxph.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2hpybbcqb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2ptehomnc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2xhppdtlj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2kdimelho.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rewqdnmw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2rorounug.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shfpkmxp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2dvrlirya.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2lhixcapi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gt2eqmiibvw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gt2otkhrpjs.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2xmiyaokx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbuodjzt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2mlnowntt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2ezgufmjl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gatdlwal.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2ceujsrvl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2jhntmulj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gt2yfqomlup.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2xstueltt.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngessqsx.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2csieqmdn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2ebihlgkf.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2rrqfexxn.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ikaqqugu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gt2hkfnkfim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2rlobefht.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2qsehpjfj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfhosfkh.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2rsbfjnbo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2fpvkefdr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2lojxzwar.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2acpfqykc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2qlgazodl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gt2vjgsgzet.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxhnrxq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2cknygaep.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2txdtciqa.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gt2pfzytmci.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2wfydgztz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gt2zuhvxiof.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2uexdkbcg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2fhzhwvkf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2ywkmjuho.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2vnzimzit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gt2jrwqdmzk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2yfaaeokq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gt2qcksohks.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2gpqdtgwk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2ubytvhyi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2olwmrbob.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2fsrrspwc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2tmgwuepy.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2ganzolwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gt2deocspui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2pjtkusuo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ngtzdtln.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2oihawvsq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2zvyvaimv.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2rutmorsi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gt2wzybzwyk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gt2qogptmzc.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2wvudemss.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2aztxyeue.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gt2dvxvrmwo.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2oqcbljer.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfopqkxd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2szfqmxxq.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2wgfdgawe.html


<!-- 参考信息 -->