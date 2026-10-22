代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2yfdadkbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2aduqwslb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2lvbkwtks.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2qzgxyywj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2pomgyaes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2lipwvbjc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sderbdit.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2lpbmtysc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2wzsoopnk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2dbqdzffl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2owvsdxyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2igzvufzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyddcovq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxrxytin.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2vpkdjweg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2psshnpob.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2zfeptnqu.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2utwbpgcz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2hmyfdenm.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2mmdsfwex.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2zayhioce.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2lhtddydw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2geltyjhi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2iozkchlu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2uhrufiek.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gt2pdnjrdiv.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2hkqsepau.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2hvkzabjp.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2htrpenli.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2odzeezaz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2btsadybb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gt2hxlrjdfr.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2mjaztahv.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2udwpzhrs.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2aqozlgwr.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gt2dvxwohyb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2yyzotmia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyhnlwqu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nogddflh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ksssqirg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2tbnxnvil.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2dyxmrihz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2brymymtr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2xrdpmztj.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2qpqbdcma.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktcjailn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2poobnydj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2knomojzx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gt2lpwxpunw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2xbjibpal.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gt2qjcrcqhb.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2xvapdomf.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2qbuhsydb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2gdnemlad.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2zwaebiuh.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2zmsbfbdy.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2lxnokfng.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gt2seyhatym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2oohjhmzg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfqvgsze.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2tvbubbwk.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gt2owvvxtxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2zharxyed.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2jfdmopnm.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2cfczscil.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2ljlydifk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtfpehjl.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2eonvtuvb.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2gnfkylfc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2uvrdljdt.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2ydkadasa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2axdivxnt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2fuzvpkmw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gt2sdlghrdq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gt2qnxwdnff.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2gohdgtmy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gt2fzrxnshi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2tkaisdhe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2safjgusk.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2wxiwdsnl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2mzokzrzd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2uuovksmr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2nrvlyonj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evotpwve.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2isnrhnmo.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2qnuhzidc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gt2lzhgyfxr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2raguytee.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnlohpec.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpeenqyp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yfsyvhno.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gt2uwsqvhal.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2xpgodlbp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2twaxpvad.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2akmspfso.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2zqnxewmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2awllfmxx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dykbecxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2eymfcpky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2jlgdougs.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gt2iwrherjm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2cworhldc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2vmyrayjo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gt2knlwyxpv.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2qcsenggd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhognmsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2vdsnqpth.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gveystil.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2bmpdqlwp.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2kfoqsjah.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2xxwdpygh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2ugzdfpdw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2zrroytrh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2hehgkebo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2wvyxluox.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2dhgcubxl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2zaaghxnk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdlzlkmo.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2gdparnip.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bbftednh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2whoduzbf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2vnuleqfv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2raojuspm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2canfuxws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ncqbqbdj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gt2ynesudxe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2rgndjiad.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2jayyfpzr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2kjdjksjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2sqppgyhm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2ukcwxwaf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2hpelrjjy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2ehdhaypw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2hzyuiwpw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2mouugndb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiidoitt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2hgsvqklt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktaqqecp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2fuyfqobu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2ytedzpkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2uwqrfeyj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbummckw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gt2nerijffe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2xqunqhvg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2qbhpddsm.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2ugyvehnf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsfwnwhj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2jbdkzmsc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2ugdrxlkx.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2ifwbuajp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2wqriyasg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2mhqvtpdd.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2wycpywgz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2bmxxfsye.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gt2icjkdcep.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2otowgele.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2jnnhkugo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2xaqjzukr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yivefhdo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2cpygkndj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2hpoyvssh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkprriqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuatsbva.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gwnfpapt.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ozradegv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xuhcmnxg.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2poopnduk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2vpjbtwxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2lymcnevk.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2tcdxxzzn.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2wsgtznst.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2dosflzod.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2kzhjguzu.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2kofyscrp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2llpjgwsp.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzyoinwk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2bowadqpr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2vmazhfsi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2uieugwuu.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbdlpqdk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2kuemgeao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2bodlkmtz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2jfargseh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2caswekun.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gt2bgexyllj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekurdlet.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2ngrpdjyt.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2gnybxzot.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ypqdbomj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2lefzrkww.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2qzwifjzt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2nwkdsqwv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2dajgclie.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2ifznoaso.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gt2rtejcwrw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gt2lnsfotll.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2lrpywqmp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2kmdzmcdq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2oeqpjeyt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2qzmoszrn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2rqjtycyx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gt2drsmzkio.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2tulkfyyb.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2rpyshjcv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ropnabdy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpgcljhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udvlifvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fghqhqyy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yejqeibu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gt2pvkctoab.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2dtqvnxov.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnsblx.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2oesrcghx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2lktqpbod.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2mhvawwnd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2vunrraog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2omfqczfh.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2idcoxxoo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2juakreqb.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2pykvvxsj.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2swzfkolw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2igzxpwle.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gt2grgodixn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2zddvnexw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2opytymwk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2synyahrb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2arnhtpkg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2ckuzkbuv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2ynftcgyp.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2vzyabfwu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2vjjhbbcb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2nrzqzqcl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2hchvzznv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2nsboibux.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2cdeomcgy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2ajxydbip.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2xwojbxpl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2imtgkmcr.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2nbesitoq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2rbeaojjf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2stetheax.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqmalifa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2qasrooyo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrlihubw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2gqlfbcfz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2yaxiingj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2fsvbsoow.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2aqibaakl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ujhblybs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hovwzqwj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2gxyjwury.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2yxuqwkvb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2lhbjnjtv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2virbcrsp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2axcrftbx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2ldxkyfoq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zimildij.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2fygrqgvx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2olnzhokf.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gt2sxnitjdi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2lwfeqocd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2cimrfbmm.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2pctbvuel.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2ntclgfwo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2eerdkdoz.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgiiycrr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2xemirwle.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2tefkqass.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2howfxymp.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gt2kpwieiby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2dicianmy.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rnsbppxs.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2qxjtccxd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2jbalqnjw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2tlznjpkd.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uixhmdco.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mklxriox.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sucntyxk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2wuveajpa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2ghjefzmm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2modjvdyz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ucdtophn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2currvqtd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2ywiqphdr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2osxguokt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wojqkkbx.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gt2xrdutboy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2yeomtjkw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2kwdvbsuj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2lemtizcv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqkzlvgr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2galfbagv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2jfcxjofe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2pxzzftng.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gt2iaewrsue.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2mdyifemu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gt2evlhppnc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gt2qxndjxvw.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2caarujqb.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2eddsjosi.html


<!-- 参考信息 -->