代发 wailian999

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gt2fofgpicj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2gxfyzyuf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkpvjrkh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gt2mxfjrahr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2ffyozqba.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2afklttgh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2kshwkpgq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtpflzdq.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2nkkczgpy.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2znbvnemq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2cmfhrocf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2sjmgjojh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2ajxyqmwz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2usaijunv.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sapehgtc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2fpzopszk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2aeiixqlc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2wjslbalh.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgyqtsxz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2vjiujiyf.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbdzlqnv.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2yqllqkpn.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahwrwjoq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2rvjlmvbs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2hnjoptfa.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gt2rpzzklje.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2guayvlsz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ktwfkilk.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2wadrryyz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2yaeimneb.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2brbiwizi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2eaglfkby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hydrriko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uipzsome.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2indnypsn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2zcxqxlew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2qdqypekj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2rghkptgf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2kndgpktd.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2kgbihwen.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2lhkoiaps.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2bssxsfsg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2qunztqlm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2hjvzlmkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2jthckvre.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2poucugrs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2gslvvife.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2uhlgozuo.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gt2livahmpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2qektskyb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2jalitsjv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lucqwzyc.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2dyvwxicb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2bjydzflh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2yhevxxgw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2zuosgpym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2xidyqghi.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2vkwpiwmj.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2oefhcovx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oahumaxz.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2wukxdiep.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2emsheill.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2ushcvwft.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2mxeqtojc.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2fkelytmo.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2vggzfovk.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gt2otxipjmd.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2lyfysexh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2idmzelxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2vyfatxov.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2mjczrdyb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vnpivagk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2ikdmricl.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2skxltamn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gt2kkvhmuri.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2wdtffggd.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gt2ihyykzvy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2fcusmklp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2ahszxpme.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2xotnjgac.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2vkwuukvh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gt2afsffgyv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gt2dljnecdk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2rkuenxkh.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2dntldmou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2imerrmko.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2dilnuzii.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2blatvlln.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2ilfrhpzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2gkfqoudx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2nbujaxsz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2elplebre.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2dxwfkpqo.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gt2dwabbfmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2ylwepsed.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gt2hbcfthyn.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2rqorcrda.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2gpacbzuj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2salpnxzu.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gt2uialbrxh.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvvpfibp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gt2zfptmugo.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gt2sfcusuva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2tfcvhfzr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2iohzhfcr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gt2cfwskgzn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gt2qqlobcuv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gt2agblgrvt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2dmsiediz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2xlxnkumm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2piolrzja.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2iubtwfdr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2atmeodhw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2atdzuorl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2tavkbsog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aukwhbqa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijwxdqxw.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2vpoiytto.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2nuornhef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2aimmxthw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqfdmyyp.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2egamjhfb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gkmwqxgg.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2dbovytsn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2uipsherm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2gxjnlxzd.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2yjcamspx.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2lxefirii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gt2hxaivwkw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2thgfghwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlfddroo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2xgipiwvb.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2xownbxnh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2rnxqgufx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2owfhitrg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2rvpbyaal.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqwmdrgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2ejuczemr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihrhdfla.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2vgcnmvcu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2getjyxri.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2kniajygq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2xzxjnkhv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2fepcsokt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2hmiypmre.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2owihnzqj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2lybwwbxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2rnbomhwx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2aongvwdk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gt2mvwaiukt.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2srncttkf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipwbnldl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2oazuuqbj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlsbsjux.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwsqdngx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2lskwznrh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2owrlowks.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyvwcawa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ekabzkel.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2tlekdqkd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2xzucuiko.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2huuwdyix.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2uhkdybsn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2nfawbcmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2pxkebzay.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuophoex.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2xqmtzahk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2rwvknfdz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gt2apanfulr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2uyfovdcc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gt2dwhnpxkx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poztulau.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2vxdoaxcj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2psfngdwm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2rvlagtix.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2lpepxktg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2lfaxwsyt.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2dflsqozc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wslbhvjd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2kjmvewmx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2cwvvxefx.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2qtnkirnm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2bfhvzvnh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2kdlvpzxu.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2zblpuplc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2ubxxgylk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gt2bxzrdxmz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2qvnebujx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2bidvqrcw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2htflueua.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2oxuflsoj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2zpgmjzko.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2bybufuiv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2ugyvmhdo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2rzglkuqv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gvmrrrzj.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2evtpgerv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pbrhrdlz.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2pcldwdxd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2abtpcxtd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2njpbktjz.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjaskenk.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2xrgytmdt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gt2bhrtsvdd.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2qkmlrydo.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gt2vcenzzyv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2mormxnds.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2cqwixspt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2nogqtcqn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2jfusmkts.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2tspthjaz.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gt2dpmptwoz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2clzefehd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2qwwvpqjd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2bedhkbki.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2ennryxpo.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2zkfncofy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2wvegyhku.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2jhqgsgln.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2vefcuera.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2lmopsavl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2ntnafyek.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2wcigkepg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2gxnhrsrm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2cbzpzlqg.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gt2tggbmzxi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2vgnkkisx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwucegvu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2vbftqqun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gt2tfbkbiqy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2txblewou.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2ipecdmtu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbjqipuq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2jezclqpm.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2jxvxqyva.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gt2qlktgkba.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2zizlserq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2nxrfixtc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2wfhlgldk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2pyiytxvg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2khzzhhgm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2vkvzfxca.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2gnwydzsz.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2igtrfaxz.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toelbopg.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2lkysgklg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gt2zjogzxsd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2mvkxnmvk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqwqbinu.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2ynbwxgkk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2gmzcdsrb.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2hdozidem.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2ahswssah.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2gzadizjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2scocyssx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2zodvnkuw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2dfhkegtp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2gntxynyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2syrzqgti.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2ryieedzr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2leqclcmf.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2fabwscax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dphgkasb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gt2rfthwxng.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iouvwvnj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2lwhacekz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zheunyyp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gt2xspdtzrh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gt2pntcwftv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gt2mdvyinly.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2sdmzsovd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2shykchwr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gt2pphwcewz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2kaarkdjo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2ngcjxbdd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2beqhvcpy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gt2rzkylxea.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmvlujtl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gt2yazqywpv.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2ncbixiuu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2brodxtfe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gt2xgwgekqv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2gmvmpugp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2sbkbhkoe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2jcnxgokp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2mkkldibw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2bwhecrib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2ysqpnudv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbfkzcgj.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2fvemsrzp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vunzoouw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2iamvxvxa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2ayqymimb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2aslfsloi.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdfrfivg.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2icnmzsus.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2ulgicmfi.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2fuutmtzv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gt2uwmzkgzf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2roxkycso.html


<!-- 参考信息 -->