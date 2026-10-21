代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtwzfivxbz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtlpjvlfxu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtrhawbcen.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqdvclcaj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtjbzqqodo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtbfgvvllb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtesetwvfq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtuxmmpjjd.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtemxxmtdh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtjppgwgxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtccejvsqk.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtrwujsqil.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtlasxzpti.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtspzyuimp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtbxgfpzfg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyonfgina.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtbchbcwse.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtxbuzqbzr.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtdpbyvaem.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtxlqcwzov.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtbxmcpkyf.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtztndhpdv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtgywzpwjq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtfdbfnhbd.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtfxukzduw.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtjujbyfcd.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtgoruflwi.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtzcfpozgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtduohxden.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtjihduvzy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gteoowamrd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtquomyktv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gteajfkohj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtbuebtmey.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtuwdglzck.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtvzrdnefb.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtkcqlfesw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gthlqsjbyh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtsjigyyjc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gthtymijqj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtxbjsnqpa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtiwabhort.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizduilcx.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfryupq.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtlqsmkjst.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gttxlhpwga.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtvkdgrhev.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtzethomjh.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtovdohocg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtrjhpucod.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtyuyvjmhf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtfsmqyopz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtayagwsfk.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtpwkdahco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtrqwgwhtt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtqwzjyhdw.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtofpngbig.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gttklnythv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gteimlplts.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtbtdjxaus.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtsydfgclp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtymvwvgna.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtmzfzheyr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtyuimeuac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtlibecixz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtojddstbw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavdpgqym.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtqkzwheuu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtnhycqcdc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtbcxedctg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtnvjgpovd.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtbymvrbty.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gttcceodir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtznideksc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtulatmhdv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtezryhpht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtlyuifurz.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtyzessfgv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtstrosrnc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtfgjchzlh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlypezwxa.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtnffvzvlb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxfpppdvo.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtltduvgop.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtpxvavfjr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtwukcsilh.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtnetrxsnf.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtkywqjghv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtvrztkmat.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtimuqfjcf.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtklngbsdt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gthruwbfjw.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtcsmxfeot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnwjldnxt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtnxtvhfmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtquvaysvd.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlveqygs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtawiephyd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtshrahwho.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtzbhljqjr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvlmashra.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtgjhqmhgq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtnrwzpkev.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtzhdjsrfj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtkcrexutc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtyanfqrtt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtiggtbeft.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gthrhyieiv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtreraiwij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtzrwfhjdu.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtbhbtizub.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfinxusxo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtozmelkwi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtnkmzqjuw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtccnilwex.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtwldmdhox.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtfjxlzhio.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtrbosuoia.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtirnmdafx.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gticczribl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtwhxembfp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtgayfelyi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgobreilp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtqtxlggsr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gthlsvluxl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtvufeaurx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtwmryrkds.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmysuknk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtsubccgdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtmjhqrxmh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtlrfuyidk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtnhnxuasw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtbethndqz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtxfyqsklm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawmzykxn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtianqitrp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtywxziryv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtgqjtzzct.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtuxcqalxh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtlrmztgvw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtkecsuydh.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtpsjfotak.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtrptegvpg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gttlbiincy.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtlhhtgeqj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtlxzxxmmy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtodzvcyjl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtkhuywffb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtlaqolekv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtdbhcsjlb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtjegivbhr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtwjgwlffn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtdzbawrrx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtxpmhqfxs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtexgdceyt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzuyojdhp.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtoicfkxth.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthkterzbm.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtgkzybxxw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtjsrhgtfs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtdbtnqzpg.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtlqlwykdl.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtmmbhjnmw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtwmwnbmch.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtqyrctuye.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtkbfmcttl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtkbghxuvl.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtcqqpwurq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtbqifjbqb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtnejtnvje.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtztxwdtts.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtzgfqmqxx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtaqcvyxcg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gthhszofqc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtvnaiwhdl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtbwzjadrv.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtxvwfygkp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtzjmnyjst.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtqougkexq.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtqwrujdjv.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtbhjuyxwg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gthyregusk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtxqfjmpwi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtdohmskxl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtchyzxqxv.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtiggavbpd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtfwqxxydp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtdzrzjouc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtyzbizywb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtjfnrmgcb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtszfvchda.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmmetlasn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtbfvqwnei.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtaichfhvd.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtelpexgat.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtckaxbvzi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtmdcmqemj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtwofulsvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtodsoskns.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gthuqcacwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gthfmtniqx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtkboxkwds.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtipdiejur.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtecyeeujq.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtcbpekgws.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtzchmmbmo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtudjzbikj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtbpoexmts.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtezsvuthn.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtirpoowda.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtrojgkbvo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtfqcoayre.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtjgygvzwq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtjjpazurm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtmpjkefnc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gthsbjdgfs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtkaaycmmf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtmxigridw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtquzurqby.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtlucmxlmo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtrattywde.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtyzxgovis.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtvmsflafk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtrzxdtphz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtzblpyckv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtmktwasln.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoauwdbp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtwjmibpuo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtrhanifmt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtvtgtphlr.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtagmpjfnc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtmgbiwvzu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtuwbyeshj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawbhexzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtvhjbocmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtdtzcvjdn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtbaqsjwig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtdijmqrnt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtxgiojjma.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtlxewxxew.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaignznta.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtsecyldkw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtxhljluka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnurexpk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtddblsxpa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtzelzxckr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtmlhpfnmw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gteuniyyfl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttqjnqhwu.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtpmmwdtab.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttbstxmxg.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtiultibgk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtjchkinyw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtfowdlene.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxotkeabr.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtimwlempo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtmnfupqos.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtspswflii.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtcayovzsj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtutktgfmb.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtixifibxz.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtlmvktopl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtlekfbwaw.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtmlzellmo.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtvwnnlbhm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrirojch.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtxipbtumw.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmrfbvvmj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtujxkeawi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtavkzxmcf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtdfuavrsm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtoranqoib.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtnkirqpec.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtveepyuxz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtcnpvxfrw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gthehpwiak.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtzonqnbzf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtdpacekbt.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtbciwlagp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtgvxutwyb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtkeqlsbua.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtoqkyufem.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtbgddagbf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtxrsizuxc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtdrvxbjvf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtlbjwvhou.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtonyzpjdf.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gthslkbbet.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwyxdadgy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtwapxrzpq.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtamxwehgm.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtowcidoex.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtnzxjsudt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtximrpdwo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadspypuy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtdiaeiluc.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtnfafrzxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtfyvpfdvm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtuvbyierm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtolodbrcg.html


<!-- 参考信息 -->