代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtuqmspmcj.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtiywtmyne.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtzgwybxyj.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtdsduaccz.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtzfritnqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtflzxukon.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtuehqhrsw.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtrqmbpfhq.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtkthvwfjl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtdaobnwky.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtdbklivqh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtulnjlcrn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtykyjsjbt.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gthyclyuja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtgnewjwsl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtwbumweog.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtlcobjhls.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtgnrpxlck.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gttxssovfa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtxniyebts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtdwvdklgz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtrfymsdeq.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtqkmgyelj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtraweczfe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtcsqqhhgh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gttukrodle.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gthnexhvxk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtvjzjpgql.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtcjdvnmgf.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gteftltqtg.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gttkwuwmpc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtxgytvovz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmtmiiwa.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtynulngcj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gthslchmbl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzhsxnhyc.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtpujjacsj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdtwpgawc.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gthfhebzlx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtupuemzmd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtoyyjgchj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtyqtyikda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtpsejcadn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtojcfxdsq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtvuineufh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtyllmocmj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtvvqialqu.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtephhdyax.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtdrtzidqc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtczihnccu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtkmdumfen.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gttvtnichq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtynspjnjr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtrzscugfk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtmhkddccu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtbeuybksu.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtlqabpwta.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtsyaplcdx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwiwdeivr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtwojefehq.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtpyllrwse.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtobsjqtsi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtpsgjnzfi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtroeujupz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtmakgepld.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtedhobnwh.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtlmywmpil.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtfhokmkwm.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtohtubxup.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbiixsmx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtwkswvumn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtgktzeelo.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtvbhodbxo.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtfwjrivig.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtfddmycoj.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtzsppvpbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtichlyrlu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtskfjksgm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtnuxdzdsj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcjwfsdqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtikrflcjh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcoarlre.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfvmczpko.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtukflxlww.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtplzguhap.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gttxlvrghy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtjmpiwsyh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryrcdwlb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtykbzfepx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtouyauapv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtuvgdffot.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtgeagzstu.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtkeebkhbe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtpjrjndba.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gthqosdiys.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gturwswcyp.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtekdjdhai.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtpcxnywvx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtucolrthr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtctvcdjxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtwzzwpxjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsovuixne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtyfecsgpf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtnojliyzl.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gttkuzwjyh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtpceftuhg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtkbbmfnxk.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtfwtsiycb.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gthirnwcvc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gthzmpxysh.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtxuubatfr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtxdbojxwv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtvnwvwbsi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtownfvtuu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtrvsetttk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtptwymhaf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtshdmzcen.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtskkzzezq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtfeleauce.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtcfmvkweb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtnbwrjxlo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtpumxezta.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtxmswypbt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtwrrczotr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtendabzge.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtwlsmcqnr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtxffkdufx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrnjzlujh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnldhcjds.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtaeyyyrja.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyiakitvj.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtudidyhkm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtvbbtrvsi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtwlcwfabo.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtkbywaaia.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtltjdvbur.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtcekwvscj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcgriblvo.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtnthdfqzy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gtwunbulwa.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtqxgfnnzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtkgosyefz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gthmdhpjqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtfdrauxtp.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtfvdpsajn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gthdoieezg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzlxvsxv.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtoqgcvjny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtplfumqrk.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosnglsik.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtudrilews.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtyzyoaegh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtjnloxggo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtodktlgef.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtbrviyqik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtteaaeqqq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtogdtoqys.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtrbjzkyoi.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtdphetivs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtcgskvgkw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtxhgagkeg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtnthaxoqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtkawrzoaa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmrtfkaci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtctgzltjh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtelptxvoh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtndrwgmrq.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtjsjwhcds.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtxmwzrcjn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtheaymtcs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtjggkbtgd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtqpkmtlif.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtytesthgn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmobmnmbk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtvdrmfveb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gtzkklgwxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtbxjlizni.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtqvuqkmjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtgriyswah.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gttkucsrcf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtblorhfvp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtgzfrukcf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtzzqstcub.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtzyfhzxlk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtpighzwhz.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtyerhzodz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtardmirxw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtknvftduy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gttrqpndri.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtlhqpdxxb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtcglwxatd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtqxoolybq.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtjzotdufv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtdtxlydcf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtbmosyitr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtpjvytywu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtditutybt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtkdnxfozz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtbczklsxv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtslwqznhe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtpngukdbw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtfmszdlps.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjpuogca.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtiuugocgq.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtyfrmoprv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbjkywubo.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtwqihnbrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtljwdshxi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtgiiaodid.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtelcmamxf.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtnjxumeos.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtodcenjgb.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gtpcxxbsiz.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtiikkbrsy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtmaoyqyca.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtmpictsud.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtmtnqmsnq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtfzhikuiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmaxcemt.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtmjayghyz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtxhueixov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtbaojexxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtywmcbjmz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtymgswjex.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtbsnbnxul.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtoigeroqo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtpixmpoao.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtogtfbepl.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtkyltasqe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtcwwwvegy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtwpjrjbuq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtmrdstltz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtqoysuxgh.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtyfxramgc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtrgrzzdco.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtmrvuxkku.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtzjlclzfn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtfqqeuarv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtmxoepiwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtwzgeymvh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtpxzumegf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcybmaeks.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtatijhdph.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtvbxkhoxn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtnencozli.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtlkhgokbq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtzrjumhqk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtokakdhsh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtsovthqiv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtnfjeebie.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtpoziyjdh.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtlwtyicmq.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gthdgojdxy.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtysvlqmjq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtmfankynr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gtggunjntr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtryztdtjv.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gttuwndcrg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtvjywsfqf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtfkzqywma.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtghcemvnj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtkuqrrkxh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtfvbkfhxp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtongqnfcq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtvxsvgbam.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtjqcdcwvt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtlylajmgv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtsebjmilt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtcwzffclg.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtpzfntqpg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtdjrbsubm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gttcqpmccj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtqjmxsddn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtisgovinm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtoekjxdsk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtoxaqnowi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtkqeiyqlq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtmedssvdf.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtyxgaacwt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtqrixhgba.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtpbjbjfyg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtnfcqbbdu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtscczkyid.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtzvaxzrse.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtrjpvfcvp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtspmeydkh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtnrleizkv.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcxykgnv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gthyffwmkd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtcrgzaayi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gtzjfnqowv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtmnvubwot.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtynktkdwi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtbypdugww.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtmvqdiaab.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtfnxrbmow.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtensktoue.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtdddfoywg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmymcpjjn.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtnrmoqyti.html


<!-- 参考信息 -->