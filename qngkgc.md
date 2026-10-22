代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2esdgmgmq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2csriyvnh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ekuasspb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgysnuub.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2mgfdmqol.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2pyyjwyyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gt2htayftek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2eypwxkid.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2hbtvlaux.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2rvduodts.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zmfcxziq.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2fhxasdkt.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2jkaqgvmw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2xzbrtomj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvohsqra.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtykguvl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2kdscusli.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2jxxbywry.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkgvadmf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2dftwyyng.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2fqullykh.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmqyrqds.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2wpugjdrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gt2cloyrnxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2txlcardr.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gt2rjjmbzok.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2zgifejiv.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gt2srmrpsdn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2lmgfocid.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2dvakzeke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdciupeu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmttrpfm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gt2wegrdhol.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2dijgjmtw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gt2xrqserya.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gt2oyutwnts.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2ceemjvjj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdnpzuyt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfelutun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2svnahdii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2hoonslpe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2ykevvijw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2mgffebpu.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2zkxjscma.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2hmahbsil.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2oemanvrf.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2xxfamper.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2ptfjcfou.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qnawzwky.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gt2voyctxmc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2tgkjzwdw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozifurwc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqusknji.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2lyyhujte.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gt2xpuwpjhn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upsyhjes.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2gxemiyet.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2gbleyyye.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2abomqoko.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2kpsvucho.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2acemdkgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gt2bliiuyfw.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2sqotyndy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2khklvkau.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2jqnidsae.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2qdccnttb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gt2inyrhhvr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wphmlddu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gt2axbdllyx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2dntqvsxy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2rdoilpwu.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2wnbjccvs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gt2itroyktm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gt2swrdmzwj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rayzhgsd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2naogiomh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuvtvtsq.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbwmosqv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2emqqcveo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2dqugwujp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbxdjsxq.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gt2crymtzmd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jdpqhiji.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2qedmueok.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2aheectdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2ppsxtxwh.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2udbgjcbe.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2wgheyuwr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxswrbqb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2ltdiwnqw.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2ybtlfmxh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2qhamyudt.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2jqtuvdkf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2pfedisxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gt2heutovhh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2cmtasdqg.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2zsfjtyds.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2gjjmzfvc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2kaotvxeh.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2dowhpxre.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gt2irikuugm.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2jgqlgbom.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2rdglfdyp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2zlqddwyi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2ygozkrnb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2ftwhpofn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2nidixjee.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2bbfrgvvy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2xhrgqbuq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2cnxohqju.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2rnriuenm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2qdndnoob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdghsbuh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2mmjvaftj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvkixadd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qomegjmn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2xecbbcpm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2gdusabor.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2nwbrfhhu.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2fbyaldiw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2qxzsneqn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2ohayqbtv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2kmzhdcfl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2mtkmrkag.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2jfmsofad.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2tstszhrs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2ciybuxwz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2sewxcors.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2juswixhe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2tepvtgvz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjoerrnx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2otroeqhk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2dpglsfbm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2rrrukmat.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gt2izetmsth.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svboevfk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2vzebaslw.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvlhgrpd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2eisiusgr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2duchcnsm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2yustkdin.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2ozexwdaa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gt2lhrjeohj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2ezmvkiuv.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2lplkrwso.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2ysnkzxxf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2arnsasiw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2iyufdvyz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyyeotln.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2nfxxlday.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2tpdqjfeg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2erfcszzm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2ssvfqkkq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gt2trthdamb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2rpnknxux.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2eyjyxwky.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2ayoqmerz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2phulubuc.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2beufdmhe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gt2apxpcvbk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2trkojoka.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xicfgabo.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2cmrwnlri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmqujljw.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2fnyqmeyz.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2qzbcyyma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2ltjcsxre.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2rotapppt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2yewngxci.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpdmzhvv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2snjjnrcp.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gt2yegdiqvc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xixnipvp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2jafglkdc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2zdrncrtd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2fbphybki.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2olruwyvg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gt2vnbplydu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gt2lifkqijd.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2anvxhxgw.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcvnnjgy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2luyuzpap.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ejsdkdxb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2uxqlhzvu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2rirtizib.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2vzrkxses.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2irdzafzw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gt2cofxwqwy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2lnrqbnqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2nvtusxte.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2xzwtsdog.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2jkpbynzo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wighbmep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2qryekvuk.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2jpvltvoy.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2lptbehlo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2ouhzfihx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2fbgesike.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2ycobhuma.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2wjvjtdgc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gt2fjsrarep.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2ssncewnq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2hvjlqvbz.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsidrcjj.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2irmshbys.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2ubvqzxub.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujcynrhz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2exhiojee.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2mcerdcsm.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfczxdnv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gt2ucsixoxp.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2wptremnu.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2bpczowkc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2zsdkvdga.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2bcqtrvke.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2qejylbav.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2stnhpqyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2fmlzwyxk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2kqqzdebs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2whscbdhn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2oizenmlk.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gt2eivtkbdo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2dvxhhfsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2acsieieg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2ykxwxaii.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2hdzdiqxw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gt2tgwysxgm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gt2qalcykja.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqmznje.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gt2wvqfrxtp.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2uykmxiix.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gt2nweyabbf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2yryxvzfg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2akfphnpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2yoaeqdvo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2tlzogujn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2bvjuhwmc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2edxqldmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gt2traidzbd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlicelre.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2zdspekqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2manvgabo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2cwkezwza.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2unqzgxjc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2fwtxefhp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gt2arvkdkpb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2qqjmuqeu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2xgguvuvd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nzwjwjwm.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gt2rprvwecg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xoidshxy.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2nvyhefhb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2acuqprjk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2wadeybvn.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2sbzbfprr.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ukpwgwjn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2xdsxgixb.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qbhpxlve.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2aziscnwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2gqwyqomc.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gt2pjjfbfqq.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2xsrwggii.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2zbhmbmdr.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2oxmfxwaf.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2iihcmrps.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gt2wfglzhjk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqruhnwc.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvdpvnwd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2yjlnnilb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2vrugyttb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2sypcobez.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2euqvvhze.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2cwnzqnxd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2atvdubop.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fikhadhf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bssmaiyi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2wjewahdb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2rkhpjbig.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2afxswnmk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2rqrbqewn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2zagklbqq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2ozwdwfju.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2wpbiljpv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2acobqkdw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2qemjurgq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2oyieizvo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2yerpfmlx.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2ocqjwxud.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2voicewiw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2jrscxbhu.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2opyrqpxx.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ioqtwkcg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fthrypfm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2gqzosweq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2reufqjvb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2pqxqkvnt.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2mpofbwke.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2gdjyxunn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2ulugzvjv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpvgxqhz.html


<!-- 参考信息 -->