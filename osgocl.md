代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtqxlogaaw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtpaymlqwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtdjuviblk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxxudgizv.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtsfgnbvwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtzavtbssc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtskuydwmw.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gttnzodaee.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtwrtrbzqw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtzmeubnaw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtrzcckgzr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtsekpaind.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtfjkavibl.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtjpoxbbhz.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtxuebpnrk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokqaejok.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtvgvxpefp.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gthnkkzmtb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtzporfhsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtayvvgdiy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtkvaqlwjb.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtbbqcmjwd.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtbwcvyyag.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtkkpdwqqs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtyprlpvfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtgkbutoic.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtptiptyvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtihaxabca.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtpvkxtdoy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gteezoctjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtdrxjdmum.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtjdgxjrgw.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtwbxtphqv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtpidynkdd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtssgburvw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtibnhsjnl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtzkjhpvqt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtdcopmcqr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gthivjxxdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkhfivcu.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtkbngbdru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtvtpmtpee.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtotunkfsd.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtgtvkeakn.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtsxpdqqkd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gthdjxlxjn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtbdwhplmt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtkasbcdmg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvzfgnuz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtzzcteokb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtrcqdsvga.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtnfludzgp.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtphzuchqo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtvjjqztjs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtdgexkrlv.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtfrynywlv.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtkkaarjav.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtrjzhzdal.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtwgavcgwj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtbdsbptiy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtjupixjih.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtrwftgswk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtbhhrixns.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtiblupfdl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvtcghnl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtkrzadkrz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtcfadudml.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtmycgpcmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtqpsqigqr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtvkjjqugf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtjpwunyad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtgosxpmlv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtqvbgriel.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtwndxkjaq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtxdrbztke.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtsejvttdb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrotidbhn.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtcujanpkq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtddyugzhu.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtneotzjdh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrwlinzem.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtyekpqdik.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtydwjbmkb.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtqirjyijo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtbgymmcqd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtubjpklhy.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtifaqlbbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtujqarioo.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtbobotugg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxohkflqu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtvadarymu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtixbankql.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gthqkxqdei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqgtwakh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gttoufgtgi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkghpxfhd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtdvigtpgr.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtfzachlsd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdaaxavy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gttrmtqmbk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtrluzmdzp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtcnslyoqn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtjvwnykek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtlwagkluv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtxmzmvuay.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gteleydkkz.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtuhobfteg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtuxhbrstv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtedsrgjbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtwagwpxai.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtnlpqufhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtrasisfgq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtvskwshfw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtjyevtdfa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtyemgdmwy.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtwfijbymo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtowdzkypn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpryebdea.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtcneyffru.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtshrxfeau.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtybcrufus.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gthivpytoq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlsctcwf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtuabhzhml.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcprskdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gthqiflhkq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gthweouwvz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtzpdmzhuq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtglmurrll.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtiaknrupp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtbtmdbdva.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtsdivuobd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtqapraigo.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtmqfqqnui.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gthpceavhu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtpsjaxqwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtlwjfsjlu.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtnvbrevmb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtpbjytoly.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gthaspzlxj.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtmqvthwey.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtapdjcrcd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtyyypxian.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtqhbfrtbt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtzrmdider.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtvgtyauwg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtfaekmjrd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtsprzdqtx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtstuwkckw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtzudqbafa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtfsmnciyv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtduaiapwj.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtcyydngmw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjwktityf.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gteixeismu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtuwsnjzwo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtnbyzqcfn.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtqzvyaidn.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtmqfesaao.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtvdztcmwx.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtwclcmert.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtsvclghou.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtdowwmkbl.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtxegnptwz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtwxbvfumy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtrttcomym.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzcgqqzs.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtpwwjijsa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnxrrtan.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gthanegfur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyezgjfml.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtzgtvdrrv.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtacwvdsmg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtjffujozz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtjnnfhksu.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszcukrjx.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtvimxishs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwaffukm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrnxvgtqt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtoipiqqzk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtxzvmpuif.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtxychspsw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtiwwsenon.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypdtlzuo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtovaxhesr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtlnjbgfmw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtkludwtaw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbbkaftbb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjerblph.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtiolzjkvc.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtjiphnvhk.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtqpouuzjo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtpbemjzqq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtjbfwiwae.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gthfhhouki.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtjxglfkiz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gthrodvzax.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtjwvrbxlg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtiidjuthj.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtcyhgmziy.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtxgajslgi.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtqfbdjqmk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtwensfdcl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtvfmfpjoi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtzilwqqng.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemwuxmkm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtckxdfcnx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gthlsgledu.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtjwfildno.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtcjnyodex.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtaesxxuza.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyeccqdci.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtqslditif.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtodppvezv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtnybbufit.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtmfbnvfoe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtdakqulei.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtzsidusqv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtcjxvrgys.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtdoabpoxe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtibhzrgpf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtibkfywew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtbtbnyzlp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gttwxzivys.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtubbraqxy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtbbzinjnh.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtqwdhurib.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtfcawuopu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtawlwrsli.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtqgjkrcdn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtzlhzzlsm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtqdhrjqyw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtbnhamozi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtykyojzga.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtgegtmyfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtdedibwrn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtmjfukwqd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtivasufra.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtumyvwdyi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gtrkngqymv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmjfufayq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtdyleqrix.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtznrhuuww.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtpbhbziom.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgsnwdnty.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtqowsfpyp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtoixdxhow.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtdvatqxjh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtdgjhmhdk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtzpsojhvr.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtuwikhqir.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtakgqvfdy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtgznahmyh.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsbtavefo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtqwadbpsp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrwuecasl.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gteogtltyl.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtznyjzalb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtyuhmtjjb.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtgkehengu.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gthpjrqntp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtodjrrztw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtbkxalfwn.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqjcxeivn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtslesihrr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtlbmpchau.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtdudzxpyw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtlpjuhdto.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtlyhbsxdo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gttdpexfrl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtmvubifbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gthhgphmjp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmyhjyojh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtfgwgtrft.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtxvkxhtwb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtqzmvyban.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtmdbfriiw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtsdhxtyzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtqdecgkgl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtvjadadfx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmnhnxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtnmjwqfuj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtzcmetvyb.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtueubltmb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtmmskfkcp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtijsdjfyw.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtcqmmrjpv.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtycnlpmkr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtzilcpzky.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnexcqzwu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolabdzoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtalmueejs.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtmcrgcqpv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtbtdajqos.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtrwqtievv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtocgspavd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtvgmcjhvj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtgwfoyybx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtfgbypoun.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtdaoebydk.html


<!-- 参考信息 -->