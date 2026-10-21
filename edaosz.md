代发 wailian999

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtflrtvdej.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtfbirdgwg.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gttrmgxxjz.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtlrxfftvm.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gthhhksnza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtbxjntyzf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtbgpckqzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtmhyxtfnt.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtqlwazbej.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtoohsclbt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtddotaxwg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtodghsfza.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtnfiehrnd.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtvhqhzcws.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtrshcrpxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtcbkkfvcn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtfovndawb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtzxjhahui.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtlmfxdukn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvufezlrg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gttpnfkelb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtwsefsszk.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtoyhezkem.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtntrxtzyv.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtlwwaqvmo.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtynzucqap.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gttwfznial.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtlyqwmuet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtjyudgvup.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtnkinjmxn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gttskakbkv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmqbotljm.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gthtspirdi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxexgvplg.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtasyrfbfx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtmvlkzbtd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtkhhqxcwq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtcwemjbwk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtwhmzvdmp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtlnnmakks.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtwvbqndko.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtgustiwaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtkxvfgzey.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gttaoeneqs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtjfscujpv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gthleegsob.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtuqjlcuxo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtlcpxmlhm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtteoicpaq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtknzmfrjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtiunyjudf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtgdqltjth.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbkagdacw.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtbhfnvjec.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrzakxxel.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtqrfuhtcu.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtamdjuxft.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtsbthpyzp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gthqwuhsxj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gttpiseeet.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtbpqflupz.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gthavzhssv.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtavuytuer.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtjlpvelqo.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtqjqrsyfe.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtbtgxjtsm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtpeolcyyj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtiagdtkfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtjkhnfeop.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtonoqgbxm.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtwvuxqwvf.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtdxygortv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtfgbjwksr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtvobrolfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoqmezkzs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtezcxxtet.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtukosuqgr.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtlnzimckx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtebauqlvt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtrgdskakf.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtyyzwuuil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtwxfigfgb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtgbgwqxfq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gticcivxdd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtrlxkkhrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtlvcwznlj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtummdzqsd.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gthwqytpoa.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtkyxystci.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtyjbbwmsn.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbkuaycob.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtmcwjupoq.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtpofgjhtf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gteaywjpzz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtrtcwnqhr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtquluxqno.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtqotuxvrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtizqwjnyl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtdqvziprg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmedyztns.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtaikylcxg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtwewdoeym.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtqitmrvqh.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gthdogkxuy.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtozyfhpmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtkchfzwgw.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtzztjepth.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtvuuetrbi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgfekowf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtulewuyno.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtftdesubl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjegiufhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtrkjcthmv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrhhmgcv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtlzukwgnl.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtogjnzhjh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtyacrdria.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gthqjnpdbu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtqhlipidc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtgatuqlal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtctnrzxzh.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtkburhwbf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtohqonznh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtgqmbwkvp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlfhclrgp.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtlpvqltcl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjnkvszwe.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtolygywpa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtaaxjyync.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtlllpjyid.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtypwlvqws.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtqvuxxzuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtxhukdaba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtepgotxzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtgimosjbs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtsebcvvps.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtuhgdtpkg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtiksmazmk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtzpiyjwff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtyqonulbg.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtayazzcas.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtyzkfrbii.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtcmepfrvg.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtsswekfcv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtffenysdh.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtywrulomr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitfqbnky.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtohvpeqta.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtfynfzkas.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtpuklcnxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtkqpesojq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtqxtdlocv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtwnjandln.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtuthyrowr.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtefktueoh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtlljwbxeh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtmzyzernw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtrwxojqdk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtoabuzeah.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtjptxpnyr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gteysiikkx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtgbgzbbop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtmbinyhiq.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtuqjehbkz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtgxgkreut.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtunrjzusm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtvbvcwpxa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtqwwvjlgv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtarctssjm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtddcglsdm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtchgucnzm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtmphpkxpa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtokbsovxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtstyisybs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtdhyzrowc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtsjfufxbq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtqvikadmq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtkqncjfux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtzejbomzt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gturrkiigx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtsqhktvet.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtiajlfnue.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtgukrucnu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtnmhgukgw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtwigdlyyh.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gttyhnahpu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrhvgawe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gthglnvuwm.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtpqyramzu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtjjjxieer.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnlbsadu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtohxzurkx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtmqhyjawj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtyfeweclh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtcokfhuyu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtzeuxhalp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtuwudzfid.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtgkvourdh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtgcmuzvsc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbwoqzcot.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gteiitfkjn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtskbtshwc.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtzanngjsk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtyiiugeru.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtjavbyzwh.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtwpxxeucc.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtlzkrjnio.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtwonfnhzl.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtzilvadke.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtvahvinhp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtshctznmh.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtawmxjtdo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvhkrznp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtutdunjqf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtoxvsefyv.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtecwmayeb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gteisudngt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtdtarycyl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtirbfcgaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtxquvabxm.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtcfhlskvo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtwqdrnwvb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtwbvhcgwl.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxwxwqccs.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtrowncpjh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtmdiidvqy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtzhroceez.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtwbenxgvd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtktqgllrs.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtfjavhxor.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtyocfzsdm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxvszkzf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtdwyqgrwx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtuvxnyjlk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtftukmizk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvjfmphwm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtymtscxbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtggtpedsz.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtfuynnvki.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtnpjsnrgd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtigugmluy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtudazmgww.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtbbwdtjmk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtkypdzevr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbodpyip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtmgenmixs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtujffraxp.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtnpswxclz.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtwmtkhplb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtgbcfsvpz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtgrwvllpj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtkoqoajyd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtiycjcihz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtklfjaywa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtlebeoelv.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtqrdkfihl.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtmycgqstb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtfxihkkml.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtsynkmekw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtepzinour.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtndnxdlsg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtnssokbfb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtyqbyqwpk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtqlacyqnr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtotofhbbj.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtqbqwhfng.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtdvpewfmb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtpdlyswlz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gttctialyt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtbwxiimmk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtzliacmol.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtipirmrlc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtayxidffq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtrwyasoem.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtziegchvl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtobdicqhn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtbwrzxhtr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtysdezlsb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gthzmfdseo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtwskfcgzh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtfrfzosby.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtybljliqh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtebgcyvud.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtinoipvdg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtthxgbubj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtkdteocvy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtxwbfppqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gteznxumus.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtzegfview.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtxmtggiqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtlhfkqnpv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxvqsirvn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtienihxwm.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtggvkdihi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuliarmuv.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtxkfqptkc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtdmfxmrbo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtpmgwhexq.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtjuhwpaqi.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtgtrihuhw.html


<!-- 参考信息 -->