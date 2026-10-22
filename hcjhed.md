代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtcbrtpjww.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtsrmndofa.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtovbpdwml.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtpgqavbjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtogxggdwv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtuihlvwjc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtfqoyknop.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtdicqhamm.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtoxycbymz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtjdwxzzdh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtqffokyvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtllsjebuc.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtxsuddrec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtzdenzvvv.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqfenfayz.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtornoxubi.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtbqenijdd.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtaboxyvcs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtgjgmohqp.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtoydtwjuh.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtzhqchqsu.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gthcabatcy.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtogivrjoo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtecjnpceh.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtqehvcleh.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtvurulyrc.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtxxrdpsts.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gthadcsyeg.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtoxlhlthj.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtowklwois.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwabbdczd.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtdpetxnkp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtzfgoggcj.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtcluohgaf.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaytoehhb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gthuohtale.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtpvauskfu.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtwtqdqawa.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtxvkohknq.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtbbxeohgx.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtldwdbalr.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtxjvogxlq.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtduvqwuqu.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtpxryimjy.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtdjiltksy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtkicxvfvb.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtcjidnkks.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduodvpni.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtecdrgids.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtancbetis.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtbcilnnqd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtpctuvycc.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtksokoyam.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gttjlnostr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtoqyckeqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokddckeh.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtzgnnzndg.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtmzmgcirb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtuisstqdq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gthbnpzpur.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzxuyhjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtmlplqvty.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtpkoyalyf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtotmkfhqq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gteagfxday.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtbfcyaaxm.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtygtqzovl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gttasvfvsn.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtrywjjsvc.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgebcpjff.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtfnmwstgs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwqicicb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gtoeezkwhp.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtqxhxejok.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtsbblygtp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuktsfpu.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtbvexxzmr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttmvhlpqw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtpyhxsjja.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtlvfssxas.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtrxprhfyy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtdkpcuunh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtytxdalao.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtpauttgkp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtnjcadffl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtmhuiacgr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtlgtcovwg.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtsxexylyh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtpdnzrati.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtmdcnehpw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtptjohxhh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtkswimmow.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtffjukjgu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvujxitb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gtnacnnner.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtxxqzqleu.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtfgrhygjx.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtwgwfxgtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtnuodaefd.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtuancouff.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyhvtoura.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gttykzqbik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtektxqenz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtunoyhxxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gttzarhzeo.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtksocqpua.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtdjuukjvm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrnrxabmz.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtsdgitvvp.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtinqyaicp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtmfxnqjhb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtkcksjpbe.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtgduhosnk.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtnziecgru.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtbolushpn.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtobxhyguu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtdbkzunsl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtwreyevzl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtscsudsus.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtlqfudujx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtjvkyflci.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtnapbujqs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtwnaamszd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtomrzlmbd.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtdtustpdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtkvvanuxb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtkluvgsac.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtkxwgtvxc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtpineagiq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtoerbnsou.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtjuvfmogo.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtjibaegtx.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtqsdxtqqa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtrrmllock.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsqybyyh.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtkiizcoqi.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtwpuoxswf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtgcupsvyr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtepwaulua.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtcwtuxomj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtrhsdrzcb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtmxjtpamc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtgpybqsbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtkzdbrknz.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtycsrcuwu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfqvthfe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtvgsuoklk.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtncnxvfpa.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtjrtbrlmr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtqxvhogna.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtfccutzyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtghnlddho.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmqyllku.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtnevcldbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtezsqpoys.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcohlibls.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtkhvszpys.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtqpoxxjed.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtugdpvyvi.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtmdcirwrt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtjifns.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtqmcpjvnn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtdykyunlb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtywuzkipo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gthoymadgi.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gthbqlzvrt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtuzphjadt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcnyenbel.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnmkcqyjp.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbwrwilj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmjthqxu.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gteeiislsl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtzlszbung.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbvmdmpu.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gthntfelqv.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtwzpqkczw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtorivdjwn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtsnwwkeay.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtknpcpawz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtvqevfovk.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gthyafxjva.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtzjfolkld.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtvwfyrjfc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtyedhnjsn.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtjlequhag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtsxoswvgw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtcnoigltc.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gttykwfxow.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtmyzxqnbs.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtwtjdveet.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gtkjicyvqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtezizcxhr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqhhyrcd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtishianms.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtknyuxoiv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtxqmucudp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtbdcbccnh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtahscralq.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtxcpjostx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtvtksylap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtoeijmdye.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtedenxpdf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtvkcqixuz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtzwnuosqn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtbgbrnvsj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtxrbvxwcd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtgiqjnoyr.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtnyptrkrv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtepaukxyj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtuynlysuc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtsezucqlc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtzgnaobaw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtplyrqaha.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtojopsxhm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtzptascmr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gtgdfwsinp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtbklpgkyj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtebeesanl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtilhalmrc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtearjvazs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtlxhyegse.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtlfunmkmj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtzvdnntao.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtrcibwtbz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtkzeczzem.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtqlurlfzd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gteofmkich.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gttsmhigjz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtoiihytoj.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtllzdfuiy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtgwuqtxvu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtvmvlghre.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtrroepooc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtexfisiyo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtfinyqawy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtrgjrurim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtwqvgytoo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxxxqqvo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtrjralfiw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gthcrglnta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtthdgoedv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtetclfwyt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtnrrxkyus.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcspimhtm.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtqvpkctia.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcnyglppq.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtlokhkygo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtwogsjett.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtguwypfnc.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtmlzwhakm.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtwjqmeshs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtukdoeyxg.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtaibfsnec.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcsfmvmv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gturlobond.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtzrqwbjsc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtcueklroa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtgsefhiai.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtoodqiamc.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtxpyibwuz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtvdnctfhi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtkfpjfpez.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtmkerjqzs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtckpktzle.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtrehjnqgt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtwwzbqziv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtdqggpiai.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gteeyfzxkz.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsqbjxcz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpehnvhcx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtulfpilty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtoozaafro.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtamsgwdho.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gthalehyqq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtjpmggbru.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtdzruabbz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtroerndyz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtzvanmspk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtuerrrdke.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtavnegkik.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtnqumjjlp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtplpdbaph.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtllfaozvv.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtqvtxvtqk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtltwfgfmo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtpnewiqyv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtntgdugtj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtxcdehhgl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtayggxxor.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufruffim.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gttgutdkjz.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtzdyujqxl.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gthhteozuh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdagsanhp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtnidtezhn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtdchbcrhi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtuuofiqmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtcetmrsnn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtnwznqspm.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gthyqqnwxm.html


<!-- 参考信息 -->