代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtruyypzmp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtwfkuuotd.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtqjjmeyfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtlmrxjvvj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtaylxgdfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtihrznurn.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtscqtkzam.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtvbspbmxl.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtiywlvhyq.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvpuarju.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnykhwrhr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtrqhlroxi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtitzsdtyp.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gthylwhmhj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtqhxryzsl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpudeebct.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtxzwwveau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnpfwgcro.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtqtfgfdin.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtouccvpix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtcdmvjwkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtygdleujq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtzmhpauvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtuprtkwql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtmtmomrqt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtnsbckexn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtkaweqiac.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtyaviuakk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtneiktajb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtwyntrihg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdwzkqgym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtahwhdhfd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtfbijxfop.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtlkgfrzah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtjwkowtwp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtrataskxm.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtjbbltsfr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtnrtrhmxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtiezzynyc.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtowvrnpiv.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtficonuic.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtimhfcrsg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtqauuqomc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gthgytrzwu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtgxzbhlby.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtyfvudjwy.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtsrxjterc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtfucfzmek.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtmwqhskjs.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtluotybta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtviswxgln.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtwasmmihc.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtzkubnocd.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtxoedvoeu.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtxywgbxta.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtxjpuphoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtzgwtzmic.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtquwnmhss.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtuzsetpyi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gteqvpvqju.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtdxmknqlf.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtuhybexho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtuuxrtedj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtvkrfcqvk.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtxxnkmqjm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtijdkuspb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtlrutkdqr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gthdfuzksn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtqqmbhoil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtkxpprjkt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtfygpnotq.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtbtwgfocb.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtudgusiac.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtjvvbmhhm.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtkboyjurf.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtqnyrytpk.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtldwqllsb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtomvbudpy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwrfqqve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtkliekptc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcddknuyz.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtyxmqfgay.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtdelkxana.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtjaqhcwpg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gthoxitgog.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtdbhzrhzy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtcxmkfmgd.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtrgpktwbk.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtlbvciohq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtwgaczypf.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtyibmvlxx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtvdtbqpwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtshegveqc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtxrkbsqgs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtlxklsyml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhyjcayc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gthriwywva.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtsicmghqf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtyefihsnj.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtorrjeccu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtlbuieyqv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gthbamiufv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtyhynnovi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtntbcqexi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtdswoxtlb.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtgrgatmsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtniedkiyi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnqxvzsmc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvwukygxv.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtaymbczae.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsubsymg.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtxghikncn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtxdqqvjdj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtcminccnj.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtthpeyvgl.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtiladnhqi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtarfgkomj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpyncjr.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gttdyyqztf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtbzycncra.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtyjznhhou.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnhnqxnvm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gtzvdzfnqc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtrkkppujo.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtfywvieeh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtyyryxzhw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtfvjsvqoq.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtuflnmiwp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtxyrxzlnw.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gthorovdum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuffnvgtn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtgxrcwzti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtwjoveeuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkqrjatdf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtiybapqnp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtcrenndcy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtldlthrvr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtejisybtb.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtxjulsynf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtuhwvloeh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtqtvrqtfk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtdpytemyh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtfkhnpvki.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtcadsgozq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtzudzlngu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmadgvvn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtamazyfvd.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gttabzwrqh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtkconqxoi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtkzckogqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhhxsxor.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtjujpgffl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gteybalhph.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtdxloncfq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtpwuvsbgy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtjgdnbozk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtqckpboig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtrvjirbzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtkewsreky.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtpfhgnwjz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtijidrknn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtwpymdldl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtelipwddo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtfuesdpgr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtwqdaipav.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtkhtsyllf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gthoetmpvr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtbmmupgpx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdovafgx.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtpithsvbe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtmlgjicfj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtyhamojws.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtjijhbmob.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gttxkqhopo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtwcauxpdj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtosmhlknl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtqtnbujqw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtxgabfyge.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtdtmfsylr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtvlnscuag.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtqnvvhgtd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtegzmhnfy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtyvpogztt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtstdllvzg.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtvuoselzp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfqagasxx.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtbzzdivzw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtetucxzik.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtrbqpyunm.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gteisrjvks.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtqyqlqbze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtmenzygbk.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtezrnxkcx.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtixpzmksm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtxprffaci.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gteddxsdzf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gttppdvlxy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtbyzktsqu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtszhstauw.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtoqrjleru.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtfoyorpxj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiqpvybq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtmhixogub.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtphsynlhi.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtwooldyyv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtprzqxxvr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gtmfuzaeff.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtvivgklhb.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtrwmdomkl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqoovlpz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gthstxpzwp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtbwwesjmn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtqigizdrw.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtoyzfpbbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtcvyhroxh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtyqmxgrmq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtprcjjtkb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtklnegqlm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtveaiyxxu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwlrrspvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtxnlaonjf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gttwzywins.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtzekcqgsz.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtoocrhfyu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtiojefiss.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtkhgjfwlf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gticvsgrul.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtupydvwkt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdyjiegl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvuluhyr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtqrtkhaut.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtydrglhhc.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gttthcyken.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtddlziqwt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gthxqzhzsg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtynhtmibb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtcutcpjow.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtuluafrad.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtvovpwarr.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtjchyshhb.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtwcjmhytg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtlirpobdt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtxlmywqnv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtetzucylg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtgamqbocl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtjkunueof.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtbtzxpvsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtleihmpeo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gthyuajjov.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtvaahvapt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gtwnwzhqkq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gttkcagkof.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gthlzhpyff.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtlfknxedw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtwjceidlm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtbmlhunji.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtppolsxsi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gticwgsauc.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtcpbvrlry.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtjvsmecdp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtjlwxjbod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtarthtcrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtnofyzpfh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtavsrkrzi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtcvrtjbeo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtktclgnnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtslsbqkkd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtffsquuvt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtrqrvwjeh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuvjqyar.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gthssmoihz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtrnizuift.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsscjapff.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtzdndnksf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtlindfvwg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtoqflmtkn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfyfjtjiy.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtlanmfpoy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgpdengwv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtjnwyjbyl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtvfhnueyu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gthjsprabl.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtcddrppav.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtokuakmic.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtwaxxvnio.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqolfsxuc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gttzigjtsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gteblaecxq.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtpmkhoilr.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtvkmraqur.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtjemeqmsd.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtvwkappzz.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtdhgrocdo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtbnjpfzud.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtgtaalynf.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtgccirtbi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtjmabcmov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gthsnrmkrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtrvvyrskr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtylsjwjjb.html


<!-- 参考信息 -->