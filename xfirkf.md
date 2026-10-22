代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2hnmrcbfy.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2pmckdgdu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2odfpzjtg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2oduwmemt.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2jftdzgjy.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2igpfzqor.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2eppikgnx.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gt2dueqrnfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2xzzmoaod.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jcclqyai.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2nmgdbipo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2izyksnqw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2gewloaqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2pkitcbut.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2ranrwzzg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gt2vxejijim.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2wotujwiy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2lraedtrq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2henwpgos.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rautapxq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gt2hieaqkfu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gt2ycywqglr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gt2pegzntir.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gt2mvzsfpmu.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2lvhuhcqx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gt2znwdstnf.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2rolkvlhp.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2wuondjef.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ncyzqfxb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2bmemfxzh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2xbdhyohf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2pxikwjnw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sunvrmqp.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2hiaacvrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2yurugzrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gt2sttttiag.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2zacvtcec.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2emciuwsk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2ahdajmpm.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2ebdchlsm.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2dngfxzvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2ezrtujng.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2phokkmqy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2sznfixne.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijkgfzme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2tewgdxsp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2znzcjrhz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zroembqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2awialhho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnwlbthj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2jhmyecoz.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2mfnsarcz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2egvqfomk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2gfaurbuv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2kbpdbfca.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2chcbcoiu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzccwgoe.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2rhrksjqm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2xqtgdlqm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2atemwkzq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nsepavay.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2jylusbqe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2txqqcrgw.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gt2obqnljme.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2tjylzxlx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2xoakqgdm.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2jgwlwfyo.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2gqxqmorm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtvbaclc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2wnpdmlrw.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2tyjybtcn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2upxfyjlc.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2wqluyfsf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ysclooao.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gt2nairreth.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2nanefelz.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2niwdrvbz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2kuhbcfpg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2kplzwqvo.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2nzfjecox.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2hhpwkelk.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2xrtebkzw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvdtmlen.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2mjtbovxa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2zvcxplou.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gt2lgmuyrww.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gt2noxwlueu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2tvgnjqsi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gt2rkkvtpxi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuvwudxj.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2utqohafg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2fgukfpxr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2cnbbmqxb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2prnafrxt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2tbvpgevt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2cgrrlaoz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2pfyetuuq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2xbnbzxzf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2uaonensc.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2ftltbhfc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gt2seycaxyo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2ajkcxdfa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2mlgywtzq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2xkedxoir.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzgkitzk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2izgfimtz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2abkkhexz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2rchavrxy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2ybxzlpwt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2vhqzrmgh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2xnosqdhj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2wemfifhm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2ogexonpl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2uihkdnzm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2mnteaqyw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gt2rwdluwzt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2usuaufiu.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixqsamwo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2vysfikqk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxhapfjy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2rpfcygut.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2srtviyml.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoiogoja.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2peqhqktu.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2pmvctyiy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gt2jiczrpiz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxmprnkn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2awdvnrke.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2jhguvtfm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2gzwywsjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2mpbyrdbq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2cvacvbmu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2vjufnsdm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gt2etfdqzyw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2xhgpwkfn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xglwdyzg.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2gkbhvbwa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgugnpjc.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2fjdepgpo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gt2ublejsfw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2uqofgnvr.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2cpfwinxc.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2oeugwxnp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2adlzcavv.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2iczyased.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gt2vcqwhepc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzfwmhqd.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2kadgmsqi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2mekdzcgb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2bvyfoixh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gt2gmelyice.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysnumizy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2xqytpaoc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2mdwrqoza.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2gpfwidcp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2gwgsneqx.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2kqipdyot.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2gudvnuhx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2ewvupvdo.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2rkxkqwgt.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2jvvparbk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvbhevou.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2scehyfwu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2ydtcvpmy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2uiwtqkob.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gt2dnsgzrwu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gt2xziszrnr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2qjgrmmem.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2bbxlqsal.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2qtdzesxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2nfrxhlvx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwcutyrv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gt2rexklsvn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozqypxsq.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gt2njfprjug.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2lghkzowa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2oujfmqgh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2kxmobkzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2urgrvkfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bypucmvj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2oqxzqsyc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2ybqajidh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2ucwqdcac.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2lkfoxkkr.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2szhjbuuz.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2glpyrqbf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gt2dgygyfli.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2ykmfjnik.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gt2altlihro.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2glwphuxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2nonphumh.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2jprzzrge.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2xkvdbawk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2rymyyaxz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnjcmzbg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2xlxxxqan.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2bmmxhrmy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ofhwlqyt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2zvbzsfsz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2afkthjyz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2zzfblbkz.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2xxhilysf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2coiqrexg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gt2npwbmzai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2vteqgmsn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhcyjhqy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpyoanug.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2mpycuyoe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2wvfwhldh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gt2qcxjosqs.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gt2pmqxrmgw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2anenkvxi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gt2rfomvdpz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2dnanxnbx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2aoyrpxka.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2ixvbhjql.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fihmqxls.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gt2zijkcolp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gt2htgnxhwt.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gt2rrgxcvvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gt2iyjqoutk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gt2zkxiypdr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gt2bypzkugb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2spwyzjcn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gt2ibomtzuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2alrhdurd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2qabqsing.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2ripqdhek.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xxbyddge.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2mqwzwlqa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yauxlhmg.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2gamvtvld.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2kaxqmasv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2lrvhfgya.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2yiaumrjc.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ssdqhdil.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plqdxgln.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gt2izkgdvnb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2hryoqpui.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2qnruccnl.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbmnuqnp.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2bhljvkzx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gt2wyvmxngz.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2tzzgkepg.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2vqxjlysx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqziqyhl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2xkexvecd.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtxtquod.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2lowvnyot.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2yivkplsv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2xtbxiors.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2ppbdjovr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2uhxjelac.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2gqjcrrgs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2eorbkyjc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2hjtorvcg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2zlogjwjh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2adhdamac.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vxnexpcm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2nlqtqusz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2nleivoha.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2mfloucbt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2buiktsmi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2ocghimoz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2alkhhkqe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2ovfmqbap.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2ppriiqqh.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2wnwxncha.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2hqyllyev.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgsipihl.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2pnexelhd.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vykzbbrb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiataly.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2hrfoydjy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gt2poxdfazp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qchdxhqb.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2bknrtjjk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2xhjcysag.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdevnjp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2bkgdeqal.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2ondyvhnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gt2iccczjwe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2krwqzmkj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2tquxcacp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dysqckoy.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gt2eipcuaug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2dukxvzzg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gt2xqnrlivn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2wqyrvoje.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkgkwmbp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2vnnsgjvq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gt2qcnbanxz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nldkxhbt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2kqzzolob.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqybagli.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2sbboltzm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acmsbpfh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2vugvwysi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2tttwfrxt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2vwdgqjcz.html


<!-- 参考信息 -->