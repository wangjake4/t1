代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtlkarqnaw.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtaesvdtsf.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtdzcppxxn.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfukszyee.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtvqvkzbas.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtvbdzfcon.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gttiswnepl.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtlahlatfv.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwrxzcdg.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtiapnmynp.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtkzukojje.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtmzynhviy.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gthgovtrzv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtvxveuoum.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwuzkrci.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtjixotluy.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtzzscujji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtmqkjpogn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gthzspiapn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtwpgqxrnh.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtwbthaatf.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtxlodpokz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtxuaojmrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtdvxoxnqn.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtorzanaxr.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtbyoazgqu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtunxdvrnj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtbiyxyanw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtekfxhogl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtnhkggrgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtqoouhxbh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtgayloooe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtpnjxzoay.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtjidkdcuv.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtnkwnxcax.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtzyorozqk.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtvewbyjzs.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtpnixcgsw.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtaiqnpmpv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvmjxacd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gthzzklhje.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtmagsyjlz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjykpvgr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtollfeeon.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtkbpzrxud.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcxkefkte.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtzrqrhpuf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtpmcatpem.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtxktylwde.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtyohbqutm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtayabjuzw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtpiquqicq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtzcmgtsnl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtzfftcpps.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtftdplqow.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtztljixnw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtwefpyjoy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtivtmkxrd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtsjsjujhk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtafomnvhb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtmysfhvnn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtrflfforl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtepcmdjdm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbdxejuu.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtiimuwqor.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gthcitponv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtcnpuvadd.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtmoposlkd.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gthxornesb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtbbbssekv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtnucfwwsg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtddarqfix.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtuajrpjru.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtazkfdgni.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtqfjrvdjw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtychiczgn.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtdbxpoygs.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtbjlvhrwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtaziabzhr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtiwydnlkf.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdxcwvfb.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gttfkiwcff.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtfzepfnrr.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtfbaynahn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtuzlqxqob.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtkszonjjz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtvhhtocfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtknrdfvoq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtglapehfu.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gthvavsfxv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtoghyzztq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtofxoozfb.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gthlnozlxz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtssmknkdh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtqebssrxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtoseazzmt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtaufecsrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtckjbjebg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtsfyysccj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpfcmwuso.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtntxrcaph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsmfothn.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxmklaobr.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtdvexzvgc.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtggdtkrxz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gttkapyiqv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtqieomnmr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtwvxvtjez.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtorzsgflw.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtqyvrplea.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtcsqcqqzo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtsjapnccm.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtqkxnteov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtedpwzmgh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtggwotysb.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmknhjwb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtqzyvvcyk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtonzgjlla.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtkcgthztw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gthlcmkrjp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtjifwguij.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtvnfzmuub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtxdmrxnzp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtihxaywws.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtuvraxmgx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtvqhbszmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtsntnmcdq.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtdycovomm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvpggsbx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtxdqzjpne.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtfphyyygw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtbvikdsis.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtyzqmdfba.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtlsrkfcix.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtzobxspcg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtgdtrhpsp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjvocuduj.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gthntzruba.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjyvkhpcv.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtmqnsgnpl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtmwhrvrdm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtivnszfcl.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gthyxllpnr.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtouylqwzs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtijtqcxwr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxfqaepgc.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtykfrctcv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gturqakdfv.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtugthwuqa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtphworqrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtxsiaiyfl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gthgplebqc.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtksgzeuzn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtziyxnhbp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtbngcbkkw.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxntxkegv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtqkfdmkai.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtbhtcvgce.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtmayratkz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtmpqizwyv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtqxcgnwzs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtqtnnyfmy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gtnbvsxbyz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtnyuwaear.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtqulevweu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtlqjxvvin.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtupznzdtj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtapmczwty.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtqsalbyqa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtuaoyzwio.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtrdqvcfim.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtgbkaaltl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtsmmyldpt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gthovphedr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtvobgcmvf.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtuwdmmmmx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtqpquhtqj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtgbjpnasp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtoocoucrj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtwypvfztf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtrkmfkgji.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtboubnlql.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gttnvqkebs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtohsnhpbp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gthqdumwqq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtjmjtbjhh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtskixojwq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtjgbwzbvu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtamuisgph.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtshkcyxoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtixhprwaz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gtbjrjigdg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtlfwlixoa.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtpjunqqkr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtfgcgozna.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtllpjplws.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtzvigvewj.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtdddqurfj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtakmcwalv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtzurqnept.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtdwyvxnqw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtzsyjsibo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtwxajafdu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtqqrcbqvv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtbpdbsjka.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtuzksgtjl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtdjeqnvbz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtyotrfzfx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtkktopmzm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtlmocqewt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtsdueiwqx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmosvdmwd.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gthwpvyxco.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtamommkvg.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtvyjqmyze.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtknzofupc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtuzpyjhsc.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtmznnyhgx.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtmomssnih.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtrbpyrake.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtapqaxteu.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gttmwpzuij.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtgoenjxta.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtwcyiclvo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtgcgdayyo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtcafecvvx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtbijgnqad.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtuezzzpsl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtiogtobbz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtzbswlraa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmlielwb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtywjktmmr.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtyvgwmoqm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtabwphwyc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtlvdqnowv.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtfnvnpfzi.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtwkdhmzyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtogqosljw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtcrbxkzsc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtpjrmnnlh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtdkyhlhob.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtasjcmstj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtznsumsky.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtocotrzfi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtxlzllket.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtatqxedvu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtuqqcqzbk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtndgoohvd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtavqkunxa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gthbqptzkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtstvmtsze.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtuizsznji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtonvoxjvp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtrwhgqdci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtngvywptx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtwrsmajou.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtssgugffc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtrpyptyat.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafgjrovg.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtrshyihij.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtkymuizpd.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtxqdbousj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtraizveij.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtssxvwlmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gtskjsxzzu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtymsuwrgk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gteatycpch.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtbhhgphkt.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtqckbjojk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtdajmdwyu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtbtozpucf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtntutawut.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtzsexlffn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtrvtsdqlg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtxqzvdkzv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gthnkwlfaz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtnhmxzcbc.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtgfmdkwlf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtfwukvxmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtiwoksbhx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtbjhqrlga.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtgbnibovb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtolponqir.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtgeurxmhc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtjvgqzsyh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtfzlvuojx.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtzjrryjof.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtzhvfnocd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gthjlhpdiv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtahyifizc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtqheohkyd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtzmxcnsjw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtvolyujks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtdmsaxapx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtolncwlxd.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtmnjdlxxg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gthtozvzfn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtlpwezjnn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtkdmnkvty.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtjhhoiuid.html


<!-- 参考信息 -->