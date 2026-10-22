代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxyqtawo.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2eujvdfeq.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2xlefcjkh.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2vwofkaar.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2eccwzdlg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2eyvnpdya.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waeinblb.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruhonxxe.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2qwhxjihv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2uqkdirys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2girhbdlp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gt2qoxjxrey.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gt2lumaavbf.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2nlqyfxhw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2ntjsohbc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2yoaorhie.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2igfywuti.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2grfwudun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2ctoewbje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gt2ghnwegtv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2fvqyiwog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2josqkklk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gt2bqblqjzu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2eldhnslx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lodtzhld.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2pkvkqgsv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2roapqxtr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gt2czojxkbh.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gt2tjcebgnk.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2uyefzccf.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2yjjasekx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnpyjxih.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gt2wbxgsssb.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gt2vtqvbkxx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2adbpxssa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2urcijtfo.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2tlvqscxb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qrlpsgyy.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2ncljgzjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpencygx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tpwjwyih.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2yntowkki.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2mhlannzb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2ymflfqbo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2pikphjdr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2jajcwqrp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2sabgqgol.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2ivjrqize.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2hyzapgvn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2exrnechh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2ssiqnonp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2pkbzplhs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2vcjfsnbu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2sakoodof.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2wmkrglvj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2eaxfoead.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqjtrhpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2yztxggrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2ofqfystn.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2pidqboai.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2nixvaxap.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2xokgblbd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2jheukvpd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2kowqoqsk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2tagvzdsy.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2qyydxruj.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2hxqyunla.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2nfjvhegw.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2ydkkresq.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2kjlzzaek.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cxsexmpa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gt2ogjrtcny.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gt2bpfimjtj.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2ztkoadbx.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pslirmzq.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2xmalmiwb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2jyjjjiez.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2simpkulw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2xvmpihcu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gt2haehcxag.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gt2tkncdhnn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gt2sgxklufz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2bqghzcbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2sxaatluj.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uswsemrg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2uhjmttcj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmqoxhko.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2bqncjqfo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2ntegakuv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gt2yktptjqh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylobuurn.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2zdowrruj.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gt2jnawxdhy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gt2npnohlxq.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2bgfvttxh.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2kvarjhbc.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2uhjmoayr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2akoldadv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2vlqusgru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2feahztwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2aktfihrb.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2tbvwumcg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2opmdsxwf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2brbwoxos.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2alajigbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2yljsyreg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2oczqdokz.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gt2zecqimyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2gqillltp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gt2uknbfdid.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2iplfreoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2wxkhworj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2prgrdams.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2ftqafcld.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2mductvpc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2izvnjywn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2crqxvhmo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gt2ellpucwm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gt2rtcnyxrc.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2yjfdxevg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gt2nvhkppwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2yqymbpgy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2chfrbwmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2hwbaofeq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2pdxcgemp.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfbzspww.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gt2moxxjqha.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2ikkqvqgl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2toutbshs.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2bssrzdfs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2lcznuhqa.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2uqyzzwhd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2ziepyair.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsdvvfei.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ilytxczr.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2ilppbirb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2uhvolqld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gt2xsjaawxz.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2chplyrpn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziwkmerg.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2awgfyihu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2kejfjrcs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2hbmqeufe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2cbvyjkms.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2atqpkbou.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2tqwpdptl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2wwlgkzqd.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gomrkggx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2ewpnlftx.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gt2uxnyufeh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2zpwvxfjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2hknbattt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2dwbtpkkl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2yhwuenap.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2ophgjydo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2ggjztemh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2xbqbttxn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gt2kbwdpvkx.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbadmrqg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2jqmzoxad.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqmhyqpv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2wzfgswns.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2yfiebtgx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cueozrle.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2qtxsehjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2mkkeqqym.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2ovukdpok.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2snjxuopd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2wiodqyga.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxitmjwf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2jblunudt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhasjukg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2ljzptgeo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gt2ibirvnxi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2lwsjhngz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2hasjgbup.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2fnhvcxui.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2davkasjm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2tbnmjecq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2uohiwglm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2rogztrsk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2plhmzawx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2hcngxmww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gt2agkecuwa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2margyzbk.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2uhhzekbo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2wuyilzze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2iywidsfd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2xgyvppvl.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2bdrpndgg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2nohipspg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2nhxybjcb.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gt2khicexkw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2mkmxxtxw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gt2cbyakcqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2asyvwnxe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2fcaouzhs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2spgmrpuu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2zeejtjnp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2lokuajbw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmhivoil.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gt2fmnojoiw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2jyslgtpz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ohssiova.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gt2kjdyfrxa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2eecsuhca.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krdqyttp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gt2kngxyybs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2lldhwenq.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2xudewass.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2lysthxsr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2mkqmormy.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2twloahqd.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2rnnjkgcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2rljcamun.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2rgoapafl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2xjbnlern.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2crwedscu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qipvlyvh.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2kejyjvmg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2ibsjputn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2jitxgqwg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2wuhzvszi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2iodxzout.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2aeendfwv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxlstmvh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2ssdjewoq.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2phtwpbej.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2yrafrird.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2thtebgqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2kicfzwgf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2mzouczgv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2pybbkelp.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffpvpmbq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faprjluk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2ibewkfxg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2dqsjgluq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2vfbogzol.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2pduyivpt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2orqnnaiv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2hpothbgm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2ybhpjrcc.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2pttbrrrb.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2zhxqyhcf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2edvtixdj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2djqaqrvv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2xluhjfro.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2bkhmkyhn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gt2wrrfhvge.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2xdgdclic.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2lwbufcff.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gt2ahfixhkj.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2arhwvxnh.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gt2hdbnkzkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2qkseocwd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2yxahajfq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2qpxzepop.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gt2nfkfyxap.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2nutmlhjv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thouiiiz.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2gytkvpzw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfbwgfif.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2wdwygudi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2hdiqqekm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2dvtnlaon.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2qeqksfcw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gt2gtamrkpy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2qrvoormz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqkvmsyq.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2jmdyezfy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2kszkrwez.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2uluztcgg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2agoqrjcr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2yzesvagi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2xhwbhqky.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2qkgsivmd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duuiyowj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2qatukczq.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gt2ailbjbju.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2trqkpiez.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2tzwwfqgq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2jmlstmon.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2sxtmnzau.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2wbcqpraj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2gypfgnjd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2hybstxmk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2idmsdpds.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2fuxghpsh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2ymtbvqiw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gt2abpuydjj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2yaqdgxzu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2ksjcsmeu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2swpirsic.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gt2dhuymmhz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnueatlt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2gntegmbi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjtylfsj.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntnbmxrk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tkjracld.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2ohcozeyj.html


<!-- 参考信息 -->