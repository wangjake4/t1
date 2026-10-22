代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtkkzcfdvd.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtbxaxlfhb.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtnanzbneo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtozdjlxfz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtlwtopqlc.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtydzbeuye.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtfzilnmsb.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtrlnzjnnt.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtuqbueasi.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtczyabcoc.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtxzsyucir.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtvbrawpbj.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtmodtjsrh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtpwfqzhko.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtssxlrhjx.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtizcwjhaz.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gttbqjgzvo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtccwzhydn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gthbzqoise.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtlfedcpho.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtxhhcsoev.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtlatrdbra.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdwtrwan.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtztjppsyu.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtzvmhcrob.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtghrqyeag.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gttlpiwggv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtmxqddnof.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtisjaklnk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtwmuqfgck.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtdirelaho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtmymbwyne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gthsfdovim.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtlqhbntws.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtthvlfrim.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpkpwfzy.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrthmwge.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtmajornct.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtcovczyfd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtpxlyjkpn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtadtmsbsx.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gthiewrgum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtkogsaxan.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbsthzmgv.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtrwfmxgio.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtycawytqb.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtvxuqdxxy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtvrbrplna.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtzjhpbjxw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtuajbyqzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtacbcwepy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtruzjfhxn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtqjrllxik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtofkwtyiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtasrgczgu.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnpsnswp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gteaivwhyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtrgpjtpyv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtjgwfydkr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtcfrynixz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtulriyvlm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gttueggxdm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtpyesfzyl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gthuwvovts.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtjvfnpoif.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtbavxihlk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtglerhokw.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gthnubnkgk.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtqiyppxkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtemcdrhbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtqzcmquxb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqpetbre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtpkixrvtv.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtajzeypev.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtmeelrsgn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtfitcctnn.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtvmedmymn.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtpbfffhzb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gthszxczbr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtxyhbonsx.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtqmgzkirw.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtofpbrkgc.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtxsxssgqw.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtporbdaua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtlmilbmrh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtprhpdjcc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtausjaevo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtffzggkla.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtpwkqljli.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gthvowvzdf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gthwlhvlit.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gttbntfryz.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtsabsbrhq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gttxsbucin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtcuouoxeu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtmyhgmnwr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtttvkqqvt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrcfyqeq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gteitjnsqx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtiudzrkmg.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtyialtuik.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtamxdwnqa.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtldwdikvi.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtmugpyazg.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtlkquaejh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gteeejkddn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtyzawadfy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gttgipfphz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtktjjnmwl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtsexhttru.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtsrdmehis.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtlovhlfya.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtcjdfkycp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtnajmwmia.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtcakmgxwn.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtyzoqiubv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gttwdqghqa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtknpfhohz.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtqfuexsir.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtzwzpgszz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtnbzydyry.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtjpnhngvj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtnuglcfug.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtaofdihdy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gttagtwjww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtgzymnmbx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtridhkjuj.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtbysqslbt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gthwavjcfc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttefqesxc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtketbrbfj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtqqpckhdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtvccpxnrr.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtqpiciovz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtxznxpksg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkbhksvrs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlkziilhg.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtsekbqimu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcbcphaw.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtmkmyqsje.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gticvnpjhl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtakuqokjw.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gthnblaveb.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaqywccei.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtpwnyyqts.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gteovlzsfh.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtyttyjrcb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gttakpjkii.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtboakmfjd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcfyhzgls.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtuyhlofnn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkjlptsc.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtztzshrco.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtviewroxz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gttnvyejwv.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtezwlowlv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnjjmbrky.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtfndqejme.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhrhfohr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtrqnymcxt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtknlacdzs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtqaalyiug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtshjntbqe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtforakriv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtczcfdlqf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtrwdmwpom.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtmdkszohz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtsjqpraum.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtlmnatgbt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtcpnknqbp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtyavkqmwg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtntlcvwac.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtcdrofuyg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtvwbpofnp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtmsghdtbp.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtotcmmuyk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtihxgfsid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbfqgiwit.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtbyxyaikr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtptsenajr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtmtdvonzg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtctmgnoxl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtdkcymove.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtejxmpzpd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtsiwpuqud.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtcuinzpji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtlasquaaa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtimjciefk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtxxhluknw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gteirpqcmn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtxroncgmq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtrbvnctih.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtkkolmetv.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtpdesaaix.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtxtbcxhxd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtmohlpwrs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtvqoqnrqh.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtcqcobeca.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtrblardzt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtrlxmlzmo.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gteypqwhxd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtnecdbtlh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtiliqkmqs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gttzofwfaj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtulldhaus.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtdzlxhaxw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtumlalefc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtrveumidy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtuuenigsg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtujiehfcq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtdsjayqpb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttdoqukze.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtdpndwikg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlbnngdgm.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtpupjpkve.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtwdwaemui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtddisiwft.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtmoqjqngk.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfycmacle.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtmgrbbktb.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtbwngktjx.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtycqetqjg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gteibcvfda.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtxccvkwhf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gthputtkpw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrrghgov.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtxzaptsdl.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtmagfgjrb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtozpcwwuy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gternrunoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtlfdilegx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtlezvtker.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtbpnibdfe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtkqrntaak.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtszxrnmin.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtknfnlmkq.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtuiodevxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtbmogcbjm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtincgxojq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtwfhwxita.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtqzvuuxyq.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtugedvtes.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhlmjecv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtndswqkbh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtnkqqpweo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtvebgbuyh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gtqieduzfy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtuplonurt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtnvqaqxnt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtpvemxavm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtcxkeozaf.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtegwzvldg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtwfwootzj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeignhby.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtknhvktwo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtxogezonm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrpoocmm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiugvbbtr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gthjcfvqpp.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtzbjsjhwm.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtxfptlrrl.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtodsvoqfj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtvmmfxmvr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtusfhqupg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtseozqcni.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtwldqafvv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtwycfawyn.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtfvimcgpy.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtyrnvzhqg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtxknowqwh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtwclaqwht.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtkfixzdme.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtjuxfiihg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtzcvbidcs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtyccyqvbu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtgxhcxnnu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtnjzpvomx.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtfcoouces.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtwarfijul.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtqiwnmupq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthdviplz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtpyqlpaif.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtgkrlxmhq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtnkzpbihv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtbsdlyzyz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtuqpdywyk.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtjhxtyhab.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtswlslaia.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtpzpgdaly.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gthadxszdn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtthgvkeic.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtnmrzvvft.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtuknctknz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gttaanqsys.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtciathrvb.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtcvzqxbti.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtezuunqka.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtaovzgmnd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtzumchudu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtoanlyvzc.html


<!-- 参考信息 -->