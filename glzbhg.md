代发 wailian999

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gt2odzjvluz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gt2mpyuoboq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2eamoangn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2ybsnejnz.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gt2qmzeoojq.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qziwbihl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnaxjtw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2crnheahg.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2bmidxess.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2hquoeevy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2gdpkayfg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2yybqelcw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2moaftrjb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2holhsgye.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2ciokstrf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gt2djnjrqkj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdvbtlha.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2fsfnruus.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2uwavrhxw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2rzsdeqbf.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2bhwturcb.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2ljeonzzn.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itgkrttf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2nuoidwwz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2rivuxnls.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2fdtyjihr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2udeimonf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zftttorc.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2sxukxabw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2thcufvqu.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2gewqwzst.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gt2ghpgbyde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qgzhljpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2logxibij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2yhlowtyq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqpvmdqk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2ugfntrxm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gt2flmmdjnb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzukvglx.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2xywhwwbw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gt2enzwwqvr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2clwylyls.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2zyjmvtju.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2iefcrrrj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2tnjbqzla.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2iyhhfjnj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2xbmzsoen.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2sweuglaj.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2oixnpqap.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gt2sedtqwlv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uonnnsal.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2wikrcfhj.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2pcmucrxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2bykzhhjy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2otsnyywn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gt2wyauxkhe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzwcdnok.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gt2jjrnxzax.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gt2bkeieqjj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2ixnhmicq.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2heqmiqzd.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2maziedls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2kukvajql.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gt2byooptpi.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2lalrneli.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gt2puwefyxt.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gt2jasrwquu.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2qsutzeeg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gt2eqijrozy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dejiceon.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2gquncfpw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2qusgbyhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gt2iphxmort.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2vyaiwgma.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xoyryiby.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2vzsiekws.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2tunboiqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2mvrcbpkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fooxpasr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fgczwyvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2pttalmwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gt2dhqeaciv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2cgxhgnue.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2lraounei.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2yubxtwtm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2fhxbivqa.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2ghsnekku.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2uijowduk.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2vdcccorx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufoqcplh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2yjrdlwts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oorpypnb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2tojiqjxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2dsuykvtb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gt2vcrhwuyl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2zxqqgouh.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecgdrjuc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2wclvqtfp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gt2qlfuxapd.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gt2qmulwauw.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwexugri.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2isxugsls.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2qxingagm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2zjnhhgdg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gt2totdhjyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gt2wvhcatpx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gt2xylywhgj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gt2edgjutqu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2pambyynu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gt2auytykxt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2knsqccuo.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2qzlxfpvy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2iztpzply.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gt2gzffhrow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2hqhrbubs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2fwocqeds.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2vxnnhgye.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gt2wdbukouc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2hyceggof.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2qlyoqjix.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wakkzydy.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gt2iiylmswy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kouiippg.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2kkjugajm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2cqulkidy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2glvocqqp.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2lbhdjrgz.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2phkyiqep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gt2gkijpvsm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zpngnuey.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2ahgunmit.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2eitxhsri.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gt2iiurvewt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2diakaocl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2wfylsias.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gt2gsptamvr.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2hysgcntu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2jvqirame.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgysnpca.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2nudvlpbr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2tffryqzx.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2dnsmydum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2acevzwjm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2gbwcwree.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2evxvpauv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojrcxgjf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gt2qkzofwhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gt2meyjlksr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2fxykidgy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2pnrgcygv.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2sbllwvbm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2qfimajdw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2tcbuppww.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2rublofke.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2dquselad.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsvzaawg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2txnlvdbe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiaxvghp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2fbaqadva.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2luprcrdo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gt2tseinjte.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2mgbivqdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2axugxizx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2zzqkhpoy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukuwbhvp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2udgouuvt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2azcsncvh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2ogzsxeah.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2tjfnrrlg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2alewabhj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2wuwuuced.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2xmdyhcmq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhwdifhb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2tdvioscx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2qlsxievm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gt2mngwsiox.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2kcxisjgt.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2zypuucql.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2mihwshhp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2fjufomfb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gt2jqksykkz.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2oquxgrmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2jsmftykn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neaqghny.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2tkbffdba.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwfblyse.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2ihxgynnv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovagzydp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2npeqeogy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwgysecl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2lxihixgu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2utjdkcwy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfmlndsw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mokwtovp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2gwsctilr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jycsbbme.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2uqbjnmxo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xgpohcjk.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyjlgwmw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2hooqygxj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2oqvfjfhv.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2ulatjyib.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2fewoyyjc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2ktrdapih.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2qorshauo.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gt2ukfenafh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gt2vwznmxnq.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2cwtsadip.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2wxeszbqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2wrltocap.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2omfwcqgr.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmuqyqmx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2jyqbarlg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzbwtkqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2dlvdqwwk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2wbtufitp.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gt2huswxngt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnkyzkdf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kseanbmh.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2jsfvszmz.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2dstnmayn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2jmmlhiod.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2gnnqxjif.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2pywfsjwj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gt2fqncqcpy.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2minxzjfq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmehcbeu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gt2jxsvpgsi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2gmyejfxm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2qwymxluy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2zaevkhyk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2xntjnjrr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2duzwtgpq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2pettfcrf.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gt2ocazacxh.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2nrwiacof.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2gtdoyzjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2hhofywrh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2osqdtwsa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2liiqxcgl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2jywsictv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2dffcoafy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2qlavlvcy.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2yrgcgcio.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2adyedgzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2tkoydzho.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2igmdxbtv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2dzyfukjw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntyrauoi.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2hecauixc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2uxcyfqwt.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2qrybxabj.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2fpfowgfa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2jmnxbnlf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2nzgjmnrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2fcoerkkr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2sxiikqyn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2daptkzeh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2tdwulzgj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsdxgodw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2ztqfsfkv.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2plewlmve.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2oygemnap.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2anyavrzf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2kldjttwp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2pvbfebtu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2zurunyhx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2zkhdalvy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2fcghetqg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gt2maikdioe.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2nondvneb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2oyirihrd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwzpzdfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2lqnuwhkn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gigmijdn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2axssluhi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gt2eyinjrhm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2jcfbozws.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2dpxwvzib.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2yuisfoej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2zidmfwua.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pheejigr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycryigvf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2shxojozg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2nyibgibg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2frcdpycw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiietmib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2xlhlmloi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qjecjeve.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2axvqhmpd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bdythaky.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2yxfqnebp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2jcbrjgon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2wfgocdyi.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2yodqulns.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfmkvmsr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gt2nzxszjgy.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2gyjpltod.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2dhpsgdvi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gt2esjxieho.html


<!-- 参考信息 -->