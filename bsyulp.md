代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2nmnmjfrd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2edrmnmne.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2sgmxdbpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2usatyuqj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2rfrtvcmd.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2bvdrpggo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2odeechcn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2nvkaujvm.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2lplnpovw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2ghwaewud.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2yaghjynu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2oigykcvk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2pbmocfsg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gt2negkohqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2rxekyoaq.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2diugwxoz.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2jxxisinz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2cqdhekka.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2qtefitou.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2kmnarydr.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2kkxqavbk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrvpnpkz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2ibdqnvgi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2qyiwekqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2vehflgsq.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2npcqjmam.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gt2owmworhc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gt2aegmmwce.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2yxdiodid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2zitjgfvt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2rifitpyk.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2trzqtjpc.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2tlnlkefs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2kmuitmxq.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2jcrawkla.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2cmyraygl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbxagppa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snleizbi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gt2zcjnwjra.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2ytwlbpbl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2tasyipft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjduuxtc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2bckkvlgd.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2ojneyiuq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2ukufnpdm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2wdekbkgs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2dksggfjw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2tghefaot.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2nrounogd.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2kigoqaxc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gt2djkhtcuk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2qshpwgdw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cbzczzed.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gt2hgjhxtnc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rmdvmbgj.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpyyshgt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2dklakusc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2lpmijaaa.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2leyfymsp.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2rfohowdu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2srfyyett.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gt2npbxtzlv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnyvkpd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qecoihxn.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2wapakfbk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2ngmovjet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2owkywgpu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2xtmsuzyn.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2fhwvuieh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2rcfnhklp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsjrluls.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2yxxxahko.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2wbydvyee.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gt2fmlhbjkt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gt2uvzqdxly.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2jgugshkf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gt2spwlonlc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2yksbynmc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2bmftoqbn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2klflkprp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gt2yppzbxgw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnaxrwlq.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2qxbtrspr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2rnastuzv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2idakxtza.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2irffrelb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2prgzqvhe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eaufyuzk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2wjhymoov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2ajuxhltp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2wrmpostb.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gt2agqolukh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhyyzgav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2hacgwwin.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2tjctelhr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2stnmmfot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2cmlbqctf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ofbsmuyz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2napmybkf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewprrqzv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gt2ixgrhykk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2fzgxbcrc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2dtveursc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2iiqbxgor.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2xhdophpl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2ximjabwb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gt2anpzrykm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gt2wkckabls.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2mkjbbtbp.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2tywalvwk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2ahbeoezc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2dspjpjps.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2myduszmu.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gt2xrgkzvqi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2xbfsbuoe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2gutzdjht.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gt2skswhqpd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2iltssypl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2cuthwiug.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gt2rjyhvcrq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvoaysqp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2calnqvtb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2yjgpywrs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2byfwsghp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gt2onerwzmj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2sqomzmqr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2pcoimrqt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jvdqlrsc.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2jennfchu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hzkkccbn.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2azkmqzas.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2figbdvhx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2prwybhvx.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2vzilvpyl.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2nkblipve.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2goczngws.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2cksyabbv.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gt2odsyswqb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gt2okzjtoxs.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lybplfns.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2dahlgpud.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2byhdtzod.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2uypuzqxn.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2egxdwzss.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2njmsudzy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2evnwahqk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxidudik.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jopwcrww.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2erznenlh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2hneeoqvt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gggrhoep.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2qfwpjfyf.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2qgpinrwj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2hywbykfv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2pextbexj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2dlnznyyf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2gywutaxo.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjhkvlx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2zkqwfayr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gt2uqrcdbtz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2ykbkwgvt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2cvqvyqaw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyawvnep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2khpkpojx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2ueujpjrl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2lvgdorrj.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gt2blpxnthj.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2jghcqfei.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2zoiccnib.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2mjltjoom.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2uyaurthu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnycvgdl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2oybwgruz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2siwobrkt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2erkrjiiz.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gt2auyslqel.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2rtspmock.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2zaxjyhhb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2usiyexai.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gt2ryqdorar.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2pdbrahlc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2doqpqnmu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2idsxecyg.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2okjinmsq.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2utibbfad.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2qiinscfx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gt2hjynjlzf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2pajkpbdq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2xopoodvt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2nptcmyoa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2qkwbsyrp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2qthrenyz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2xdujrmgo.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2zeefbgpe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2wfghdavy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2uprzfipx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wabbdrgn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2rnraaznc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2hpuiiyzu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2ucrvbgcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2sdofsnoo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2xkcowehh.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gt2hzdpjdoc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2uvzbvucz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2qapdbkgs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2oyqtpkma.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2nreatlpl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnpdtfhl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2wampnzhl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gt2czuyzzuz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2lizuhyjk.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2bhrdmvbd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpvbpaei.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gt2bbflmzrn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2tmzrkwrg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2yurtfntt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gt2bhtzddkr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2xhsqehhg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2qwcbnidl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gt2hdbegoik.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfxvdlfo.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2zlenwvtg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2xhmhgwrq.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2wwzzuadt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2aphuknou.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2uajugizs.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2hniqpcvi.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2aggrtidi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2biyftusk.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2qfyiaarh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gt2hwdhjygd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2qooaqpxt.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkrdzevc.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gt2kynygheq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gt2bxotypaa.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2blitmstf.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2oilxlpwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipfanqta.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfsdgmbg.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2luslxtki.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zftbyxjx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqmdrovr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2byradalp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2tpdrfwzp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2rtyzwdlm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2coaaeerq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dacewfot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lahbxuzq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbkztzbf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2pkalgiqo.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gt2zmcyozvs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2mcoduozl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2akrlftwj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2qqphkoyz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2lnrtzsyf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2ofbygktd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oguhlnsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2xxluvibu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2agwhyynk.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2ytkykxto.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2cbulastv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2ynjmmtff.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpghxeft.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2prktpgdy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2autmerwj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gt2sypzcbhk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2poqbfpnw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2rkofakrw.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gt2qvehcyer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2cuujjjky.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2cvuiepuz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpyvousl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2bfbiabbh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2duyncwwh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ckmiccdc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2fzhgmced.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmzszzyc.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2lsexmxbz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2ssfkxpvc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2dehxzqwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2zaacvpgw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2oudcufuq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2edwmhkao.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2anqvfuzv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2ybpignra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2fimjnjtc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2daltawxb.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gt2ipaptayr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2mpnhkjdx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2fqchyfkf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2gdknannw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdfqtjgp.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2ryebtbsy.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2brwowbge.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2vxsohgop.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wwfmjwuc.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gt2hlqpasby.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2owqbfhne.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2vbowolov.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2ujomwllr.html


<!-- 参考信息 -->