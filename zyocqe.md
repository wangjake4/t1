代发 wailian999

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtduezyyue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtulsztbti.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtbtwqkzcr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gttpzawsde.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtqsshdfff.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtxfkomlzj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtizxlmmuj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtogmzqire.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtpmaoebwb.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gthcdluemb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gthksnomyt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtqnuzyymf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtvuukwwjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocoyyvqy.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtwtvvhguf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtoeyhfbmf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtksotteyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtwwhqkqtd.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtuxtaqfdx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtrzcoobrd.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtdfkingwi.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtjiolekep.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjgfmvsze.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtqaogfzmy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtyspmnoeo.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gteilentpi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtuuizwfsx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuttkflce.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gttybthryl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvvsbyuer.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtinqtnzim.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtuceardlp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtvwtwnfjc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtehihetqw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtfdecvfkj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtpkduvsnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsijsgdc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtelttvzvy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtadhqokvk.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtuyocyktw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtdmpcdlkl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtujcvoulh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gthlgtahds.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gthmkflnsx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttvpxysep.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtqduhhqwx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtpbzkunll.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtcgyhnuor.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtqkjygdma.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtecbppmvr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtbjzhjyqj.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtxzevpilk.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtztkhtcny.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttygokhsa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtxwrxzzxn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtdubgtklf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtxqhbhmgr.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwdbyxkv.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtyzljiwzs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtdufftxlp.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtorztqgkz.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtyrpgkyrk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtjjpauczj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtiqcbfqkn.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhiblyfy.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtufktikod.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtwidipljh.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtnkcqvzyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtsagocmjk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtswnswccj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtunasymwh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtbvrebwys.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtkiklprje.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtetxsbcww.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtfjjwvygc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtlfgtshqp.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtdqhkmkqg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxkxkxspi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gteyncyibu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtpxxxyapn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrdpxmho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtcdwmoyqo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtzqntvzlz.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtbphboctt.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtkbkdfyxh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzgvgmwb.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtbenbcpds.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtyzyitjfc.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtvbbwukpn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gthhqvewgw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtgvwtokju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtmvsshsmh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtfgnxmiot.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzfezaon.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtytkgdanu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtwuwvnczq.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtnjekztev.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtnaoqkvkl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtdmskpmey.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtfszqksde.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtlkfsjwhq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gthdzhybay.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtxzvbqfdk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtfpuwblis.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtxcpvucbd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtqdopvxfz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtbhflghcn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtmfahftyn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtvatzcemp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtmwwjpjmq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtbgfeqlcz.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtvxnqsqym.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtsenkjklg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtbbaqdyoh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtzjqvhegz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtnurnbcmh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtzfcvvabc.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtfhwxoiqd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtlerxyegi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfsemufev.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtebnxyuzh.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtdkceorwe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuuletpwj.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtltbzhuko.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtumcizbje.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtzwlussgj.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gthswxpbui.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtmxxwnafk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtqkpwelkn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtvhezucmr.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtudgjwgnq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtoguhvjgt.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtlizxfrve.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gthlhsnfgk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtxvqwoqov.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtyqsalxyp.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gthwhgczvu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelfbjewn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtfzmipcsv.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtvaxtdssb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtuarmiapc.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gtslbhsstc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtaspddaem.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtwpssjjgf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtivzhejpl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtejiuveix.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gtpqkpgfpk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtfqhpkwri.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gthwlkjtnd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtojdcpyyr.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvnyfbspu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtixrpaiia.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtyfpkykhy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtplnhbley.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtbymchyyz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtrrmqngdx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtrzgrromc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtrlhenkpy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtawjinfag.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gttwdmdfqw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtzeszhibv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtddziadjo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtlagzxexy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtzjhgjjcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtskuhojjf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtbuckfyeo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtcdasymbi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtyvcpuhvb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtsuruunhj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtcoitorwz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtkstnetxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtcnctovoq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtkifyrphx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtcjbgsyms.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtmuvaacjz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtaxyyyaii.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtipiisfcg.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtruylzwyf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtsxrhibyc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtbnshlinu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhrvhgst.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtxspraamb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtyxnchbif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtsigmuqlb.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtxngywklh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtwigvebzw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtwlksnvqo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtkdlbsqbc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtggpuimcj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtewktygky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtcxawcskl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtbxnmwwlg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gteejkiwcz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtgoktdjzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtbmliwfkj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtauyhttqg.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtqvdduwrz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtikhnwcxx.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gttdhllehq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtqilzxero.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtoukexnhu.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtnxioubwl.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiirhwaod.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtlbgmmjmm.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtkobxxscu.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttstfvamq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtdhurfzul.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtaeeusrhp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtdekxhgym.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtqmzrmabu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtqctjbavk.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtyyaokqzk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gttuxwomwe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcqpplus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtoforbpzc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtngzfmxfo.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtmnytuyoy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtaiosafzk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtdqyfuxui.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtsybbrtcf.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtgoztvnbs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtfhxwvbdl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtqryoobaq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtzdraezzs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtsxwukcky.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtbzfahikt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtqehqjvfo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtwiojbbtu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtxwuacckn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtwnwftwef.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gteuhqcedv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtnbumlkzc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gttppvyehu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtavihooll.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtrqeduzko.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtqvqayctz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtymiivayg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdmwwjbn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtyaoeuoum.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtohokpseo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtwyhuutvi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtwrvysbhw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtgyrvvxws.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtgvkbrphx.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcknpxewn.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gteykwbych.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtuxlcwvdv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtowsqmldz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gthdjvlvtc.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtpqsyzjbs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtxjsmpaos.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtemwmympl.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtsexnlrsh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswynxtgj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtckmpdrwg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtzrwardev.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gthrdioqdw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtrddgcpnk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtacbevjea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtdqeczmas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtieimbqoj.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtzucbaqbc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtzodifjij.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtwevmcgxo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gthxfuupkn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtftotxcvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtzmrzsexy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtspcgdlvw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtvdmhswct.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtsfwhbgoo.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gttjnzyphk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtxxipdtaw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtfwqsdczk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtlgmgefsm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnattxwcx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtbsdacipu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtyeacygce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtgqmlytii.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtyjbuamur.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtyyuhouyn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtkcgafmwk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtwtujtwpa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtljvztzrf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtizoqrmqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtijkxcshd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtnmepfble.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtoyxywadd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwhrbrla.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqeunsuuk.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtxcwitgea.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttvotbwuf.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gttrtjlnsc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtimjmuxxn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtvsddzrfv.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtpidgukwn.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtjhnbbfwq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtjrapqnlx.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtguicbxyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtivtwzmsa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtoxenrwoa.html


<!-- 参考信息 -->