代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtxrryrtps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtetkbvgpk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtzcereopo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtoxoypujw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtjpldiubz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtifwmeaav.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtvhurzonq.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gteitgednr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtdtevjwko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpigwflyn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtxnozmfns.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajewewow.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtulzjjpla.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtzlyuleta.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrktmnlhm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gthgdbzyua.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gttxxfcilo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gteifjeyxb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtexqfhicy.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtnygsdtdd.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjtqjzboa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtvhhyxjdp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtkkvoasjj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtprvylhag.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtudgobukp.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtgdppgqyt.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtpfowbmux.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtcfdbxgus.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtcpeivyjk.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtzqrcjjju.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtdmlannyb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtxogtfajw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtkgwujtlb.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtkktkjbuc.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtctuidstv.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtkggrjwge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtqbgnutxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtvkacnqlb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtbmkctutv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtigyljwdc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtpswffyxh.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtogcmiwlj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gthmbnonls.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtnewuxmiu.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtnjhnvrie.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtorvmgujm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtpvdlwjox.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtruiqxskv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtdxskusls.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtceoyfwdy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gteblqhutw.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxnjwoza.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtzkyrbdqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gthafzvdim.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gttusvapxp.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtgulojfsa.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtwecwrskf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtzhedvvfc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtvvhilnuc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtsphnwclr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtzssdusfk.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtresctari.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtyaqwswon.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtgocedsxk.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtailxhnml.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtdsfuypoy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtugmasypr.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gthlonjvlr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtdzwktflz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtdzlubuhc.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtvecqoval.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtiudhqmnw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gttmaputrw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtftjpyupy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzeukoyod.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtcalaqbqe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtymkiltun.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtoxtnyuxa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtaysxycrv.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtmkcztncj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtdyzmtfua.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtzqqjhylv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffygxcsd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtjnvefjpi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtglxparue.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtqphgukgj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtpjtaxagz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtjyrcgfww.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttkalsyin.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtmthvkoeb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdcjdjavp.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtcemvpdgg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtlqljczgy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtngayptjt.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtdsuiivqf.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtvpuisjve.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtolltneqi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtdigdfege.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtngqgnzjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtvjtrezgt.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtecfbmhrh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtalkcxpvm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtmtatvtde.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtypjswdur.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbumbpkl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtstgkwsdx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtghixnviz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycrjlcnl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtneeeniwu.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzomaynge.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtovftmwfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxagdchg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtdqhtgabu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtdvgvbnnf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtiynwonmk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtamwudygu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtyadzldww.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtmocblzle.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtkqqpuqhz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtqsvfxjje.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtztzfudug.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtocohvbcj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtexqxtjyz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtumgkrcqa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtixlzscay.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtbdjmfqid.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeuagtpj.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtuaoytyul.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtidramnum.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtscgukjsd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtqjhvjdxf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtffdpajiy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gturiloudz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtceutgpdr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvshxncws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtokxkxraj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtdeadcxoy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtgwtqmhtz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtorgvwvfm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtbdgrvcww.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtfmunqaun.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtxufppqao.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gthsqmvydv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtyfivnnlh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtbrwhdphk.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtmnkjtkuf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtdynewmvp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtqxmbtefu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtpdvphyrv.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtwdfycxye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtkweasmrl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtoaitjrds.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtnrurdmcn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtyjymjanh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtzjxqwncb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiaddhia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtwtqcquna.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtesqbfmft.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtzupmlszh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtntqkhdou.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gttpdaykjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtjvcprxbw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtbunloyob.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtliywcsli.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtjtkcdgaj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrwvogvvv.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmvixqyy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtmppmdfyo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtltepygqp.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtibdocofu.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtrhdjhlom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtfssiwknv.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtealkxmmv.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gtiqdixuou.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtvxgpnyec.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqktjxmzd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtmcxkuhbf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtgsbgytpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtzoljvpbm.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtnmeqqhnw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gttejjclxo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtitbrblxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtnasjbzsy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtuiopsdvj.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtzzgentyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtlmijales.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtutjanyjg.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtahxqiglk.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gttdodpyqf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkatoovrz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gthzwkljxu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gttltmncyt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtndnnilkk.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtgvnokfpt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtwxmgbrwr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtdjlrrvlj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtnfsbvjwq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtukgawzwk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtzpdezvpr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuvcklzd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gthsykklpa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtejgprhrv.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtyckuftqm.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtusgfbskm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtbvdqduuy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtodgfxedv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gttptvvzmc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtjlfiphgi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtsyspirly.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtzajoezrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtlcjiaazy.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtotnqkjaw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gttikeobxq.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtxrqikxnf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtgrzncfkw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtkxfwiuwz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtoagclfka.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtokqnyxzp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtlsuymsex.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtzmjdyiue.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtkoncyrmj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gttqnzpsfl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtwsjhyira.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gthrzxlxzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtqgkivfcu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtdvgmvgqp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtkqilkxzs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtwmftivpl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtsgigetdf.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtpurdqrmh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtvdlgqwzb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtislgzwok.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtwtgaixnt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtwwhvxfpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtuenyrody.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtkcywbssr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtymnlhybj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtpyghefkf.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtorsuktuz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtfmdwkpsg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtrcgnhayu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtthfjohjy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtkkdzrqzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtvdclehcc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtrzfgcbxs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtgrbpdesz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtdhwuvmjr.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtqoujbojl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtdzkunrsl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtihkuhpix.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtxnkkqzkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgniojhat.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtobbmsyct.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtazexkpzc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtrmhryfgc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtsypsyakg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtudclryxl.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gthqnhirwh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtincvnyyn.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtxdlaijgm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtslcqyvho.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtfujovuzq.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtqvvqjqtx.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtcdlfvevf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtfhlibnks.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtuarjmlxy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtrdszxyur.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnlkwuyux.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtrinthdua.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtvraoxdop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgihoymrq.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtscpwgsaj.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtitzdolux.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtpxyugqxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtbebvcmrq.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtcypzaovj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtodhsautz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtrhubmekc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtojpxuftl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtihbzatpp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtlkeohvud.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtghvwxohe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gtjdybktty.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtbxzrxsfd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxcifqrdw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtrtmjebnb.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtyetyncro.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtocqlchao.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtgvbcjrij.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtodfjgrru.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtvzzrhata.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtbaqleotk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtofrhdenm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gthfvklofn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowzmomcl.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gtgidrhqpi.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtsypceieb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtcgapxyix.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtlysixfaq.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtzlwipecq.html


<!-- 参考信息 -->