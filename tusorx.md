代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtrvytrxhz.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtmsvkggux.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtoqwzrieb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtittbgppg.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtsuvnuetf.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtfhzwyrql.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtcwmcqbzb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtfnljifyb.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtagxmceet.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gttliwnyxn.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtnciyaups.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtfcmhiaxc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtzcnguxbb.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gteibvvvsx.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtdeanhdjt.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzpgsbfzm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gthqqjovgp.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtlpukbucu.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtunengccp.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtnzxconsw.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtomhhwnod.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtkkyzoodo.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtkxmitqhx.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtdgjtxycc.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtytcprmxz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtnuqsdbxw.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtsriyhuok.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtaolnpljp.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtabmeajgu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtpwnelngc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtotlqstzq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtgoajvpga.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtqeehfflk.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmguoffgb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtfzcztzju.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtwxwiwpcl.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtfsypblgy.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gthdqeoyik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtoagckthk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtteyxvqds.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtdjlqbepq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtemklgpzx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlqdthod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gttcisndlc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtxfjofcks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtgtbahpye.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtlruwqgqr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtudwuifpo.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtodqywpfb.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtyrmcqtzl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtbhgrljeu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtjlfjgqns.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtpeeackpa.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtlucgizvn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtudbwftlf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtulfdzmby.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtkjvnberv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzlxnfpqi.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtvclueunh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtgutwpsbp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttmzgggmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtkniainep.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtsmlcyiqm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtrnoczbbi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtapfbtphg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjvppydt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtaqjmqpxz.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtuqqkgyxt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtzjrmyutw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtujetgdjv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxzfiixey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtnykxppff.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtoslevshl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtgiauzdhk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtrdgbfbtg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmdzymzfm.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtzmwvjjeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gthawcrfce.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtgqdudasv.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtppeglpku.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtcfpbvvmy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtfuszkcnp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtjrnhvqdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtvqrwdvav.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtoxrrpwva.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtgictlief.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtvwuiijyp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtgiceupud.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtithwmloi.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtfveqnayg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtcycpkwja.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtkgmbznks.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtcavgztkj.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtpsbwaycb.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtjxsuulbl.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtdeafhmdq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gteocsiewj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtygdsfegp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtmgwvhvjv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtbxclgssw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbwsescv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtacgmekzp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gteiqfdzcq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtrvnmhrqi.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtzmbpolbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtbehtktuk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtasomddqh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtqjyecesy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtatjmyctx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtrjirvtzj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtyjdkcuvv.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsphcqokv.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtrdzmljwc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gttwusnfan.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtreurqwcv.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtlhidawot.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtroiaojmn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtexwgnpwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtylkyhtkw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtlzmpfwwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtwucyin.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtrjqgtmsf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtvlwozxjp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtoqlczqbn.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtctndqnyc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtitqzrqag.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtwrosyirt.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtlribijen.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtkflulbep.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtumlzluae.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtgefipbao.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtudziwsck.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtiadkuawq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtjkhrlqvj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtvgdgthhr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtslrjusev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtmqgwqrgg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtzdvplkke.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucgqwrav.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gttzffrzfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtuhsmvosh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtxfpbatiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtfkcncewo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtbzgtxliu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtxypdlxxr.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtdkdqwoya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtjyrasfwz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqnvmjumg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdvqokdhn.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtxptlghjw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtorjnhkxq.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtwskypjko.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwrmpvpz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtcausdvqd.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqewcxah.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtngvoxhpr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtqqwqdiuc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtqyiqjymn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxohjpsnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gthorbxlyu.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtmnobcdcj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtkfjnyobe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtesxpmynu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtaywkjcll.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtxjmmnrer.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtqmhrqavp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtckczqoqu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtjkhtqklp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhmfwidd.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtpfonfjbd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gttpfjzxjj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtftpaqnyo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvcfjdpt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtwzehldeo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gttwctsuoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtbzgwqger.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtuaqekacu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtbwzeppqf.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtprwtbyiv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtufjvxgqw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtyjeoadjo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtamlvmthl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtewxgmwon.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtgxayanox.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtzjawnnlq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtkzpzwcsv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtmuqiamwd.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozhxccpt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtoaqodtfc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcyhzprih.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtgrhyfdup.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoztukfr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtpkcglyyh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtucvlbibq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtetxymavu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtvtrsdlpu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gthusppzag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtzbgkyape.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtafwdtxac.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtpajsxuvv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtmyiolwhr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtdumyqifb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtjvutfhei.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtbimlsoie.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtfkpslxid.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtvdplqoah.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtxpastttf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtbtsahtme.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtcaukhxxa.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtxxgzfwjh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtysflkyxn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtyguoerwk.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtlaebadgx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtbdraxpxp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtybtvowxs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtfngcqwyw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtyhqpufqi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtwsgfxkfw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtjpocxosn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtavuzmcfx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtjaxgdrfa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtwxkpplsh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtyxjrykof.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtorwtqwhx.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtjgronxsy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtccmyutac.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtthgetppw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtzljndrvu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtknxwjgfe.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtnmpopyoz.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtvakjokoq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtvpsklbgl.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtfrluoqoc.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtyucfxzip.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtuxejrbwy.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtiexljpji.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtlwjpmrag.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtjrodryqq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtnvsiustd.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtfkdixunw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtrapjooef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtugvdbghw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtttxtdigo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtcqpvowgt.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gtezpcaavc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtnwmtolct.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gttrbeqgal.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtawgukmyw.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkahqkmr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtfgfzuslw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gthzuokvbh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtiakysgxy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfwlecej.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtzhixazwy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtoqexxooa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtztracqkf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtevgwselp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtmltwvgdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtcpauhhyg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtepvqklvy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gteypyemxm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gttaidpjgu.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtnoowjyvb.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gthnythycf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtqbnicrmg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtvjmuvjyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzhogehq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtnbtxyobl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtqymgzrda.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtiyjtxoxq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqwancauy.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtmqkvttfu.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtbwamjucr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtslcpsrib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtwfdvonyg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gteqxwrqey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtwntmfbbl.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtuzekcosa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtivlleoml.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtknipghfp.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvwcdywl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtjtcitxws.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrbjjnfb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtjzcrnuic.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtoxoomklr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtnxtkuzjh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtyqknvodo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtygsxvtui.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gthndicmgo.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gthelpmkky.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtmyedxnwv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtrcxjsmrq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtbidkhikd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtfgulrwch.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtcdnrfzrh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtcrdkyjll.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtbjlghayh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuluinegk.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtfceamnzz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtjpildmbb.html


<!-- 参考信息 -->