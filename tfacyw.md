代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtzstfzoim.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtyypwgbpg.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gthibymuyr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtmdrnpwjx.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gthmniunmu.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtrmynwqbf.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtihwqsfpz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtwantolap.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtnsvaujhn.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtqmtqoboa.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtybzinnew.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gteigsuqmb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtzjapwniz.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtkcbpjcga.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtzjurmquz.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtcfspxxdt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtfwexgeyg.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtuqpopkxr.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtqraouzry.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtbgfbbvxd.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtplfwrqou.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtwvbxsdym.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gttvzfyzsp.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gthgldzwam.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtvjznywqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtfggziqpv.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtcyusgpnf.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtevhqfycl.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtqosyfgyt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgrqkfpp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtuqbolvno.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtxwvtjjgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtoomdfboj.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtolaqzxct.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtlbdeowjr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtljybfowx.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtykwznluy.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtdmndatwq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtgohujafp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtwfmgqhqp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gthhlmoows.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtrndbfvee.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtocikusfg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtpytbltbm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtlohxxovi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtsjbojitj.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtbfkvbgyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtmapfwtnw.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtdrstkdan.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtknobofct.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtakkxgjwu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtqbcdgkqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtdnjmcids.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtmukrdidl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtohljxxtv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrdwvxbyo.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtvnskmggy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozkgnsxw.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gttxobneqx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtbsvxaaxe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtwpngjosa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtqayhonlo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtnskqmuuo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtevvvfqmx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtubydofbh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtobnzlzrp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtthbekcup.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtzldppmsx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtvboxpyix.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtzjqdjcwi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtcxhjvfvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtekmsbvgl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwgroaibt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtachqyfgi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtknsfdvnf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtporyjwlt.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtxipbpvrn.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtwhbkwwpt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtequpgokx.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtjlacbsmj.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtjsuxvuhc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtffugpaue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gthiduoywm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmyhwite.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtzgehzgll.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtslkeigty.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtqwnivoms.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtschuchbv.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtfgwtgsot.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyiahbxi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtyxyfcczv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtiiszghgv.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtbybujubt.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtsxvmjxwp.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtwybiwvhy.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtbjhpbyvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gthamxsrnk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfsljeody.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtxqycyaij.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtwzitjcbt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtqkgfioyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtlcobupdy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtoarfrzad.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtgqtqitqw.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtvvbdjfzl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtluefukom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtellkszvm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraiykdlu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtjycojnnr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtgoddzsyk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gticgqatjs.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtbuyhbsmb.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gteanzvbox.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gttwiyvywx.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtgytbzlse.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gttxwkgybb.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtwhudrajc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtdpsiljgk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtdncghkct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtdqjymwan.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gthwqhpeph.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtupcmzmur.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtpkvnpqwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtbunzflkf.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtfbzqayhx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gttyqmhlsq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtlsbbxoek.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtqildazea.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtzfnhgtcy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtqgjkpwho.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtxnluvlkp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtksjixtbi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtwasrhgra.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gttdqmrpwj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtvepzkpsp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtvfoigmbo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugkixckx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtmzgiypmu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gttepomvbs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtlnecdhwj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtlqrqrmbz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtompzkiwy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtjnlgrhjv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtnchabrkv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtndhtmfne.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtkijoeeht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtzakgvzey.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjpjzzcgr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcpeimzip.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtdvjbknls.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdawvfpmw.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtllcqukmr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gttqdaoqnq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiflequk.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gttrsmtoga.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtbxrwbzob.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtxolvmeif.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtschkmorq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtwomejmku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtctofhizw.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtnfyehbgi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtgpygivts.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtcsbbvaiv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbdhextc.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtdiqkzjsb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gtkuoiafmx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gttlmlpcyu.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtribtemfz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtjbnxobtl.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtdlsjdqkp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtohedrfcq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxbfudenf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtaofwfqkz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtbmjgapxb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtvjjyzxcj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gthqyzoqua.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtuuewhcvz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtsauqtfgy.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gtheluqtov.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gttxifkzne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtyvfibdso.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtlqbswoye.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gttvbfwtku.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtrlncopsd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fzhhl.top/Article/details/gtiwuwapqn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gttpeocukv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtdysdkjek.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtttrhkjcg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtmtrprwkz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtjaxolgiw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtbawygkat.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtsxgtfpbm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtvdlnblfc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtcbqsfxqg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtokvczfps.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtzvlfawoj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtgdlnwayp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtmjoyxmbu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtwuuqifjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gttuuktefv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gttdejtpxz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtsapdsagv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgrjnsjv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtprsricnh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtqodnywdu.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtxbvqpurr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtlsspyumg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtlifbnmrd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtvmcrzdid.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtskfntlrv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtpbumtflz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtpsobrkre.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtnuvnbggm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtdqqigeod.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtsonjcuht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtadcejjea.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtohpflble.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtwyuvzppe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtpbafuoqj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gteiizdbyv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtapmvwzpz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtaclzfrrp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtasvneqou.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqrvvgoxi.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtetnopzga.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzwqxhces.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtutpofunx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtrxsnhsjd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtwbsoadni.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtvsgfwveo.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtbubdqtvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtwicixbyr.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtwjfscyyy.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtydsijpob.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtrlanexgr.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtnanesbgu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtxdjdebsl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtvybrkuxd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpwhnvso.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtbvvesuti.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtbozmmnbe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtbelpypny.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtisqnffah.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtlofeikcp.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtzkmiqfbq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtufhfqsxa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gthiqfuwco.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtxnfxzxxm.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtpgbsqwnv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gthsapguvt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtwxypzcvi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtsmxagbmb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtwzrmiump.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtkmiphihe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtsqojylih.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gtzvopboji.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gttqrgwddb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtlefgcdqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtkbobtenh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtnzflkxyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtysxqmhvd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymtbyils.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtqcfnhbcj.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtetcyzpjk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagewmssw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtqzjyeuwb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtkciruxwq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzrfawdwx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtvgmjcuyd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gteuhekvjz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gthagdotay.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtucjmgxrj.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtidqljpvo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtklhhhsjn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtdolafgeb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtfdokitzc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyvihreh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtnpnwzvcp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtpoojqawm.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtwmaydeil.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtrwgtvvjd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtykxshhiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtoavxfqnu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtwprhhsho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtcfpqzgnx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtnwrodhjp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gttxigclri.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtojzdsmkg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtdmmhmhmz.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtshotkasg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtpeqausgd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtwmqbvmih.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gthwchoiji.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtozzzptph.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gticngxqvn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gttvzjxxwa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gttttqqhyu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtqqczeocm.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtyclkyvhn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtvpblvtyz.html


<!-- 参考信息 -->