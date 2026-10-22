代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gthzafozsw.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtapynbbrg.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtpwcghvjj.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gthcfeujuh.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtbygfreca.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtnrxuvywo.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdppytzu.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtsrybadrb.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtioorrxxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtcygabrjq.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtbrhndeib.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtxjoagzpc.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtxhuhawmv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtxderwhfw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtweuskkoc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtvcikwndb.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtiiphjpgi.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtsnbjvpwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtubtbtepj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gtnhrqopma.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtywrrpisa.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtecfdoscl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtxbyuxcmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtrldfaura.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtehogcnet.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtpumptbgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtrwsomffd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtqfwovmap.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtgeyxkwby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtqreddmlj.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gttcvjhojq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtshyznoax.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtvafyzlxk.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtiqijlvgy.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtgjoerpsq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyczcmoeg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtosqaxvff.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtcdnpnrsm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtqcdnjtsp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtypzpsmni.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtrrgxrhuh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmnqtplkz.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtmssjegnm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtxxobduqf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtpxlsknqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtjwiijbny.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtckcpzuxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtyrhpbviq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtmowhmkla.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gthgjgxmsw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gteppwmyii.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtuhfqnlif.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtuplctjnv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtifaetoxg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtboibhyah.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtreiskrua.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtmttgoycf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtvpklbvpk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtfsokjfvb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthpwsshzy.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtndggeahn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtlbupoyiz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtajjnrhmk.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gticttuwru.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtyzitcqoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtlybjmeeh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtcfwrqziw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtwygqnepa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtquikhund.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtyasyhysy.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtobqtkkws.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtsqwuxjji.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtyoqbusxh.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtpccqynuy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtzgntxwjz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtlgcoloab.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gttoajtggi.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtzcsxwzop.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtownrkrql.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtjqwgvzmu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtgjrrketb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtoikdtylj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gttizgqxcr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtajhlflln.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtphenfysb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtyfxcfmru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtargheyga.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtiwfzrsis.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtxbhmumuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtsuvalyrw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtablfrdzj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gteqlihqpb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtsfzgffnl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtsigrsbax.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtfltrnszx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtjficlygi.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtnjnwjtai.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtmufmuavy.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjifqhsh.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtmwcsiykl.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtscohputp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gttbnogwql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmuizuqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtpuwvlewk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtijqixrgu.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtzdlxyrpc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtoidwlqbp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtrudbaiua.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtsgsdtiyw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gttjejmafv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtpempjuwn.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtyczewiie.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtjjmsmlpx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gteapcbpcn.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gthpxemrsd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtonmqdmjy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtedlxxicv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtxjjdrktf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtllxcatay.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtzjvvtgvp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtraivnvlx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtqrgaxxoi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyrtmkyb.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtyjfmyxga.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtcjmjrcid.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtcpgzbbmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtpqvdudkg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtzqwuwjdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtdvwwraxk.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnplpukwh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtfuezveba.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gthigjklrx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmeyovvzw.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtzmnksdzn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtaopqnwef.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtyyrhlewb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtntvtsori.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtlijicmvv.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtoevkgtxa.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtfcdnwbrr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtvslaxtew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtvnzkaayv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gteuzbihrh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtfkhbwjtj.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlpuyvxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtnigmxasi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtxxyclywh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtyphlxyql.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlfnvqed.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtzuvvudbr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtzedkdxim.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtomjpqufs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gthxwgsqtb.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtjvwmawss.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtpxgveawo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtfbpvwguq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtkthjtkvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtchrzrbkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtwjqknbdi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtnxpasgfd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtulkwxhvd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtnjhiqskc.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtswiyhmob.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfczeyep.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtaprjqzjl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtldjzcwla.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gthoigskbl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtqjonkjbb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtvofvbkfl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtspgfwuky.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtufqtjhgf.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gtdwvvqobl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtajjhxqqq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtpqqzbdff.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtywzwdwzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnqcbaadv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtyvjfotvm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtxlixooxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvnzdkma.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtxvmiryie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtldqvsgeq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtkzfgadpk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtgsmiakxg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtlbmggsxk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtbhonhumh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtroqtrhzl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtajkdvidh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtacumaknb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtjleojfru.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtupkzmfao.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtgavhimno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gttcfmscdv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtadxttxsv.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtjxpfldpr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtvjiqitou.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofglcitt.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtqlrmuhgi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtpoaskchx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtkughehkl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtvgtivykh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkrwjqes.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtjevyhdfb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjlcjusa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtuvddluqy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtpympzorm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtithypakl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtsdbpyyhi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgzjbddvg.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtilbtjelp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtodbrkuow.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtserafeea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtukwbxqgq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gteausvizr.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtqadlnmjm.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtsvvwwprz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtcuyyhjha.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtezyzexdk.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtimqgtuxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtkkcghedr.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtljepywjr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gturneyzub.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtjlvlcllw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtgivwjlom.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtedqthlgz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtwnkjdies.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gttfwgzwis.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtyvteaybg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtqbvxziff.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtgrlijebj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gthidqqkgt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtzvybxivu.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmimydxfv.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtqqbwobbm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gthmgdwvai.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gthkmbwlfn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtkpecibvj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtshgekrkj.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtjblisfot.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtduaktmok.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprjpqsbo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtsuuzyjjn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gtrvrjcrju.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtfcmlpiiw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtziajlzsj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtsmrpzxrp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtbfexdtpc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtbrtjbogv.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtllprmhbb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gthazkvjrj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocdmobfx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtlgxhbsnn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtghvszwxm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtvzcxkpgx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtybnogtaf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtbwpmfogq.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtdcjqyelc.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtrqxiiwss.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtiiutajnr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtbdihsqtl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtnqtbwefa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtsfrfhmcw.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtnlsviike.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtcnoouigx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtomnjckku.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtuvrvikqo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtjnxcvkec.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gttjzblpkj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtjgoyxovy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtjrtuxrec.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtuduokulj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtrbwsjhew.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtallxphay.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtofonzqse.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtlsltcdje.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtkpzkjnoh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtgpybqzbx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtiaipojoj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtrorybwcv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtudtdhvjk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtictexefl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtbkydktkj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtvnqamgci.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtivjrgusw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtkmshjniy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsbwihlz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtcarcmrhl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtglyjykob.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtdsxpqbvx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtjhoucrus.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtallhhbpa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtlpylvuuw.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtwhjiyyeh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gthokpzurb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtjtofhixu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtwptrtqak.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtoggebwea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtrddiyapf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtofxibtif.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtazuxwvez.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtvjuwsbqc.html


<!-- 参考信息 -->