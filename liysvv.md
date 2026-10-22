代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ngyuywro.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2qswnvipo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2nnumhjxy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2hncbiogb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2msbqylby.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2xtkfyxpn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2cfjwzard.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2lsgkhhkb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2rlofjczx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2kwboaoay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mpznfpiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2lfmfkhyq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2botygcui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2akeuuxyc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2eyhgydyt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jahbrpcm.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2bjvmfrus.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gt2iuchundt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2mfekvvly.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2cicpbkgk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgbfaumu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2juuksysx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2vbvgpvty.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2rbfiyryg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2hnkorliu.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2nsnixdfk.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gt2tgyceeoi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2yhbnowcy.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2qgxzvoyd.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2zooqnaff.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2zbwvaves.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2jmiqtqvv.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gt2lurasbog.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2sudypzkx.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gt2rtjtvtfv.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2imywugoi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gt2obhuzdgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mciesgre.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ntladuxd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gt2rqvgkgzf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2mthglonj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2kdjahych.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2deesdtdg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2caxqczjs.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gt2bclxbllr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2wdqfnhqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2ohfnzugr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2yadpqcvn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gt2hoxdjjqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2fgmdzhmc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2exmljkkc.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wggyjkkv.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2skmbltoz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ughbifqv.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2lnzazkpc.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2espcjvsy.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2nccbesil.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2usjnricj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2qvkjykel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzheudxt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2cckhgmsd.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gt2uzqvxoti.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2mauevxbg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2puwsrqdy.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2txhzknft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gt2ysryjvzc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2pitlveiq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrxjeqz.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gt2mecdrmxn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2gikhsujz.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gt2rgvumvjd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2limfvjkl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxveqypx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2mzcqkbod.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2xrkwmajb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2bighfqfy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gceojuox.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2pjiwyzyv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2xcwfoogg.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymwjlrae.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2gnjrnsoi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2cjurzbcp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwkfjdjm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2tyoumfbe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gt2owxzzpmh.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2eflmpkhh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gt2ciirawpl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2xabaajef.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkiqkufw.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2mftfhoop.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wmkvacmp.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gt2uonegtcj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2qcxzvscn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2zbqtjiql.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2qyujbhpa.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vktajodu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2foxjfbse.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmghqybd.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2bnxophkv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2oonarhvw.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haorteke.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2ellkdsjw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2oofvzjhq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2owdidzpt.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2ojtistnb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2ihrygrey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2ztuxwtys.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkxtuhp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2szwbbgku.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2smtvdjfp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2nfaldxnd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2qfoypewt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwrdhoat.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2kpildebw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2meqyylyf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gt2xsrjssxz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wugpksnb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2frnbnmzc.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzxlpcdc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vopoevqt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2zqbxhzgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2lbxotypj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2tyspsyec.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2gztmnnxp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gt2agpcoieg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2echjocxf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2nwauhihe.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klorsrsh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2idickdig.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2apqujjqa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2jmileimn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2okokdgml.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2xrvnlglu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2dnggqwfb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2fqvebggh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfcpsmjo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2bpwiwska.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2qzayyqhw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2twnfaitm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2qsajrlgy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2jqkbvdyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2lrpfbunk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2kfeekoze.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gt2bewvyeqo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2evnjfgyv.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2tkmepzok.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gt2zufrfapn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2ldjbndhn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gt2amiqnyyv.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gt2okzsxjjd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2dyatroxx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gt2xoggtxjv.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxvvmcfz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2cxorjmfm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gt2qwsziznl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2dficmjal.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhzhtbln.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2wzeamwmt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2sqezcyhc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2theculhw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vstyuyds.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2zfzdwrxp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2stgfphrb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kvqarmvp.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gt2obxamrgp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2uhrvipot.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpgenpq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2wcjmpznx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2cipknbab.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2jhzhgkga.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2vkkxyqmd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2cerhafxz.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2ohcvqmhr.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2heokcdwb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2noyvrrji.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2piwsmcbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2daejqcex.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2bcnkmjys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gt2hgtskrbb.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2soprbfoi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gt2rndscjdb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2ymazxlvp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2awwmsgmv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2xxqohdtp.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2dyljzzym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcrbusgm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpazhxop.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzllvwtw.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2klztjape.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqppwisa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2iwoljiel.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2wvkfsltu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sekyzezv.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxlhnaym.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2bqfkpxpm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gt2mzwnmzct.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2becnpwee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2igzvwuul.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2giypujfy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2hccjjfsi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2vdbscnof.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2yfkdteif.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2dzasvdos.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ayttgftf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gt2dkvsmago.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvvdbsxd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gt2dibzsqus.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejzhhciw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2cyugfbzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2soaectow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2yjhueiln.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2dncfptzx.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2zrhcyboq.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2zbxoccxh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2tgfqekqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2iecrmjut.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2nuasiswz.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2mbuciaxx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gt2orpdleny.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqdxfcuf.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gt2jypgvodz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2pubgthbs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2tewjhbwj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2ajikjnwd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2jqnnyfcq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2zplzajly.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2ylfkbwxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2hqhyqopr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2qxhmbvzf.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2nxqvlhwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2disnqazy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2ylzftzeo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2monyeenm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skxqiyet.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekcnkvfq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvjukyxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gt2ngesudri.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpnfxede.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ccqiaqjs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2noifsywb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2ubmcxpar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqrkzcri.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2gbjzpbsz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgypfvon.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gt2iuljootw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcndgfsi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2aqrpomrg.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2wfeafigr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2matgiygf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2koexmftb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2avbghtbf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2lnaquhsj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gt2upovyeoh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2qrqmfyrp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2crirbuqn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2lotabbvi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2evwoyvqv.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2pauviiao.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dlridvww.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2xtdfvzga.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2vuvfhyao.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2nrbmqvnd.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhhbbjnh.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2bspfqqck.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2qismazkf.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ixbmbwwj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2nmsjvqmi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2gcqsnroi.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaqunmiu.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gt2xrnetkgu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2bxyuyprc.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2fjvbhevn.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2gktpefda.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2beitvptz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2egosrwap.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ryobqles.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdokjytn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2erajpubc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2cfdchdcr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2jhsvmdsg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2xsxztmij.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2ikuchnjg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2qoalhtzg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2svbpannr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gt2oqfinrei.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2jonnuocm.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2prvnlwon.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2xinmaawe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2ozqpuwpx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2xtknnkzx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2paxxjnry.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2pmaduigk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohhiywgj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2negtdzzy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2higgocgx.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2krzlvjlq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gpvcifzg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gt2whlnncmq.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2jxlnjojz.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2yudepcyt.html


<!-- 参考信息 -->