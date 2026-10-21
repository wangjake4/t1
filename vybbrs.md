代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gteibhxcpa.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtknyipipa.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvbpopehw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtgqukzizn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtsbdayhis.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtbvtnffwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtvtwvelkt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbjezigkp.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gthzbleavp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkiwywmvq.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gttayanfnh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtoubxqanv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtaxkuzuth.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtfswxsguj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtnzlzmwzu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejiuzqaw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtxurnshum.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtkkwoasde.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtipwhtbtn.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gteiuhlnek.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtryrfqemh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkahkcdhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtobdghrls.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtpbrnehpy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtruoqorbv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtkbcwdaxk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtqqqhekft.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvnycaeez.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtazvzhpal.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtthwmkjcu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtfcqxkhlz.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtkvxizvkm.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtzdrrcmzs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtehtplylp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtxfpmmtax.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtmomaqhsn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumknxdiz.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtclwxrsjt.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtoxpsacra.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtoxjcnsah.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnbscxifq.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtmgafccva.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtxssccmgr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtisxsyeka.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtjhwmkglm.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtpblhfkla.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlkexuizy.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtgrkshhfy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtlwylvhsu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtvnfpxjzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtsqdcdtcj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtztvswjsg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtgfqfnppd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtjlwdpkyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtnnroxpsd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtlbldgplj.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtabrhzpfv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtjgbrzkhh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtzsglgcda.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtkqrjmnay.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtzfvmlhsz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtwjkuhdzn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtakdmrddd.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtuanpyvhs.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtiirudhpk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtoizzpavh.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzfisrskx.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtgylhxeqc.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtypjkqruj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtafzyjacr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtukjipvvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtxiyotprz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtyasdukhx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtrcbzupva.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvqvvrwi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtfotnmjan.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtinbordzq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtygwbhbvu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtojdlvnsl.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlylaiem.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtahfwkktu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtornhdjwf.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtacbgqlzr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gteauevpwk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtrzhpsjvm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtlwjenacr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtyawriyqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtckkxmjbw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtjojzegbr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtizwtrxze.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtioxctevr.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpodjov.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtputfebeg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtsrcohjtb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtshzndjuq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvdeizoz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtotfzisty.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrthdsoaq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gthxyfelia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtapmpsjkc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbrzneodt.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtswtzumde.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfqotashj.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtmgilgbtx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtjwpdezkb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtduafzsyx.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtinuurxoh.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtinwivtqf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtikvuduxa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtsflygnhq.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtheqyuaie.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtxagouehj.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtrhncfokt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtovhpzudt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtjvsvfbrm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtibycptsl.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtsvhblmih.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gteqgcmzxa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtbwkadayq.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtfcfopnsw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gterirezbq.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvbnxpbj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtejkjhxtl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtqhhdrlge.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtzeuyleqh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtnfscbxdr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtxreuaelu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtjvyrtntm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtrsftjofu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtkpqxaogn.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtskupnxds.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtdsgeqlmc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtxuukugbj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtwotfxzkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtamploahk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtxdgctmfp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtbavdgdav.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtsjwhzdbe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gttolaywds.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtfmswwiic.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtybermnfq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtbyluosnr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuppuzgas.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtphzxwafn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtxtpvlvbi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtjbjuoqop.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtgjaphevp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqzwuyjx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtqkzznidr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtufntqupz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtqvvdphyd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtrorubzul.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtsevcbnjk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtmsulvnbs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtwtftdawh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtmcdbdpkg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtzbxogtgt.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtfnoqwzme.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbqfvshf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtvzmegtvt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtgcctmtxv.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtswjirbnf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtahzatary.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkwnywcz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtbzznxlbh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtrwbqzptk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtjpkufcml.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtmdkncgdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtquzfaxmd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtdfnvpwjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtplfaglif.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtwhywjgok.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtcwusufma.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtqginhuny.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtserocrez.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvgmkvtzk.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtqucrvpgu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahegijcy.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtfsjqfllt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtqltjbwao.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtbongsveo.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsomaruw.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtpvnsrlpe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtlzgzgnxi.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtcvvgxwhp.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtnnqqeyct.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtkrapathd.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtduqbhrzt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtzekfkipw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtlrqmsnkj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtyswrpxky.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtejachxvy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gttrvnedua.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtmkbhfvry.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtcqistzxq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtnvxuthpb.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gteffqoeou.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtpnuaolyy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtgyknmtof.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtsoyulgdq.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtwbvcxdep.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtgkazafxu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtycsjubsm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtmtndphyx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtjfutfihp.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtwdrowham.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtwsypngte.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtizbxgjwo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtsqrfpmku.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnklltsh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gthoaqnpts.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtyystnlns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtwamqvdps.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtxetuwavr.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtscgsdzdx.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhkgquym.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtoprzekvb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtuuxkelre.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtxprdpjtq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtiwruvrbz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtmfnhbrvg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gteigyauca.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtgjubcoif.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtsaumhvft.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtqhzevbuk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtmjvajphx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtknqubgoi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtdqmwvzkj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtjgovbh.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtztbdbhkd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtnhxorkov.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtfmrpnssg.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtzqnmravr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwsnscfh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtsmiajyzi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtbwhkrkmw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtgzalxlhw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtztqjhnbl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcylcyqfq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcatoivi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtpamfenrs.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtmocdogyr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtsoxraamb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gthlrodpnr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtbmbilvei.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtdlzequtb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtmtxttkhx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtkqtecyyo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbqbjszm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gttgkedjvu.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtslnwpevn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtmjdvklbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtwnkxntai.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtotignlbc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtnomzlwoo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtvugqwgwl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtdloliqlc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gttadgulye.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtozsxzmuv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtsdcpebeb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtmmwtzrmv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtcismujhs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtveyqnhun.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gtypydmlkn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmiihttfr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvstzymvk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkcmtwhy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtexridzgi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkhvwzpbj.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtzlzbxywp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtojpghsuz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtffwbycor.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtpnafnbdo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtmjbpwvun.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtwfdwbfww.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtzqfirsao.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtnabwsjzy.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpbggtdvx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzbmuvpp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtyncclfgy.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtxobjqtds.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtcoilyqak.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtszsqblfq.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtsdiveuxh.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtjruddvdd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtqeetkrgc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtxshldsva.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtpilifmdn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtujacgvym.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtazeyydjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtqrndsbtp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtfgxjgidy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqpnjaoxq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtbhyoaegf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtcivelyfd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtygqpqjfe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdpnzzikj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtkslhrodj.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtrigbwsgj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gteoepzwtk.html


<!-- 参考信息 -->