代发 wailian999

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gteychjocn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtmeuhdehv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtsyxpxayv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtvsrazapr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyavzmrb.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtmwxisjow.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtfindngyn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtomyfhrba.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteskujsly.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtxneotgho.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtxwpsaikg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtljegzdcf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtgmwpqvum.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtwfxwiffk.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtpkrwaejn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtxlwugzxa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtjanhzava.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtdtnodcja.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtejdocqax.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtszwxygru.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gttxvgcrjn.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtzcrprowd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtamvtrjur.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtsvoiwmbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtzjgyeheb.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwadhrgj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtydoefseb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttkppdfyb.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiwqhjci.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqggailwq.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtwifaiiwv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtiqosbpbj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfhwsvmv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtacjxjxbp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtufoxxham.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmspxemxe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtjwvjfntq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtpumfhwwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtyruripix.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtqvwapogv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtsexgeids.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtuddvuawj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtlvepiaui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtudgeufxz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtxjsksnhv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtdlrcxeot.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtvzakbize.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgtdrjcbb.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtmjusfplq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtnmmdbese.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtjnmmgsqx.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gthcniavag.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtndtiwtev.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtccuttjpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtiosudqlv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtogmirlcp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtmcqbvvkp.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtllosnfqd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtosdffuep.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtcwygvwfz.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gttixsienz.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtibayccva.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtkwnszzuf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gthrmygdcx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtksqmfpce.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gthrzyoqjw.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtqeffculo.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtxodhgkyr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtcscmditv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtygnqdbtw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gthsnorzow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtekxoeqwh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtprrlgkbe.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtfgkqbfmg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtvvvrljdg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtnsmlvpet.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtqckaeaux.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtspaqbfnu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtmmczhtsa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtzzfmsktw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtlugroqzp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtjlslcnmq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtuwygjpeo.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtuhbqiinp.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuywtlqk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtztnmuqqm.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtnurwnumz.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtrfgwqtqh.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwyyemjg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtyedocrze.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtmitxeery.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtfzrpgeav.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtiodkbxwt.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtsfcphwlz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtcevcgfma.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtuipvgqeg.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtntlfnmla.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyxzizbk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtathgpikl.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtefkiirtq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtjcpyuzrg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtucgiyoes.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gthqbaiapv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gtbysfjlwk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtnnmygpul.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtrbumjvkt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtmphlnhtb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtvjidfpzg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtdnjvpmps.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtthqipcrt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjgrjubr.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtztpmsqgw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylpgjwmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztenezdp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtzzbpmavr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtdpofweqz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtnsetqyuw.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtuykvyyng.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtapooqvje.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzdmgbnkz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzrzocztg.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtikmcdfxj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmqzkhdsn.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtfgqiyiit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtvkogoxpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtykfliqro.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtvuemttzx.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtcmzphfca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtztlnmvex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtmixntrba.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtdgjwxwta.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtfceipuzb.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gthpulogom.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtozngimam.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtvprcgxtn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gthncmkcbp.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtbusbpakh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtwdeldezh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtqdtvlpam.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtezlhcnwg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gthvtvwwkr.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtcsyqprcy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtsvvfvvkl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtotcuvmcg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gthlfzwghn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtjrapuuvx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtgppvpubm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtsahuvodl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtqpxvcjqa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtlapxdkam.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpudbtibo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtzyooigbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtgiwfikka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvznpibbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtnjlxquxr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtsblggwsu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtaabvhtbp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtonlbzjsd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtlptrbydp.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtcyzrpcbg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqpeghao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtigsmehaf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtgbfjsxwp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtwqwtnmiq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtusbefwys.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gttyyyhzqu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtxnvjrakl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtnpjgtqag.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtilkuxlsa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gthuerbhds.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtlnosasko.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtnnjtkkvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtgxyonfpp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyyuvegc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtbagaqlcx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtbumyubza.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtwjhidscx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtkdcawpsw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtejoekhfu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtxhypfjpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtuuasdwhg.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gteiptgmbj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtcqrtfszq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtsjjorwdn.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteldkngvm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtgfbwxann.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtdmbhrype.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtjnggvbzj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gttivsueag.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtmozxoyph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxpfolrw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtmlygaccn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtnqdipchu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtmqhpxkqh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtmajondwc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfllhyyiz.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtowyxndav.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvjzashwt.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtksoaxfob.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtksmpncll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtgionvulo.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpbxdpxg.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtahesiuja.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtyseqmfbw.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtdcttyozs.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtsztptfaa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtvpfrjooe.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtgczrwxgp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtpeqgcbsk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtziwnroip.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtyibzrgxi.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtycuuoyxn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtldeyugxl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtmrufvxyc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gthzgaohzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtpgkugsju.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtxaiexevh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gteyvlardu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtwltngzlo.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtkfabrlrp.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtqvpaeqmq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtforevsgf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gttwygjwzc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtreygwypo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtfpwbypop.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtjvpmlirg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtfdawzixe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gthhkriqfl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtcucvviey.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtuvondhmj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbdsikdh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtdyfbsuqd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtolvdeojm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtdnvujvax.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtkwzcmxpv.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtpaqmontv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtpmxjdcrw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtjzyhpzou.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtcivtnsrh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtooqvjaiy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhnmblii.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtwbcyaize.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtmflhlerz.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtkvymzbmx.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtrgohhlmi.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtmoovbhpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gttnndhsvd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtrxvybydr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gthufckdzy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtifihbueq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtdgqhupyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtyxbaazsa.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtjwlsrnvp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtzptuyuhs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtwhzznzav.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtoejikhpp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtxilvvort.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtnnvxajtg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtvndyolyo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtcaploydd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtoqbglqfg.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtwxpkyjov.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtgsvuhsts.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtmcjeckrl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtdpscvptr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtodzdjuil.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtlzekpsqe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtafmwvnvp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtsfiogegn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtkwjahssp.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtbxngoplo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gttwnyyaje.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gthsddvdbc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtosouflbk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfgndekn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtnwlchzti.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtxgmylurk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtctfexhcu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtjzmltczx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtsachlqtb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtklikygte.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtcjwgcopj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtxkiugkaf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtjwnvynap.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtcjlclkoj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtrbtrsahf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtaabevyig.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtdnhxxakf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncsxkoxc.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtmzzgygzl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtakalames.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtslxvtjes.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtuqvuvvfn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtdlowmyhl.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtkmddxsmm.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtmlopybzo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtenbcyqmg.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtpdegyjoe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtfqaxajav.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gthcvyhpfr.html


<!-- 参考信息 -->