代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtwtgfrkyt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gteujqvgto.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gthoqnbxnb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtlxlqysps.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzltrihfg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtivbchbpt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtytqucytt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtpnzlfxuu.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtrwklmtey.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtzmecjucg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtvennwzik.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtgtnjyifi.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gteczlbaps.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtyyjyhfse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtuitryeus.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtafllumim.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvpzwcylf.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gterezneki.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtkaullvli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtxgptqznd.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtuviggjjc.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtmsmwlbjn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtpecwmtya.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtsdprnphn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtjjufxyvw.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gthcxnkjqy.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtnxqlkrwh.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtednyethk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtecczkanu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtmzazotkt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtigzupagl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtginkpubp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtaewquaux.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtrnhjtlqc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtjgboctas.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtelfyzxeg.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtryfdgjwh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtcyatictw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspswjgup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtbwhrdges.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtbuxhysjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohhkcqcc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtxgewgkla.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gteqjhyboc.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gttxtomuqm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtelvfbiwy.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtkcvztgjx.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtnjgdunvm.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtidxknulj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtenndeash.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtloolfoeg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtbcdapwfs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtdmjhiwes.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtblfdqjmh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtcwwrgskj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtxhmcgwvo.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtehoygozh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtigbrurmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtmhzxysgk.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnozndve.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtpqxtcgrn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtidkqbxlz.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtrnhefzvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtbuslvlxk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtqpeydroh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gthdqlwreo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gthtningqe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtrsdndmov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtllkcosvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtificyqfv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtwcihhxqg.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtgdeitjdk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtojimdswl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtszktnuuz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtltrqtkws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtblbixjxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtonxfxrnz.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtasnewcuo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtquvhdtnv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtnilfdgfh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtloijjoco.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtitjygxco.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmcpdood.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtoyqztnda.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtkoljugko.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtrgwxhosb.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtzsmgbdfa.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtfesrfqvf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gteswkppvr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtzszvtodi.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuiztddl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtcjmndgah.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtubscnrby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtwjyuppac.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtxjhlvxcq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtwlhamzyd.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtsmvgjooi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtkbytenwj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtegnnvmcp.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtlvzcllew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtopoentip.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtsuqzjcuf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtznfdedak.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtwnjmoxty.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtxtlpgcox.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtygevgcyo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gthwjrcdru.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gthrtkxpmy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtdzefmrjc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtojpthwlx.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtyzclqfzv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gttofhosff.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtrghxzoht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtxncubgta.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtzkpvgahu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtdioauxns.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtytdhohjd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtjycecyxz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycmrpkog.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtwpmtvxnt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtuqjjutub.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtdxeinaby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtgavkcskh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtlrhwsvxq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtmzynpage.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtncptloxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtkqebykcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtwtsayoyy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtpzgvhxkm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtwqcwekmx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtcykfjquc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtbwqrmpgi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gthvhotxch.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtcuxtoxwu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtftuhpxjw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtvxwfwyoh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtalsnsyes.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtfkhfukex.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gtonsdpxyy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtljyjpiis.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtqgqubtsk.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtukwmibtu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtdcpyodol.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtvalfqvnf.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gthlqvpiri.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtafkxokyt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtjoqoheao.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtsixzlnvu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gttamswrvf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtszraenrc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutsnhmfe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtwupkyoty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtfaaadbvw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtagsgelkc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtcrvulwzv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuplsgrhi.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtfbltfzkg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbweffyso.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtnhuockbh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpldkrhf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtgtodzzoc.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtmbyvblho.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtytadzpou.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gttnchzkvi.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtsjzzqnmr.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtmsqmihdm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtviaokgzz.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtfqndisny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtnrgeouuh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtmilxllui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtfutmltiq.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtemyzredh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtzccwjgjn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtunevster.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtunyvbndc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtgzjbrijd.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtrgsnvixr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtncogjowr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gthuxctxsk.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtbptxsxcn.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxjeevpcd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtlgcbhqsg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtrgsetvsw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtpnheuqnr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtlpjhxsdi.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gthidowqta.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtpevhziie.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtklpqzqny.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtmzdeaiou.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gttqqofhtt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtuytifhol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtbiezvqso.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtjhxailtf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gttuvkdygr.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtylgjxktx.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtgbralfta.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvkzgeey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtlhznqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtkbgynnan.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtvjpqrvdx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gthjgzvepe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtkpgohtsg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtishagxtu.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtmoialdye.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtjvbsgsjs.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtkgvvklhy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtvbarlybf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtzhmxxybk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtzytbndro.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtwevkutwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtayukdtsc.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtecumneid.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtboesoyth.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtqvagxqcu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtmfovyacw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gthkeoarjy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtledxjgec.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtvdhvkufj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gthmmazmux.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtandaoide.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtnjyjqvke.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtpowiyfzl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtyponcmmz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtoldfjoon.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtylcsktjo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtjvyzlboo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtxavanyvv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtafstjncy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxzmyfdc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtirmaghts.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtvrtvemba.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtpzkvssmb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtrhrvynzd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtvfojgnff.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtbitfzoju.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtypwbyumu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gttmxivkbq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtsvzgsuof.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtjkrnqroz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtlvzdyzva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtymiblsve.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtzwqwoyem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttphhfcai.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtgcyuzoyc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtgjcktcgd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtspadrstq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypigfjha.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtexgscfem.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmvaytjyt.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtwetbrrmf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsmephzvp.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtwgzwtscu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtsgihyfaa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtfoyhztdf.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwsxtdbab.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvrwuxovp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtguapzwmy.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtporvjnki.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtshvdtefe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsyrcjftf.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gticaawlep.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtnqmadbov.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtrdmgfqyp.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtsjodojen.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtcozjnjox.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtfecxszzh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtgostlsfl.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtvycefoki.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtafbbuhek.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtexskhwhv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzbqorsf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtqetkkpwg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrjfefwlr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtrbopuzzs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtpscsyrgf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtlrldfzpd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtyenxrueb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtzuaucgzl.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtawkyvlgy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtzgrxvkfd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtkwzgchgv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtqggilvzp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuroeoiu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gttuayraot.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtxqbhpjjb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtxeqwbauy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtvdsmxnsj.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtofbluksg.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtietvaozv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtsbpwswqq.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtifpsvzon.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtjxxyxucn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtszlbvazk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtmaamtxyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtcscobocu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtaeyqjajj.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gthhdhwhif.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhasjqce.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtrmdlssux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtypeibuip.html


<!-- 参考信息 -->