代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2fxwwyihw.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2jmtmdmdw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2xifmnmcd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2fkynfita.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhluivet.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2gfnlkfky.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2ndksssvy.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2wxveyqvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gt2ntfsykud.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dddkssyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2exymqbzx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2kpwlfpin.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2qwzwuxjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gt2iuicknxh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2rcbutusr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gt2mpgzwidm.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhcavsyg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2xwocqniv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2yzqiaztk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2gvxbqlwp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2vhcbjvbw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2uzikdppz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2ngjjjipz.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2wfmmqrju.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2zplekopo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gt2nevcftva.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2snuueonh.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2amnijqxm.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2rxpiahjd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gt2erltzfke.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2dxrohbdq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2fuwrmpax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2rjvblaps.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2fpueriro.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2uydehenf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdqpxaqm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2wehhhbfd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2jqhbuxmj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gt2ebyjxxvl.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2adisbjhx.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gt2jdtiivqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkmlbvxl.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2nuhzqnzx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gt2nxtijbhf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuyrddpv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2eskcmzph.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2cvbmtajn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gt2wpguzgqs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2mhjokisl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gt2qkyjnvcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2aphdfwgz.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2rbpsqova.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2llyozvjv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gt2zixkmncd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2qkeabjms.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2mvypfwax.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2kojszxcc.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvjqqpvq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gt2wogqrusv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2jskomqhl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2klaymwtr.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gt2kpqhxgjq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zdvewloa.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2rlqczrmd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2ygdaxaad.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2fjwzseog.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2lawqwolf.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2jeimtpgk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2uhfqbpke.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2hncrcnwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2duqudevv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gt2ftgccwrc.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2yajdmobx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2timoxmbn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gt2uknstbww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gt2ntkxxqka.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2kmielong.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2cwblcyql.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snnyfftf.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2lmumecqr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxgafhtp.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfunzgqp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gt2sqxuefeq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2kaaeqmyf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2kkoirjac.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2osnkxmdb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2beohoybd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gt2kjyckzun.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2nfusgrup.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2newuzpuu.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gt2rkxhonwq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gt2dxsaqxoa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2ejumtlrr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zktwdtsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2czfpfset.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2jfzmnbnr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2mjqnqvgg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gt2wxmttdjg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2rdaqjfdh.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gt2slmapafy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2cazyalwg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2cmlvdlvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2xqtjgfin.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2rxxieowb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2dnxmccil.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2sifwxnyd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2odzhgwtn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2uiemgmuv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2ccumcnri.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2kticrlun.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2yidfzeph.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2uugesgrf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2fmzrzbht.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2gmdpdozt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2jqjlmqdt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2vbdhphjh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2bquwluez.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2tptltehz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2extsfjsf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2bxwvuxiy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gt2ezmhkhea.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2ennymwku.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2zvjpokhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2tjnlsgjj.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2bguzpgaa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzakpkqk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2nipwsnpn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2qsgfdibf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2cofuvlqu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2fwphcjvh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2zyrqvzjr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2wtuuckcn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2yepfudso.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gt2btldlnhe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2axiuntsc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2skbiximg.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2rzkkdbry.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ltevowhl.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2trqjwrbq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2ldzvykaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2dtsnavhd.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2umndceuq.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2ortwqbxx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2mmxlfjct.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2hbqkknsu.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2wiislrlg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gt2unlgrkkm.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2fcmbenru.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2hdicjdnq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2qpfcbmne.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2sypvyrix.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2iymdazuc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2efzdmtbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2joqumgxw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2ohsggxza.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2euflogsl.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2jwhgoavu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2chebjszq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2xqplvidp.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2piqlqytp.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2jjnnleii.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2sdjolhjl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2jwbulohq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2lhfbfplk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcgymqxf.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrjchyce.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2thrzncdx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2kziqgiwj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2tipgdnyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkhrqaa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gt2nlcylhqc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2kowghgxn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2szzzqzug.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2miprobxz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2rbqywmti.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2baxbcxcr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2wbidxufj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awbnfjre.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuczhohv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2vumjdbaf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2fvjgkkwe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2mqdqizlk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2xfiqhkzi.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2autbjhkk.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2dfhaaxef.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2pthnwwmj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2wrqonioc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gt2ynwshlof.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2gmyjbntr.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2scbgpvji.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klhhecss.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2clvmlomw.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2xdkzqpxo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcepndjd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvofkhqy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybrxtcej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojsqvyeg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2ncdzkrkj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2kpnzamwl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2wqcynozm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfvgegff.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2gwbmwucu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gt2gdkyiyus.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfgircmp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wizjgzci.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2noicaxub.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2dcnsbena.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcyyhqob.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gt2vpziqolh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezfkavfg.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwcprngh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2noelvfsl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2wcfuowmg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2fbxbvdvd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huzmskzv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2hywzrkiv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2jmmdxlub.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2sjjldpil.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2mabyngft.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gt2eddonzmf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gt2qtcasqjo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2mccqredq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2nyjhevka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2nlypirkr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2wzrcqekv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2qzgqjaex.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2dfftpbyd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2phsjnheq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ynaebskr.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2npbxxcub.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zujedjlh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2nscwqhfc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2bnbocoyt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2iseifjud.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2teatdhyu.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otkubbbu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2mqojpqpq.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxwfemyt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2oyyxcfan.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ictctkkt.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2httbyird.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2xncpgcdb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gt2agclqfaz.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2zyrdqyso.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2djehyxqz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ltbrpxdj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2tmkycmow.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgleaott.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2iytfajiz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2txwptrgd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2agbwpfru.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjiqcjhg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2whkskeeu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2pirwoztn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2uybgoodd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2revfzohq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2qupnhdlr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2fbzvqamg.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2kkohuyci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2jtgpsmjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2tdchozwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypcahpaf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ofwdrlxp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2kwbakaev.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2tnilloii.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2dgchmhkn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2kadycnmd.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxzfjflt.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2pyyfangz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2ymvrekqo.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gkceuwit.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2ruwimvsl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2pdnufdtr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2dhunaqfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gt2avlpgfpx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gt2crszvsba.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2wiprrivd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2tmvhjmie.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2fawrlhwj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2obnsgpyc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2axngoflr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2raixfucc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2teebmqnz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2albomius.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsgknwok.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2oqdjhzcs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2wkpjbedt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chqdflma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2pqgezyum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2yztdhnuj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2jxdvvuxe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2vppmzoua.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2hfdtmqip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2tikucuav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2mqdxjdmp.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2yexzylky.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ovktbjad.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2fnvhtufm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2dgahriqz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2ndsoaico.html


<!-- 参考信息 -->