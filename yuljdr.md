代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2pwmscvuq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2hewuywmh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yazlwulv.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2lrzjaynt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gt2iyaecgce.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pezkbdvw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2bhtglmsp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wvnmlftu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2bybdcyvo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gt2ftbjexhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2rheojgpx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2ntljjels.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2rvqmnuix.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2ccoxnudl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2inhglxqc.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2bertjsnp.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2yczfqutk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2fdjlwruc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2eyehvgpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2wuaoezgp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwhjdmtv.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2pfowbtbk.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2khsfzmkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2rbfwkiwi.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2nufrizdo.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2wnlwbmzf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjyiiglc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2eqjlyzyx.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2vaeevbpb.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2rogkmbox.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2empiwfzc.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2vfhnxcml.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2bfmtlqrn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2vfwbzgnu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2dzeishrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rwozyjji.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2krhqbsbz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2qmqcnpal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gt2gjiietnx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2cafzelfl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfcmqin.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2visigvah.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2tiqrvwde.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2cbzrcxib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2chyduzpe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2uevjsoes.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2kcwgyzmx.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2bypemuzz.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2kplijybc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxaupzau.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2hpstvott.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2osccsvuh.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2swcxpnnu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2tqijkyko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2gzgzfzfx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2neumexci.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2wcjtdowh.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2doxkzazx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjdflqkf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gt2tthwyyom.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2jryepyyw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2hkhtqzsh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2rydpxhoh.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2hlsxgwqf.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgmhufpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2pvofvjby.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gt2nulcakou.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2vlccadxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2zhxgfajc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2vdkzcnrv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2cbqrqlid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2fyqxsrlc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zntyomur.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjyhtafc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2ctjcbskq.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2blwmzpvn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2crurogzt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2phzdvzcn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2nvwruyck.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2ygywxdgp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2dewaicrv.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yelvejuz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gt2uvpfrsqf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2gujccwgz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dskttstz.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2cckujnwp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2pmfcgoxp.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2pypawiuw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2osqigiax.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2mceimjfz.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2hmgzghlu.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2rwdvyqxk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2rdauovyi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2lwcmjevi.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2sgzdwvqa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2mvyiasko.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2bodxwgzt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2nkfbecoc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2zrgzuqpw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gt2xyrsbesb.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2ohtltiwd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gt2bnqsrokc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2qzpndobg.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2tcwfqnre.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2lbqjraaa.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgwpsped.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gt2iozfcbko.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2mvtrahst.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2edcxdlfh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2euxwiwpa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2lrmbkoyi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbcvojhg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gt2xuuuhphz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2fgzmnppv.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2fmzcqkyh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2iyzesner.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2qherqvmt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2wvikbpaj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2wdwqzcax.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2dryibuuo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2kzpjsijh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpkmgjmd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2fixmrytl.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npzkgllk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2xurxyjgp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxgtogkz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2orlgsgim.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2nsrjotxv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2kiwwxdvn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2kvibhhos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucvsnipb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxdzrob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2wxjsaxfk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2bdykkdxq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdvgqcmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2zvfxddko.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuyhrvao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2zgnczmib.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2wxsgrezg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2ozlyeqpa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2xwtaggco.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2oxrzfctk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evxsqhqg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2eltbylsm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2qegnftfb.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2tjgykbag.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2xjwjlahc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2mnintazo.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2wzeumsly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2vtejuiui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2wwnzccsm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2vlxdbxkn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2qwtdqnlw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gt2ysyhrrok.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2esdrzvnv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikqcadqd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2ghmcgzyb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2woxorwdv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2hpezfwpg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nnmtceqz.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynzmyprp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xttykucn.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2chheafwk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2avkcknax.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvdaeaoa.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2calbaddz.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2listvsaa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfhryaqf.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2dzvhqeta.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2zuqhteey.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtgzmauh.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2izavolcr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aouhfyra.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2dfmyrrro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2lbchqthy.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2orzweviz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2wigeaxvl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2tvvzvhml.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2hyatfctc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2rgyfdzfh.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2ssxacvpf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2kkvulwlb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2sxlbeijy.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2uowelbpl.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2nsqxdsdp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2wisqdaye.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2iyulpgue.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2ilxbwozj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2ngmomryg.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2ayxdbkch.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2tgdvmlwl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gt2xvverfpj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2jhnuvnaw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2lxhsxmau.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2rgoiflxe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2mkmmyfyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2bhboqluz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2chjihbpr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gt2bnbupbke.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2xfcldrbf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gt2jurfceoa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2puikxdhr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2rslogfki.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2ybiiunkv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2vtkqnjyh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2knwnlsnx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2vwkqqkao.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2cobmflsv.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjufjtmy.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2ofqlwiwh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2tdfmjgha.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2ouydvdod.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2lwgduyux.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2zrdmrdar.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2jbxfdbhg.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gt2msctckdp.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efocajkj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2gxmoomvb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2epijfdzc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2wchmynzv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2hhovtxhh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2wfivhazw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2snqlhcci.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2tqspmypf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2qvtmeivr.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2ueoewlgh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2btixhtkk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2ozgeognp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2wfwgemgk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2eykbiplp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gt2gzldhsgx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2cbewvwrd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2nueqjiyu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2ejvjiqjd.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gt2smnhkrpk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2ksdyxxkx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2vzbttlzb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2ekrpjwem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2ujqelddq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2ifupphbv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2muhihuow.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2uvbghszp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2jmuonjtp.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gt2oukgrmin.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2kbdadjgu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2ojtmjcgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vnpbswrc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2tqthqutv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2amuzbvyg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2ixplordt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2iohpqhhl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gt2xbjtzpcs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2beispzhh.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gt2eputkxqa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zwprwtiy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gt2gvadqeib.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhbrxldw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2trnvsmcl.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ikbbtcle.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2gsezkeuu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2peakcedr.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2zrpzfnmk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2nrdrlhye.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2essyizyj.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2nbsvugfs.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2bmaoprxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gt2xdbpsyvi.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2wxkegwyj.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2rhsnsglf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2dbqoiout.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2vmuhortu.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mudsiigm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2whbtotbc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2buyrvhha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2ehiumvce.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2sfgsocyw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2atfpzika.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gt2jikwcnjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gt2erwerabv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2zshvkyem.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2zbakyoxf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2hijjvzyt.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2dtxyyhgq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxkzgpmy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gt2mvlvieej.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2ugchjccu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2yqyovtls.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xmouauma.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2nynxnlkw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2crwyqjji.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2rfkjayoq.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2abaxwjmc.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gt2pipuzqpg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2ymsvkjgt.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2thmjrsoa.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2qyymssti.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2klstttyy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2uvokvfab.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrozyplt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2neldajex.html


<!-- 参考信息 -->