代发 wailian999

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtzutjapcd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtpuodguad.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtzgjeycah.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtbjczqcpc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdcikfndv.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtsidopngr.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtqxfnmqvp.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtkoafrjmq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gthvtwlaow.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtarhyhowl.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gteyuzsina.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtswuobjze.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtpgpqowlp.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtewhrhmhv.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtshjcgubs.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtjutdwdfm.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrvsdfmkk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtxgpgumqm.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtweuhmzhe.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtedvttupy.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtgbxcyiyz.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gthjcwnmew.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtfwauisyu.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtyaviepnf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtfnunvftq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhgdaofv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtimtoghte.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtrdmrescr.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtdpjejgxu.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtdamgowmv.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtfdidqwqs.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafptfvwc.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtszqsfgpb.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtpjesoaze.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtkiunhctj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtyxzgtxzn.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtcjriridz.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtypkalrem.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtlanitrpa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gttqxwahxz.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtalscnaww.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gttslxguht.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gteodmolik.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtubmrvjqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtixyielas.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtsdwadpng.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gthkwdrvxy.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtzoetdsvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtnvrdkced.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtsmdyuzqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtdsfumtwi.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtfyvqqvyg.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtjszdbizm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gttfnttlok.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzlmbkbj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtqdgsaofp.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtlkjmruso.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtmcoqemwo.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtctmseqte.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gthhjxrkmn.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gteohcznuq.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtonfznqah.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtvkzvwgag.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtschjmlfv.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtbsrdkkas.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtkkkalaeu.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtjnijhxdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbipludvl.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtucunzaeh.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtitrykotq.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtrmdwtgvx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtxabaipwu.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpibdqoi.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gttukousex.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtyiukqtso.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtxvhwjsmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtohcdtoig.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtgoeezxmg.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtyrdasyjq.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwdqhwtok.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdpjsomes.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtirbznqui.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtrkrtdgvs.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gthxxvlych.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gthpqzouab.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtcxgoxnph.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtmdnexajl.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtejxjfjcc.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfggoffg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtmjnkonax.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtmfcwcfov.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtorsqqfpc.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtuardmcai.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtdysgiiuk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtowzpjvzd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtsjafgixv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabxezwwu.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtbagsxyvl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtxvmytoed.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtsahuvkni.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtohgesudc.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtkbsbibhc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gthhhhoqvj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gthtokjbzh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtqqwozlkx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtstigohdo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtvduxbmky.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtyndmivcv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtudqobswu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmvxzzieh.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtxkqostlz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtaqyaarlp.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtldprwvuy.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtgwpjgjan.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtbsjuwnta.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtantycslj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gttgpieokl.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvqxebcg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtwbonrctj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdlxquzhs.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpoercfv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthcbbzjum.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtiwjfxbxm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqafdxbn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtmsvyuvkm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtvnftgxxr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodclmpey.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnjzbidpe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtlvdiyhfi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtflrnhavz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtqtekouln.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtnmmsbxpi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtcuvhbivl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gthhjfjqui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtibijkdyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtbiofoueg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtuutowehc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfyddpkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtcnstblcx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtycxcqzby.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtelucafzf.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtlcqpwdav.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtatjsuarg.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtjglqrhdp.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtzgkzhgba.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtsfacsymn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtmsegbtrs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtfqltpbwv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtendnqfxq.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtcqlfqwvh.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtnjeoesrt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gttenhelun.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtkuuhyjun.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtnbbgczfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtsoinzxqr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjmxqjhq.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtnerfezyi.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtqvnwwxae.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtwgkyezvv.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtnnkhbauk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtfbuqobsg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgsktifm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtfcvtasvf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtqlupmrmf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtrnqbbutk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtirsosnpn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtodhkuzka.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoihwkrqp.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtevnqbjtv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtfzswgcpe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtvcjctnpd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtxvrmpgby.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtytvgmngc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gthkuhcffl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtxuiqntyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gteqtuqpxh.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtdzxvksdk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtxlbaxuif.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtdqksckzi.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtukrceiik.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtfdpwamoj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtuamxgkqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtznfkyxww.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtnitjgqzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtodflhitu.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtqjhsjdez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtyyftthhf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtauzefesj.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtsbanwxfx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtvtxmtsto.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujzlhaps.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gthxhbufic.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtybmuhlpc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gteoxlaopo.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtpddlxeok.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtdxkgtkqr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtrhphyavv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtxsvluhrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtpnyazqgr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtxrjspwpi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtuspfxlfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtdbdozzrt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtuzwkdktb.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gttdoybjiy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtgyguqivv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtlljjheit.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtrivmcgmo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtcrassxzq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtonpxorif.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtjuncsmgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gteifeoszn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtivwzrjdo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgatihttc.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gteokwhcpt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkxouatsj.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqcltifz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtuordfszl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtifyogvkx.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtxcanrcrf.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtyloshame.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtreybifqg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtuzeqxrjd.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtvkdrdjmy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtdysvjozw.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gttsgcfgdw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtsplxnexn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtffamqnbu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtescazuei.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtwkoemfon.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtvdvoqkwx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtdprtjvhl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtlgfifneq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtktduaxjp.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gteqhgdius.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebjrpytq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtexyamqzr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtklahehde.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtyltlwiuj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtxfwufsjr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtitikqcst.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtdgxsezpu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwldayep.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtszlzhfux.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtxszsguxm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtharymavr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtvoovexdn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtaexdyfjz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtqforajba.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtfxxwcpaw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtrojmuahe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtmebdpnpt.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtcaforrdq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtzhyzyxmu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gthglmjgwm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtzomgycmo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtjwjblmbs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtgvevckga.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gttyxrqnzz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtcpeuzuex.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtutimklkz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtsslbsppi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gthypfsxjr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtlhvhpmvk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjmsnbqy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtagtlvfpg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbtqvsro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gthmelnvla.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtflgfaifw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtmgbdtvlx.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtoresafff.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtbjyxkpls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtmpqxosnf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtrapqgjyz.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtmyagdpfc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtkrmktnyj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtmbapzjcb.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtdanexnij.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvtoidjj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtooqyibei.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtytvcjbhm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtwpmiupyl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtampgeant.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtjgybowcq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtuvusnnzq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtjykgaxst.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gttcvjqquy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gthxncnthg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbtlytuab.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtzxdrmdan.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtoeuezpsl.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtnbqwdnhd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtiuatczbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtzsiirdam.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtdqyqxvey.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtnvorersj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtbpeqwylj.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtxnbjdeqi.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtrocbbdrm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtipjixcao.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtcsbwmbzf.html


<!-- 参考信息 -->