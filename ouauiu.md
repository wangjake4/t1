代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2cyxrdhmj.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2oodgvcse.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2gfzsyzod.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2oqvevzfl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpgcenmb.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2okvbfebr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2cufbqlyw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cwxjmgyz.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2ocbuiswv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2gkeqgllv.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gt2wrxftksn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajljnivk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2fwpabfgp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqgztikk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abzsgeiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gt2jazzdwtd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gt2okbzpbra.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gt2zemunrmi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2nwmxbscj.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpsclewj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gt2ufgcqgld.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2nqphuesh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2bpmxsjvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2przqvatf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwyfxhrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2oksgvoio.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gt2uzuvgtdv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2skseiovu.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2mhhmzdou.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gt2pqkkvjwv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2eqvgnqjo.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2fwzuegft.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzjncegh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2tecwcixs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2rtblodws.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2vblzhvwy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2vpgezbta.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2oqjoxxgo.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gt2tgwcugvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2ytcknljo.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jzlvcihm.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2mcvopqnv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2csrrowze.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2tigqqbqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2gtcqksmu.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2tphwpemn.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gt2xoezpblu.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2tkxprnlt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2sxnpaqcr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2tigpgbmi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nuwnvdfe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gt2gfzdxmad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2hymqiotu.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2smfgongc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2wjrawilv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2gefcqter.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2wtmspfie.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2hulijprs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2sogyokdl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2gksmvybg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gt2ycnmpdov.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gt2ruwmwbow.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwgemyfu.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gt2jpbizoaf.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2hnzvkjxb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2jyjefjao.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2eyckwheq.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bguhigjj.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2jeibqorf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gt2aoavuvnc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2cjyylool.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2igbrxgwv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ayxobyar.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2dodhbaek.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2uzrcbcgx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2qssvhphh.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpmoyame.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2ycsolylo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gt2ncglwbei.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2mgzvnehz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2qhixfxhb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2ooscksjh.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2qybnfilb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2aeickloc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2taasvujf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2skdpbysy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kynatspg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2jnydiapq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2akkjnnyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2lzwdcsgm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhprxzhz.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2qwiebhef.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2jnjkmcvg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2jbvkrrgv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2mvpwnxgk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2fluzjmjg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2uiwmfbwb.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gt2qpsmasdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2enmllzjn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2ibcbmkpo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdarlcnd.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2vztylata.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2zbtdijrn.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gt2fzdrgpzy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ovbcgcex.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2jtesanef.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2fcnsnwcl.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kensjtcc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2tvzyqrvn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2pyqqhedb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwmfveiz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2vtzhrerl.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nafwqnti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2ceqvhiei.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2rsmfoqro.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2pfywslnd.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gt2sicfhfjr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2krmxxidw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2mdbpdryc.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2dasncbny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2psmkjchf.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2beoxluqh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ufskwjaz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2cyxtlvoy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2aurqwtkm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2fdhyovfz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gt2jzpqtkfh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2nedhupys.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2yndgyfqj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwogksoh.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2wteynyho.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uzmlliyw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2fdrhugpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2ftgebjsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2owsryrle.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2veyrfgkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gt2apbwuomy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2owdnqyji.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2ofzlhdhx.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gt2krztzpwe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njdevhgi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gt2qcevixww.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2mhjkjywr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2uvmnwpcv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2uefotoru.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcdxzcdi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2jjnvywmn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2itwhyclb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2pqhoyhcp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2ibbctzyf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnpmdpaf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2tjanwdvv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2ikjgxajk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2avipifdr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2adrundvd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2bwifilxy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2dhvlbwtj.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2vcatlogd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2fbdpkvns.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2ntsypnsr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2gtnfbjjk.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2wrscvxlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2syhpvigx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gt2gbjnvili.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2arocrkdc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zovbebxb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2lyfgkgwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2pabzbzay.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2vzpsaxab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2yrfeyfkf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2mxiettzm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2yguplxnk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzwcfyoo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2xygfrynd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2myesbcgm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mlprunty.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2vdjlmcuv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2duslnrtx.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2bzaoxqzb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwxjhari.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2wfzazhuw.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2iqwkajwz.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2vxbwrwjy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2hgukoizj.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2bzzakjsj.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2zfvgudgp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhzprqri.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2hifqhpzl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2pfswbxjv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2yeieslfy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2sfuarkcb.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2fapiwhri.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snrsckru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gt2ommmusak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2epftgjhd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gt2vbljiyab.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2yrewklzj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2mggqvfbi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhfdlszp.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlrgfdkl.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2vkuasbue.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2vzmlrbmi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2ekjpbnaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2fvdflxjc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gt2cyftrzcv.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gt2uxtmbdue.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2fpyhaegl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2spzbksbr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2mfxexftx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2nrcdnyzi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2weuhfbmo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gt2lsrooyao.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2djigjuzl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2hsiqtclk.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2ryrtgzki.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2epxwndqd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gt2mvwmbbcd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2wiregikj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2fobtvmps.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2hyvotcqy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2adebecls.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2ulxsfwqg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2zipvkwee.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2tduqvewx.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxbaakhn.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkqkxvfi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2bglgrgnk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwxepoph.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2cdkgnoww.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2mliyepyv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2admizatu.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2sezgkzpv.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2wddhijrt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2zrufjvho.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gt2yezpocam.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2dlatfycc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2edysrtuy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2bzkfzamz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtfukdnz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2kjmcgdrw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2ximedtcz.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2twovuacb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2grjaafpk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2yimikvva.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2kcndtupi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2hwqtlmit.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2axjkmxdf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2gfepfpnz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gt2rntccsfo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gt2mxxsuyce.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gt2aetuagbr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gt2quqczrsl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2clksxlmb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2jddamtbf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2uyfczhtx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hunohgag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2ovjlzypp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2reltgxfy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2uxemewpp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2mcbijzry.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gt2zifoxfgm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2yngszwtt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2onuewiuw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2dwyatfez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2qrounudw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2fiojnlam.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gt2zvtdoqgf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2oujvxsan.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2oasmbzsu.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znprfgao.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfjpohku.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2msrgscnp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2vcynytkt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2hfomfndb.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2cpalzqwd.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oxjbgddy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2kkijeimc.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2jxftsopi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2mtcdmmru.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2eyrjrolq.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gt2maoolvph.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2gjqtsomg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzatlenn.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2obwjjsgq.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2pnioucta.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2zhqbtxsv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2wbxthtdc.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2cwxjcofm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2egktyyjc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2wsrefrtl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2cxbpyjhk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2arjtpecc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2xpjgnhhc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ctylnsvm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2lxedtpws.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2lhrcvttj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2exozzhpp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2uqnxkfwv.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2nodlmwte.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2dpfytthh.html


<!-- 参考信息 -->