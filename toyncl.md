代发 wailian999

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2wemnlndz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2vcwmjwfq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2tlbvgale.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2cnolnkhs.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gt2wfytoibu.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2cviutjny.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gt2wchsjdxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gt2abigmowg.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbofwufy.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2tyhytrhe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybplzehe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2qhlfukwu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gt2smdsmpwe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2rrawkmyg.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2mqdbvlcq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2kyaszknr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gt2fotvwkoa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2yrnkztqh.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhypoorw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2bijaasvn.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2eltlllhe.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2tsrwkjii.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jioyskuw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2tbdsbtit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfeynseo.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2vjlzjhlc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2qhkeykhz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rmbugojt.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2bujkufpl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2clyxfyks.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2bfanvcjs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2dkuwqrpj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2iyjocicy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2fbydqqwp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dtoonupm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2pzcvezoh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2lijlmenl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gt2wlsjnmrv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxhrtfjx.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2sfezlqmq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2jrzqbetf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2ipggzhik.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2mvtnbqgx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2ntziicgj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2qmybunqo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2pgjltmkn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gt2frieyhko.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2yrlvbhpg.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2yypjiluc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2gatjfsyz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txizcdmz.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2xfdtbiov.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2bcoypsbz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2acljolkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gt2egkbmzyd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2bcwixvnv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2vlpycduw.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqydkdlb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2dmqwvvjo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htllrmpr.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2zzrryepp.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wyqtezsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2emdtdona.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2ktordtjj.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecjtgouk.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2puicfqdk.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2uyyinxks.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gt2grxofsbu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2vspykqvn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2rxtrgddp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rwjvtvda.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2jsoxgadq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2kwolrhod.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2htokoxqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrvderpx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2oeslgtpf.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2xvhpmvnd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2fnoqrabh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2fijckjrg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsukmqyx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2twulsfgg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2dxzoguqt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gt2qbdxajbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2choawrww.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2hoefmtwb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2kwkvebep.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ppyvgvrk.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2mtmxdiyr.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2slsbjemd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2qurcmjfw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2hvppvdsr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2xkrtkuaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2iegtuwxc.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2kcsfdypu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2pckkpnjj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gt2cglcafdh.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nprnxgrz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gt2oybzygfs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2vgldhogs.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujzeirto.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2hbaxxtkl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gt2kwzhxvrq.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gt2zrzgbfyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2mmjwnedq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2cpjmczcy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2olvaolyl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2eredtajn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gt2zcugmcul.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2ohcwcpwz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aujcopvk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2xtvqbfpp.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gt2xkymxcyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gt2pjypfyww.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gt2ohaciutu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2zihktefa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2krlovral.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2fvowocif.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfntsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2zyjrwych.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2iycapahk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nrwbzope.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqheaero.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2naoaathn.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2noovtokr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyvanctg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewqllhmx.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sxkjntsq.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2remvojbt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2xsrwkamh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2ixjiduxk.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2ycoeftub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2dqynfuzu.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2tqrjapkz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2qsfkrsri.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2uydesswa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2bqlstixv.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2diblrsce.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2hjyivmhn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2aqorfsqz.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2fjuvxcnu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2ldrkwokb.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gt2kogbphrr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giouehak.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gt2nxjckpnz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2whwxbsbl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2tgmoinbr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gt2wxklmiqy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2aqunjcgb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2jjdyyupo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2pwnyuglz.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2zwxscrpf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2ipizdsrz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcjthuzy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2xbnsxjup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2gbktlhgi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2eifxgnds.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gt2higkzmxk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2iekjimuc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2bmrmudqy.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2tsfugxsc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2dpxhhdcl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2dizxpkfi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2kyjgtuvq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2nxovxrls.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gt2wzcglebe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2mnfniaex.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgzgfcgo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2pwjnpnfa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2mxuforfq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2krsjisag.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2ekzejuyf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwjrqozv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2omvnjhpk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2jdjhernv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gt2stumimno.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2nkcxzbmc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2mngqlfrc.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2ullqhogi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qejijhen.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chabxhsp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2jehmbduy.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kapzcbxs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2yayexbwg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gt2qfqgtqkw.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gt2exbgurva.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euweegpu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2rwoejuea.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2gnvwbvri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2cjjpqvhz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2tdngxior.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2npewmvpm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2jigumndd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gt2ptoafhss.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2eeazgydz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2elmaloab.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2kvgmtqhf.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gt2mavzgbjc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rscchomd.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2pdsohqyg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gt2viurdbhw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2itgkpbun.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2nguteptk.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2ndgpsxko.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gt2rrjjczhw.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2hjufouga.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2omgmrhgi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gt2tznrdudr.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2uxpvsfto.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2jopuxiox.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2qmyshbfm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gt2vvvlvuba.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2mmgnutqz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqssht.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2phjjvgjv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2erayzzjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2nelbrhsm.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gt2sbumpfkb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2viwzwnvj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2kdmskmks.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leiwlpwi.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2zqpyyfzy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2kextahuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecllnsgk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2hfnfqifx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2hwcxwpiz.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2arrjluop.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gt2ilpdgppk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2bqbddkus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2kygzaddf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2lvnrjdkm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wztilffg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oabckrqh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2tbjlzrfn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2vpwzqgfp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2zycbnogz.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2keykwoms.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2gxvgciap.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2ogprnqoy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2mgihanvl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2bmyapjdu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuxaxlrl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2tlomafpt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2ztboiuyu.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2bigfurea.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2ltnluwbp.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gt2ebkncscp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvlsbeak.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2qocllgmq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoarvem.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2zuefkqsa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xllyistf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2nynrywol.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gt2sweoxsun.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2ksrtegtb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2ridfshvx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2cbvwgjkw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2xrhxzecv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2rsadxfsl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozwmcfro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2syedvvxv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2uabklgha.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2kkrbgqzq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gt2moeskdhp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gt2xywpkvkh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2exaqnfsc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2zlfssven.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2urzgkdmc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2vjvskuua.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2fgozzjux.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2fmahscsp.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2jyovogfn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2vciyfnef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcafwkoc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2absltawf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpszeplo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2xssgdhmz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdxnwzo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2fskbosnk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egmdyzau.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2hboeqrra.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2qtsuqfju.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gt2shxhjwsb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2fzbtrvan.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2luvysppc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2jcnvhtcd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2tuawtrnw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2ngewzyog.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2dungzoci.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gvvxsmmh.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2untjkoba.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2lsqxorto.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gt2lafufjzh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2yxooeyrp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2nezkldqx.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2uqtgroaq.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2fvufssoy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2dddrznon.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bptskteq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xymvokdo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2bkkpqqrq.html


<!-- 参考信息 -->