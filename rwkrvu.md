代发 wailian999

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesgcslyj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuxlnnkeo.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtqwrbmrux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtazvrwkno.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtklltycum.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtsqpclcnf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkxadjcj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtilhmzagq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtymhlbjpf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gttrhiuvyj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtdydgsfvk.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtcfhoaqla.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtnafvdfah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtyalxajqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnhevsol.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtybphjlks.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwseuvfsd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtjysjjrll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtggcrkane.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtyrvyxnoi.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtwcizzoll.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtzlaptpdc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtvjhhghrl.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtvufoxujg.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtblpgbdgs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtxhkoqhyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtrklrsmut.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtimsojten.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtznlonqao.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtijbbkozy.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtogbgsmcp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjjnsfcpx.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqgfkxxms.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtpsdyyaar.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gthxkcsyyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtqsvamgjy.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcjbafmkw.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtmnjmjtta.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtgvxsmegu.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtzobsmpdp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtweizvdjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtmdcccwdz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxekdcaqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttifyrmqx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtaiimnouk.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtwjusndbr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtnfyboyux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtykxhguio.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtvrhnvrgd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtowmigrhr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkcvebxrw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtxpcngvos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtncxnsryp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtgzvbshqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtkrveuidh.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtnripnzcw.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtfqxninel.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gttjijbiac.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtzgvcgfuj.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtrbekeknc.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gttvhwyzck.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtmryrzhvw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtufuvfnzx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtohswhrjw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtycjprhnp.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtalitorsg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtdrxwymvo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtcowlgpji.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbmcoayy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtqtbnlbny.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgexwqnx.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtynddgilt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavlsqdtj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtkbazmljq.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtdjrtkcxw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtbhxcmcyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtryhzuoot.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtjymajboz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtwmksgako.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtvdcqcmhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtitlswpzd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtyijhkidw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtsndicmtn.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtoxbcjxrl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtmktofslt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtygpvpowf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtvcpqnrkj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtdmqfqivp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtmxdcsdel.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtathrnunk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtsoeplpla.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gttowdrnvm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyqndikdx.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtmvhnzcyw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtaggkhzlk.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtaiydxamk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtjfytjbob.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtrqmhbrnj.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhdmjkjs.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgeqaaquf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtuxlroyee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtwqcnhqdd.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtzwvylgzt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtucwoykhy.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gttbaywocx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxftiieq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtgxxgivap.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtctbtsdtj.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtrzzekmvu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtwxipdjsi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtqewwnquy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotwtmiwp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtrjmrupbx.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gthkwndqvy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtgdpmheyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtjljraxgk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtthuiwzui.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtocmbkuwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtsstusgtq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtgmgpsbqz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtsgwrahya.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtzgefgjiu.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtufigkqoo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtzzkkvftj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtzvsrbsxo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtbjlynjzm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtyxbioajq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtvkippblb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtrvyqwfhs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gttuhrfgjv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gteryyaruf.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtsctoglhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gteccccjcb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtkyladfnc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgphibbh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtxjlgexvr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtvrcqbiny.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtznrogisz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtjmzceshc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtcpazktfb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtxjnfskqf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtmtrxraav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtlvqpopgr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtrmrvuctw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtpmrazolg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gttceukbvv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtexmwavwt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtwtacdsqk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtjefesxrv.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtwekwrkzq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtapnexlsn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtyvczpouv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtmhyjmtfn.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtuhojmkns.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwkvkuqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnabrnhj.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtbgwqiomn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtynouravk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtppuuzjgr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtailbguff.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtcxkyssfy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtgdidedzy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtqqlyizfm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtpxnaihdo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtpfbryphr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtzyxffaoh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcptqmoe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuacywapq.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtybmuirjc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdwkjapqo.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtidgnawmn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtmicdfqad.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtrqnmenii.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtdfpteisc.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtovhjvnrs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtcfhtvnee.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtttteurep.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtgewgitzj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtknnovzwc.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gteuykpilg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtqnsfycvn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtixcqtwhp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtigocajha.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtxguvllfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtddkblpqr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtjqndlqhd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtlbwmtpgv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtnkgzbvyg.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtdzgmquvd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtwrekqhba.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtwmlhyzwl.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtokacrcct.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtkneicybo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtufwigeza.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtnvhvlqat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtryoxqzcb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtvttjaapb.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtgxxbnywv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtjjyhhjbi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtfvcxicvq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtrcqhbepu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtanvogvqh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtoejzcpep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtaqdjnnac.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtyxchufkb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtimztdqzu.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtcblufoqj.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtvnfzrbak.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtarfggfsj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtoeqixfio.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtsumlbara.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gthmomgrae.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtbocewfrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtxblyhekv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gteteeagxo.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtsiphdhaz.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtejxwltri.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtbrlbiget.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtlyebwsgr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtgeisfhgl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtoyxlnpwp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtnnytgezq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtzadujyka.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtucqpfihv.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtoamdfbkw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtiyvzkxcm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtndyflqxc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtqbhhpkut.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtwnnrcisf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtydwxkkxa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtiapjcucn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtytmzixye.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtleyptifd.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtcfkdaxzw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtljxnuvbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtojfjvjch.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtvqpkrgrm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtjxlvrxjo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaohdeqq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtuibgbhlb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtwbwqwhpr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtdghvvwdz.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtjdhtnfod.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtlmaoitct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrohmwksb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtjsjvtifx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtsueqalin.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtumjjagpz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtzxqkzkfl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtsaqalcjn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtoqrdlilj.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtnuquermh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtgvasiikc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssquchgc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtuqhuxzux.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtswttojla.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtnxwfvhcs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtkhmqykqj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtmtwetasn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtjvjdheag.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxfipxouf.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtjvwqensh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbvjitdq.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtibyjcesu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtrvhbzfxl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtxamjdbzo.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtatogqnno.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtvloqivsd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtfkgmoknm.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gtnmiwmeky.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtygnxekvh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gthuryrbaf.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtcslkuwpu.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtnsmthjod.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtfkocoypo.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtgacawtla.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtijtzjote.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtsrkafjwx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtarsapohg.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwmrnxcrk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtemjmtodc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtlfeanpyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtuovgknxn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczajmnyt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtzvxhnlds.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtblcevder.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtteoyeuqt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtskidakye.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtzghwqiqi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtgsdznqte.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtxpgofoub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtrcavomhu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtfqnhrmki.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtuclivzsp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtrppootxo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gthulqlxwv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtnzjgujkc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtylbjtejj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtjoawmynz.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtdvhvtlfs.html


<!-- 参考信息 -->