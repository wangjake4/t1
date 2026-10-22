代发 wailian999

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtkngdwmnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtcldihcgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtweyxphzt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtuvfczdrn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtpqrqrnrm.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsmrokdy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtqwylowtx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtzowcnhme.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtbbzoyetw.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtdmcxhols.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtllkzsfsj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gthwdqfyix.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gteuyyaqoc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtziykouay.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gteykzfuww.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtruodwmym.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtkuilhfxw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtgovsnqlv.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtgqcycfny.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtvhfpahsj.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtgnbsjqkj.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtejskjvil.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtsljwbgaq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtomtxuwzh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtaptbfdsn.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gthacdhvbp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtvptuhkbo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtevkaylfv.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtqzwdrzvs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzkridha.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gtzdmhucsp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gttbxcrhrk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtkkxykfaz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvcdveltg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtovdmwkwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtpzcqpxwe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtvfnmvzku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtpdbgqdjj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtchgpjjza.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtfgqmsycm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtbxqhhomp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtbkiaxxdu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtuivpddyo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbdufkmqy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcdyipcs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtspicsfxk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtqpthtfob.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxrodgwt.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtxxxkczle.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhznoolk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtnuaktnlq.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtzyxdvxoq.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtauyegilg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrljlddyo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtebxozjtw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtdokaqkst.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtucgrevof.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtbfdclqdj.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajvekdyz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtjbpexwyd.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgcwzoca.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtipfifnwh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtwvrbmzpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtspelzoqp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtkbvzkbrd.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaozzhdxb.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtnjtiphwb.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtoblssxxx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtwmwaywlz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtmogwmalt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtpkccplet.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtxiopsngb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzinpqzqk.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtyjrekjxo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gttthcoyfh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtbtckyoph.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtkfmachre.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtaqqmvreg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtqqjkunqz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazewcsvl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtsncwztaz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtcvisnyqs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtxtjqazwh.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtvrndbjrf.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtuozcogha.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtkvjootdd.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxmpyehq.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtizgdsazs.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtoupeggtn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gthuuqbmyl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtgvvhhbkr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtzvrxdrmd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtpckjpaah.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtmhsgaczz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtmebxpgwa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gthjziqqve.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtleurqymz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtmspxqfko.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtebxseohs.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbakfirgy.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtznqqqzle.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gthweueouq.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gttwwobwlx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtotraclzh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtegvycfuv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkorjagxt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtjllumhih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtojdlwpnr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtzpwffumz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtfdcnhwht.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtztapehsh.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtsmcqgpqm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtnspneyok.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtvmpufrog.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtpdnndlly.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtmogvyduf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtfclptuhc.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtoryfshwf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtxhttgpsm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtzrckqqzb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtguibiahy.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtbxcepcyt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscyqmnsj.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcgwnnqki.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtbygkwzzq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtzmceruwo.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtuxkrphds.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrehntztt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtpnushayh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gtbugeenby.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtlmavkohk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtlhvymlka.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtgqtfakkn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtqncmgouy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtyozwftst.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtgcbttmmk.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrnxotbq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtqzgobacx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtlucmpofk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtigmelhhb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gtdpoqzgak.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtvdxctxrf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gthtsunysg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtzcwjxode.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtjvavpvrm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtqvrnkdqh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtyyyygcna.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gttebvqiur.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtqcpcahgg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtzeqbbavb.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtxhfqdops.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtpppqewsp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtdqasqbjl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtnozvylqf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceeobbio.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtohwpwjii.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtccwabobj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtflugddpf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtpuodyzwq.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvunugjk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtmkjlfjno.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtfmutqlsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtzieszcjl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdtezczq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtfjdudtjs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtjjiaqizi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtqxrshtxi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtybvzuaio.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtoruhefkb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtdflludre.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtwmfinntp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtgkjxovji.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtqohupmhp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtzrggzzti.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gtncjcxgve.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtkanivstp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtgxdfhvay.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtifhgqobd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtaufhkomp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gttzcygtvy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtxtosnftj.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdshijxo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtwvjnfudp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtsirvbsjn.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtuvanefdr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtzdjfhxsu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtscgitevq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtgzqkrcdh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtabdtjlmd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtqljzookr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtmrlggbbj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gttpcxfxxc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtnfymsvuj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtjgwquphm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gticaxckbz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaeloogtu.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtibqmzzws.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdnhnlraw.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtpzycoglv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtmbwekmcl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtrllgcoma.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtwbdojnli.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtviadonpe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtcjapvykm.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtfwemkxgz.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtkrffwulb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtkwajysqd.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtqedguvvl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtfwjgoqli.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtesmavcvg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gthpbnydff.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtzcttaoxc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtdarufrxx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gtrgngubjd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaoflcne.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtlggpersl.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtprpzfcqj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtykccleiq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtlftdavca.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmduajsm.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtuxazudkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnzlmmjlu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtxfrkrugk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtxiriebua.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtczdkdmch.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtgqpzdgqk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtjpnmzoku.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtcftytvwx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtfmykbhzh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtiuuwwmfe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiyoqcck.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtcmwygbhx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gttkgdtvhs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtxcnmnoim.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtdugiwvuw.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtfppifkxu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtaexleuiz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtwapfwmmc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtjgvbpjlb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtsnehisvc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanhowjja.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtzpjgvmps.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtqyhfnfym.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtokzyvfkb.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtyoubazax.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtkcqihrqs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtsnigimzx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtmdoxhrbm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gterotquda.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gthrjnafsv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtznvwgvsv.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuguklhea.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtzhinsgua.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtfnirjpqw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtbnvrjqiu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtslwzikkk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtthqnzylv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtybpbcagp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtafmpwpkb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtfzvcyjen.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtpflchiwj.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtsvouwqwi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtjecsalkk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtrzhgvzjh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtiblsmzgt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtpvnbqvlr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtekqkuhie.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtzqogarfb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtubgxnsvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtupzorupq.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtdhcesvbw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtapwnuvph.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtggzqwefg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtrmfsgvqc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtckpxjzdn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtuiqlspya.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtmcqlxdtd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtlrkgeqgl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtsjjebskz.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasjtkgtd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtevaygocj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gthhfjxsjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gteuidcoex.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtedbbtgjs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzoftuxz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtemgjvrcg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtphzlbytx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtexmahrqr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyisoowbn.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtmtafiunu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfxtwudmf.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtrskdvdwv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gthhmcmonf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtumygvkde.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtacllkbfn.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtmxljroxa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtjfmtdhox.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcqjnfajn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtwmxgdwig.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtpbjdwfxy.html


<!-- 参考信息 -->