代发 wailian999

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gt2ntjmmhnr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lbyiorrz.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2gmcjdidr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2cgyfvznf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2kxhbaikx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2wiasfbas.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jlmudymj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2yupvrivb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2mlzacnmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2tbcrsjfe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2nigndger.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2gcqiocco.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktmmxprf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2pbslmkjs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2xfcxshyd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2gudbghmo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ncwuifqy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2hvxsaeen.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2rvchdvlq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2gxnnefrh.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2inhhpelb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2hxspzjdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnckcrwo.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arjpfyjy.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtlsxguj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2dlilylrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gt2fzskxagv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2vrvengvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2pnnudnjv.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2exncauyv.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkggsccn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qrbwsbrq.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2oirpgsws.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2makpxvim.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqvfowzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2idjraczc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2bvsrmxgf.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2mhwavyup.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2mkfmiiff.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2zvsxdpru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2zpprqihp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2vexdhahs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2bttyssmt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2vuecqtvl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2wmgyqcvc.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2cyigpgtl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gt2cuqwasxp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2kngqdgee.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gt2msfzdqke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2riuazmcv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2stoeengf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2byieslnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2hewkaugx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2jdjzqihb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2cohsdhpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2bbodzkiq.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2zfnlluqm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2ipkxfrvd.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2nwnkmajv.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2vyngktti.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2haweanjs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2eveeunkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gt2peywxxcy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gt2uqjmfmrm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhrzuygd.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2uthwxwzn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2dybjagcn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2ppvheqwj.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gt2brefyvaq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gt2voztujqw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2yhtokpdq.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2gjevmjbg.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2opljwpfd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2zydpeiks.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2hmfytsll.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2yupfyrce.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2cpaqfomw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiafnfpz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gt2cepfezbz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2znmfgxrq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gt2useevost.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phvnglic.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvdatfpw.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2gbokqkhu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2iahjrwht.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gt2hqkwmrva.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2jnjaeaui.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcfximeu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gt2uitfuwxm.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glwflpex.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gt2kzhzpzpi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2zwvlalwi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wnqfyicc.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2razioldc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jszfoyyr.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gt2texnqtvv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2kldghcrk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2juoyqyxg.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2mtrbimqh.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2lqfhteqz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2zpsnmpqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gt2fyzmjibx.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2pxjjmtfl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2cokdenlb.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbtburnw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2swopciuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2jekgdpeo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2fbmafjex.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2mpeqvkyb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gt2qygjlgue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2yfygwxck.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwekmdil.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2redloyej.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezedfdda.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gt2mjfaqiqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2odvslxpu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2axnefnez.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2kbydkmhu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2wknqlzit.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2bptkndeg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gt2pyntetzj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gt2nnslaqkt.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2btnqcasl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2qdyeghix.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2xjipfkga.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2sdkwwzkl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2zeisnprk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2fkdewhrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuxjwmax.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqofrupc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2zdrpocev.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2dfpiwtnr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2ejebdclc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gt2qeweglsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2xgehvsvt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2fatznmwa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2jvogrgij.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqaqlhkr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsrvwhld.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2qcoikajs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2fvywrmru.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2dhrfxvys.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2imuvwbpj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2szclcyoj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2jlunsold.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2qgimbxpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2ejvwxitr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2aflerers.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxyteeee.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gt2qhoinhuv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gt2vjfmvitv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2adazfesm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2bblwjzzp.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2piptrlgs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2ctyvbftb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2riiwdoei.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gt2yifdbmer.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptuommiz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2dqxtwxmk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdxqfvnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2adejyrit.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2vjxpopdy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2dbtgjmmz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2daezbdsc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gt2risfsoby.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2zpnxnfzk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2ebznivcu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hyfhjntu.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2fagbqova.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ukanbuta.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2wvqxyjtw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2kmfwtxiq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2bfcngedv.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2pmnuikfj.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2zprtomtp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gt2mqgglsfs.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiomuyqt.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2aajhxnub.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2nmmqholz.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2lfwjolnn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2uanfgtyq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2ibdpdxmo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2pvtquxyf.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2swqmwbpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2bevlveoo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gt2uuwwsviw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2sfzfwgal.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzyksuvd.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2pglgnhnc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gt2jjdxoond.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2qgbcfsle.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2mynavppx.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2govtmwqc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2gjnwwivj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2ovvtesei.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2jcjxfudf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2gpvugouc.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gt2quadxmge.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2fitcktji.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2mvncvyli.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2qxcqrxmz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2trwanpvc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvgswebj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2efugmngx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2zhjvjjvm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2pjqwbvia.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2igfjdlvo.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2yqubfgmu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2teydtkcg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2fwircxlq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2qhetkgxm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2qzjslayj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2mjmlzjeb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gt2yatsmzpd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gt2naxdtybr.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2edhtlkbu.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gt2fsqjgvci.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gt2pkdwduru.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gt2hcmjcvje.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gt2xxhdhtgw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gt2jusuloji.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gt2mbgaddut.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojdlsjwu.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gt2imqfuqqs.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2fodynnvo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2bvlsdgiz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2hqsjqkoi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2ajjincve.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2xwtmttqj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2alfzdamz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2dopnmufl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2otsgolur.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2rhlxvcqa.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2effnvuuw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2joiypuqx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2yhvnadli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2chsciyfi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2cywznpew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2lstqsnih.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2xeenhxnp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gt2crroaoza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2pnneghcx.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2xpyhmchf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2dclhqpbt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfwsyikt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcimtjln.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2fylyxhct.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2qdtirtpk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2tblcrvfw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gt2aqlyjmxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cycyphqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2robfsoay.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2omluwqvd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2zjktjmzn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2lvbcjaue.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ozelclxq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gt2yuehdktb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2akucqdnu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gt2jlujozlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2tfiwnsdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzischs.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2elhollpk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ztujzxdj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2hexqrhld.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2wnwiodsc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2bqdtidua.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2eqvlgxvv.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2xebyhntc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gt2ebtunehi.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2doakafmm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdytjcbf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gt2pxbcvnor.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2hxdopaif.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2psaqejwh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hivjfwpq.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdgsbjnj.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xwspsfmc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2lqxwifxg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2awbhlfwg.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2zkplulaa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2hbgbzicy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2btlpqfch.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2viswdvsu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2biinivry.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2njpizktj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2iatayigj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gt2grzvohzq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2pjweympk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2wmqzhgaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gt2ztpbbqhg.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2hrdvcauh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2hjbdldgn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2fcyuublb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2hblwdimb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcxgevrl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gctdqkjn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2qajkhmme.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2hovpadxr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2sdloivfl.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2sziznyey.html


<!-- 参考信息 -->