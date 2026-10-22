代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2aeomtquy.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2eiviyfxa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2qssgsmax.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2wsqfipkz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2gsnvuypc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2mkqmpmhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gt2dypwyqaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gt2watskokk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2islhiqyb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2tivwobfo.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2nognrhdj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2bgwtulck.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2dpahoszk.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2bufvhukn.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ldtobaof.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2pbewvbqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2wvoqzbgg.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2krrrctcf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2hnwcwdrp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2uqgolqpc.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkjflhvr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2epzukjls.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2wsnqtjjy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2oavbhodq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2wgkwcyhc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2fxpknqjb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2syuqtocq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncoebbjg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2wzsgyyct.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gt2torsojbe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2winnnrls.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2qyiqdcwg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2nbfomnza.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2ndaqrvoe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ihrlmqzj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2dtpqlqqm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2kqatnnts.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2sgxfkaxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2eptpbgoo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2dgtuypaj.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2zxqrukxr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2pljqlcyg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2eaeojqna.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2cbnmfnco.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qszclmzx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2chhhfqdi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2qsqjouwh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gt2ikqylcuf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2efzjdrnb.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gt2ubpujssh.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gt2lmgdbtyv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2eqtxafyk.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dmafnrom.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2ztkvkmko.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2hjfhmwhw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gt2fjhzowvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2fgbygqdq.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncdthsjj.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2wzcnkxbg.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2tkeilvoh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2drocdotl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2rklahyxh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2tgaseook.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgpwaypj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gt2wwxutzjb.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2wuxdtoba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2loplmkmx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2jciffmot.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2lubkenqz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnkkpvge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2ptkibqzz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2mduxzwba.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gt2oblubhel.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2ejxhgblt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2zdyowlst.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gt2bnxwrfgs.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2bodwhxvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gt2rvywbcfp.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zejmdzrp.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2izswnqag.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncznbram.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2qrgczokm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2tbnqlfxm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gt2jaqlglvw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2bfvytvbq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2vslyatwp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugqlekaz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2kezvbwnh.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gt2bxdszkmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2fzsajuok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2vxfzjshu.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpatxqlp.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2atyekwqy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfvkbtwa.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2wlnydecm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gt2anxhknmd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gt2vzvjbysy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2rdtcelfk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2focedimt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2pognxilc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2uofmanon.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2okqpmnrz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2yetjwilb.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2lxtdvvkm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2inxczgpj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2zynfohxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2lezzikir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2ihngsatv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2ccvgqlpa.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2ngjuxoxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2yfgwmmbt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2ghuybauz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykuvqzqz.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2eufqnbgw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jvcqrkuz.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2wskhnnkg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2hqwrwbsv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2nutspsln.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2eikoidca.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2xopvovpi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gt2orocpsng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xoyfchoj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2vudypave.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hecochlo.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzddpguk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2ruwajwqr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2mfwwemyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2jgulvtfc.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2culrbwpj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2rimqxtqd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2hswppwzh.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2brrzkpss.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2hypgsjxs.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2fedkplvr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nulwjsbv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2kmimcqmv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2rtmjgaky.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2ngsnrcdj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmtpaipc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2vewfgsrq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2vrctncah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2yhumbtvo.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2zuewkpqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2zxbtnimt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbjjfdzn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2joryzcyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2osuilunr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvljdsxq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2gjmtvymz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2loogmdhm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2kdcediub.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2siaysirm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2lptozdbx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2ycrjbnfj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2vihyitew.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2gpjozzyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gt2uixsejzx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklfztdv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2fhmmkcby.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2rkzxcykk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gt2uoltnqpb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2zxbzdirh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gt2msjdljht.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2nlahjzlr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifambdgl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2xfwmgqci.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2fxalfsvk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2akwiopft.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2kmpqcjfp.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2zvcgoxex.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2swoowlhf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2mbsgcqdq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2bitpieul.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlriuxww.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2ndgvqkdv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsbeofqh.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2bxklyohj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2pzulmqpc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2nvmrdnkf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gt2cowauryx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2exacvinu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2opkzfbke.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whbardmz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2ctwvruye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2gbkpmewp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2oosybxea.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2zndjgqwq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2qejruhzc.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2soodgccq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2brjtewnk.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2vjvwihne.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbigderq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2ichncbff.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzmtjnko.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2zxfxxuxh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2jwylfxwm.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2kxohhdxb.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2ftearjcv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgniqbee.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2ellwymqj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2gbqsqeiq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2fessjzan.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2uchkkyfj.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2posojzlt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2cxtarfur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2ciplbmxp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2eboduxhn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2bffbuarg.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2bahvmtpt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2kklhrqmy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2bdhfrvdp.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2yixroblv.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2ewdxiqtb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2itldvuyf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2zwjsauph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2ahfrazes.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqoafgig.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2zcvkusgp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaeikvsm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2cxvxtmpn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2aueyzxxx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2eiqpvtsx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2ctlyyphx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2iqdjdwof.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2zyxtzbau.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2shabyros.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2hmhnbsfn.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2imihgagr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2brgxmnmx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2qbsjehde.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2fdtdiydx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2htpjqieh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nomiuypc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gt2bjtqsszm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2tbrtjiqw.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2yozyttxd.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2uuhhsifw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2yofvhjtn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnkxiurb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gt2anqujjnn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iplnqzaf.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2sjknwplr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2qjydbgvv.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2gptazodv.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2uiznawrc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2zicrwlvi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gt2grcwovdc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2kmxthbes.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2nszhtiow.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2porhvgft.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhzsdtrq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2wiupoepb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2aaafweuu.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2crekwqpe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugorngbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2cpjqxbmi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2lzlewygo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2yfornjuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gt2ysrukmwr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2lolgujir.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2orzitolf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gt2rjhuorav.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agxmncxk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gt2lbllonyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2rybsscml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2pmxlcfic.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2lrzcdafv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gt2epzyxbbn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2vmcwcwux.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhqxlbqi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gt2wsjcjfmp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2jndkoicw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2jpssafce.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2caekanja.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhbgjvji.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2luwfhvsa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wohijppo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2igoqlrat.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2gklhqhrg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyiksphl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ylcnkclk.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2kbxllxnt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lwucfjcg.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltfgpida.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2kwoqytts.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2swcarqqq.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sbnnybbz.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ftyompzs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2cmoejiex.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2zlbqcrik.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gt2xtedeonb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2kdsfytrm.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2onxbjzjj.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2wtwvlpuj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2iuvljhfo.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2ueevgdjm.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qplnpjyb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2inpobwoq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2glgzclwa.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmqfdxew.html


<!-- 参考信息 -->