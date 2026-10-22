代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvcxdqna.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtqdeylyjn.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtsptrndhz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtkymssjvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtkvddvfkx.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtixzyeymd.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtpbfupnzf.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjbypybb.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclghmnnx.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtjrlnfipf.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtllfydsfd.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtgdakgaot.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtpzoemsrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtbgcnvwvf.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtiluphfgp.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtvjsgiejs.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtgrwkjkxi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtieoadalp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtfgqtuqas.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtuqgkgtif.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtctpcieiu.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtthwceaum.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtwqswtlpq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtvihrfzqb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtffvksnah.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtepnqqdpw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtgzkmvegr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtbpvbddli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtslkisvsw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtpxkhssxr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtdfsfyrjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtxufwxodw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtztabrvvf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtnigbflaq.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gtfmrudkax.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtrisnmcxu.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtmjpwyuln.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtephanlgo.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtcjjjzkix.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtoeeiezgi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtqhcqnurd.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrdhuhtm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtcnazonxz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvfavvipu.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtxautyqze.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcfsqphck.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtlwywzfom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtjblsydll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtxasmgsdr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtpylbxltt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtocppkzdd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtxwjjaymy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdauhczep.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtxbilejvm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtxvhkocaa.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtnpgshaws.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gthfapkxox.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmmeonhrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyroiotcf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtwhwtifwr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtyevjyfge.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtuqjgwajx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtizdnfxlr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gthqzieolf.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtndyolsam.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtdsrsutns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtamjfccfr.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtpytvpnak.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtrfzupfuu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtvqtrpzmp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtpvjtamgz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtzktilusn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthuokidka.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtiytvviqu.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtaiyxncbh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtwtforryl.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtiltoitlz.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtuhsumlxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtlhqjjcjv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtclouackd.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrqyexxws.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtjinsljxz.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtheqqqqgc.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtbclygbty.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtcmflvtyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gthftoyggu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtsoaomxcx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtrjfmdgop.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtoderyels.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtndnutqyd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtfdssgtkj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtftocvkbm.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtatwpuegn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gttuuzbxmr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpqnkrqxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtngsumoqg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtlfiqitat.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtuaqugxzl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtkomfiebs.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtezzqleeu.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfhzdabz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtvrcvvkdc.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtsqdegbug.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuzhokkl.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gthzafqnci.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtgjhdofpp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtufpuqvmp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtxgcdzctq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtmqeuwjmy.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtnqvxrhnd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtjqmqbpyf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtgywcdhcd.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtsamsysun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntfxyzle.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtjkewotyi.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gtfcwhdvzg.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtoddpxuhn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtqfkilvms.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtglbiokcn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtgpvcfvok.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtdioxmtdy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtobpljlpn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtwbllhemp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtyixqcqeg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtwgnucbff.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtqqwoxtll.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtrgxmlbat.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gttboxxrhv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtjhqxktiw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtqanepkxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtiobnggve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtelrrnwio.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtpeacpwcl.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtigsmwdfn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtrpgthdps.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtuddquosv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaytdjqly.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtyxjrkbdk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsodzplkx.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gthykvszpv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtcthcuako.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtajpbdxan.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrytkzol.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gttyvtviqs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtkresnphd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwmpryjfw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtkzxezimo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtncunvgkt.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtzslwewwd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtaxbxstso.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtwfvwhwxg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtjbaefhow.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtgpwzzlwv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtdkpdtdsn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtmggttniz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtjfddxbdz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtugowdrgl.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtbydrxsai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtnhsyjwzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtnnsrcrjw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtblieazxr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtjuvygfkp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtotvjkwyb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtraocimtq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtzchkvqez.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtfhgqgmmj.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtxmxwqyrg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtmyamfwph.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdskdopd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtxdutbvez.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtgaywptxt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtiqqjuyxy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtfhfugory.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtakjexdne.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtotodzsjw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtiflujzbt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtusrbpumq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtwnztsuul.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtyifvklqa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtcwlbtemq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtapvajozh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gthsouyurx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtquvwwshi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtijqjxtik.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtzvhmnpxc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gthfodinez.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtmxesvsda.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtsewdxvxx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtwbxkqmvn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtuhklqmej.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtgmoivqtx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gthxqjupop.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtljvzhyva.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gthcguoyrd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gttvrmsesc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtiwwaztvx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtbglfddvt.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmdjrfbd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtrnrmilye.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gthgmsnrsr.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtnnedpabd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtclrmankj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtgjowxrur.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtjsadjorn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtnemaeknw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtkewuwqlt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtienxlvfq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtjexvaneb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtykuowcub.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtqyovrrsz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gteqjcttzh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcfzzzhb.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtkqcigsag.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdtjxtuqz.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtpxidszix.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtrshibagh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtmvnpflta.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtyenxfsma.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtstcgphid.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtcdvnnuey.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjinxgtjw.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtjaxprvow.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtjcoidtwp.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtljplegwc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtfermiljp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtruxbbpml.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtifjcyecm.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtvreaqdqa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtekiuqntf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtpfmpznwj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gthkrfjzth.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gttkdxqkqi.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gteyiaysvl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gttrtwamhv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtzvrrfvbi.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtobhlbinc.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtqovjlwen.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtqduavfmi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtcpczjebs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtupiixukx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkapeprw.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtocnclkzq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtruitgdvf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtywnlcpij.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtrylcfwpz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtrjpbqbku.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtofkpgdqb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtgjedikqu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtdjvcqjpx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtjbahsazm.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknlmuitx.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtcbhdopht.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtjorhabls.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtgidswrma.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtdvaqoxmj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtylgpcipv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtsmgxsgyz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtzytwzxbg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtokxgwfsg.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtioqczjfn.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtsehgtcyo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gtoqjkhoxv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtsohlmnjd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gthucnqnbd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzusafpuy.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtykdqkxcg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtriznxplw.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtyabdmmrl.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtydeeetil.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtmdfrfoec.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtrwhezbam.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtevsywhrk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtficuicib.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtinvjolkx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtjevokpoz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtzqlbndnr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtznxrkbfb.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtiwpsruvx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtbxfsuhdr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtosutfiow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtlksschiz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gttycrgite.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnmrcdku.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtltifufln.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtbbhahfga.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtbflkpfuq.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtdcjljvuv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtbwgtwqul.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtsmsupkcw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtepdboysj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gthoztqgbg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtxdmfshig.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtsviplggk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtvjftammd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gthrbllenz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtbvmjgrmo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtcbyelpsj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtwqpbjjdz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtrhytsskx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtiyfcnafb.html


<!-- 参考信息 -->