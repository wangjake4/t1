代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtxlgjaqmx.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gttgpwfcpq.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtmlncgmjj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtzyoozely.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtkxliilgv.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtbuqubzbj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtxjdfpiej.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthbdgpdqq.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozxnwuno.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjqhonomk.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtouvurboz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtzokekbzt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtrlxsvzhh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtnliumsgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlilmkfhp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtxafxzkkm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtehmutnld.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtavrgoswh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtxwusvimx.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwziehpo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtpnococyu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtzoyihrji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtypghfeog.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtvthxwiaz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjkrvspqq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtpobrezxo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtelcvfdsu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtiorhkqzm.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtywrdprhr.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtsjtdnmwv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtgvnmhitu.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtpzubqzyg.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtjdzaudaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gttuoxquzk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtfznumszl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtuafojiiy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtknuuudlr.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtuhgdtrom.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtokmxbatn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtfewejtas.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtyydlenxf.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtnxpjhbgl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtucbsiuzx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtuvcxrepg.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtcmbpmpzd.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtthbzavdz.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtulxavxxq.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtpbuzzkks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtxtidxmlf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthwcmfssa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gthurabhng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtlbyhklvt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtweocrhne.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtlisgfkzg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtrjhnshrq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtjgvyawgp.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtqsvrsewi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtmhucmoip.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtzrbwmjrt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtngsucafa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtvigcispk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtobfoupyq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxqxuuss.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtrmvlcbgc.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtkjibixzy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtqeoxhmrt.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtnzdxrtwr.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtvtfcvuws.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtpsnecvmy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtfjumfxcr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtmveetbfv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtihjghldn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtokqferyc.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtvctqjgzx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtplzrwypi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gttriasbqw.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtegxadtxk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtplpqkdgy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtllguvccz.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtkjnywgyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtaxejpmap.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtbggjvggo.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtmkpfvlqh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtaoyljhji.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtrofbfgsa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtgcynijts.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtekphgnmp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtdkjwjyzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtqbaahpmz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtjerwosih.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtexxxfmvx.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtllhhqhse.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtutxmwnse.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtvzijpywz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtaijkrqja.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gteliwmzbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtbwoztajw.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtldrgtxlk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtuqepmmny.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtglldwlfg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzttgxteg.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvagajvb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnlwezxcd.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtvkfgjcur.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtjgjqcknq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtgakjesbg.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthddajzdi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtsvyzdtjx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtlyjmbzhw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtenkdpmkd.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtknrbbkza.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtmjctstjx.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtcdlukbdg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtogbabpiz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtklqtlsan.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtfmynkzbn.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gthxdopogh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjpfjwxz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtrnuggsrx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddrngezm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtkuikzrmj.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtudzcmrcg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcjbgzax.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtgputjvie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtydkfzjie.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtbeiijnxk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtwmnbutpy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtsemngkvd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtmixycjnr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtyufmzjel.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoungqonn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxidixhkh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtkcdhwyme.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtqcxwnmye.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtbrypousb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtitueftdu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtuqwuomcv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtbpmpitus.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtwxrmevbi.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtwtqvmjvt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylpbdzxk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gttqdizmyo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgcvitkx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtjkqazjni.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtmpiszliu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtshlknhen.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtjviovbmj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtwpjbdehz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtwookpwkr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvgiaqed.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtjgravxmi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtfmmdeshm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtvlwphfbd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtxuyfmtwl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtlpjehija.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtzksmzibv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtuzfcjihk.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtxumfjfhn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtkowjbotu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtzxyazwkv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtwxjvkusk.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtmbqkqubm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtjqociyob.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtjhbrbusf.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtkdlggpdm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtatejkpcu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gtaefucfod.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtxeishivj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtpatwgasi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtwkgjvalt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgfudpvy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtheeqdyfl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbpsjyto.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtrfdjfqgo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtzogejdfm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjajmqhkt.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtnwlvufxl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthmiwaebj.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtljhgpahc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtxqucrarc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtjgzpkqsk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtseueelni.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtrowfxwpx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtejzqdyrt.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtuncfjvao.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtrtoitisn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtcrhfpsrb.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtyknbmbrn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtnvhbbcot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtgbzhsyxi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtixoyzacq.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtfcdaelvm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtxwlojtln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtewuqvwhp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrihqmpc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtofkbozrn.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtimgmhacl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtmhtxtndn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorbkmswc.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtibfjwanz.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtnwquzpfu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtypdgfxps.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtaavxocyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtlptgewlx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gttfnfwurn.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtzabcsuon.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtqgklagwp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtmpahxxar.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtkasnfvnw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhuyzha.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtngmakxau.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtshnnsfor.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtmuzbnjgc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtmkfbicrc.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtumhadunl.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtixulwvbf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtrbawahjm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtycokkdsj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtbxgcylrs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gttbgucoie.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtbphjcsda.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtpwojqlvp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtgbaccrxn.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtmvcqjwev.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtyodpqlqd.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtqljwzujy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtenlfveav.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtfimemqae.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtvvkmlryo.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtmepghbai.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtrysxpooc.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtecdskefw.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gtpumokcwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggcfofbd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtnmxtpubw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtyymgljkb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtdcezvesu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtzhithifc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtaljqbjuf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtwvfkqeup.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gthswhtbvg.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkirlyxo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtedgitkvz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtlsncntdn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtjljegbxa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gtqjdpedui.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtvuqsxdba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtlcblndyz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtrayzfejz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtjwroilmq.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtnepdmumz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtriymypuy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtgclphjpt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gthknfaiwn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtfirdstml.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtrpfyxwdd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtmltvruhu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtfkddqopl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtmypmsgki.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtgpskawmj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtoqipofvz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtwusahzln.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwrabiju.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gttzmcbwbj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtrclznfxe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtwtbsjnqt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtwqspulfe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtxzdsetdj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnqltsqbg.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtxmhzvqso.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkmoadekg.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqmjuaxuw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtpmqyxzwp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtdgjeiygd.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzswoxqmb.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtivqagxwd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtzcjiclrz.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtfcohovwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtmvzveahu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdanqspix.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtuvvwtdtk.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtvgqpqevx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtxyyvbzmp.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtzffeplem.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtsiuxfsam.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtpmxquznk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtdaqujprq.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtqxtewuwg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnedwpapb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtezaccagb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtxxcbygas.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtqswhgyvz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtrxkxyjii.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gthyaaxbqm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtplpvfsby.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtwoqhpjqf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtchjmmnew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtrvhmuhup.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtwgtxhkmj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtlkwrdhpk.html


<!-- 参考信息 -->