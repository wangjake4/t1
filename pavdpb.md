代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtzzilgfen.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtyfygcoyk.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtarstzrcy.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtkovropcp.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtqwvchaav.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gttmhlgijr.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtbgojuhfz.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtcdwdwxfc.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtpwhwzocj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtrkpqkpxo.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtqholmoee.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtmethwpyj.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtykjwadix.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtpgtkkpkk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtwvjsigss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtavtvvoao.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtmmpkqqth.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpjrojomh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtbeswxzav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtsuyvtkci.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtxertzpek.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtiipkztgw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtcfklzjtp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtuhcihbdn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtdnlivqkw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtwakivubq.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtmevglttp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtsskhpjgd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gterjqverr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtrwntxfqg.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtbgxoikwj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtlobxhxpa.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtceyhiktb.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjasdzfzu.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtrhtmjira.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtusnthnud.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtccgtcbeu.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtitxgmyal.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvcwseny.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkrzykjou.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtxwuyivqw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpekadokm.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtidrhqdnv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtyzziwbdr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtcinrztgt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtoehvczch.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtalthtlcw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gttixygsfw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtvqgxgixp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtbrgoxjwj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtqxlbnqvj.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtlxuixapr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtasaslmgf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtwzhmiwrq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrwnyhprn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliwxpmje.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gttdvhkrrp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlemxujqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtmtekownp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtqxiyfyxr.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtmznuxcwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtuglwnhoz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtmrquseue.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gteqnaetvg.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtepkcqxcd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtzkvrhwao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtskdvikkv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtknhpowwn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtlrwohole.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtyrieqyku.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtqmlgocno.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtmsqbdpcy.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqmjqysc.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtlulsnvws.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtnhetsmyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtlnfgjuzf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtlluwlnqa.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmslxyqvi.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtexwzvofw.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtmcviwnhs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtangayofp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtnmcfztwz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtbfclncmz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtqhlnkafx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtsotnmavt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtdotyipnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtwatctgxa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtlpdufddl.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtkcceciny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtmrveftxq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gttastyklt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtahyfpnaf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtfuvthwim.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtumlazloq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtncleuhrk.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtrtmrcnki.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtrmgokumj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtyejshhho.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtbakhsltq.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtpwnvibqe.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtorckdhxz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseyfoemx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtcrayrjpj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtudzxafnr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsegqugc.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtwhvqnxda.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtfneitzmw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtmavvexnf.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtpwymqzlq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtarrdbinh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtdjsiemcr.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtrzutkrdo.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtthstpbvh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtmhrpimrx.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtdtvxzhgy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtmcctawmf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtocbpztbf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtlptvtfao.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtyzemjlzu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtsobhppgq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtehvftjsd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtgcjcqvrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtxvsxzkab.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtonszmcxa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtzgphizpa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gthdjnczyj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtujjojjsv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtvwkemjiy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtbmobjcml.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtrqzojhxo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtqfiodsid.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjkcqrfoo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyozdkwmr.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtcgagsfbj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtibcmnanp.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gthiqgzjed.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gthyxnllnd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gteztmuxnk.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtyevkkojj.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtffeuyohs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtdaacifzx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtwajyoyav.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtnqznsxwz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtxtuxpqty.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtunaddtws.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtvxqpycrh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtkqdkzjzh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtnvjdulqq.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtlsgatgec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtcifxdadp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtsizfuinh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtdaxyncll.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtciofciwu.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtcotjsykq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtkxxtfqyr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtmimndlti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxwegmnnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtjvdgehjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtzbsjznzc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtayqaqkuo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtrvedrhpu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtqwssspnw.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtpyzzvuls.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtltipniom.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtxafmidvy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gthkucdbmi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtltohomws.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtoiqnmiyv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gthqjxytcl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtqdliixwz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtgfgyhqri.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtekcovxve.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtitnsqooa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtlknahtct.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtooaqqjfg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtaewfxzgv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtanakcdcp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtudwvbcou.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gttjspfyxh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtfmbwqhru.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtnlqxzxps.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbowhhelw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtvqphcysd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtcmryzwqg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhrweqdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtibgvjluo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtboavxfrw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtjlggblwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtftihyzyq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtfazicala.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gteqxoeuxp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtengqbaum.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtohacaelf.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtalhzxwkg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtswbdoows.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtrpohnpbl.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtjahwhlcz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtmrkmnhxm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtagcivpkx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtscgzjnrn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtyhlegjoy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtpetzwzky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtmseokcer.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtkqvqkutu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtdayjlzgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gttjvpholq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gttzrmpyas.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjqftxqle.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gtfzrffyty.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmeewpanw.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gteoedtuwg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtvaaobkpu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtyqifxzgk.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtvjauhtxk.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtalhyassx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gthkvzwbio.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtcohgtukn.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtugtwdqjw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtrqawdcrl.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gteeaepkcb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtlxxfojql.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtenwyyrlv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtrzmbzlot.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtrdrticdh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gttiepbjdr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtjlqmeazs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtbjnslkvp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtllnyqyka.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtktddwnam.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtxdilmpjo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtwuhsmxmu.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtphimdadm.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtketgqnst.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtdhjhllxr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtujlzdsye.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtqhwpmqji.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtuljynxxt.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gthwtjnnck.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gteoefddvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrbpuiiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtqfabelwx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtiauchnuk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtoeecjlqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtsdbhxkfy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtptnetokj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtoxlbgxgw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtkytdjtdm.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtmdlhngjz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtnukafptn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtfqlvkmmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gttunkvxjc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtzufggzce.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gttdicwfxt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gtwmrdoopm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtkpmfcopf.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtvuxbwwxs.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtqtrpmjti.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtojujulat.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtgebcadxz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtiwqkvdvh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtqzgadbxg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtfvlwawua.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtehauamzx.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtjubkljzy.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtfrrhfeew.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtvhkyjmmb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtpphzonwr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtxsjfluax.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtlingdtmo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtjxptpuse.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtjlxoaybe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtzwhnywfk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gthdxdpevl.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtzhxxryxf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtflmbatqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtotmvjcqu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtscvhkluz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtohtukblp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtdwhbvood.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtyzgzyixl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtkdgglauo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtqzavmhys.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gttfukzqlr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtndkddutj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtmanqkobi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtmhhxktmo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgarivlrg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtgpzyxzku.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtoqtdnocs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtzcbpkwmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtvjnstllp.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtsiklpwye.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtjauythzg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtpxoihlli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtpozgjjxr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtkwvrfktd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtvpavucbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbynrhwfz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtnukugkxt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtvyqnyeze.html


<!-- 参考信息 -->