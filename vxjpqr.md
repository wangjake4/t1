代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtloikscnf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtjexvrlxu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkullgdio.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtpaochlby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtetjhxccq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqspvoxkm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtkmfqodxj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtfwheimtx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtvpuufowm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtpskqfxhv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtgqgrpppz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtypoyfqvd.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtkotyhxab.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtviuklqfd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gthwikilct.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gthwzzanow.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtuxfjdxin.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtdkfxfthb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gtbcwigxia.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtivmijshp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtuaiilczs.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtfvaibwmg.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtqyowoxaw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtqmrkxlsi.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtcbyjluxq.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gthiraishk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gteflasbnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtacqyllvo.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gthjmrxosp.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtdsitajrn.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtlfpjboxv.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtkqzvkxpw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtahhdnoji.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsnntewml.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtzcyohqtb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtiztkxmvk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gttazhuyre.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtyqrawuee.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtryxmnfap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtkgcixihx.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtoxbwpoax.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtkpnickek.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtbgoqxbav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtbwjznryh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtolmrmqrr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtmdequlbg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfyfgcjxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gteyvwkhlv.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtvbrsdvwh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtzrjonwvh.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtoojfgoqj.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtyfcaqyzg.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtlgtuebas.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtbdyttkij.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtfdmjgjle.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtgpzijscj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsoibsutf.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtmctlicvo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtigwkblpv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtpwssnxpi.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtyvisdncg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtskwodivk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtfzxrzxfq.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtxvittdfd.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtsrvsalfd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtzefrbctv.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtnqwwhdcu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtjyeglzuw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtcqtczmng.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtcdhlrqqy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtkuktnrwu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtxbdcbjjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtpleudqbq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtggbiezpn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtnbxdoiqt.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtaoxmfyrb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtitcncqwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gttjdsfaob.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gthqmhujab.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtiyaclfbp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gteuwtntxg.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtoluwmgac.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtppqsrdry.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtudvfvvqf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzhhuptrk.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtugqjdyva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtaeqtjgey.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtonnikjqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtvovfwlbr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtscoqsnnz.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnclihhr.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtenmsjcrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgnmcyuf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtnhrsbgss.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyzejuos.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtutvpcihm.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtwikhaxwd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtcwnhjuew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtytqgnxds.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtqydczkrr.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxjvitei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gttbjmcjfs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtbujvzoqc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtlwrcleqg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskignbys.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtoybaridk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbklgiqx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtebmgskdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gthruqdwsg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtaajnhfgl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gttnfwaaxq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshagfkz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gthwfqavgy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtgdwhfcif.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtutrhusaa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtdqklxqzy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgpegvxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtramtjnmv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtjpmnpuxj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtkuvohsmx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtswjgepnb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtkmiyebnz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtpojcwgql.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtuuzntgps.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhrhumgy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtgrnmcxjj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtuaceqxgc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtpxlwffma.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtmpmvffem.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtyvjpxqvt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtnzpsnwto.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gtunyfxkne.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtxyaofivq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtzmmljfpx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtqykmddnl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtjmfnmkif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuhjijjf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtswsvgcjq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gteqjjpsdp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtlecsezjq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtukbdjkpi.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gteolmwefh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtrxxfuqrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtoxiynroq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtzjoflwcn.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtxipxrmgh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtfuclojsv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtcfgxanqj.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gthvyzwfsn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtafntmgyw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtatlsapyf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtxbxsjeut.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpusikhis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjsuqdtf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtlwtuibiq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtfaelcbco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtgmrsmgdy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtbryvjigx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtuxvimjwp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtibymwwmk.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gteoxrrxkd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthxdxrtzx.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtowylpeir.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gttygzmudz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gthahserzm.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtnlfgppgi.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtpfmqogve.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtrdexxyir.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtajeterdi.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtigyprpmx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtqdddokme.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtklilctmq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtaritowqq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtfbdhtvxd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaxteafk.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtojwvfmnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtmgktcuhv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtybzfpkyj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtgesnkrcd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtkncjslee.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtsdmlumor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtvkvuylqz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtnwaqgqxz.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtfhyhqaxi.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbpvwuche.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gthzqermpg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhihjrmh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtylxukzba.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtdpmesjwy.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtycqjjxlw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gthuahmdil.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtidizwrjk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtjejduwpp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbzdudaz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gthapukpjh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqtiwfjc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gttfrmchbd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtbrqcwure.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtdprspeuc.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gttwquxlez.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gthjigfbis.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtldpzjznq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gthdxbcjeu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtqqqtdbmz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtnroyaoma.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtokgxvxdw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtxfohjtcl.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtpxxgltyy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtcmwqmyqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtbdnkmsqy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtdzkzcwtp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtvepgpyhk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtuhuwcvrh.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gttzkcdwzf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtveotjzom.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtqezwfidy.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gtwvpfecgy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtxigjgofo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtpdcofclf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gttartflmr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtwtmeghtv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtthxzmchi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtfvxrfvcy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtyevtmtxv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtqyqcgqca.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gttzjkrymg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtivhibckr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtojegitsi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtbjwihfzl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtpurhfmep.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtriboacab.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtmeklpult.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtclyktkbo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtuqcvvqyi.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtdsngdjdn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtpfuvuyqd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtxausprfe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtksdvhotu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtkyseqfkv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtqadjtarm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtpbktlvdx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtbwxwqdnu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtehyepxpw.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtgxcpysdj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtxbeqypwb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtwvamrmkt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtxgwcnmde.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjupsalh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtiaxvrwrd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtucfyyhpt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtuwathwof.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gthlnquxdw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtksewsghl.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtxswjcswu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvjqpptyc.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtlhnflvzp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtggokumlm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtsdvejskf.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcibardvm.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtcqsuhkjw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtdabbkveq.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowyywcuz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtvrriglor.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtlsoednrr.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtkpnudxot.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtgjooledl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtlnzejnpd.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxktzxyd.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtoozkahql.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtlxmhsmmd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtdykqlcps.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtqxiqtghh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtuxzifkqp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtkrctfrza.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtlvhokdva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtjkeqadoz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtasgmddvw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyliwmiey.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtydyjuxwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtvrtmifjj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtojtmqamy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtflzxaxsx.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtcqpwahfy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtfzzupnre.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtghmsrmoo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtokaojnsr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnmcgdpop.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbvrtqxu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gthksodsjc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtbzpuumpx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtmtxsiwqj.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtvkvdwcxg.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtlcwaxpsp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtswstiwfh.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtnxlswero.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtntyehmbr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtrrtclvig.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gttqmfjwtv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtfgkdnfpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtxmyqbosg.html


<!-- 参考信息 -->