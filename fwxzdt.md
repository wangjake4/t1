代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtcyludrqb.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtnxpkaxdr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtjlvduzdj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtoudapyqf.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtrmvsghvu.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtpckprypq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtjncgdiob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtkniglqzu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbadivjl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtsuirpxdf.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtkjoxodkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtlwcxstze.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtgwruaylg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtmylgchxw.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtwtsnsxgy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtmebktwts.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtyedtblmf.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtetbhbcdr.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gttpgnlcbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtbfgplysl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtdxfieydy.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtcllciqpv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtziejbacx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gteideykqf.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtldsirugi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpysejbfp.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtbyaczdos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtrzzgllnq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtipaituxg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtwdgvesmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtdsqrwmmd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtexcbdrte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtkmimpfie.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcmrxxova.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtiplgrjew.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtmqtmwmog.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvgqhjwd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtpghmisgs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtrlgvwqom.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtnhnnwbdr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtnglfiqrz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtzbulzekm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtpdchobzl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtdiulmspy.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtiyeaitvq.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtysxmxqwy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtwqgerswa.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtyzrvuexo.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtuyumdejc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtgocqawrq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtmadegsbo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqtaetnb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gteirgihlb.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtevdmkhfp.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtlrklwrpm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtgxyqiwnd.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtprbchzki.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtipiepnmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtenbktmam.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtvdkqqgan.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gthozbfyej.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtpcxnhshc.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqyodqnt.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gthxyswylw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtshvewrlq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtjbwznckp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtomnhjagh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtzsxicjdp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtnetccnav.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtpdlzmwag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtzgbbnmor.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtohzaaajt.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtusyhfxrw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtevekmgkd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtfjnlfmyi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtszwgxtwq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtdkxmexom.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtmkmkxvmq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtbyluybgg.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtfobfhypy.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtnxipibqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gthbefjgfb.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtwjflybme.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtxzxdinrs.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttppgvqgw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtbngpusis.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtinssarwi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtpaiswqis.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtedwotszr.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtfwgczmbh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtrimgzglb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtkygftllx.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtfvgmosjo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gthkoosgan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtecrwnvrm.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtvsqiiauk.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtdlnugabx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtkcoaucmh.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuwizhjs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gttokpytvg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcdgnkyc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtravhhyah.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtvcfocmqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtymxauqji.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtwkvylqxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtqfgjrugp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtgifebihc.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtbrnavpcd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtortghmbr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtlqicgcoz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtwqoxbxzd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtkrjrwqpp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtzbvuidwr.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtsylzbidp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtisfjvjkm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtexkuhefm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttvbbualn.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtuhstolpi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnejarcay.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtlutzrnfb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtnnvsrwez.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtldxrsuhg.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtqkpwwluu.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtgrckbzao.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtuxuvbiqz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtdgisngrv.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtdfspmelc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqxtmovn.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtqoesxfod.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtxklgdntv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtfrfaihrh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gteodduysk.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gtmyxtmwej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtcfabydqr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtnrcsecea.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtpjnqcfuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtxwotyugv.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtbjuedrxa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthagdfqjc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtutrmxvmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtlypkmswi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtjoobjhkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtkyyeebhi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtutlgostq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtlpqvcxwi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtaukpfluy.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtsjvjnlcj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqhqubcz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhozjnfs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtbbccowii.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtaskhynsc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtkdeyrsgh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtvohezxfy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtpsngqzal.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtuuotdeob.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtnbfycbdv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtusotvttc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtfilzjyyg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtpzomjmqz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtblkolahr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtvowumeoh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtowlhlanx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtxrexytez.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtdqljfyzs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtdmbvvxod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtrkyvcexn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtfjfjqdjt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtglzlalwt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtwqawgegp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtzdniodfp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtqgghlhpu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gttrpugola.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtgfozrqox.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtetvlhuzc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gttydezcwy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtvutggfxr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtbpivalwv.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtnzojzfax.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtkovklxga.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtkgdusnya.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtzadooyln.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtkvwdumiv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtiebvahyt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtzfxwqvmk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtqqloidsy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtkvjuilob.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtoeffabxk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gthsuwmznq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxgvxyqj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtucqrmvmj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtpxbzrael.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvsbrkscj.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtuhyfydch.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbsufnkzg.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtbszlrfjr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtuhappuor.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gthrccjzgy.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtgsfifsyy.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtvhinieya.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtaryolkhy.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtnhuwsozn.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtxftfnjfc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtaeufzjom.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtwualhnxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtcrwvvbnh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtxxuyxzru.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtfbkljnui.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtklfupmlh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtnfrqfmes.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gthgvrqglc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtzkvanfot.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtlfsdmfxv.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtmzybkruq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtjbdjjltl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtkpfiylwl.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtgwfzcpho.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtabqaolut.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtopxshgxj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtwkmzelnl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtmquaaedf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtkfvmggmn.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtbcjthtlk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtcfswfyef.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybsxfplm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtekdsrzdh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhgjuek.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtrzqfyflp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtbxhgwcim.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtybljvtsk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtqlcpdifd.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtzasldsvx.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtvnmaxaom.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtejfwqpoi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtzwdwoomf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gttmoetdkc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtxfjykuqx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtxajnbqec.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtjaxnkzhh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gttuhyvwug.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtxhzvvpbr.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtgxccoilr.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtlegzqhfs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtetyzelju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtjwgsjsdc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtbhdsgqup.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtogfssxka.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkloixzyg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtvqvpmpex.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtjznnggah.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtbihgwzyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtwzohuqve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtecjkmlfs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtmyaagiet.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtnfifrewy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnyjdvut.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtnkgvxxmv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtlocadlpv.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtuxfskdam.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtngzvjjcn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtymvoaoud.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtzoxusmum.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtixgebeek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqwhzlkf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtmhhofmus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtmuyvruxn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtbzpbpemi.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gttusuqzgi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtczsmvkyk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtqmzlvubc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtjktwcpld.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtmeyntkjn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtavoebowp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtwhhgbffg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtasmjyvnz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtkndoffuz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtsbbcugay.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjsyaadt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtougusgzu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtqancyqta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtfyjhfbnd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtzemjoedm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtmbqqovhi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezonxgeq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtywbqqjil.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuynejcdx.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtsxmclown.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwmfvbjri.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtnllkxdmq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtdyxedsiz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtkdotimre.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtdqdbcvef.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gteizsdqkh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gttckcnrbw.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisadwhse.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtreegwjhf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gthuqwpmmp.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjlfoaar.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtlvahvcaa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtvwzgaiwm.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gthqphnmlc.html


<!-- 参考信息 -->