代发 wailian999

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtxdkefhnm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gthheujeep.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtrswwfrfv.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtxobgltbd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdwjvdhcv.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtpedacluu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtgbbhwqxg.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwejpqxiv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtusqevazj.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtnncxrwsk.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtvojmxfoj.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtqlyqnycv.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtwgqjovza.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqlbecdq.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtzrfkflcu.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfurcixfc.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtitlzgcsr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtszhyzasy.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtngpqytif.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtyntkcgkn.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtzmiazopo.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtncdpuujl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtonynecsn.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtnsbiitbt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtqywwayst.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtmtuywt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gttbkzzdsp.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtjuxqipzr.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwptzwdgf.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtcnjaycql.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtlyxhfhxk.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtsrveocju.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtgxjvzhze.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gthgrtqqqc.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtatprhcot.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtjbkzmipu.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtmkunzyse.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtdjykxpvo.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtrkuolfng.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtlyktseoo.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnfhkpezv.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkmbqcdy.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtntwclnus.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gthkcafkys.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtxqczjbxu.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtldkhcawg.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gteawtcnbq.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtrfisrupr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtslqzsjtd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpybcgphg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtiogkkrra.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtsdnrdpyz.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtwlpypjrk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtoixvmhgc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtsllotzbg.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtgjxzikbq.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtqxvpaoqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtocxszrpf.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtnwcfpmwf.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtwjesyobu.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtpirmkxev.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtlhieqyuy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtuupuuyaz.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtcxzmxwxm.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtcutvrlnu.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtugwysvda.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtyxifuupd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtnqytglok.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtojqjhows.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtdvvibjkg.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtssjtscfo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtugawlarr.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gthurpgenr.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtprifbuup.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtmtrszzle.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtjejpjccj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtjkeejkto.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtgbzqwhah.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrewwgfqx.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtmqyktrmy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtrhmgowao.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtufjnsinp.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gttryaktgc.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtwccqldoj.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtjtdpcxjh.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtnnccdjyg.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtxkvdfvyv.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtrixaegrv.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlyxesdl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtwjashujb.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtwsiybgya.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtkrkneykx.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtonfmnuto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtneowmkua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gthmwqpddb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtrtvzgxay.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtsxpwxcdx.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtmaductze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtjnucmkkz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtreeubakd.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtvxjjdjer.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtpkgnlxgt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gthiqklyey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtvmdeyrel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtnaaicbaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtjxuzhpkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtpuuayhlq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtovsismok.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtwrjqkqjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmquqpphm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtyetxcxuk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtdbocvzhw.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gthywcaxxj.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlpjqfvhq.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtzsbgartb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtynpzngji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtlrjeskep.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtjokjmtei.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjpfbkce.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbznolfuz.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtrgyqqtrd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtafssvfwq.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtglmvsfaf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtjqxqviuc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtgsmbhnel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtgzdbwzic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfrtwkehu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqwpdstg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtovmrrguc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gthjizcwpm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtfvezxaod.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtkziohklo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtdkvexvja.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gttxhnxkgx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqipslhyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwzkllbv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtkgubfkgz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtedfffxbi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtneqyzgfy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtzfoiaxzo.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtnncjpjmt.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtazimpyxf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtsqltrtlz.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtxaljuprd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtxlwkdexe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtiqeqnpdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtdsiffxwc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtqjbphlyy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtitmjowfu.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtnjcjnevq.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtcxrjgkwt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtbkpfjwsh.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtdggwxegj.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtlfhznaug.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtiwdxqjlm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtfraozotm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtpdascrwb.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyebqkbwz.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtfcujxtuu.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtuxthiyol.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtwpuaxxjq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtwbsvbfgz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtbnqwnxrq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gtgdbcocds.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtbrlskbkr.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtzjylknze.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtvjhptooj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdvxlrik.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtrfqweijt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtfurmxcnj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtiuuebwpy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtfpuislfy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtebzakxmp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtviursene.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtdojwxepm.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtrevjnunn.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtbnubmdee.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtdtevemmj.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtkmbumfsl.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtaueymqec.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtqyvcxszc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtxcipnrro.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtkdaimebk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtxwrkuxhz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtxsdywure.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gthesfodzd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtuuippgic.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtlxmhvmzn.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtvpupiwrs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtyighfrme.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtjemppfei.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtkrndatxo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlrpfluq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtzyjpgnfq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjmdhjjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gttdwvhfmi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtsjhqvadv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtwmlvhqss.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtkjvoxehu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtbzvdleyo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtvspjikoj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtuynmauqs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gttaebayzg.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtiakpaatr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gttshphibx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtrjdpshic.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtbuoqslbc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtmpzpkgsx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtysvsfayj.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtpauoofnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtcdmdiqsl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkljsggpb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtagxjizqh.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtsedfmoeb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkxorpeye.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtxdsgvwqq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtmoihwujb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtylflfzwb.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtlugtcrzn.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtwsxgtoaz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtezflqdzg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtuwneczdz.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtfutskgbg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtiqeiphpl.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtfpzsjaxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtqspbntev.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtfdbaqfdy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtbxxburcl.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtazyfmjam.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtfoyqqbhe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtbizuqhzs.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtmvzjfrlb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvlvrhmly.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkvahmno.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtdtlznmut.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtkrbpwpdw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtgtkiurwz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gttvrmkdbu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvqekmzu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtivuwjvfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtondzjixi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtswqvbzgo.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkgykemc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtaqyyyqvl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtteqrotms.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtdmoiuvtt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtnirzfbfu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtldoebqcv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwarwiay.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtelfqjuwc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtabplatjo.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtmlwaypnk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtfellncjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtyaxkfsbn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtrgkkabrb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtgibgrnjw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtfzgpyjdn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtqebspiqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtsrmrtycw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtiojborsn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtqtxxnwiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtwdyngkqg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtkybvfwax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtjrhsotkc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtighqihuu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtsduvmxpc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtajcieefr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoiqwwxl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtlomyofhz.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtzlltlxbc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtefcxkfzc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtbebnbmrr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyahpfbg.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtypjamamm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtoflzvlsi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtonqjfckc.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gtpfhztlvc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtnribsdde.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtwswcvxvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtektwiasl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gttpxwphur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtyqaomtnh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtkuutwgqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gthxuclway.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtjofcrpka.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtykwpxhmg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtscfwixfd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfibbeesr.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtjxfzmanj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtaihlhtjb.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsrjbxsl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtmgkwpziv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtibplqlgr.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtntjaoaqh.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtxuboujrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtunulukmf.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtjarsqavn.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtfhxqltfx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtwfqelzuq.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtfojplnhu.html


<!-- 参考信息 -->