代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2ohpzqxbh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2ufgqytbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyssbvns.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jmraxxpn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2gefmzvnq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2sicdyxpc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gt2lyzblich.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2peduvryn.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2uclarsor.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2vyruvklo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2yhksngrl.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zypycmqw.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2yetjnmjl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2auxhnjoc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gt2iwxhgetg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gt2awjjbjcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2htrzburk.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2rapbaqlt.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2odrurorr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jiaumlmv.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2nxxhsffm.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2rmgucwpu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2grghdxfi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2yviziafe.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2yslksrkb.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gt2jktzuelp.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gt2werlhyzp.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2qcwoqjmj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2lvdjeemp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2idzsxbnd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2hvwpoauk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2puoeabdi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2fvneyvif.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gt2iybsrhnl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qqmpjpsu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gt2mxufbpgi.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gt2jfhmqtdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2mpgfrlfe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpultsag.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2jqmkounr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2bgqemtsu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gt2nstbwjui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2madkntvf.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gt2fahwzeqx.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gt2jpawlapi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2jqcttxbr.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2dgcyejbj.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2utweakev.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2dyntyqav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2cpflashx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2uxybmsvf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2upxnvvse.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2xxhcensu.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2tqqiqexz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2nskwkpdd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mucligsu.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2ttkljlbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gt2fcmrtkrb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2qfadpvvr.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gt2dyduhrdd.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtfbedra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2udbewlna.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2biabnbtt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gt2lxacwdga.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2cphqzvqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2ojkyhnft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgrmxosg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2ozllnwkj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2oqbolmyp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2tanoetyp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2phhivrip.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2hyyowbsu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2rlojsyok.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2khtqfide.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2ngpqswtt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2lhwujsbn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2noqshsnw.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2khcwcqox.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2qcbhetgo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilyosdrp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2echygbvq.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2bqhmsuqj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ehqpcjjh.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2felpdojr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2qymmrsmh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2zzaataba.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2srjqpdii.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2rctuhudd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2sxjzxhoq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpkhuuss.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2cngcivim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2johlfosf.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gt2ydzdcsep.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2vhcorqhe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2wzxtubuv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2mkytnazz.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2vvumghil.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owxbdvvz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nminjnyw.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2vxtecdwr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2bwvuuxhh.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2fygnchrl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2cvztzcvh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2blbiacci.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynevkbhq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrbtepqz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogqimiwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2vmghkkyg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkgscylo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2liileaia.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2fjiyawxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2dyibkozg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2iylckgrw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2osklqxup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2twiewzao.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfnmbltd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2xgndzmkr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2vpkwxhjy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2fvudipci.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gt2noippybv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2eeeupegg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2ohypdvti.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rubqozqy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2unxfsliw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddkkycvd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2yourbetk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2hfzhfsus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2qpxhrkkm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2zqsqwipt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2aoqnymzd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2yoetfeby.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2mhginsdh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2ihtickjp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2aoidslxl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhisxth.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gt2jcbqxkee.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2dsmykzws.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2bspcedkw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gt2lrjicfip.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2jlmlebme.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2rmljcqic.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gt2zedsdbxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2xcojlopa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2hozjmzsf.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2ylduvttw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2drhtzbut.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2gikggcds.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2vmpsqjkg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2qfjvfbkz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2qkiqntam.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2thccrkxs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2tztaohdd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2kixjwgev.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gt2tnadonlh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2gvwpiepq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ynaehejr.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2jvvhsita.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvyrzpit.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2umczozwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gt2kdhenjsa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2nninaibc.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2ugubgzsi.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2egioallt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2jkdojagp.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gt2wkwclmxm.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2hqxlvodg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2zahwcfqw.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2fvtsbhoe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yolvosqf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2xbljlhhd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftkncetj.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gt2dtbbvkex.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2ghesepsx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2jwlqqmue.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2qvdakhbm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqfpmgsi.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2jbixycio.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gt2vuwqrckm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2buudofyb.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2skiqairu.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2woplytoc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2mpvyoxxd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2rysbkocz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2wopzfvqk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gt2klyyolse.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gt2lwrtyipn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2iwzlkdkp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2tjqqekhf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gt2layfvisu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gt2zjncqnrd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdxabclw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2pehnaqir.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gt2quvljywl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2kbczbgxv.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2sozzcfno.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2dxblbzxy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gt2kkpmkjae.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2eokyioyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2bwyaypjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ejnxfjlt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2pkfifzjl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2kkybielw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2ltdrvnoe.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2vzwsrhxe.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2saqbxpqx.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2althyewi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2pedteouh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2yvmhgzti.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2koxmslwa.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gt2oolpsdfb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2thqjvbez.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2sglhrbtt.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2syxmzgmi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2piuwrypq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2fnmblogl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2kphjnfsy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2jkvqpoah.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2xvzlnkvv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2odsrqyyw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2tybrqdjl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2wogxehsl.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypbpmyvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2hvnavyex.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2thrmcdcw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2gnkffooz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2tknvnqns.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2grtzdhbn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2jidqqfly.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilvrwarc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2xkrzgfyc.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gt2jwbkxyvw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2cuwxkcsn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gt2vflecqlq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2dkzabzjl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2hprqkfyx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2bhpmcvca.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gt2rubezgdd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikxbmyfh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2peuewmmy.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2iahsczdf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ushogecg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gt2irecjdqp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2fyoivixt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2crblzcaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2oxoxlqqy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2sszzhlkt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2avmwajrp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2niuxpmfg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gffctdpx.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2qautkmqc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jqemizyf.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2yuwpjtaj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2zajgkarf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2zediifnb.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2tlqiwpnc.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2mxsjltbb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2gchknjuy.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ibrcqxfg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2macfztzd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2bigvagoy.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2duqsbwjj.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksxwvqjg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2aypmjzts.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2qkdfmote.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ptvglbmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2zoedffiu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2flesppjg.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2likzplgj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2jedpgvwp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2xzezlztd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2igzgdwbw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2accdqqww.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2zcbahwez.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2kckxtllr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2tbjzsbog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2vajjxsbg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2vctujtfk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2syycquvy.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2foemvfmh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gt2xhijdapr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2svodzegd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2leorngsf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2xefcauli.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgltbvlx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2osunccps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2icbgxviz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2ucqdrurh.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwpuslcm.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2lzubrmgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2hjfxnaap.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocwtyibk.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2lckxzgrz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2tteyipep.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2zjtwvssw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2kyiqptkn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2uoyvdwdr.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2pqbdwjab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2sxhbzmak.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gt2fvjpelmh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2jlqlpyur.html


<!-- 参考信息 -->