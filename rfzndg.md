代发 wailian999

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtshoxrpkt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtrrzqcepb.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gttfsarbvh.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtfclmfppm.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqulfzcx.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtyyxyxvqi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gthcmoneyl.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtzbjmjqyv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtrmkhaidn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtketxsgov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtkxxxldnf.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtsktkigiy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gttbcbgpja.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtgtqggmlq.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtmrtrgqms.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtymyqoqdt.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtnxcmzaqr.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtnnezeisk.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtutzklktf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtbosspbdl.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtcradbkcj.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtddmsdsot.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtdsgnifyc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtcflctogn.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtrzadstfb.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtncsfkaes.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtkicrnqxq.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtftzebcsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtrgnisxuf.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtpmyrkjnu.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtfcbjvzqc.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtykkagjwf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtnqnvfueh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtikrmxnre.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtpdfyefwj.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtascngrfu.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtxfljzxpe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtkmcyvdwq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtvdvtigfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtqvaztqfi.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtmxewlzur.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoehrkrb.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtcawclizp.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtwvyibzit.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtzlpxbznm.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtqztdasae.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtzhfvpqsl.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtknquetjb.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gttgzcfmuy.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtbeqgublk.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtslqkqvyr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtojwnlxjk.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfrbuzqe.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtcemqbpfa.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpetevaea.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbndbyaa.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtijtmmirw.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtkquaueke.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gttlmveugx.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtlxpwldlz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoepqrlsn.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgnczdvoz.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgdgcmxqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdmatqucv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gthmygctso.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtqizxcfon.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucawbgzd.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtdckuikss.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtulqqtusw.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtpggfkdnn.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtawdhgiyr.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtuwgupxmh.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtevjdhksu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtwdzfolhg.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjjgqdzf.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtxzzpamdz.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtzxmhvsju.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtfsqzlcyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtwinfdscx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtvmomppan.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbqyrrsg.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtfwedyjxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtzvvflrvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtsogfxsme.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtnmdltdrc.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtwrujxxfy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtmufflsdg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gturbohnev.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtxwmcdfrf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtntzvolks.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtjvszovjb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtxaesyueq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtrcuyzbgw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtxelsqdvw.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtiimqxfzd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtvhpjoqep.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtkppcpdli.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtkmgjnbtv.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtwbuqfqbx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gttlrzsbwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtdcnlcweb.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtwtfzfqmy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtypqyjjti.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpzmvzhpr.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtkidbezua.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxuodlcpg.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtslhaunvl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtyyelkuam.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gttmjrzvbl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtftjvupci.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtnrgczlfz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtpfpeejlq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gtjfjtkvtt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtafgwaoer.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtixhfusra.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtrhjgdlgr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxucmtik.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtplzhsnin.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkgbhfwef.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtartlmixm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtesqaxfou.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngcahkmt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtncaxnxeo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtaovjpygd.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtgtwmcnml.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtaeblnfqw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtgmcszjkd.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqwyupvze.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtfbgqzoxz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtlngfiguo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtxeggjeot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gturogrqlp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtnqoxigbj.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtfnphxptd.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtpclstbsz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtahvukdmv.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtauruaueh.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtzjytvgxp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtloqjqztg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtmjxmcifv.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtjsptgwmn.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtdjnefasd.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtjernscst.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gttrwwkrln.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtuuwwcuib.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvbwsoepc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdxfpizvl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtfokafmzf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtepslnhin.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtdzubwehq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtbhgbszua.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gttlbuqddz.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtwhhrvppz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtmdazdbmf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtsdjggfho.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtwwozkayv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtehclyqrk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gturkeobyt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtprdtkptj.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtksjjbhxt.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtmglfqfuw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtjwjdqamu.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtlewgonvi.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtdbesbqdi.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtvjbddpus.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtshctnxpg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtbszrrrlk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtsyjyfwoo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtjeuiyqsg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtkzoznlgx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxjbhcra.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtflkbewsj.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtwivlexdc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gthkfzayig.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwwimqca.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtdopceeki.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtfvudrnut.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtrgzzocfc.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtmrntrffz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gthacpukih.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtzmyfjipi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtomepjoll.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtkckletmn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtwbitaesb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gttcqxpfuj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpjizzmw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtbqzhmyok.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtozlkcbpk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtstdgtdjl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthggxmxaa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtcstfiscr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtsyyhvqog.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtyxrpwvnr.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtqhfiboii.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtttboqwag.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtxalwyver.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthonmcydi.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtrenmjetc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvnzypgku.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjayypvrs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwpvtjsok.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtnatjlhvt.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtxkzmqadi.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjegjajzu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtrdlycdoc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtgjsaguob.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtfjuhatdb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtinliviqd.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtyudtdzik.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtrreoqcwf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtrqctynoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtgpfswpam.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtpsfyvjzw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtbwathuoj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtvpgxedrf.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtrdbvfajr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtcopkeeao.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtwmipgdcr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtcfuctydd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtagjwtaxq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gttjcdhexx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gteicbekht.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtzltghnqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtzdhayqwl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtgkhidewe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtyiihzjcn.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtlldvsibo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlmubvk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtdtbmtsct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtdymmbino.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtorhefphm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gthtjvzulo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtcurcdzrr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtljflzlrb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjvmyxnh.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtjiwvmqfw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gttvgffvfd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtayjrspmz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtbpivknkt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtushralgy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gthcdengqi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtnacinelk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtlbtdclui.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtryvbxbxj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrjvmgfy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtatsvphxy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxuiufdz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtmcgduuhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtwkjjazva.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtndcrpfut.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtswzwaezh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtnarisytu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gthculojhh.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtygcaatac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gthqqxaron.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtaydwpgiu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtlhcnhjzh.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtlpytoaqh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtepdsnwgp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtqppqbpkk.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gtbvachnli.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukjyklpi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtirjxiljb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gttqmyoqhp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gthzyjtmla.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtpahyqjun.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtnkygsilm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtparcdizw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtsjubcaxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtjvapdigt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtizikbfma.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxinxwpfg.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtbltdljnz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcfucafuk.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtocjfknyc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqjopinf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtkljmjfld.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtbidbzsir.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtewikqlee.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzkcneqd.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtohkowmzk.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtdrehtwxo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtyytividb.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtumfmtnux.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtwzbtzwse.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtvcgyasvk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtrgauggko.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtwiihanxw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtnfxhpqmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtlwzvebid.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtqqdnwmfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtfobrlswy.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtznbifkuk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtqayijxnl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtmbxwgkhh.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtqueuhisi.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtjlzrxcze.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtxywwxhlm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtjuiixlhe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtlpwxcqch.html


<!-- 参考信息 -->