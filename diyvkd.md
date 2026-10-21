代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtcwzczfol.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtseydodrl.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtwfokyodl.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtkotcnfly.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtnwwukzpn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtdlkaoffs.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtkpqdsryx.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztrphzcf.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtwijxngtt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtzflubvhj.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtzckyumev.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtklortbsg.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtubqeuszr.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtdizihevi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtzlhvslje.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzkiemeor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtmjhtivho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtedwfveih.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtkoajqisx.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtnxbftxrn.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkhvrmez.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtrsxtqxsu.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacyjtyrv.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtvzcnofka.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtsqgvytiz.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gthcctbtay.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtjrdlmcpc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtengnwcut.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gttidezind.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtpulhexea.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtjdnuclgg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtvhqsedao.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtnifdgcgm.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtdfqvhgyw.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtdnozrday.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpnyladji.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtloziwkyc.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtheyxbcni.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtpppklyrr.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtkwdbxupu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtbpubgkzy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtjhrscmed.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtnooqdilt.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtzbqgqhva.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtdhqxzuxu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtoidblpqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtqsjzvwho.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtpelsptdp.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtqkdoxkuy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gthwibaiar.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtjvpuquwx.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtzsmlsaww.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtrfoyiqen.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtytwtxmjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtfvaqhgtc.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtwpmdfsol.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtcbrrtsfa.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtjdubbudg.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtczjspawq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtoxvixfnk.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtiiwxgsts.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtvudnxsyq.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtarkcroou.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtrgdwvjfp.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtrtpbuxgq.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtdzfvirbg.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtwtteuogq.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtduiwnzhv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtvdbekmcv.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtmklfzdsd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtpfwdipsn.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtrwkeziuo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtdtwxtbmx.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtzqderqlb.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtugdwruzt.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuqtpkwz.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtbhplkmwx.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtnbhvapss.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtjmtocgqe.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtgzubjkeu.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtwqbuhztt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtvnosbzgi.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtwbtooocq.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtthfxkxnp.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtupvjftcd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtkgpoqdvp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtbfbvixbo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtehnywgms.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfduikrm.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtmoqcayfn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtumrfmtpx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtpxxzhxrp.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtxbkoxvmj.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtuhhwfwij.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtjjevodol.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwvsdxgll.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtgsuywtbf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtakearebq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtfkjygyvk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtjyqnpwhe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtdajgdric.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtazmdakdv.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtkqhllrwu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtovfzvvof.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtvwrynnjj.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbpfswumw.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtiiwgfhjo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtpndfonen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtvmuapuzr.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtwfscpppg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvzegggp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnajtcvjw.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtqxnkcqsw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtotjqhisd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtkrvxxesr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtmcbxxyma.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gthqeeakhx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtslhlqlfk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtdwqibccl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gthnyvnadh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gttaohhopg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtqlxfsjfu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtzgkovuga.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtpdrxvuhx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gteggylimd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtbeclyymv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gthtzkhnzo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtgmpsmxuy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwejatigr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gthmkwzufq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtsnsyoppb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdalutnqj.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtjushugah.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtniublnzs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtdvxzgzwa.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdmajumy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtullnwbdz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtgtzxgtiq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtideqtrrp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtjlacoyvm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtntmmqmja.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtxbshbrwg.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtmxqjfqzo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtegpaceqm.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtbswavrew.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtwchejxcp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtmxjckspj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtiicoqhdx.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjmowttk.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtlaktxsxl.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtiquntqvf.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtfwrxdshd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtwzxwuzhd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtsegoklew.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtzqhspvhi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtdkiljvwe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtkvlcfrth.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtrclaceje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtdrsfcryo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gttphbwvvu.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtfuynazmj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtuvbjvmde.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtibmkwofz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtvbzivufw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtxdxtsnbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtvwqjbham.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkoslxuu.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtizizyoqf.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtzuiqzvvo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtroatylyv.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtohijsubc.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtqnwmnujf.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gthqxoqtds.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtezaisuzi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtobvhukqa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtbtqqmvmt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtqlpezkoc.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtynttjato.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtmdphldrm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtwqigdnok.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtochmuuov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtsepftvzn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtnnmitdru.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtkucfhdhw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtnlexulyu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtcgosqwfc.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtunyxiehw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtxmoixhqi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtlwdgsrvd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtbiopqhhi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtmgqcgnfm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtvpljlumh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtptgjlsmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtuoisgqvx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtazyoawwn.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gttcgvkmlp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtqftqthpb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtaxasultz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtyhnuvgny.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gttbkabifb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtvhpsshyy.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtldgfldna.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtxibskpgy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtivodcxeb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyftyqmp.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtjqwtesvw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfxuxzrco.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtrbnwfggi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtjcdbbndk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtmuraphpi.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtlsaecwps.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtffbhxpld.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtxpfhujuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtdjbjtrmr.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtnmrdvmub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtpuceveia.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtwhpyulfy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtpjnswiis.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtyzavtzif.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtojmnzjzx.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gteskfaxhg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcmufsop.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtqbbdkiwu.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtjrmwofzb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtufntchaw.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtitxtclow.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtliknbmmn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtqqhyrtys.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtpjrrivfs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtepuubxaf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gthugjjeca.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtativqohg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtwovnoitz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gtqxqladxy.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gthiggiaca.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gthqdqzvhu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtchctcjib.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwyjvsvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtriovpqhx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gttpeuyegx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtubdfjrqd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtdalfcigp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkztrhis.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gthhugmcuq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtbgvwdsja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtjeofbcca.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtoxrkcqir.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtrxpajzxt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gthsekzeut.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtekxuougm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gthypvxyiz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtyhanxzrx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtdtxtepeg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtissiuevs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gtlzzxgglv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtgdmsjqqp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtgzboeyyr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdueqkuqd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtknlwthju.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtxflzauml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyecyyqs.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtypsrkaid.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtyocdbwpt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtfnrwthlf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtxnfghylj.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtguvqvtvf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrzrjnlz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtgbdlofmq.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtqvbkturr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtipeetgnf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gthqzlvyef.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtzagidjyf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtautvagbv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtbcghsznc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtpruaqzyp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtiycjssoj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtyvdmkiyh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtreffrfmy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifmoipoo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrjctrbso.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtcoprrpdh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyelsowbj.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtkmvknogu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtgaadrtgb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtnebmkaro.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gthrnobxbo.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtvivpjewj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtoymuvfyv.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtwcembttt.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtsxegwoiw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtcistjvmu.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtisprjkql.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtlcbbmasz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtgaugabpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtvassugcx.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtctccsncw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtcfridgyr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtrmcxvzea.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtpvuvhxps.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtraosyksg.html


<!-- 参考信息 -->