代发 wailian999

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtmxgckvhw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtpmlmhdii.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtpuheimnm.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtgrrzpsxl.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtjmzbauya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtvwidnegb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtvqfdciei.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtrvfjhidz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gteogqxxfy.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtxggyhzrj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtjeptpcwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtmnneawdz.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtzmnlevjd.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtqufhuflp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gturrioboe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtahuvoumd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gturssplsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtodrzgqvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtegntform.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtoqvshqsd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtitfqheqq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtejmjcmle.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtlxlypgxo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtolcjmxps.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtytmpkkwf.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtgwjuaynv.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtndubuinw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gteeqmtlvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtugkwomit.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtzloonukw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtrlaqkted.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtavulqetx.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtecgpmitw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqzhwsnzk.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtichsoiph.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtfymsnbxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtmtqmkyhi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtfrcupnnh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtkqjmrmdq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtvjqeiiez.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtqvjsyinm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtcqqtoarp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqwirdmhb.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtwuhbyfyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtymkqocag.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtapbouigi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtxlwfukct.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzckfczb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gttoijoqzc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gthujyjxxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtachjvogi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gttclnuqqq.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtjcontuif.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtqoxdmdad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gthoqcmqos.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtgawhprje.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtoctfmzyg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtpvlpdemq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gteidybcar.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gthvyqooix.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtaroyjnlr.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtkjfavzis.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gthuyjtmac.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gttzmwezlo.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtewpadgib.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtwscdaomt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmkwcagz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gthajtpolv.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtrvtoetit.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtyibuevrh.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gtnwivbhmu.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtpxbfmldq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtjwmpmoqj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtiyjpojqr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtpbizhlqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtggvwcevn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtblruyzoc.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtxslrnkyu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtegskfqlz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtmvucloca.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtndllmkle.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtaqpcqfim.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtbmixcoph.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtbkdqggga.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtikdfdaqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtqdzhroue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtucwpot.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtumqmmxax.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtadtnkged.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtathbttzn.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxlcsyjh.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtsvlhmtmb.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtlkutjhlb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtleosqyzy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtlahtioyn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtkathiodc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gturejhbql.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gttvuqygzy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnvynium.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtgqbyqvvn.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqozycni.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtlofppzby.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtvukatpvx.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtccvzfddl.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtknrlwdvu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrckzylb.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtqacndpaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtwkniowxv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtzzrwwgsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtdecalhnz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtdskabebv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkbgsfgd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtmxdbbmac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gthowsgrca.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtypgpslex.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtkmimpkmz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtyiuilkcj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonhvjzhe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtazwdkyte.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfygqzjb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtfekgswjk.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtwudcipte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtvnufzwnl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtevmvymba.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbacmuxcw.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtcaffoyse.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjwwgwqjf.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtufruzmcz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtwaphinxw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbnmufvym.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtazgfhbfd.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtihspkirg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtokzzhixn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtoafbcpwe.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtdbiyagor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtwcetrrzt.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtztdtpgzy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtktijwsib.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtyvbjklyp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtiplebsew.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtfijhhxgp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtdgqlhqmr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtlofadziu.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtjrydxhge.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtccatyouh.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtojhogokk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtznwkerlk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtdiziqqiq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvtgcpehh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtqhnkyxju.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtppkqkjgd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahnwnvdh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtpuhoxejz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtrgqvzwry.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtvfhxljli.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtoevuybqv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtuvvasjzm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtznxozluw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqwholeib.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtutgmjhfd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtysrixevd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtfrzacivr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhtlubhr.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtxhislfwi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtsfdvhxgj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtozokrosw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtkpriwkwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtxonpfypw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtyrltjmqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtwarnkhuu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtjdhiypcm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtkmqtheki.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtxosgakra.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtsbqhkzyf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtxwvgtcth.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtawxmujbf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtueepltwe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtksaaeuco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqwmyhfy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtiymrgseg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtdyzforwq.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtjalcbuok.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemiyshod.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtikdfvexk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtybgfctij.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtodcuqian.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtvxlvkopz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtmolssfdk.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtukniamzw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtuidwpvym.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtrohluhzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtusjpssru.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtlzjpevtd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtqjyqnfga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtyrpwbxdq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtbkqeqjin.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtrhlqjgea.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtitujukjm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gthhetckrm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttcdpxduo.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtvidwimzv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhwyspxq.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtwmiahyst.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtyxrekhdo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtanrnbnaz.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtlfnwizkp.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtxggdjlzo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gtxvscmtja.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtseaayaed.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtfgqfmmgr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtovfruvfz.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gtayedwlxs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtlhmjqzzc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtcofsmink.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtjzhsbuqz.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gttowbivwu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtndioqccl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtzlcuylzr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbxcguok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtqaxctfgg.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtdiezdaat.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtijyupzle.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtzvvjoitz.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtzgxsiams.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtixwbkkwc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtnipizhyq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtpkjauzny.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtnuaypwvh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtsdjdhtcl.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtnyzrzddu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gttcxrwakm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtwehvjgki.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtjpznscdu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtgmmfglqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtrphxlpqy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gtxvafaoox.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtypwiqyia.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtwrssqksi.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gteyrjzkpm.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggmwbvee.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtkngtswzz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtgzjmmwpi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwbcevpd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtjyaejuwf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtguhcyxne.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtsxrldugn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtjtmpbgbe.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdpqpynr.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gttssyhckp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtguxqiknb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtpigzqskj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoycphkrh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtxnkiruic.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtjvodfcwd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtiwhegfpb.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtsiwtxhfc.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtglltzcyo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtoonjvdvl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtqzccnqpk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtgawpompr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtvpiwxjtb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtdxdeowci.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtocndasyn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtndoivbcv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtfzlghhuj.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtvudahiun.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gttgzlywmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gttipkvruw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtywvyviag.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcjkbgpx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gthmqvptxk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtovkfziwa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtpzclbmqi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtucwoscab.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtiejwduri.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtspwdpbco.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtqgriymte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtqenmubet.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtuoaruubk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtobccmrut.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsubadble.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtolhzhvmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gthrnqjcna.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtoutmeqcf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmburkzie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtppsmymkg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcfgpeuz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtqnzudlod.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtybpdnwhx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtmrhlekhl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtwpqrvvru.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtchoxnjtb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtthumcyrw.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtfpxhboit.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwbvxkmyq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtrxnkmdtl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtzwstlfzy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtxjvjpgfc.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcmbpwfiu.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtujdgkmar.html


<!-- 参考信息 -->