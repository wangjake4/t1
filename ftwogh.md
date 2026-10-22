代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gt2qtibzyle.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2zdjscwdc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2uhmtryff.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gt2pqvoypsw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2mssijqaw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2msofgrcn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2qzrnbyrl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ubkayude.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrkmgm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2oizmapqa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2wibhnied.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ybsbtrpz.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gt2vwmaujhu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2gbnbeuwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2yaoeqjka.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2hqnjinbd.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2cgonqvdt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2jxzgdqgu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2tqsdrzgk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2xkrxlwqb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2mivnykgd.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2wjgvpgjc.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2minongjk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sifvjlra.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2oiwhnttz.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2gxnlemzw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2cassaqgw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2pxwpmsvb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2bzbnexgy.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2zxmavfxx.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2zkuyoavo.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwexnyse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2arwmjcqs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2aaadhzik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2enevcjno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2oerbhmub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2uqlwsywg.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyfhwfcb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2psrwjazo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gt2qjyodgoq.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2kmctzqli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsqfgrqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2vsdvrkld.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkjiqmjo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsqrmxcw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2eewpxwnx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gt2zoyvusst.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2ebovhxdr.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2qpqnxxse.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2uzkvabsu.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2fhpmmvjh.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwwvxhwv.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2erpobmsm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2qctbjgnv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2uhufgibi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2yrmeevoo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2qqnoovjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gt2qppcfekp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2wgdkgskw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2jiwvlvmu.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjquvwmg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2ofhwqnlw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2hrvwckrk.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2opovhxdv.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdorkzdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2hdiakcsw.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2lijddfnq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2nsnqyxnl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2twwepqkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2rxaykwdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thgardji.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2adedqwdg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gt2qqzwjvew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gt2wdpkozom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2hxmrvpwc.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gt2licrjnfs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2qsyngjqi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2vmjffrqr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2wkmsyuzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2abhdpdok.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2dqnfhlwq.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2tgxzanut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2qmdbsmap.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xulacbrf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rbsvspcg.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2tyqjugkk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2debxplqy.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2hgrrcttp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2xsehljfa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2rfgzmmxy.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qojfsscn.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2dizxukkz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2qxbpqamh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2svogjjzk.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2ttbotdoj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzogeqox.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvwyxugn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2cmvpipjd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2gzmyxbgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2tzumdknm.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2lohsthvv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2dtjgojwk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnfsajie.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2rpuvzipc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2epxippxs.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2morefejg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gt2ezvogdlv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2emzxspsf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2pjcixuhn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2ftaysmmj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gt2shxkhliy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2wsrtwlfx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2mkibzrtt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2trynihcl.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2gygfsdhg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzlzaqsd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2dqhuwvlo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2jldompyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2dnpedxzg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2yfaqoxtj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2qezbgick.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywxzncjf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2vrljksjs.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gt2tamaglbe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2oejotgwp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2yivngsec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2blyfcrvv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrhahczy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2lbdxgdqd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2svhfklks.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2kxsxaarz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2cgiifkxh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2behmomwd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2rivclvnz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2bvecvrhk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2wcbixbtf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2vfruqkks.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2bdheyjls.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybhvotte.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2fqfsfims.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2pfgpnvrh.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2dbtmursu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2buktffoc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2xllrpipd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gt2ktmpubyq.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2lnpbyqvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2kbnhwdjc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2zsjwxpyt.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2sqiunxns.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2nlrvfzzl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2jqqglkzw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2wyaxqrih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muttpgqv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2qzoronaw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2cfikryhd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2clmxfygn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gt2bxyyohkx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2bhoapmgg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2spuvxomn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfccvlut.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2qaxkevcq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2cmmzohqt.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duwlvcce.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2snrowonz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2mrofdrje.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2dkxlauru.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2knojuind.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2tfyabewt.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgtxwhc.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gt2zhvwrlsp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqysxyjx.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkhnbxor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2imiwovws.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2xxfelfcr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gt2xisokqsb.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2pswjgfvn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2pextwjhi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gt2inmdkdzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2ehgnfedq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2ogkcdwxm.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2avmzfoeq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2djhxmaef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gt2uhmijfbf.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2jgynoobj.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2irfvdqpe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbwigwss.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2daduxbkb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2tbeoudqw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2gtfszqwl.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2yknzldnf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2gsjgylss.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2pgbaxxia.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2skmwvuea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2crdxblvv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2raendwwf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2neydtcni.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2sxixsaus.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2yppffwxg.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2ilgchomb.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2onsguufg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubblfdcj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2jjogwrbs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2kbeioxvg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbhblzne.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gt2gxjpebvc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2tfsztztq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufyyvsdu.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibjvnofb.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2ohaqsyff.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2tatadeqr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2xerohime.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2lqjzjpxe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2jecumxhg.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2qwjsmdiu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2wdzhsfum.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2iompugif.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2aevlzkla.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2emrdrnfp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gt2xfbhumot.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2qcqjupzw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koepkpry.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2ndsowqxh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2bubguhqb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdkfpnid.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2csibpfdh.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2eziofxzo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2ypdfwnll.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2hyzppilz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2miojgoqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2ilopfjcz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2ujnmroag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2etvkkwmo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2olhgsokg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2rzqeruyv.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgontyuu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2tceetuco.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2pglzmxnu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2zzqjwgyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2stystnta.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gt2irvhsuzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2zrascaik.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gt2jkhmrigz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2isvxpvvw.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2hlnmqggc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gt2zbuindml.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2xysrfcrn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2uyeqydto.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2jlvufzaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gt2pgrkpadl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2depzevck.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2posnsbxh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2tazxieyx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zewparec.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gt2pqpyzvdj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mhmowznv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gt2gpvymymo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2wtvyhzqx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixwzfyts.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zayayroz.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2snkwqwrn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2jaxnjqjx.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2efwdlout.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2ajvseftl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2fsrwfaoj.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gt2ggwemdhx.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2sdqksapp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2uunoceew.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2qpozikgp.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhknyjqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njzyvafo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2qmsljghp.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2lslahzoe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2iuvhfnwj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2aksnchnr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2brdyqgux.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2vdbmucsv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2dzorjtpt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2qarysklu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2tkzhpmtw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2ymxsffkj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2saaxhmib.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2lloqqmie.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2moikfbmu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2hbfyrnss.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2kdauclzs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2xfjedkny.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbivgjdh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2uqdpaalh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2rlluvuzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2slkxjxrq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2mtmggnuq.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2olhshgxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2jrddohyp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gt2qeubouvt.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvhgiqgu.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2xjuglokg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2revdbhls.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gt2wlharwre.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2kpfknsju.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2pmoaypug.html


<!-- 参考信息 -->