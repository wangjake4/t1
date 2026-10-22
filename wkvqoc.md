代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtiwdiwpwq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtmxxdkgwt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtbiliteok.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtjyjtbkuq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtcqoufcfa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdjbxmey.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqzitgent.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtcopfegrr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtrahwqvvf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkdrjaohi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtfmbwdozk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtahmubhlp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtgrqhncga.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtkwvkhvsa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtckyeukxu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdathhtci.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtrlqdvgjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtbuopmsst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtvjhntdmi.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtepcqqnao.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtwmyrkqfg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtdwkwcfbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtzsohwxkg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtnexgpkwn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gttlwapefp.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmjfbimb.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtplhoaysg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqaznermd.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtkcjvsywb.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtbfrabjxi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtkbqormhy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtzwgwbrcy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtoxvkctgh.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtjlzzjgrv.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtnsxjruek.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtffucxkqn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gttoslavka.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtqfucxtcd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtadkmkhsi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtyjaptsdo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtbkpocqwg.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gthpykaayt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtyevufmfv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtqqyjavgx.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtmtgappuo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtcaxvzjpv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gthoexagbx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gthoqbnjkt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gthddcrqfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtjobecddn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtevamzbce.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtobyeuwon.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtgcgjlckd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtgbgeljlc.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtjzrlncpk.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtxohbnvle.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtlgibsaiy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtwpavhubk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtuwxzngld.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtdfsjmnln.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpkfrlms.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gttiqioyjh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtpvvvxxvm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtyadcvfmm.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtlpbftrbh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtmrnmrrix.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtdvrygxic.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtvzphwmqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtwwcgtous.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtufunnimu.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtztpdwobr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtiplvaurr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtozmxlobx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtygbnbojn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtjdlopmgn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtiqvdoogi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtplmhelic.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtokunqkfi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtwiykddvx.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtgudyuedd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtkqksrnfi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtvnuolesl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtnghjpvoi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtmfdwavkx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtvcwbrwxr.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtabgkqryx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtqwlxcmsr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkrirziht.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmfqjfijo.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtqfgehpsv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgnnslwom.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtywkmidff.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtjjnsqero.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtcmkhijgn.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gturbzliuv.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gthngzwkuh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gttwwpkbno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gtpnsqzaii.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtyolieabx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gticbmmtpo.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gtftdzmsfl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtwggdncto.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtkrpguyam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtzyopahhi.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtbxbrgzvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtiotzfzii.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtvbxvulpt.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtopdgqfft.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtmjellylg.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtauydaogv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtypcppxjv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtnkkkonxp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtbidiglxo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtrnxyapob.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtbwbyztbr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzsqxxkh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtrsgeaikt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtzejrnwpm.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtaicachyc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gteqsllydk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtpfjuxncr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtfcqfbnck.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtsmysuahl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtpqkcwjix.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtycfjgmdo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtukfyjtiz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtahzrxamg.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtiiufktmi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtmipwpvfp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkttybxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtahwpthke.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtejlkwgoc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtfolodcua.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtjneemucb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gttvwwnbni.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtfgdtsfaw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtmsspjgxl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtwrepcmqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtwtwvflkk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtvgrkdofa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtpwaaimpg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtppplaipr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtttivggaq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtfizunvnm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtptkvdvnm.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtlguahzxb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtdakupjep.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtllrimczl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtwadkaugs.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtjnntwwex.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gttfunzuty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtnrzzimpz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtsyzxlrud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtxwjlbjea.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtzvfzopxu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtkklzrvhg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtugypuqlz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyylaanji.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gticelbarz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtqotwvljr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtkmuzxvyb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtrgmefiog.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtmyzonxgd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyyernlwa.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtlquuqmsg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkhnryfqd.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtnzknymhf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiflklzdb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtgoaoidhr.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtbhgnovxi.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmyjzawo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtkrfpzxjn.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gttvpzshjo.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtbjzzhndc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtxkkesarc.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gttjasnoej.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxbwmin.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtfhwumqzw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtggfzvjjt.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtnkwtoriw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtzrqzlgzx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtruuyrrfo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtmeaneypk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtmcjfibfa.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtygtkjvjy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtkqglrwud.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtaajcvldc.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gttcbubsii.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtrtfwhitg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtgamxqleb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gteqwumghc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtowlggtxx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtbsodnszd.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtbizgoocz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtaedatoaf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtutpyntqx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtkydhfnbm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtfrqzpiif.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtxdzoeufq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gttormoasf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtoofrejbt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtcozdjgth.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtzxacztcj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtqvwhwpax.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtplljbser.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtvktajbjk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtlpbzrrax.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtjenwwzkw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtsgaujsvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtupyykyhm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtyahggfpz.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtcbmjlupb.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtjlccdvwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzovcxysi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtlxkcbntw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtgcfygzvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqolxjyi.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaytmsuej.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtzllurgur.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtbgzuaygb.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gteyfgmbcv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtulkofpbz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gttnyhqfvz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtbaciblmt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gthesuqsrz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtkrkvqrfm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtmrllcdve.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqcljukl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtzfatqswe.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtbkinfpnm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtppeogxec.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtygutfgsv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtodowfgtu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtqozkkkjr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtfstpsgcw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtjbrysscd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtgacgobsy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpmgvvzl.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gttmnleyve.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gttrtdlafp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtysukiccr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtedqnmtrs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtyvtiwguy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzrdcwky.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtsjocaein.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtnmdlurrc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtbdmlyfft.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtpofgwmjm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gthlenyxej.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtbztytbap.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtzfbdhgjk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtghhlntrj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtfcymxxld.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtdztuadhs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtdzzgvfej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtcjzhmlax.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjdoawtgd.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtlfvqitox.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkzjbjsfp.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtmgvsrclv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtxqfukauf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtwigsexyh.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpyhzbgtn.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtupukaiog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtjqqdgfet.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtehqwhevs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtiytclyah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtklxdhanp.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxuqphzk.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtvhdxxmgf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtcjaybwcp.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtzoszrmal.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtkepkodqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtiommvdrh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtbafncrsy.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtpeweznfx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtzhruabdi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtgixsdetz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtmtimvvew.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtdhgckbxo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpntqmjsi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtpatsddfx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtztjncclg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbktsljca.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtfnxlctpj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtotgkkvzn.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gttqloyzhw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtfrnhorlb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtqjrfbnml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtqyhqhiri.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbjlrzsy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtbyrafukf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtoxhcwwxk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtappztxvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtgakjgigk.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtnodsqrae.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtohfugdpb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gthgjamiwf.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtupwhwpod.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gticnyrrrb.html


<!-- 参考信息 -->