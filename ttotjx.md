代发 wailian999

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2bphajqgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2ozlczzfu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anuatnwx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2myajkyua.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2ljucbkry.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gt2oqvfgefb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2uchhdasb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2cqnbjmje.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2rvoczhvq.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2uohceuvo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gt2hgnmtfza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gt2mjvcldgj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2cjtppzwz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2uzynwfhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2xfuacqri.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2ivgedbjf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gt2pdmtlmho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2qebuutrr.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2kwybvymt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2zczcebwz.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2ozvmegdd.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2jvyisfpe.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ajelhrys.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2xkaqeinu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gt2dvqcelas.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gt2ztdqgzlj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2nrwmgggr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mttcampt.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gt2ebgcbmiv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qppqaasi.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gt2wlzhgnng.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2makhmfun.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2blaoiyhd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctgugqrd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2iwvwlczg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2bshpxoml.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2fghgaxik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gt2vbrhzedt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2zxhjqqnu.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjhbxcho.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmtbnina.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2xvorijqy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2fsmwutwj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2tcduipwd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2etgviiyz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2ubokuxla.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewxllqrz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2mewgodkf.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2ucudzxjs.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2pxpsdtfo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2cirtznbb.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2qtkofrlh.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2dwmkhzeq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2dndjihlr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gt2vumvuqgd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhwigmkr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2rulipkut.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2txwtcqsp.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2wppfzbor.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xcofkgzq.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2icxlwodz.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2qzljfmya.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2saduszeq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gt2rpsmdeco.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2tqwgqgmc.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2fwryxyey.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2nclywodu.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2kadmqtye.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2octlkxdj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmewynfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2uhixsnoc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fakldcuf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2vihrhcfd.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2eqktjwhc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gt2waysuclp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2kssumuwb.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2lpgsybei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2wqljzxrz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfofwveg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2feukfzea.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gt2rcgrjwkc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cndbbsvs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2rxgwquyl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woimuedx.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gt2ihwyprie.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2bcywhnbj.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2ixevqzdh.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2zazduwcz.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2cemqplrw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gt2lcuyiykw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkyomtmm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2jebfcraw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sopixbny.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2gebnyyap.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2aklxngmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2bhpmgzea.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxvrmvkm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2vqtafdge.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gt2bvviirmv.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2ibcpfwor.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2krfkxkzk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2jjyqiymi.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2inlzbfpm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2xzahqsza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gt2xuomqtkb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2hjziekpz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2jhgngavr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2awnceedo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2fuglgdhm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2msbklknn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2eenzauoe.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2hdjzglxg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2yohobldp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2dqbksttb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2bltlpcyq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2gzvwsyen.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2wgnobgbh.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjfgexle.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2giyjuqjo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ldqtcyna.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ruklfxlh.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2npbzsjct.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcrzjhgd.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2gwtvlgog.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2lanhuaar.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2vwrxzzwx.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2kcvkcbuh.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2xyhotoik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gt2ofkcqxld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zfahtpdh.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2uwtqeogo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyfjvayv.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gt2hpxounvl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thqjdmkp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2yhzgiofv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2terwkyqe.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gt2kescrunv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2rpassvss.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdrpjakx.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2gctaguet.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2ecdkulxs.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2vppaaxzy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrowrao.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2vuhykdui.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2zadbtpgw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2oiwnrhxq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2luaythuz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpzdcsad.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2jmoqzkti.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxdwmcsl.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2vonxhonb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2cyftxwiy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qjbfwmrz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2qtejyhgd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2mkzdtndm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2ijiydyjr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2ftivpqih.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ntxgryvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2lfcmfneh.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2qxsqmdpp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ewckvezd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2tsplortw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2mkpaqcxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2unbxbher.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gt2pjwexhny.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2vfxavahp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2eanpdujs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyizhfkb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2epoebjwk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2gatkgvxw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2vyidtrrt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2ufudgzdy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2qagdflwm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2rbkmpdwl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2qsffnust.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2asottvne.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2xlmrbyzc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waoefszr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2nohmdxuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2xzdzmxnz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2xefeegvs.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2ydxdvdet.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2zfpepydx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2tuhawjdg.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2czdghbls.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gt2arytpixm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2wkxltrwg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gt2exavkdpw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrxiihxr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2nyktbyfy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiaotwuw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2azyzyvop.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2ucxeuvtj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2ggqnjxoj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2jfdqwzip.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2iqxttezf.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2staumnzc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hefoooyf.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmgjnagl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2qpljlouu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcjmqcnu.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2mvhmkged.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjfrgczv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2yrylefzf.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2egyfditp.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2jfoyhael.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gt2zkhlxywo.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2kcettzvw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2fxniguaa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2qnwlnqkb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2tvvowwcn.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqskbrhi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2frubplva.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lovhnzbp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2xucbzxyq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2bwqbrwjw.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gt2qmiyvsfn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gt2xwtvrbjw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2vwirweqo.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2eaobfdqw.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2bgxrnogw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2abrlzrvn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2pjgiovaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2gdicqvie.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjnxexwv.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gt2cmzmbbgh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2khmpwxhf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gt2ptahlooz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2fvgakqdb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2kryrpfhs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2kwemsjae.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2zasuytup.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2jnakaewq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2olxfpzkj.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gt2jucukmgk.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2mzmyoqtz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2qaboiabj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2lexfezjm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2izvbrvsr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2jgatwyte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gt2zjxljyff.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2trzwqhyh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2seadjwfz.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gt2apejdccy.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gt2hwjcoavn.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2hxjccdyd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gt2yzmiocxu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2ylitcdyj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gt2echsswqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2oxqwmkly.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2jowhtkfj.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2dttsxplf.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2wzlflsvg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2upzcrdyj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2wmpexzqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2ewiaqhzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2vwslulpt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gt2nfvrndry.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2ntgwohge.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2anhaagvu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2mvvfpoqc.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gt2wekogdxm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2ghjdnihb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2qujjwlzq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gt2wceytogu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2bcdywrmu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2kduwnnrx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2yyjbvkmo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2kuizjrsb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gt2hhpjqckj.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2cqqjjcxh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2trdscgmf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gt2ykdvalja.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2xuiamnff.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2okklewzt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gt2xtbytfdv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2cfdbxhhz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2buhnlbip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gt2ryxaufxo.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gt2sfqqgjzz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gt2igponcct.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2exskvvtj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2oolxmmmb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2wpuzkzzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ozwwpgsb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2iovnhzhl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2oilduzmq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2xqbkziil.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xbftgnvy.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2krkxjggt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2inyjuaev.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2glmwusjg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thidrxhn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2wdzbyzbo.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2mmgwsqum.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2cljmcrrr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2tnriovsm.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2bjbfbcay.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gt2rdmtdikw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2yqatmuer.html


<!-- 参考信息 -->