代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ececelib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2xjssaoqa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eydwqgev.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2qvigucwu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2rkbkxdzr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2tzgsnojk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2wkcntfxq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2hwlkxqpb.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2ejyojrpx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2klrncabc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2wmpxtuto.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2pjqaoufz.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2myqvxqmx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2jhmpxefc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gt2jaaxwkwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrggmjsq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2vvrpizkn.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2sjdkmtwr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2brwvgcje.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2gdemdxvy.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2ygxgafcw.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2inezqxri.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2nmgqdpch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2yzygddxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2misulzqm.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2xzizjzko.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2vqxhgtcg.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2uhjiiirc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnjlshev.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2skwzdqps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xjpjumsn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xwhzdtnv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2lvlrvfvv.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2ajntvrdm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2mrtvarwx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2ggzwduce.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gt2wfllcsjh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wuffokbf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2limqodnq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2dhtnfqxl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcyanpkb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2pioumxwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2rvkccrbp.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2ijhwwskb.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwimqkko.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gt2ponywhit.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2pfwmtnry.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2iltpbtqf.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2gvnsjrpf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2lpholczv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2yrnuqcve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gt2ipnzdkaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2lqclevjc.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oeyfhorp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2zkvswrla.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2hqxjlslw.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gt2obawjhbw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2bhjaymth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2qpknsznr.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2nogcwkyv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2kvvwrxzz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdihmhcy.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2fwsycica.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gt2jjmoxwbo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlphqxow.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gt2vscymdth.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2jgprbkau.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2mljsxypd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2xricgtxd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltubkcgg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2yxkrvksm.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2ppuwglha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2qzjzcbuf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqytgesi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2dwaiglml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2eqdghzlz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2mvlpvwql.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gt2kyaxjhzt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2mfrbtpno.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2imqvqjkb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhgjmssx.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2zxtccgze.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vonxelgm.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdtcqxcs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2gfjcbasu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2pljknclj.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2fkiisekg.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2muaxanzk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2qpcthcwx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2llwhjsxw.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2fagbqxpc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2lqxhvdtc.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2wybqvcsc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bqmoqtxh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zihqmada.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2pxszcqjz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qltqhtmi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2gbobehnr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gt2mltguquz.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2xqditlyx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2sxmuyqye.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2bgoimjfm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2vczqdjbi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2qvkqkqre.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2pqirdltd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2fpavkjij.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxswjigw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxxoluhc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2bzbfidnl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2tsrqmglf.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2aghrbisu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2atmacndy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2oqgzsbxe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2tjshgntu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2blkfewvj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2khxvxkrs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gt2inhyhiqi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2luhdllxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2slthzxkn.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2xvqturen.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkuzacpo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2catsvxmp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2bhpvklug.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2gtnhpznj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2azvskpmw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2rtudpruv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2klbfjlln.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhlqjau.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2piiwduqk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ledusrzr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2gwbspzgr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2xwlgpwpw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2bsrvtpjo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2wfjnqehg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2vjmnrfzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2bddekxwc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2qlzkdfyg.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2irjknsbp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2rbmlnfqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2skonysvt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2vfomyyfq.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2fpvmiufv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbhxjgbt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2rgghweyq.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2gacsydsp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2uibcdbsq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2uobwwgvo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2lppvyacd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2oreasrzs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2bgimsigc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2uismnxut.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2srwfweej.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfixcgij.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2ixdyqnzo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2rdexfauu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2batnmnzk.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2zrtywakv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gqhowuzg.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2itnixdfe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2fjezofvq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2yvexeguz.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2suqxbnhu.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2eokbouny.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2opgoaafa.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2xeyfoefu.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2pdrvgzsj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2pdplzlyk.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2uqjkrvcv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2zvbgedfd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2gpqnvbjx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2bgabmwvj.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2unmsdhzs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2voivdcsr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2losgdvir.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2jaexehoo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2azvfgwps.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gt2ggfsvnkx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2ypefwjmy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2epvqhdfc.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvwhnyps.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2mcbacfcs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2zypyigcb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2hzvepixo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvaowucr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gt2slzruaek.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gt2nucuabez.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2jbbuhbwp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2wtbofpvi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2axuztdjc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2sgtketpf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2gxhhscij.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2javimutb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2ytpjtgdf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2cqrazbga.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2dmcdajsx.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2uoopdohg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2urhqnzdj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2hiozqlpr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2hvxuvqyd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyhyatqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2nrnswivo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2drcmwcnw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhztgtul.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gt2ycjjwjtj.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2nvryddtd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2dnjvwngt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfxmapcf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2qzivllxm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gt2dhlzovuq.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2waczkdgc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2dendbwsu.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2oecyucmd.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2trrbuuwm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2gythgthz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2vydhpqnc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2oaawpvsp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2shvpafsc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gt2dlvgwqka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2buogilkq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjizlsgu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2gqvsfbny.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gt2yoniigvt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2xabqowts.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2aqopgpkq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2mqeuqpxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2dcurtnft.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltpaodgj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gt2blcaehro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2bgfmtgrm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2siswqeur.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2wkaxtbiu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2vzwtcenk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nweiikqe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2alrclhkl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2lvieojbj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2myhhegij.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2guqfxdah.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gt2muhfvszb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2msnayxlx.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gt2hxwoxugs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2hguqomcn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2qkqkylez.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahepjkbq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahdubyzm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rkhgugic.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gt2otfucqdu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2bozyvacw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2begggpxb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zzqhwfpj.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2thpdwrjy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2rhbcwjjc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2rhldhhmr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2adqaqhdv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2bazwkknm.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2pnxkhjvw.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2akfgvobx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gt2isuiamjz.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ggomynfc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2jyskldma.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2saenzgct.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2npvgxpme.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gt2ltmagftb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2ayrtggnn.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2puestnxl.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2phnvclcj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2haokwdqh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2tqbbgtxp.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2tdzrrxjb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2gbvxxczi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2wpfmdcjc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2jkweukvp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2xacflycy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvztospr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2vizspwgm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2vipeknlz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2jbwjzmaz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2uzqomrzr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gt2whasvzlq.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2dbjetbxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2nlcyfaxw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gt2eiwwogbv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2agfptanf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tuaiuccd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2qzizjyin.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2vqatreyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2zsmrvovv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2beposzer.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2ofmdijwh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gt2quwppffj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2zfdvkyuf.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2rickhhal.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2kuqcbthz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2xnjzkyje.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2oqvlosxr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2ccjwnmtb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2biypixpj.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2wgpapkcg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2ijscxukv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gt2ufjakthr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2sqcwyhdd.html


<!-- 参考信息 -->