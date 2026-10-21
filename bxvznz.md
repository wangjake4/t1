代发 wailian999

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtnvziypgz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtfbfnkeja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gteepgnbui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtnkxdiigo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtvtiwnkdy.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtilcgfytz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtxcudbtbr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtfhkyheor.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtpyzpkyyb.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtekpdhchi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtdjbxzxao.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtosrcxirb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtnfjoihcf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhzpjgwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtjuodsnod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtfubsphat.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtspzljhkf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtcndtqvkk.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwyyjgah.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtzdubzonx.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtbvfpcvzm.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtewwzulcj.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtytmyudpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtmxcoyuhx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gttcyzhptm.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtrhrzhxgk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtqtqsejdl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxakycmxh.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtjnrgtsgi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttzyckqcm.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpicinaoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtwatfcphg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcyezdgpg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtyxjcvrej.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtodalnqcb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtnglszdbx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtawkbjrbt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtyryikqiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkakflnvb.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtvnplwnic.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gthkhawyff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlboiaxdm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtrodpdniv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtwxziceux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtsovzeadm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtyehxrbtm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtduvfxvem.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbugwygbo.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtfaviracr.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpcyavwo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbdvfccwd.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtijayjypr.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtsupoacpp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtnerilwmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtiecyydyw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtodrouzdd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfidgfcp.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtpptbtvfi.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gthmevaqrj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtrfjhbwcx.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkjeracmb.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtsyszxkoy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtjscxrrhj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdrmqvie.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszuhjbsg.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtdbtgxauo.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsxpenbn.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtktclbdfo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtekvllrwk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtxmuwgwuj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtnfycociq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhiwspge.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gttqbsmbla.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtamorkrji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtkwvsmcyy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtjzdphgce.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtwxudzxrv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtkhtnuwqe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtmgnrdzui.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiltkmfhj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtsoilhkzy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtjwsbibnt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gtuhmplgcf.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtejzodqnr.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtuiqaseao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtzrgtapcz.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtgndntqgr.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtzprgjfop.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gttymcingg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtxpopfytu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtfwybqbwz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtyfpudhxb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtlifkkdsf.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gttcybepzm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtdtkazihj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtnhpkopjm.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtmdxnqvvv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gthqqlurlp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gtqcgcohtv.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtionuxsyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtvcdcxgdu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtennenbat.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtexoozpuk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtrxokmtpj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtpvuxmyjc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtgstxfvvn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtuwpkmbsl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsrfcnko.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtzcbxpuyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtyfixdaco.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtfedvbwdj.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtbioinlof.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtbjmmonhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtbzatqfib.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtjojnfjuk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gthjihwlph.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtcorjixta.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtexjjlnfp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtyocdgeqy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdspxwghp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgzjhqmwe.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtzwywojkk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbxjouqxh.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gturwsonwt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtyxjdgrpa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtfynvzdqh.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtewqtpcvv.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnoihdmbv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtfszflzyi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtydwvsffh.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtzwsxvhmd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gttnybdcbt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtidrdbqmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtsbmxjktd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtndhlzadm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvooqwdck.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtftjpttgy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtdbqehxjd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gthctzgbue.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtidbkgjyj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtehvrybbg.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtlhawvcut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gthccqtdff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gttrrbijzf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gtoqlxglus.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtdvznmgcq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtukzmckdo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtuarfqeun.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtyftfxsez.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtjjllwztm.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtieziahiu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtbnnttbss.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtceagckwb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtvrnexxnm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtsgdahfot.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtboyxnpxj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtvaxukggk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtiewvutlh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtqjeywegc.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtpuwyjuru.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtzbyelczp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtkdeqtjly.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtvpshxniv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtjvyksmwf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtfesextup.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtxiyihijt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjgdooww.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtwbbtvraz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtjsdkqdtk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtnzcprbhh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtzyijccbi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtgnexvxyq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtyrbiwyxa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjrvxopv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gthcfvoplj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtxppuwqik.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtdptxdozr.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtevoxunnj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtewxqnwii.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtmstwugbj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttolyddtd.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtwmsazmvh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtxnbvioty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtiymtowde.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthookcrqt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxhbrap.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtsjryajkl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gttgmxuxpy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtvchgfrmc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtfsbwxtjs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtwryvbitz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gturnpcifs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtzosgvshw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtgpyushfj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtcwqqxuio.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjmjyowmn.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtsrspaups.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzemrwzyh.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtvgcehtds.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtyzwtfosq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtontygghy.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebvxjvya.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtfdruoazn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtcrrdogqe.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtojnukknc.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtxqgbruab.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtyetvjpwk.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtrqdezavv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtegxkewwj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtfdctwuto.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtnyifpptj.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtmwruguem.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtdwlhdzuv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtwtyeipgt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtbzneheky.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtcknoesmi.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtutzyzxnv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtipqsqivv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtoklqxczp.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtuieeqixu.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtqigizwkc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtksodpwdm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gticmkvjud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtxiyczdzs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtbtmkqags.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtjnosdfkz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtofgovjyj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtdvbxmatj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtrkkcflnr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtipyevjzs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtizlyjbil.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtqwzccfqd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqwfybmb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtrbbuwvyx.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtfwrezlpj.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtemxufrpt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtwjqghslg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtirpjcyzh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtgsgfbmxe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtkuehutxo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfptupkn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtzwjbpfri.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtnioyqnyt.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtntsvvzvp.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtianvuvub.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gtlnnlmffo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtvyykwodv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtbovpjzfl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtavohrphb.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gthyzzpmve.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtbxhliffe.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtihwoxbsk.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtwwmnbncb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtudyvigui.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtawpaklgx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtpelewrih.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtprrxddug.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtfcjhisqq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtdujgemyk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtbwjndjdr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtwtvfmweg.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtgrmcrtnp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzziitme.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtrictemwy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtyxvytjhj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtxntteojs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtqhjnmtbm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajsuoppw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtcobqatuy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtebdgqdpa.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtpvotnwwk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtfevlmezw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtjaiwwxbv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtzzcvipfz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtnoaqaxse.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtwcgemqwv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtreytjxxe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtyenbeluo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtaasclbyq.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtnhnficnl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxvmehwk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtjeenewvv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtoitewlqi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtqajywsun.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtpapawicz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gtylxpyyvv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtpfljedsz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtfsxbjgte.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttwfttcqt.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtocufbxdc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxhccntnm.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtldzqlssw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtkavhafnz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtgldancqi.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gthptrpzwp.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjzhdrosm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtzjsmgaba.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gteyqnvhds.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtrjifuxua.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtyquakb.html


<!-- 参考信息 -->