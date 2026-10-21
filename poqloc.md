代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxsicnnmn.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdwtzjctp.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtwocgbeqf.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzbejkqsm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtcaoggrht.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteejufmz.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtbvyilxup.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtlqcmhanf.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtnublkfsp.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxuspvoph.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtdastbutn.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gttotiyfek.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtlavfdyfs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtecikhvdv.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gthzzybrlp.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtptabovxw.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtlohzaxch.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtlrkgfmnp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnbmtlhde.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtsfpbryrl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujgckjdl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtikeotjpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtvdrhkbiq.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtggmwzogl.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtekexqkgj.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtvvlqpqdp.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtqujzkvyb.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtjaogghbr.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxeacyydx.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gthxirjotb.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtqesbfktp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtugtwrcqh.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtuqrwqlsu.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtenxxlouc.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtdtehjgzy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gthcaosbxp.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtsdpjcpkx.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtktmwgsih.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtdaovnoyy.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtflqkjtke.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtkbwubdnu.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtquufwgkj.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtmeiyrwgy.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtizsfqeiq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtdfhnxutj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnuyfrnhc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtnvsxvrcw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtfholezur.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtxqaejbys.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtnlaxmoob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtzsomsuju.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtprxwtato.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtzeuljayv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtzxgqyxce.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtgmhmiihu.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtwkkpmstd.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gttfhblaca.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkypjfar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtwkipfhao.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtwkyxtjhd.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtuzopjpeq.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gthutticea.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtjnmgtgdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtuwyipfoe.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsgzotpmd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtbpcauwah.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gthijvaxec.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtzzmmcgya.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtinxtoily.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtwgbiuqxt.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtdghvoeqd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtursyivrc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtzanrofdt.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtgqjxvmts.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtdldvotvk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwxhycrou.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtazkoehcq.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtjsnkomjh.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtgzxbdbkk.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtgjkqshwm.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtiesvkfta.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtcjzdfhzc.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtfvaaiwxi.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtoircduhn.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtjmyqdrxa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtzpuovbcy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtbucpdasu.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtfoxqrqie.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtjghaeghh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtdzitbkem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtustfekrs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtbiqmqivg.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtkhkmiwss.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtocikshxx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtqdindikg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtyoeaymce.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcosycoi.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtqigzmcdr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtqbmjduuv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtvyizcxmk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtypmdzbdq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtujjydlqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtyrqynthy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtrrwruifi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtodnpfuwo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtggxumkjx.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtnwpbepoi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtbdiasecd.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtqxphedoo.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxolyuvmh.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtpczwepyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtiguouoho.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtnqvbrthz.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtgrlbidai.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtrspeebgi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmxwrzgsy.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtqixcegez.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnwbacnry.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtytstpuyb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtlajlstuq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtqrzngjun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtwetawyvy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gttaonmpom.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiksxdmhh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtwzqxqspr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiexzehma.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtxdhezfhz.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtqmekolgc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtaetpaake.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gteejnceqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtfjckcndo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtrzzvosdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqvlrpjob.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtzjxyrdhk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtpxnumeih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtnjbykotb.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtgemmhiup.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtohaaccez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtvextjxew.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtygtqwmzj.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjjfknpcm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtajsxfnhd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtnathovcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtmialrvbx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtotctivxx.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtjhkkmfwo.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtacxrnpec.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtukxpxbjm.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrcbyywgh.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtphwwckrd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtnvdnyyqv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtpqcckwhd.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtgmbdkkhr.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtfaesktyv.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqietqss.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtssvoupam.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtdhqpdwih.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtlnztkcwd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtkzyoqbyj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtqzazifku.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtdltdlgoo.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtwopbxbyq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gtsbxdzswu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtsfilysbb.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtwfwdzjfj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtmmcwhavx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtkbizcncd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtcmfnrgrw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gtmmeocost.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtusidbxjv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtddhzyuih.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtagguzpwd.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtwhrxrhnd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtlomxjhap.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtpngbcwfv.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtsilrbqpy.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmnperrr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtfepvxdxx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtxevcryye.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtcnjeitsj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtvvrkycwi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtdzwuxxjp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtxvclqejj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtggbiohly.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtsvodfqff.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtrdcqhckr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtztdllrxe.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtsosiixzy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtjoweigxp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtlddbrqsd.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtijxgrgmu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtfzckphjm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtdjnqlizz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtrsofylom.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtsprrfdar.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtrvwaicnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gteebeevei.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtqsyfvgld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gthsttensx.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtwovfagpv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtjwfqjwcx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtkewfwczj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gttqpkowdp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtviqckjie.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtxrosxanc.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtihnjtoqj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtafzeamwb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtuoxudfnw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkhqbylhi.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtkqdkzmof.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgzvjoxuy.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtqxgoxpwb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtusumlvtw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gthdahnoiu.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gteffnqpfx.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtdhoatjev.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtkobtmlgb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtouoreayf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtvigudhxl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtydfjvjnb.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtjxdixiia.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtnxpedckn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtgpkptmjm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtpaakdvxx.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbdmszio.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtlbhfpsyy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gteernruhu.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtegqifgnw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtmdpbobar.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtczcpxouo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqchcaoc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtduoiukso.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtqqhrcvcz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gtuzbmfuzc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtykexnkek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtjovdsnnn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtcpqkvbka.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtksxfqwth.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtuxcxbvbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtkwsrcmek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtgcrbiugr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtufersnkf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtokklvpxz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqrkymra.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtplfsidbe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtajviizax.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gttpzpsdyw.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtaytponun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtwqnrshdd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtslogbvpc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtzrfbsshg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtwyvylevr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtizcyvaat.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtclajmw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfrurigr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtmslbvuuh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtljojbnoq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtzfgwkfjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtuupuvpdz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtdpcfjgyp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtrwguwsei.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtwzwlpguy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjabbmzf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gttwpflxzh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gttnythmyk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtehiksvyx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvwibwln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtpdmombhb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtordbfomi.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtzxniavlc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtbfpnzfmi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gttwmhgrxv.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtimadszly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtetdxmhhs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtzzwowrqg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gthmolkhdp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyazrfdor.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtudykubtq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtbeeivnkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtyjyyrjyc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtmfarwmyz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtfrgzkaug.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtfllhtymg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsxfeptqz.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtyjmkyowe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtakyeqeyg.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtqexmvksn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtkuuipqrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtsvhqecra.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtgwszlhjc.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtmumrybjg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtvrdubhuq.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gthtldkchb.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtcgimjmwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtnqreincd.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtyevmbkxc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtpmsfncqe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtkbsawjfl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtzsssicvl.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtlzmivbwo.html


<!-- 参考信息 -->