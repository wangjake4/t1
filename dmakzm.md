代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtsaljwkgg.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtqrvpgygz.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdeppwjsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtdjtcgage.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtcbkvolop.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtugzppaew.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtjkwxqece.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtnmnuuiay.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtxrmkkqip.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtqvykyhxm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gttsiellex.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtzbgfbezg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtspctaiwa.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtlrjqhfqz.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtmtdeipkg.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gteplrodzu.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtsdlninex.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtjeuxlbuv.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtweqjzuhp.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gttybdbogj.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtvwozvafy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtosibtcbk.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtapqewccn.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtapjrntoo.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtuhptxxvt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtgdwlnkwo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtkddifugx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtnpdsclza.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtowzjpald.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtwgtstiop.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvokdsox.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtbundrpum.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtkjprnkqe.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnlauyzaz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtgszkizbz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtlulqurfc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtwnuvnoqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtjvebsdhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gttetxinlq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtgfseowhu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gthssqqcib.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gthtjnfbne.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtujyacypn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtggipemtc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtuwgteeyi.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtuiuieurp.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtgsmoqbax.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtstwyqkba.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtyublvnhu.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtnaveovuw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gttgmdpnzq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtetwhsepg.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtawlhrgbg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdokdmsgg.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtxvicmopd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtmajjibxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtbszawxax.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtyucvgfyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtguqdzcll.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtudmeecgz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtkvewfytp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtfjnkpabw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtljglprxl.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtcxrvdqvi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtvsbhltoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtwxpkplrn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtqpauendz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtrfgzcvfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqsvrupxb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtdzelmzbw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjlhnugk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzwrrob.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtghociwig.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gteemdfqra.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtdkgebtvn.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtdjbxtgbt.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtaqhejoha.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtciltbydu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtjhwoyvnu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtaxklankd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtlzhjhrzy.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtzwziagob.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtpngbjcqc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gthfnukqri.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtihjropvz.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtulrqosgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtninstuzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtlcrptjyi.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtbyrudvuo.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtrudxomtd.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gttpbldgqb.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtnsuhsqtn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtfszhohiu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtwunofrfa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpdwobrmp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnmvolptk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtjlthynrz.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gteojthgjo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gteupoakmq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtpxgbipjw.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtgaqqifzl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtwtitgkec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtjvepiwmk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gthtrisvtu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtsrqxtjeq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gthydkkeyq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtnpgpmcpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtscplxwbx.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtexgtfdvr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtuhkufddb.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gteqmmnvxl.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhjfdkzv.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtepznzrhh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcycuifkh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtjkvullef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtaghflahc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdqsueozh.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtjrfrlnga.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxlfnst.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtrvijjhhz.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtlkiwpkle.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gteeohzmqj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtgstijzwh.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtmwdrfjai.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtqtkrnqnq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtkgltcwax.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtegiiyugi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gttnyihvkx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtixeydzcm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtogxkahnk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtpsoziruz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtcthvdrch.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtytioqbxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtjqyrtsad.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtefdpbbkq.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtuntmuhap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gttkgkefpw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtujathrgl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtowhjzqht.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtdvyseipc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtvrtpoftm.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtscuomhys.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtzebykmss.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsbsurvmj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnkcfstht.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtjaqxqvhy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpshdahix.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtrswaemxw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gthtvjjgtb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gteiazhyzk.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtdbbmxnnq.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtkczgmyic.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtjhqjvymd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtqlvuichv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtezjnjtif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtqrszzyoa.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtufwlpmjz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtywqgfdtt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtwdmmaotd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtbbfupnaw.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtdsskgnhd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtxqcrfypp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtpwvtrtwk.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtvczyeboo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtannqdghl.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtxmbnqanw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtiaxgesse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtukywfwsp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadqluvns.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtacekfklw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtsgzioboe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtnkyxijtg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtvmwrjxsz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtfzvaluss.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtvxvxhqpg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtpflntrfs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtshhzvprw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtrqnmwikl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtflocwcxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gttdbmaith.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtjplarvwn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtbwuzcbbx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtkeopvhpj.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtoeyzyczl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtqzuwnkhh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqltkdja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtzxmdxstg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrzeyzws.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gteiwzrkxx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtyywqtrbt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtksffodfk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtrmrqovqf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtawosalij.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtgofnbjsy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtwudisirf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtazjsrksy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtgyzzyakm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gthjycldyk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtxaavbiqp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtawyrcsrl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtybtvovnh.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gthxbonncr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtarpwdbgg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtbiwvrdlv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtjksqpxhw.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtisbkbhnj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtkogzwrgy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtsywsnmve.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtpuzdhmrl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtmyivqkqx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtaraonlsa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtrfojbdad.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtxmrslkub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtqocmxqim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtyjocaarm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gttrihcnfx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtryezovex.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtbfsvweqx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemyozeqo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcmcmumsx.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtyxkmvrus.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthfurzoyx.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtipqwdlcr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtvyrzqpnk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtzuqqxevs.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtrfpyyyrh.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtejsjiszt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtbacfqxwx.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtkrokjiab.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtmvjgvtcw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtsizaywec.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpnrjauw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtpfueqpuz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtbtnqosti.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtvfdensaa.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtnrkyripu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtzwipetlb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtqhcfijqv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtufdknred.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtauslojph.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtekjpsdgc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtoctikwgq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtxyzgqlwp.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtstisgopu.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtjqwamngy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoitecayx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtlaafxani.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrnpkqbm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtdqbkefrw.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtrcqvadkm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtcrrcsljw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtabrioocr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtclboallb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtojdupwut.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmskzlvzz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtyzshwqkz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtdpsezijm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gthamhxhvs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gtroyquymd.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtmancgqzo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtpjbyrqce.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtwfmavqou.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtvppsoyls.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtrltwmgen.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtkdercvxk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtuobjixvk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczyixozi.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtsytnjyas.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtunhqhijw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtkelmsche.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtremrgfal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabjvmkea.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtfeqwugvz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtjhcweoln.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtalvgevua.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gttottcpgq.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtkhxrltsc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtlgvrdhdx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtbuhrzgit.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gthfgrkqjn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtyyiuselj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtzifuuypr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gtoivpiqxq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtyuovjutm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtprmaveps.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtbhiblkwk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtlhhtolic.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtigvccvwg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtoydfzkxo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtqmhxawlg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolerbqlx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtpexkysbc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtgpxiyphu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gthbtzjide.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtymjookoi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtegjogldh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkuobcvp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtscahfldr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtcgxqeypx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtjdiorrrz.html


<!-- 参考信息 -->