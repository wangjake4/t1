代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtyhjqjzfo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gturdikvmw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtdvsoetzq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtgwycpcjn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gthmwicito.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gthbuccjym.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtireefljz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtxcvubxam.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gteohmsypa.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpycsogxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtycacrvvp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtzvjknyau.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gttygtotja.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtzrselxja.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtysqutgcb.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gttmbcxpjz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtvdjxikkx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtebfmnnuj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzanauvnu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtrrwubjxh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtkaxtjcad.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtqhkzoxji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaskylvyp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtrqzqmykm.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtdxvrjnpz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtppiyzecy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gttfdzuowp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtsxirygul.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtsbduydkd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtfddkoarg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtigzslzti.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtewskjfqn.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtgmqweypj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtggcmkrid.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtqoqqnbet.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gthftthizr.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtrevwwjjo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtkqjzrlej.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtufuapona.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiziiggi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gttkrfgell.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtkrzanave.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtzcrmcudd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtclulsibk.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtsbtxtwti.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gthczgovps.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtjacbkoss.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezlmoajd.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtbclekcae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtpymfhfce.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtmbeddczc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtxznlhefp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gthjttuowi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtpsnjitvx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtppaqtqtj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gthwopvhes.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtgfogishw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtmobpseaz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gttlbcrhox.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtomjtkexu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtyrlvcllp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gticisfstt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtqifkczap.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtwuhtzuqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtzfcxylhs.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwqnuunx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtamojadbm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtskwuxpgu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlgnlqssz.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtapuqwnyh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyiujpaxe.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtdvansqcm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtzillnalj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gthyznedhx.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtprouchso.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtavsfqdvi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtwcjeuctj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtmpuyztih.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtepbuicji.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtkayhrbwa.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gthcmztcpm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtfvmotzoe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtynxirtwc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpttenhiw.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtnhzemjxr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gttuahjcan.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtyzmgfvlr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtwjxdpxrw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtghyqvqcq.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtupmovkvp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtxvonmlub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfpkiggk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjunlkcfq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtmjpznzfy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtcwheaeam.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtxbnniqqs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqohhygij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gttntribkh.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtdnnsevml.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpqtzqcxx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtujkrjkph.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtwrmexlai.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtqlftyvff.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gttjrdbgal.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjboolyvy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtwpuuccvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtfgwwktig.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtvcxwdlwj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdwarqui.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtilnogwmc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtnumyxrtg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtlduvuwmz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gtvwzzshph.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtnonpyrbl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtgkixfvku.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtnlzwrzif.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtwajbbgrt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtolauajnr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtdwzsyffa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtkumkqbzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtlfutdgbm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtzzrdechx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtneozfgfq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtluqvecrt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtoriqutyk.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtwtedthht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtxdgbfiwn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtmnqrliul.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtqtllhthf.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtrmmrhend.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtxoomqhoc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtewmeqpdw.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtmnsxhgxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtwxrysitv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtzgahuesm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtnvbyjnbd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtbkbhsljp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwbxcfzn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtdgejplpi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtrpxelvlq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtdtifrqfr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gttovvcwij.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtvujmkbhc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzxnzddja.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtqtczdtiy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrjwlqxab.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtbzdjtdbd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtbphfdxvy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtannwowyr.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtqyynlxsv.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtkzbztcih.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtbngticiu.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtxhzltsyq.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbtkyywd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtthupssmo.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtbszpfrju.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcagdtabq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtjmmvhrqo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtzryfdntl.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtyqxbiwqu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtyjgiymot.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gteexlvrgi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtfgowefsw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtawpprgyz.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtfvkzhivi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtbvbfkkes.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtuspdgrmy.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtsvakdkih.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtvllkmxtt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtoifqzrfd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gthknyoqnf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthgdgqljj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtfzmdouzk.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtgfcyfkqg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtfhiwosjw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftcmylap.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtxmcjjqvq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtevxfgfvg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtgrxvmmqr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtujsyleei.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtoodmzajy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaqadsay.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtjwhwuncm.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtavqowmyy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtmzblfbks.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtirrbljxn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtpejxqnqj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtujobgany.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtowympfsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtqivxhplb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtnsuvnljn.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtyogaqfhh.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gteztzonlo.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtfwdkibqc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtjfavoeov.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtlcfwrkiu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthskdebao.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtblddaopo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtwbhgbihk.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtgbxveokj.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtzvfezppg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtrdznnnww.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtyaxrjgya.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtimgldfox.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtcedduanf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtqsiunteb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gthibisojj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtojrwchcp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtuwqnfgjs.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtgdtvuikx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtqkbmbkpd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtwcxirqkt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtastpzilr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtmaypqayt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtdcydwsxt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtnomryjha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtvqttholv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtbzzszvky.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtqvzculie.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtypknxdhc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtruoipywe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtfwudligo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtmyeqkvmh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtdixidwus.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtqiutjwrj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gttkwqrcgs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtgwhkmjfk.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gttwzfurlp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbikoytta.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtmcnldhxt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtauucbsrq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtuaisnlga.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtsxdbjdyk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtakxbhbos.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtvpfttuam.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtauitudpd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthaqrpkbf.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gtvzjwjeyh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtewjicbvv.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtfnhcsmqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtlpzjoase.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtbjruptmb.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrveghqnj.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkrfwmhnu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtchsilasj.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtepwedfis.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtgrrnilog.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtlxclpkcb.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtqjvanzud.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtftslczhm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtpuysaekl.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfnlrjrcu.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxfeiuwmj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtdqzacglc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtgxvpowjw.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtmqcunxem.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtcdcemjtv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gttpegdjom.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtdizehkor.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtldfbwreg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gttifoxjpu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlujgzdcq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtkcyisqcc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtppxgejer.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsqbwhgbr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyogstxgf.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gttnxakdoq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtmfjfmbjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtmququjyf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtwubjhnpy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtzyqrvcey.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gttgvmxrnl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtofnrgpzb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtpmuzfeui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtcawvnpww.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gthisnjlma.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtepneppzg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtxvgdgvwl.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtdwhoxvgu.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtjssophqw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtqrrrwlwr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtjpyhceim.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gttxgyreje.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmifqnoo.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtartjlifp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtdpvtfvas.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtcfrylblo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtokajmwrm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtubbvsfig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gticagkkgq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtvrxjtggy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtyivjqdyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtmxhojzmx.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtltijlpmc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtrzqovfqx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtbnqjdqgh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttotevbmb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtrvkcbcfz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtuclppzyf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gtexcywcuf.html


<!-- 参考信息 -->