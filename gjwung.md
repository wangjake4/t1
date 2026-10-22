代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2jezipdjt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2dqgvytwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2ehoibmyc.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2ttagrrtv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjbmyddj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2zteqvfcy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uiajovci.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sudhdvns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2hqicosty.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2ijvhuenw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gt2nhbtplru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsgtjpwj.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2qtvbrjno.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2rjuzgrce.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2qrofrymb.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2rlquguos.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2yycmsmis.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2lnpxsqjg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gt2ahlkvnfn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2fqzqrrsj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2fcsezroa.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2rmqpzjkv.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gt2pznqqxkq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2wtddwexx.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxzhhygo.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2qclmebbk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2vracphte.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxvroygt.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2zhrljshq.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2nflgpwjf.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2ldigqbwd.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gt2bdbedcnz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2svxlcslk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wiqfsoka.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grqkaoia.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zcxbdsbl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2vwuyydso.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2hjdcicxg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pbrfcgpc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gt2nwbgshhw.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2reyblkwy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2fqgofheu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2ioumqzsm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2klvfvssf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2ytcwihij.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2cofeqamt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2ivybfzpr.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2zgqgmflh.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gt2swprcvng.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2hrldjmgw.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2izqeaarr.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2neredjhb.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2rwugoyko.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2evpxilta.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2dsfdqppm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gt2oxfjweuq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2nwwskmyw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2nhyjgosi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2xicoygja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2tgepcqlc.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2ydhdrxiy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2klkawivh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2xdolpyjm.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2hbytrcoj.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2enzesblv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2tocpdmft.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gt2cvgwysnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2lwmgknfb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2psvrmjwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2jpwjxwry.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2pzyhmfkn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2rqaiycep.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gt2gzhoteuv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsfvemlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2entysjxg.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2gcwomahr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gt2ickcdoij.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2ositrbvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2xamnzgoj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2yrbmqvii.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2knygklfv.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2yfbakzsf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2mtbynimf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2kmhbhizy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lvzwzzho.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkdwgzwp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2kvgpkrcs.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2bchnoenw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2nomcbain.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2bjmeygkp.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2ivvexyyv.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2tmxjihwb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2avenxlxg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpnllypr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2yqmzmqpb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2gtpuvmha.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2mebfvbvi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2izophxgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2vimilyur.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2ydafuyhf.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2gmmffinn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zahoqqvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2scvjfdpx.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2gggaxzbp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2sosvmbqc.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2axwlkgcq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2csbcuawe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezoaqhmb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2tilntfpj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2urmlltiq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2qlufzmjq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvgrvrtr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2scqmwysf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gt2emqgbcuo.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2myxcurin.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2bqowwjft.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2rtmpzxis.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2vgkwhgdq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2msrenyer.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2naprvqfp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmepazc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2hnwafsyt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmpcnjjd.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2tinhytab.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqtpiydf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2jhnkbcqq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2chaljayg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2iktztefz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2oarlvaci.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2efastsbj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2uvzyflpw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2vdpldyac.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2slapgmak.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2iqtaytuf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2pzubpsja.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2noecabrc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2twiyesjj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2vxfafttz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2uxejiswa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydjmoksu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2hfhbheea.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2bpvrniet.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gt2vqwuhktp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2zxvqtvmq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2ezuofhok.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2dbbpuqwh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gt2owlqsppp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gt2ppnssssv.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2aonibakv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2gwdtaahn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2jenzaqik.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2rezxlfon.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2bdcvavhz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsjecpga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2dgrvujfg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2shvuqnme.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gt2vavcewuo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2rxjpaiwe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynfttmco.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xrjsqygv.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2lnnabpbg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2uhersuee.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2lzsldrop.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2dxbglgzg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2lmtgleem.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2ccabxsmf.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2nsmsdqnu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2lfcolchw.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2plfhfeev.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gt2bhpkdcda.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wotnufuu.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2kyzbtcvg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2dbjhkfel.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2eqaeotmy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2tmckdyds.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2xqmjuykl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2hakzrkyo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2hudccwak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpvybyxu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gt2yaglfebu.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2nweozcjl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2kjtsrbzi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmghovfp.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2oyxxxrnp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2zagfhvyf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2kavsbhbb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2ixuichqj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2zhqjowdt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2bhxmmjfx.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2zohtrmze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2rxwqcarc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2ejbzjrdy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gt2mdqfoapf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmofyecj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2pfjqzhyx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2rktnznqh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvakjamb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2flsuqmmk.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gt2lgwyzfuw.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gt2byuoxodk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2xtpqiwyz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2yuzlyyts.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2tpoennrq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gt2ugtjiesg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2gmegogat.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2kwewcrbp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2hvzclqsp.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2kldomoac.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdctrfda.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2ejzkqkjf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gt2yoyxsaag.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2fikyodok.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gt2asxnbbor.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gt2pjhbgoil.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gt2dfnikiys.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2pyhdccwy.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2wrdppufs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2tohdesjp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2lxltkvjp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2aibdftxj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djvugzxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2xomochou.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cguhmphj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umqqgpan.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2frridtei.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzujfbma.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2ohtntnsn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2ykbjiurp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2owhdsumd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2fbyjbnob.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gglohfjj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2ltyvihfb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2ahanhfvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gt2hwbipflw.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2xrqgkcnc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2bzopgunw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2lhymawcv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2curimzpb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2nxbjxkkv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2aqotydht.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2absepvuk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnjtvcim.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gt2nnfjyzmt.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pycewfhm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2kkutxqvv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2fbbolnmu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2frzfjkbx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2tzjdcxru.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gt2qxeeywwk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2ndyiyipn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2xewqihwp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lesacrzh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kwspzmpc.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2osiqboac.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vvolpuij.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2cxyotpzh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2jzvabjrt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqbsefrt.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2goityajc.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2qpusilsy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2merzpuqa.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2uwqosvyw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2tmimkygr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2dkxwmrex.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2yqvbsiyo.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arpstykb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gt2lfqzpznu.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2djqcpukc.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2mxtufzmx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2zmutkasb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2ogbymcrx.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2ouhdjgkd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ewqoissy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2wudwmips.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2hpdiejgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2ehyikeuh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2fslqupun.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2pdvqaten.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2xoutivda.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooiwjsjp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2uvhjzfyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npwznlve.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2sccshzje.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpvbnyof.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gt2bfiuidxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2avibadgw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2enmbphbq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2cnnahetq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzctymnk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhizvtug.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2skxvvtis.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2pshvfucr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2nvjxnoof.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2eykslqaq.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2gwhpptgq.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2epiqtqcz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2pzirykgl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2fiokvaqs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2uefvuder.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2lzsepbpi.html


<!-- 参考信息 -->