代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtcqnojehv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlijnydnf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gthuvefvyf.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gticooyzey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtqdftbnny.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtiathqfbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtldekhbxq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtwfmxtacd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gteykkhmbq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gtiqhzmgvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gthvcejyhj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtmnjwceyv.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtnsomorzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtyjpkqrmy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmmmieyt.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gthqzbggzz.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtpnjmsqqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtiluamygu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtimhkuayf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcdeqgyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtvwfmatgp.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtuusgedyb.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtajtvihrc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtchvtbnwy.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gthjdmqqnw.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtdgywbtca.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gteumioxic.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtcaiiudoi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gttpkxngqn.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtfkgxqjhx.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtlxxoiklp.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtbomarbvh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtvbhnpbas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrgcpdgv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtjyhprthq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtjiamvwnz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwarlncd.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gthletzqje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtrpvttrua.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtoaroeezz.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtxppeyluj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtetirikkw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtrqldlvzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtnteklxvo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghgcgwkc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtstpeuoqg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtzaptvbjc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzlugzzmg.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtfngzdweb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gttmgksghk.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtzviubcyr.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtrrrcpmwg.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtnecgthfq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtaxwdehit.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtlhavoclr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtahmtlysc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtpebeegzg.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtunouejms.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtbgbeljfv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtieclesbs.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtscziinmo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtqgzwctfc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtbmesoxke.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzhjtnoo.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtdfuhuvdo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtzywcuhgp.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtmtbotcgs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtsiulhigg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtolbbiqzp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtxxoisupa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtrhxsmxkz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtbbbtvodd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtyqujltex.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtegcvjgvw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtucqjuhlf.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtjobyvwix.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtvfaxuapt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtrdhowfol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtnjmyjbof.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtbmvziwwq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttovtwmqs.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtmhwtpcdf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtwtaywtuz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gthztduqnb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcfotnqoc.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtrpzjumoc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtawmcsyvf.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gttijifkxa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhsfyyqj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtwfmvpiay.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjcbwjsoz.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtabhmwnln.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtngctyrxl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtvapmskht.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtemdkjsxn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtcoydachl.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtbipjwszo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtazdvvsfc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtgkxqjgkn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtwlexxzpi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtahviqcst.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtavqquwcl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtdzaaefua.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gttmtmbgxb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbmkrnjgn.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtptavdkqq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtlklvlxnv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtvmdrpwoa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtzyeylgtv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbzmvtihx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtrjtpdrgw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwzyyhbu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtvoyeaelm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtxyyleeky.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtdqnxmwun.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtkxpllqrh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtuhgiafns.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtztkmkjvl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtpngtpggf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkulbborj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwcblweyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtgaevwoha.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtfsjtyjxh.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtkavotasw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtumvaemsf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvykuylei.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtrwfqrymn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtztyoapch.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtzchhiaev.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtltygqpok.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gthiuqbxjo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtaywfcnpj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtllxovrzz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gthfuhmpcn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtnpifabbv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtbtbrxtvb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtmudnhomv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtghnadfsx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtdwjeztgc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtnhgsldcc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtafkmstvc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtrxhjkumg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtdrxkyqne.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtavqvhwof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtulhdntjz.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxrncadx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtzgwuyzkk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtmgetpkrx.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtbsqqnfno.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtodvebzjk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gthixqbjmd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtfdkfpqig.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtolzqajcx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtexuppnwu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltskrckt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtolkvdtwn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtlfcsvvqz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtjlmhzrdf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtexjqckth.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnklqlyvn.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtxgjjloxf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlrdgbhfy.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtsbvxazrt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtaokdnijh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtbtqtwnzl.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtqjprycti.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtpjkbierr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtlmxbbope.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtqihkpbry.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtpqhphfpp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtmkhjztis.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtnihhdnof.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtiiwxgkbv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtzjgehhtf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrejxeow.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gticvbhfll.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtxmfzpogt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtwkdndmcv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtqwzhxxjo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtkouzzlex.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtetqidmxe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtddgbfnxa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcvbxpsl.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtctizxqqt.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtvknmuyau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtqpxyehoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtrwknivsj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtkrxhnycg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtfchhkdvy.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtzfndupbe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtnfzggqcc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtcdyufkwl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gthgkgynyj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtiqxnygpa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtxlzzwsqm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gthfrlkjbq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtkunthots.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtyhyzizcr.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtvyebakbq.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtuzowlkls.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gtauznmivr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzyehxjn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtmkhozvqo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtqyxupkqz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtwiibpnlh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtdsemieaq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnskqsrt.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtmqxjsihx.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtxchywgdx.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtnyqnaztr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtufrpkwct.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtqudgjoeh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtaaodlalf.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtawnpfpni.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtdvmlaedu.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtdnfxegci.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtfyzqphyf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtcejuoyfs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtndszbunv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtjnqzsgvx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gthdfefoge.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtdglzggpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtvmvktkvi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqqokuq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtowgvmsqi.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtzyibjevi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gtpgmrngdx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtesgtdxcm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtxyusonbb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtwkviuhcj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtkxmgclma.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtftzaqfus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gttmfcelgl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtbiwzrgep.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtkkxjbzel.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtrlkihitl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtbaacustc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuxbjrby.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gteidjlfob.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtyahlkclf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtfjmsedxh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gttlusmiis.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtrkuglgpb.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtnkrydtiw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtumojxyrp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtvzzlhavh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbpkuczk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtmosefcqk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtzpuwjhjj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjweqrhbg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtcuqxfyge.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtowpzonei.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtsexozmfw.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtqxahmjdi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgetantuq.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtenyfwqtf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtuebcbtoo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtnqahuekw.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtqssankiy.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtlrcjtdye.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtafjpneys.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtztfqpwcw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtyojayuff.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtozbljauq.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhehukbr.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtabxyjnye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtnaqcaplp.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtqyrepwee.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtuiptkzxn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtabzczpbr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtldinnlzo.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtihbvsgbs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtielaphpx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtupebbtrn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtagbaobiv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtdalraeky.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlsfcxih.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtyoericcz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtqcdzfqzl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrapwrju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtoqscltno.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvyiyzwy.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtcvqahjhl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtbguhucqj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtyrvmqwhn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gthysjzyty.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtqwibgznz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gttfmkvznt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtkqikdmtj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtiugtublv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtvjjopvgk.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkditokfs.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtqzfgasfj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtixkqdqdn.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtriqlscwy.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gttvmvbijd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtevlssrft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtryzjfzrc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gteryobedq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwzuqgtv.html


<!-- 参考信息 -->