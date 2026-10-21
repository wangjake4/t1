代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtbnixhebx.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gttummufuj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnnihljnn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtzqhjdohm.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtwcsfrlvk.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtdqjrcwug.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtozzktdmw.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtepcmlhjz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gttwumpwet.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkhbjgwys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtuvxpfdue.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtupxfmmlg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtiawttsrw.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtcjxlbxoc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdcfxxrud.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtpdwoxbjn.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtqaotpqjv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtscoevdgg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtbnvrwrhg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtseopmstm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtkpojnali.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtjvkxkrwa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gthdmarzcg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtlpzkjhfz.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtkmpxvpla.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtufvqvupv.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtflkfglym.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtfsevgqyq.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtreaooucp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtiqymufil.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtmtngawsp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtndvvvcfb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtxjsbopox.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtuafutkjd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtrmkijgpp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtsaertdyy.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtnechujyt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtmhlgcgab.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtbqrvmwjy.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtcyuvpwda.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtcvpoee.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtvivldxba.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtotvuojxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtotycfufz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gthglsrbbs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtjgjpprgg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtfcushpef.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtsedvrcpy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gttkqarorw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gttmewxzwf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtrypnzyfc.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtranlpmoj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtithwzhcn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtqpqnudui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtdlllupwm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtyfiwgelo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtktxcoywt.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtvldxmnwv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtplkraiys.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqbrfxpts.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrotguqet.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtskgxhxkw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttfcljars.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtoekavacf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtycbmeoks.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtnpwwphek.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gthlqhroou.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnetqpsjo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsqrugbf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtnyiftjyw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtvtpwcmxm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtmtaerplf.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtuvbsgtry.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtseddahxo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtznssvpaa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldowikeb.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtctahtema.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtuomehgus.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaicawtj.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdsoevhn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtabxlrziw.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtsajssnte.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gthfzvieqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtaqcklokd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtphkrvzfj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtyaqomluy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gtsvezwkyd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtcfbeqrgc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtfojdhqnh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtkyomoetq.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtzwgdsgbp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegnhxgdg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtraeghslj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtfetanncd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtcdnfhfby.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtjvtbosbl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gttuwuktlm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtiloeifnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtloprsfki.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtlbnnvxmn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcenwady.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtcqrjbces.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtpzozcxds.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gttvgqglxd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gtsuyadheu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtumpwwdbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtvwdgzoyn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtaucuxibx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gthrtvnbkz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtgqdnebzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtdpkwhgky.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtekkbhlsq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtqhfuqqzj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gteoahqmyg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtsqdgwrgb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtpkrjyswc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtyyvcwbmh.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtycyhtdsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtylogwyly.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtqinhvhkk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtmkuphjth.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtrbryikni.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtwhxlijkj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtchlvognw.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtdgsfbubs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtypskvjtl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtndqlurpb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtpplylbpl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtonwbvmqb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtaxhvyovz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtnydpinvm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtdygemdpt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtpllnzhzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtgaewosku.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtuztckehn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcxxnrvbt.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtkmsbwlpn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtevjovccf.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtndoxarav.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtxbyrkdmk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtclevssbk.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtiaadizha.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gttofbskik.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtbgtfastp.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtavwwlsrs.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtpytjrrse.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtypozvixx.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtcxrgoyau.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgwexaqj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtcwkexzeg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtwiewxocg.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtijejvieq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gtnaspwube.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gttggccbir.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtmyhocquv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtqufbohdq.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtlkezkedj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtxbkbbuvv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtlpvrhlkf.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gttxkpwstq.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjanxujz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtmlivpqiq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtrzemnjjs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gttsnjxrqx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtzmmlluby.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtgpymmljm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtauxtyegv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gteqjsluhk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtqqslrifv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtcissrirx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtgeqycajp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtdpxpmqef.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtechooqjd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtddnhbtgt.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtiocqafri.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gtzpaxgirg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gthyhwhbkn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtfilhmazs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtpdhymqzd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtuwsobmur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtskkbxxzn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtzffumnbr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtbhcghjzl.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gthjcfuwzm.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtjpirvari.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtsdsagxqu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtumdmkcel.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtrztevbas.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtsewxldsv.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtggpmzquu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpitirdle.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtmesbqqai.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtuhcsedgr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtrsmpzdmu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtlkagnlin.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtixtomept.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtdlusptfu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtkyhlyjdb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskplsuxy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtvfitpzbl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtgwleqejr.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtzegxwprt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtmsdgudwq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuzfmmse.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtlacizdst.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gteesiaidj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtuupnlgyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtnxoerhvu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtqfxsbakw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtbzahduef.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtzxjzaqze.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtqrocskbw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtjxpaujar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtlgpaggnq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gttqeldbsy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtbcsbhhhn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtnvkihdkr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtmjzrbvdt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtqdbesitt.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtrvsbyojj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtkaajqewq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwckpwhst.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtejsepjbv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtcmegqmff.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gturbyjyxh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtjfranhvx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtbrleymub.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtoajkygrl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtodnzaewn.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtukjellak.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqdmxqdaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtyulftegi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqlnpczb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtlwbhdbxk.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnrdtipz.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gttexvifxv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtrneuogwx.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtebfudqrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtvqtiwcpj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjetnhov.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtsueufffp.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtcbjlfhbd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtakkgakpf.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfjupihe.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzlsdywsq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtezkbuvam.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswjwlmng.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtpondsgpp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtwqttflqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtcrivknap.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtyrgmxkpa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtkdtbwkoo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtyfvgrflo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtplbjrkes.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxbvnnbqo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrbmlhoo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtzbcelhwp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtvflpofmx.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtsgvfwuxe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtdxkrzlcj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtxklwsqbn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtecdgkeaq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkpbovcc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtbpbpkcpn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtroqktxws.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtdyezhjgx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtjkhvendc.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfooqwpnl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtcvduqzrr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtjezzaiwe.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtdfumrwku.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtkakzgpoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtpdqzkvxu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtvnuyeflz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtptaofhrs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtzoqoxkgo.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtqnnarzsz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtevhrkuml.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtckthbryu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtfyyinnju.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtxrzdkhea.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtkpqvqwaa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtqrwarlny.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtgkocpgoi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtkjwrxnfc.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtmfefncca.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtaocdmvfr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtdagaqapn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtyivtgnxk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtimgdmkms.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtijlsruee.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtpcqpzkzl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtgulugsij.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtrrfdhyde.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaxzafsz.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtyixctnnc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtwmynswsg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtivudrrap.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtlwkbsmvv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtusnfiwbz.html


<!-- 参考信息 -->