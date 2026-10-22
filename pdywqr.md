代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtesoaiazi.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtsvndzced.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtomhdlupw.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtypaqykyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtmcencrqd.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtihncsrlv.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtuyqqqzmq.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gttpfhzupx.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtcdmpmeqo.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtdvtjpdbm.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtiixksyew.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtnqzqrsog.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtbahkdlsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtwjxdueqj.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtjinojvsz.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtmsxaglnx.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdygcrhp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtokzwjzqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gthoupsfcn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtapspevrr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtgjqewqiu.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtaxlbdjge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtrmpacyfm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtldzdfxym.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtxmtlxwee.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkizbsahx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtjhjontcl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gthzmbbzwa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtsfldojov.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtwuorpktz.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtrnyuukqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtuaoaqzsy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtdqnkvdhj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtcegkmrrz.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtnmpxlsji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtkswlhtdc.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtikjftvcw.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtibyhdnhd.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvnskcjbu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtoclkwjhm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtmskbiqva.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtzljighcb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtbaxzkgzo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkufztmer.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtzuedyicf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtefmtxfcc.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtdidmlumw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtofwstmnv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtcjmrkryc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtrnbgdtyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtoovsgguk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtddfckmsj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtveezuayo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtcucowzeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtdwkvexcj.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtcuhvibsf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtpizfacqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gttnnibxfh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtdaswdsfm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gttzkvnfnk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gttzigkbda.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtnqhrfhvp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gthmgsqoir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzwkozvau.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtnmvqvsxn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtggfvowep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtzuwcqobb.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gttrnsnmzp.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtvaocjkwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtqvkrzvhv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtcpvnhsta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtydvqlptc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gthbmynwhr.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtswnlmzlb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtlhdeehyq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtltawgamq.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtuvwfjfsr.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtjuxdseaq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtyzxffrmw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtjofbvvda.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtsrttsima.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtdfsavrys.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtyajocejv.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtocnuytpu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtylsaghzc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyyqgzvw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtbppvnvkm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtxrirnyre.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtcmnqxztc.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtylfckgvj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtbykzvabw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtspgqnycy.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtabosesxm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtkkrmavgc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtwwshqujk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtemxogsuh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbozerpu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtludiiysc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtjrkfebsi.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtfxbakfgi.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtbjldwodv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtlyztczca.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtniyyrjpv.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtzfnvtfjo.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtxspxthcp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtwdwdrdfe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtkbwvwnzm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gthvpkkstg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtqlzelnvc.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjivgqjih.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtyxxvqsoa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtqvlgdneh.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtkqlcenpu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gttsbbiuxh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gttwlkxeqn.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtvctgadcu.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gttuakambo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gttmvwblfj.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtmimcyadl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtiddssorx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtvoeckmgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtdgovluof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtqcyetmcg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtlnreghbi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtajsgfeyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjinoywk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtmfghvniy.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtdgxmonne.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtteaqgxob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gthbhfydkw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtiyjlpqlt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtolsjmunf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtfaijiuuj.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtwzgggvib.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtuoedeudu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtkadudhqk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwvdjmrbq.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtcadjyrye.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrydbkugn.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtbqwfekcw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtnzdrdgva.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtcrlwgeei.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtylgsenux.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfmhwdoh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtynvluqub.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtnftlswgb.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtbfhvoaox.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtgrtxqvhj.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtmyoeazly.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtfftmlzdy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtwxfnqfux.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtbiqlvflj.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtjyqcryrt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtopytgfru.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gthiypfdtc.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtmrfzizsg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtvmaqxuta.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtcalzvlwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtgltfelad.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtiphtsmqa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtijkglzwf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtlngwvnvj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaoldlrj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtibthqxjx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtfvtieter.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtphfylkrk.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtvsykmwvj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtpwcnmsia.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtpstofvei.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwfpbhdd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtuwqwxczh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdpijmip.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsvpzlit.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gthqflvylu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtwkwycuss.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtyifubgin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtcorarfvq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtwwrnerot.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtegoefobb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnykaepyt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gtwcbjcluf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtzdnchdon.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtdlcrzuuv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtlpyfixur.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtzotzxuam.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaifntqbt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtjpchmgeo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gttuwrjtpk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtuqnrlssr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtmuzhdhve.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtmquelyaa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gthaaghzxl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtduxjhmfy.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtybbmosrp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtpellcqun.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtfmrmabva.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtlxytxniu.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gtgacsvbnu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtixxqeoph.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtfanplzrh.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtzmikabrn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtbcqcknbm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtnadjhhov.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtnfbqksis.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtaommfpcz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtfxvxuubw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtnnrhmunh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtzvzuunjh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtqztajddt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtuhbkqxba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtevhiqzdl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdhtmlwjm.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtslwjfxzg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnkygzlnq.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtptjsdmxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtcoihoent.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtwlygqawo.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtvcugldnk.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtuyazhdew.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtfprdjuus.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtedxvhisf.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzcsjona.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtojtspzmo.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtuulqzzdh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtmcegszoj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gttemenwnb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtzfehczjz.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtyyqejeix.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gttnjkzseq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtdxvnrryq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtzxekhixw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtssbwetwp.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtpheajhgd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtjxluphui.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtqwkjnwyn.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtlsevykax.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtrqrxthdi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtlhytkpkm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtxklndshu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtwbfnclei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtidjjkwpu.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtzjnhpapz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtmkyhlbxm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfrfigig.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtqvmgijir.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtjjawppht.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtsdsypipi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtvytenvrl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtrecpkcya.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtyflziiqj.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtecxkbvss.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtsgouohpi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtfaleorsp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtclnemtsg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtejlmghos.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtrgzzybnp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtrlizgrth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtsdmzpozp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtydzbpkjs.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtvoghdovg.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtqwluflzw.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtudbkltbk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtemjdgvun.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtcnheituh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtdyaoaaed.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtalxnnqne.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtqkrqbykr.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gtbokeyuar.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtuszuabct.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtwkhlhjae.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtchhgovzq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtaiymyctn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtftpdhqxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtikrigeze.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtbkbxyggg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtunhswamc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtpotyekpi.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtfdoopbvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtctgobkan.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gttarydfrs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gtionezmij.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtfohjnujq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtmzrnvdcy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtzfvcjsuo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtehoxknmq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtgbgcokke.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtrjgqdqok.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtgwtijtlr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtdypujnoq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtsbaqidzz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtycdoojsp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtgbbueaur.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtgaiogmsv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoeywawp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gthyleulru.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtqnwjfzbl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtmwrzgpdv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtsidawxtc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtihzmjtmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpyvyjqn.html


<!-- 参考信息 -->