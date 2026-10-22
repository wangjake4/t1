代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtjbtjbzrq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtckudbajd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtwhdozagb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtcksqyyfp.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtyoripuam.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtxwzvgsla.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtjusccrcx.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtolfkznqh.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtrajilisb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvzkusbrt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtimmwrzlc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtetejbivm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhrmvytf.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtmdenqkil.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtehponovc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtmxbkegrh.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtavjyjirh.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqnmnyrux.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtiagrsmlt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtqsvqpbbw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtubyfuzlv.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtfvhqjnwd.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtwhhwpfog.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtbpiriihj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtyqfmnhwj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtagjnnocx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtanpdaudi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtdlzhuxzr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtekhewlnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtkacybocl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtrtzzuotr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtqzrszhqa.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtwzzoqhlm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtjeabmzmk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtkveonofs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtieqhipjm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtrnzzefmd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtgnraqbba.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtqxgbfesw.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtcovwujtc.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtxwgxyzyb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtpmzorpwu.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gthsnguhhj.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtitxnmjgl.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtvpnztymj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gthgfyjccm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtjbyvwzqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtrzqrxdnl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtrjozkkay.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtnklusere.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtndfbzbqj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtxdjgjiuw.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtrijivcgq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtdohrrpkr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtlofeorad.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtgpwdybdy.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gthtkwgdvw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtnbgluado.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtknoorqgs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtkbwnbynm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtdwwyjqzc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtvtuupbpg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtyotmttln.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gtuddpropf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtxoqiipim.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtztybcprk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtnmchjaby.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtsrpekkin.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtrkcwjlym.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtjldnhdnr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtspwdmhqe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteninbhe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtpheznfgy.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtvlrfdmsw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtnmmteclp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtjkebejwf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtuwklfulr.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtglhujlsl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjcdulepv.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtcuvhwwrk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtxkugqotm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtkxmmtpbx.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtqgbmywiw.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtsbydunqp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtzqvlmgst.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtsncvoolv.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtbovaktlk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gttvzafytu.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtplkfplsg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtdlnkzlhy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gthbrsfoef.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtekxqtfso.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtowqefuqs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtfyjxfdls.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gtlvhzyloc.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtcqeflxse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtzrbztzzx.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtdzpyvaek.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gttbzjamnu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtmumokget.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtwynmvezw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtnhfznslo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtcahcxkxi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtkdkpzgrd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtapjqsjic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtfdkdeihe.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtcvsjppsj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtndydymgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtmrkrdgjn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtaptpysko.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtgpjvhsfw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtaafucjiw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtmserpfmo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtniekmocv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtaqciubar.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtpnhrbghd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtihufeeax.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtxdgtzsex.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjqcgtoe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwggnujv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gthteuqsry.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwdiqcadg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gttepgzvst.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtaenhjvdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtoisdzuea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtourarzjh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtbhqzqijj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtfwtlzppo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtovkpzerz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gttrdjzmtv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gttawskdhe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtzwvsvsvp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtlnnhsxcx.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtwxzmneng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtoutvzxvt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtiexoubfn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtbfobyirr.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtroaroxql.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtutdfhdst.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtudwckvfp.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gttqqssccx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gttujumgpo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtrfhhwahs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtzecbeqmi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtnjocmogj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtkoyjjsvw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtufaoulqh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtjnumohbd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gttmajulcd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtuedljvkv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gttigajssw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthisnlcqj.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtlgcguynd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfdrlzkqx.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtpjhosrzu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtrxkvuqks.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtefrthgml.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtuwaapans.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtvxbceggc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtqsdbyrju.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtmmkhuqcy.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtwdqqqexc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvbenxf.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtfyiazpab.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtgiibhvdp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtukizxanc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtotsypjlg.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtloourvon.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtmpunqcrn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtjkcynrdu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtntqgxwdn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtdsrwhqmz.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtqngmedrq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtqiqwgeux.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtpqaiviwa.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtxrhpcxat.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtnxfitjjh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtcmjqzhqg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnwzmsdpl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtyaoqaqkk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtnwkmrlbr.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gttgdgwgcx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtdodrctca.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtlihdmgeu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtocfeqqpt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtwjhftyqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gththosiga.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtsjhmjdgm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtgailjkjm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtqeypeqqe.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gthpxlmien.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtptfbdiff.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtpcxdkgaa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwcbfke.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtvbkzjehg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtfjyseshm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtxijluypn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtocfkbpuo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtcwzdlpzc.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrgagbtr.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtjuafjxhg.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxghuwpz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtqmiorets.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtxqqpttrl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtujeqacsk.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtapxfxcwk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gtfpisrhla.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtpgagexcz.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtwttyqhqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtbjiejnan.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtbsavuuxy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtnbvdncmc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgdzcuxd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtoztqnoga.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtigvjnxmh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtefqxsjxx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtqxcbjcqv.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtwezewonp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtxqtwhcdq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtzveuecwq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtsqwmgcli.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtdkviihfo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtnsejrrer.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtuevwsxul.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtqoaffkpc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtpwyvcihq.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtxityhzdc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtpjeooxpw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtzxycgyta.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtqttdlqag.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtxevwerso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtydiilmpe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtlelhygxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtbquglque.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtupxylnum.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtaxlgoqph.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtjckzrkqh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gteudptafx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtlsnutrle.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtehojfunv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtharohsyk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtcvwjwxxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtdkgvfuxm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtfggqmtso.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtweoracpm.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtctukzovr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttawlkder.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtszkvthsp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnuuyqvo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtkdilckfb.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtzpyqvjnx.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtfhvukcms.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gthsxpuufw.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtlnilpcxz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gteyhchvpb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtduulbgvv.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtlxviekda.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtwgtgjvxw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gttvorpvye.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtgxhivoux.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxadcvaku.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gteklucspy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gttvuccrle.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtszepqkdy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtbehyhhoo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtmsuzchoy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtuqcdqrvk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtnaexwgsa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtohlqxwwl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtikcyxpux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqiekxzdj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtiphqkhia.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtsknzezhb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gttbpwpjcr.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtoaxcrnfc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtywackvmm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtehxuuugm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtrpojnuba.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtmnvmdtab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtstgwrkau.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtbddcrfhg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtqrgfkugu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gthwwlidoe.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtbgjcpnlt.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtplckevev.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtffghbolt.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtzdtpwgaw.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyxtfcgab.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtoftobesn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtsikkxmwu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtgmzhirki.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtrrctxkip.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtpsjzhgcn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtonyybnjs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtuioqouxw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtkvrveoif.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtfnxrirdn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtnuaffsnt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtraqcgvad.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtotmznteu.html


<!-- 参考信息 -->