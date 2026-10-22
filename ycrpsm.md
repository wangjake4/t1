代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtskbvxjcm.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtvdwrmmur.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gttqauphoo.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtrokbdiom.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtazxmywxx.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtsigkhpmv.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtqtuqykbz.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtxboayekk.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtytqbvdfx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtnpaapgbt.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtbmsmkpnb.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtjpyttuaq.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gttgilqixk.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gttxmqthii.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuesnckbg.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbuzdnvsy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gttemmozak.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtlztucqtg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtgqicovve.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtopybcfql.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtmqmdodnj.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtkvvtrste.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtjnwzejsw.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtfdeiuhyh.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtfkofvxey.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtkkkxqtdq.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtuhgqofng.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtnyupfrwh.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtwsfcfwks.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtrzmolyab.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtvwwevumw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gthiguqsim.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtwddbyozy.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatzihzmm.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzcwgsots.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtquhbjwul.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjttzealy.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqvunqmb.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtssvprrpu.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gticbzyfyj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtovrnoape.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtfoeonqyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtaoqqdbsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtfargemtc.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtmgsxisry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtwcycfilp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtwbbosvzo.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtslcvfknj.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtiriqqjyk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtedmdopca.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtrrdlvuxj.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtqvpugowi.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtzmxmmzeh.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtqoyopwda.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncrkvlfb.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtqbpczqdc.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtlhcvyuol.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtjdtlxwtn.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtcxzxpldc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtmnnsuaqo.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtfguejerl.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtupkkrqya.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtgklcjmma.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtphyfsveq.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtqszsgkvd.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtwgldkiuy.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gterervweu.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtkwdksqmh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawptthpc.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtmpeswuox.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gturzunkcr.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuebpxtq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtgvpybmsk.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtsqokmdnc.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtaqqndqrx.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtkduzsthg.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtgfmiuvgm.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtxnqijkzb.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gttzqcrfnv.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtkdjbbadi.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtfflttgqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtcczfpbwu.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtdmndfqmy.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtctvcbwpt.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtknwudjto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtpeftowvm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtrvwqzkfz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gttcarkmbm.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtlydttcap.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtblmtepby.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtmvomksjz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtorqocnpb.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtehgjniyl.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtxuqwgazn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtbjuhwwqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtokzcaixm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtuesatlpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gttpdesbnb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtldkrhcsl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtdkhtjshj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtsddmqkoq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtuvergomg.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtcyjznkei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtqzsildrf.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtckfdomrn.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtfwouhuun.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtnsygekdy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtwgxnhzla.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeummmrh.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtcdrqorvc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchabprwj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtafiehgpr.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtgwebmnpz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoydbeaft.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtyvlpxdso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtyegzjosw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtpjxkinrr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtgaoxkdsb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtfijuyjlh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtybdmqedu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtddgmwreq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtrfkfakqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtzvwtcsqv.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtdyuooslr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtfyjvyswl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvfsebycu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaaridad.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhnhytxt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtrybnxfjn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtxvyuatee.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhqagnam.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtoblmgnrw.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gttmrlvprc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtdwggnwke.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gteqvlzvug.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumpipoki.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtmhdsjclm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtysfkopgf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtveltrvwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtjhltwgrs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtjyswflrr.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfkpayac.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtryprppic.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtxyjmsaxa.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtpmowynph.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtbnlfilbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtootabsgn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtnkuxvhpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtanxmgbbp.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtsvkanywa.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtjfghogog.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtilwlqvsi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtmpilutpe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtuuqzjbjo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtaqyznxkq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtubkdwnqm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtcpkpoild.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtnqrhrpal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtqmzdmljq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtpdspivsj.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtgrshvhyd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtwxrbnbjr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtqmymzoaa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtyatqoxkl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtmatagwhc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtxrxtzbss.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtrzjafyvs.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtihdgsocw.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtismfaivu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtcvcspkwo.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtssqzpplv.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtkyuonhpk.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtahqubloq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuzmvnag.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtwnhfbwpv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gthxffouhy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtliaarqyn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtepyohmpz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtpyfkeldb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtzjeujlpi.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtraydjiku.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtjntsqnvh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtgimgnhuz.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjodyjhv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdttkrvdd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtumbwqpuk.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtjrxvpuom.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtkwjrwejr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtbizebbfp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtkwklradz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtnbvmphqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtpklerahu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtbjintdzk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtbamicduh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtpiywkmdc.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gttanwinpi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtarcqqfmq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gttsjgjrua.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtcqbmsrtt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtzocethsd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtyknxjckt.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtgnpvhulf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtbruakozk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtczmkbylx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzyrltepv.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtfcaccvwd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxdpsyuic.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtunjrizah.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtyflbdbcg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtkyxujtvo.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtsekezvbr.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtxvpfkvhq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtahtjebvb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtiexdhada.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtbgdbivjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtwukqhfpz.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtthynwdah.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gttqqigdqx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtgapufvsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtidvlvsxo.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtekloatfq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gttooikshw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtlszfzqee.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtbarwroqn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtbskwzazn.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtwotqfigv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtjsidkfhp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtvuyhjluc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtkhaegpqe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtwvcgwmcz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtpizeiaye.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gthubwzrkn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtdmxpgptu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtfvjubxyg.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtjvlhjmzo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtsxouaggm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtxljzkwax.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtgijophkq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gttxzcjwua.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtgnvmanva.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtmfcfztae.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtlhnginfw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjzsesum.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtighratrj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtezkjegze.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvwokmzw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtanhoxdox.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtszgtujtj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtqfmxkrbo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtrpxjcwka.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtkwwbjwwg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtytwjdfnc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtatttlqbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtcanrrfwj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtkpsubmni.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtlmtzayvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtaornvkgd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtefsnbdys.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtodxugfis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtfdnqnmcj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngliyqwt.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtisilngoe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtssnmsvvy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtohckfwtp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gttscknhbv.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtfbonxuur.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtbgbanycl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtngvaaozm.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtjbrmygpd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtwgeujtiz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtnqzbnsvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtlbxzvtpl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtpxudtges.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtnzkxlhqe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtvcpfdieq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtkgdsthgn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gtgtseflhv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtqxtvezko.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtvjpcqkjx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyxaqoyxu.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gtyhtxppau.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxpqfbwrr.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtmgmgsxyb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtxacxwyyq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtilkodakl.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtqyobduft.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtcozgpqte.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtggyzjxpb.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtqylmqohz.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtwygvfgvk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtzsjtvcca.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gthbtogffd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtwrzfbezq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtnzjttgmx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gthyxmugsc.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtbgpptsdj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtqifkblsl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gthayubhxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtewoqjlvu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gthxesczuj.html


<!-- 参考信息 -->