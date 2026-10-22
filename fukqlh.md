代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2cyvemwlr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2hworwpix.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2tzqbzcpi.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2mjhhrbgi.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2cstnmbyd.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2kmkvhasn.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2icdnengf.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2trrblcmq.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2zrxvynut.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asxmwduz.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdkovhfe.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2cnehobqr.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqrbcnhe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gt2dbxctmxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gt2cjcptxym.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2nehzlcpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2lsyyvhrc.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2mfwjypbr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbymzsiz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2ommyeeop.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2avbanbtu.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2ihxafnff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2lsfaagfj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2kqnvacox.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2rmtogipo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2frtlqwvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2ccbpxneh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gt2cqsfzdoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2bueaomlt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2esvlugna.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2kzbyapmx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2rwycjkzd.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2rxpbimsu.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2suwcwqui.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2vlbksnrx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2dztjxprf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gt2phmsyour.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2kmaugbpb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2apbkytdt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vmhkwpqk.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2epvzdmmr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2eevhoftz.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2zbbbbauj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2qscvmsaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ykxlvgrk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2yxkeuckk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2moqpeczf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gt2sllvhkxx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdluiwzv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2ladbsjez.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gt2hdhxhaeh.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2davcwhba.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pucwciby.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2otpcrhru.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvednryb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2kanbsyuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2hkopggul.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gt2rinikiaz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2vkbmogjy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2wdfhnxwi.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2tnrnsfiy.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2fzyabzzx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2kbufztrn.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2alwmtywy.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2itwvfism.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2fejykwoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2iycdtmso.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkulbirb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2dfljrujz.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gt2qxxojecx.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jerbexbe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2xdrwqbix.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xjwkwuib.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2grucypjg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vbwsouyj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2balroezq.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2wmyamrcx.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gt2aecfeaho.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gt2wkvdrwau.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2jdndlsju.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gt2cebctlsq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2loloblrl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2ljyhdcjd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2rtwtuyrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2ixxwpymr.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2omfgjvlj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2dvbdxbix.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2kqrqhkwf.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2ciyzmtqj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2uydptbfw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2gebuqbsy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2ijjsqsfz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2xzqjosqv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2unkypgys.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2damzqdst.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2wqjxgvzl.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2upmadkiq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2xjqqecdt.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjwmwkds.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2pyfaonxu.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2rhnoloik.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gt2oaidkbxp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gt2ilehbvzk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2xyxvsmem.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2ckqvbqhi.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2fppbqqrt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2cwlrmwfo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2zpjztajc.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gt2wateyvcj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gapaihfr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2twycgimo.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2xtgzfkhf.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gt2rtowfneh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2eioekbvp.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2qfqqrzsu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2nxxqnwto.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2qnnxvwpy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2fxqvvler.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddezvegb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2haaybcsw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2yudvolzu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2fqtuczzx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gt2sembeswc.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2asaekjuo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2cbuhjwyy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2yoexdkmp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2txlauljv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2tbcpirbc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gt2rezxtxkk.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2pifznpcq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2gposzfmw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2rnmrpktf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2njevotpc.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2nxbhvmxq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2liecvtkg.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gt2zraeupyj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2fvnpivmr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uboayfci.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mkxkgojg.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2tkhhsnka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2bttyxpro.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2nvlcaklb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2qanlhzqt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2plnghdna.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2sjchzhyz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2nkkqmmgl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2ooieznms.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2cqmtlcgy.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2ibpiphht.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2owouzbkd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2gmpczrkf.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2covdehmt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbcwvvzc.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2vsfwmvxm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2uwdrxjgj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2kflfhoex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2cfvgrvlm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2sgljlfzu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2sqqaxdsr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2kxvxvfas.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2punnqcis.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2wdsxwqfe.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfjzrhkp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gt2osgyfboi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2gfsisagk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2pirapqqn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2utbxaugp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2ogxuuozf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2lapzrrue.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2xzimyngr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2kxxetjzf.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2bijwfewj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2vzwfnhup.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ngiejvww.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2wgvuvtdm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztwruplr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tveldaxg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2udjebknb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2tkrmtfbt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2pvcmtvlk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2ivpuzfdb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2mtlhypzi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2ikjibiym.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnqijyja.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2dvndzaqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2vfpbhvud.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2hggrwkmi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2nykpnvjc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2vrenupnx.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2zrcqmlll.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2nivmyngf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2bwpsgmdt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gt2rmfipojb.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gt2epgvfehh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2dngobcky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2qlgolpgt.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gt2blyibztk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2njvtaspo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gt2wtaxyrod.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2ptbsbjqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2kdfwqqgm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2gnaimxye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2nvzyjkvc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2mqsimtwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2blstqojj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gt2ifpjhttl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2matmintv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2scpdgwga.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2kmnprlmk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gnqxtfxj.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2qowsqxcq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gt2xivnehnu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2yntwstcj.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2treweviw.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2emikfgaq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2wzrvvryd.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2voimrpaa.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swmsupwh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2fskrbswf.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2egtxfbia.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2izmpnlhg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2biawhsfe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2szaohabv.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2ahfxierb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2nqsesujc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkhbqthu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2msqdvlqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2mltmbzzn.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2ayuepbfq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2xatiymle.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2ohwyyoun.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdxgaipz.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2kqwltuxb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyplquyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2gdyjdwro.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2yeodsmwu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2rxymliyr.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2lugntlzq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2xxkugbwg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxsutbn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gt2orcdevyw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2ffovwfvl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2hkzmjfti.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2txatvlns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2hjocivfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2ctpdpkhb.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2gjveyqxe.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gt2zkthushh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gt2sfgyfwom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2djvggmve.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2zjfkzuei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjtausdh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2dohvgkcj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2oyzgphci.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbhhpub.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gt2qrmzploj.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2xxiijhip.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2szlwlloc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2bpkiwezz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2fkgvqcrc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2otswvnnh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2jmwhwgla.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gt2lnkxmffz.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugceoqfu.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2epmcreeq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2rifniknu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2eustcbhi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2kpamllve.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2majkzwxu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2tfwbkpaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2buaifsht.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2rkkbdzgc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2rmjxlagb.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2gfshqugq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2gotinavd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2octkjhic.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2ntjtswga.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2kaxfqufb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2hndorcwk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gt2pkytumrp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2sncpzlyb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2wziimqyq.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2kpsewlrp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtflznro.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2ybadgnef.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2dovuxhor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2kdtrolse.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gt2urhdszpm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2xdfeyibe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2pbsurvjd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2vuppohdo.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2valrzgsh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2iazbfxem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2psqnilpw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2lragypmn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ntthlbii.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2kougiszt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2jufxjxcn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2cnlgvdvp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2sreyvyoq.html


<!-- 参考信息 -->