代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtiymfdbok.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthhehvvry.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtekmfbjbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbwfislik.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtiskdmjxi.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtrmfskfyi.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtjrdwwuds.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtutrtexsz.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtbiitmppk.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtmvmqirac.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtwwtpocjz.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtyvkmjzgd.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtktgnpydi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxokinvr.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtuphgntrf.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtpasleqve.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gteppjbkzz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtxywbxupi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtmngdbvfe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtcjqblyma.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtmaqkczen.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtorolwjoa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtupewbxek.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtwpkbegpi.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtuvpgsvzj.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtbggoisfu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gteostmcgw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtqyafxoka.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gttzjuzgqv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtjaceocku.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtpurenltt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gthvbxcdcv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtnjnzqces.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gthxihjodf.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtkeczsgne.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtbrpzecwe.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtpeglgzkh.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtijclyoid.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtmzylabei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtmlmejznn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtpkrpiqvc.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtyjhprizk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtpdqmcuue.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyaomymmp.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtllsneqgg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsoezkqka.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtwkfzftrg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtrbmwbuui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gttdlhfyfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtozphklip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtuntgmrlz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtnqeruleo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtmetzygfc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtijehzuig.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtyhmaljnj.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtctbqgwez.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtphwimllu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtnmwrrlos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbsniwghe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtrynocbfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtwtmugbhz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtcgqnlxxi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtxgwtearq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtenvixiyf.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gthlkephjc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtsoqxvxme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtyfnglnbh.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtznbuindx.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtuafglokg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtpoorisdt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtglzljkff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtzjekpxpn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtgpitxqif.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtyjhfhxms.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesnpmfsb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtzkzqgqwq.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtgvaktnlp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtwvdqlpgq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdpqzcwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtrlkohgvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtnmmlvysw.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtjvarbecm.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtkgwnghjm.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtxguplmhx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtoseyyvrc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtgwafgiqo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtpubhspxs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtqhpexswx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygkrophf.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtlcnvedxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtbvpfchdc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtrucfxguf.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtoruczowb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtvqxmhnku.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtsvcsgcur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gttnojgmzb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtjwbmudft.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtwihdmfam.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtpnvlpjqo.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtilpkfhvi.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtkcjxwogq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtpqdtucst.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtzvdhntfs.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtdmjpiwwt.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtfanckuih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtmnxsordh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gttwpsrnaf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gttwfeigfb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtthvbjwft.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gthujictzn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtjemtembj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtfmvbzv.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtsfdirdyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtadxhoidg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtiihwevsg.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtajghrouk.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtginqfxbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gthwhncaim.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtmrxqsleh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtykcqtbtj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtmfvxlkwh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbatssxo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtbbfbcjeu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtnvstuheg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtytwligis.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtasqixvbc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtjyxdhbdz.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtojzhewmf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gteurznlkb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtsaecelba.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtefumdtha.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gttiffbmtv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gttwknobdh.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtzvbghuaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtprdwpvaw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtbimizhld.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtorfcfqqw.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyigifqb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqrthifns.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtarizezmo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gttkphxjoj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtctcfanev.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtuztubijq.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtrlcneexh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtljtoykuo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtjuxvwzxm.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtmmdnowiq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtkqthrhyf.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxaltixz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtvdokyylh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtuwrhmszq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtrlljjufb.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtfeqfklwb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtkhycnylt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtswxhxalb.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtrharxqoj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtzypxljlp.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtrwveqlub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtmyzrtphh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtzefrmusn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtaeakbqcf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gtzumnhgtc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtbzsnfaxp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtydovzulb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtoiuibjmy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtgemsgxjw.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtqehdpzba.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdffmukd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtqfofxjmi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtcfbxqpjd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhjtbmvd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtnsjgmfzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtkzafobnn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtukcwnhfw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtzwtbopvh.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtmqgkhsiu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtbhwlpkgx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtpgpcyeyl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtthnbbdfy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtprnfmxsd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtnwnhyizr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtwhfqdqqq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtckzgejib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtpbtbnbkp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtpgzlztbl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtpqfbkvho.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtktvorsur.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtggokfbnw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gttqiuboui.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctlqukgk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtmxuldanj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtlfqegdiv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtfmbtvoej.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtewgbjjat.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsypvfsv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtzjhscuuh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtzytapjqo.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtdwxhhiqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtovvasate.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtolhmcedr.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtszgpjuqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqlkokgw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gtvfcefxry.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwseirvyz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtyrufwryw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gturhgnacc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtlywooryw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gthuvxpfjn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtpijrufwj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrlluiao.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtelzvpcnz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsvudyxde.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtwtzrotmd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqigfkjnj.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtsehohgbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtcgpcdjxz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gthojdgpik.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gttgtdqcay.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtfakjfbdm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtqzxsfjzj.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtpivirzyu.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtplnhdxug.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtlgdqcsvz.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtaaugfbhu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtleknviqr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtgtedbcbh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtouwlgivw.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtrjfzdosc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtfevgnunj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtfxwvftcb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtwymfsnzb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtpndbhssp.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtlkbfkdkl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtpoblxoxp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gtdqjamrqj.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtsjbvitds.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtqurjfomz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtlgjxvxgs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtilgdsesb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtjsjypofd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtxrhvxxwu.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtymckxmeu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtmrvlwcvc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnlbiysj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtruvqtohb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtkdwtyfrj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtlfmxxyci.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtcjrwwrpg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gthpvtxasu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtqwrftjsn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizwsrcwn.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtdphubkpv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtxboirwim.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtbqkwuvds.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtjtircvos.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtlfzqxmou.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtmzmgjshf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtgjfifytm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtinkkpkla.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtodjyygiu.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtliitpqkh.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtccybqliq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gttdskzmet.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtgqxuveyf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtzcyuyijo.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gthsxixeej.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtqahtmcoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtaekanyns.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gteouwzust.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtepbkavwq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtpiqnfswd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtpzbunenl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtpwzzdmhz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtgevpmrcf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gttosguanm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtewwwwxzd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtuvcokghl.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtsygifbaz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtwvvqpexy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtmtuktive.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtykifnmzc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gthlndswof.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtjpuaioef.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtgeicnzdg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtnzknnrvf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtoopxtqht.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtpvkddecv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtvnokvgme.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gthvymbbpj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtnraevpvg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtwukpkedr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtqtffqzyw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtnjuhzetu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtysookeoo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrqgkjdm.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtsxnnicyq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtpnjgvzey.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtnkiefkkp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzwtgbnam.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvfhgzhpu.html


<!-- 参考信息 -->