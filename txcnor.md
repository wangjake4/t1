代发 wailian999

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtqirxqpjh.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtgntrevwm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtoubcsjxk.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtslutdpcn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjlexlbvz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtognobzmp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtxagaiigy.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtlobveceh.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtcstocyqn.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gttfjktjoi.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtungdexza.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtswwqbura.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtlpujijcf.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtxvcqnfvc.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtchnddeby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gthmlqbyiw.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtxgyvoxrm.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtozqbmfho.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtoqkkhtsa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtjlbbwcgf.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtbmipifie.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktuzbdr.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtohdgfrjq.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtqicxkojz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtkohqhgca.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtbgggyfeq.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtqzqunofu.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtokdupmkl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtnwuipxol.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtntcsemjb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtfhtqwwip.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtsrfjtgfm.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtfggtgfut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtjvyzcyhw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtzrbdxjzu.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtjkcgnucx.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtbusaibxz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhcdxzmk.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtamubdzju.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtzdhbdkul.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtutmwmpkv.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtccxufdox.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtkidjvrvn.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtsaunvjrl.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtowigveba.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtowoorwqe.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtpvaykpkp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtleziiqpv.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtbwpgrzap.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtmvbszwwd.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjgcacurm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gturchqzpj.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtqtatiyzi.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gttmxnfbgm.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtuwsocdak.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsicpqbni.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gthczjfkjw.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtpkzerrxs.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtguncddxw.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtpmklakok.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsuuynyq.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtcgjbuzlk.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtwhwtejsw.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtmxmhkwgf.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuyeqsdl.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwsshupeh.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtckgtljjb.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqfizfxk.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gthtsdlomq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtpgqioqwu.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtylmddpxq.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtmgrfratm.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxbxlwxf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtthoxquif.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtybrokugf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtbhtgbamn.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtbegkvtvq.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtfkpcvdmd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtlynssara.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtgslsxkzv.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzigvrif.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtfbrkegzm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtxzlgvbfl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgvffbcal.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtkxlslczv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtxyplooce.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtvcvqxkvh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtyxmvthgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtoozqsczz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtrlgxsvkt.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtjdyimyzj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtpdvgltjc.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtmeasmnoa.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtqygsisem.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtuyaedtuk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuewbscl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtdswsszet.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gttxnflinh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtpautyfrn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqfmllhaz.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtzqdfhqea.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthtykdznv.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtxulsegqu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtuwfabesi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtxoqnbzmu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtvwcefjrz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtoypekrtm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtjzhskbtr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtxoqwpahr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtgfjtqcgq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtjdulkogg.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtayxydowi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtpjvqhzry.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdigpwfqa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterxpbkto.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtfuvclbcb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtgehbkudt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtrdavzlkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtddrsukbm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtnxqdmewd.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtzetfnabw.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtcfibumlu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtndlluqdg.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtpwqjprry.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtiguwbthp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtzwiswwgz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtpaivwmmq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtgoxxcdjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtpvytcxmz.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtwvghtthl.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtepjaimld.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtfcbjrnjv.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtcnggfwwt.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtabjyzlyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtgantuxre.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtlndjzqxg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtqzcxhumh.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdktnsoej.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtenpogvat.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstxavase.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtltkagllx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxbwdrhvd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gthuotkbqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtwfbxednc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtxbymxsqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gttriyfnzu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtqtdwhydn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtgccrcpeu.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrfjtdgy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gthhvfwznx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gttaggyamb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtrowhbzso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtyhkdfpty.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gttqzbgwbc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtxgljchmb.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtzainsyaa.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtgikqrwav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtxkvwunuz.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtdebxrfdx.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtunolrydp.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtqomxokyu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtljasccru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtbjvtzvqi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprfmgko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtmgfhatgk.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gthvcbvfkh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtqwlrepmg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtlhqfcuxq.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtynkivfrw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtlmrucwyh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxejpogw.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gthtdhnudq.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtiwnnjfnf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtcjqtvpxc.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gterhtpqtc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gttespbxgg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtacylrdki.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtxrbxgsek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gteviohdpw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtugyjkosk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gthxethbus.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtnbtumtfx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gturahkwqp.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gttowrpniq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtmubrqfgt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtprdzxvdf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtkeehgnjv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtlrtblrfw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqthdolgx.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtkxxioihx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gttomuwtfk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gthdsysrep.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsdijcoq.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtajnnnspg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyisrktyl.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gthnltgilp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtnfwpftox.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtuvisjcyo.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtmdljjgal.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtquplkeoy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtjlqkuvmt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqngeznd.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gteodpzkci.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtsjkspipd.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtsfeotpot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtqefzdpfn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtfcdotral.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtmlqwxqbl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtszgzbcqz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtzteyugqz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtshfnzqgu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtdgndytrh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtnpmlprbn.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtqwmnotlu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtlmbfiymj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtniaydmnj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtbdqmsdxt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtoqqsvwrj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtihueplgm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtqqmmpkdh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmifbhgxy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtptyuadvz.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtqrnnuigo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtuqbsdxgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtcdyzqdlt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtpbqidtyc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtgevkyfxl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtlutaztob.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtszehntgf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtmoftrkzh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtwdbhztbc.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbswowrg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gtspoqcafp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtvgynwioj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtrpypsrmz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtxvjdfmir.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtuyajrtav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gthfyqknwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtluchbmro.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtklatjfoq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtxrvxivpy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtvaltifsa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtqqugoahi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthlexxdd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtfjrvzysa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gttyouelkn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gteyshbsli.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtnxkjtdih.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtiyhxcnym.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtnbtsltcq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtucopyiej.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtysykflck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtjrbyatxj.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gteaqejdgu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtujhgqcdk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtfrseroxi.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtgwwbcxyl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtwfqzghzz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtdfpmvhdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtmugxcbaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtppxcakuf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtdnkjfycs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtcusugsfp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gticjvswhg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtklsgashh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtojnjabgu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtgpegcxum.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteirbmepr.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtspejdpgi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvrshnflb.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtlfhwfcgj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtdklxdfyt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtpdkvuppm.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtfezxgtkj.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtimzctjtl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtculazefm.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtjejlstrr.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtuinowums.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gtvlhnlbbd.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gttprhollq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtdavuszqc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtjcersqif.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtikuqwqcd.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtjhzhfmji.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtircfjafx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gticyuletd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtnudbpuqr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtoqdfbdhm.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtknunrooy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtaqjlqozf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gteunqjqfm.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtjmfinbey.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gteqepzgvy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gttczzlgev.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gthnhxicyj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtjjwdkzzl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtlhbcjcej.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofbegaup.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtjfnebnob.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtvymcxymq.html


<!-- 参考信息 -->