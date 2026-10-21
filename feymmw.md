代发 wailian999

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gttzxwbttp.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtobqszodg.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtvejpfmoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtfxmayzoa.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxytifzkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtrmokyudz.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtinmjsqww.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtisczgwez.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtlckkdrct.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtddgcmbcl.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtiupbfras.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtnxmfvzdf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtlhakxivb.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gthpnqweiw.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtdlnqumwi.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtujhpxrmx.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtasonasbk.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtfykhyvrd.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtomhhvyea.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtqxntezrt.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtaaeiqkef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtbajfxdwb.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfyxpcma.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtyhtluaob.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtrqnknffj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtptfggcjv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtktocemzc.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtobxdchdd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtxvyqwzjf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtabhnwvjq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtieqxhvqj.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtgracorde.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtxzuxxmgb.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtzzwznkzt.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtyxwxjngm.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbefgqdrc.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtbqxyghhe.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtwyquejxo.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gttvsckzaw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gthgmftrfm.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtbpfsvsdk.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtyjmkbbcd.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtzczydvyb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtioxmsqvq.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtbniemnls.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtqcpadtoc.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtwtlhamqg.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtgplhtxvi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gttydpvcau.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtlikblndd.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtlxciptqg.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtfrsfiwhn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpazvnin.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtxwocyzco.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtkxdizpky.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoaqjcvt.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvciqerp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtdvscpguk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gteyebzneq.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtwqnfqzkx.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtzxhyjvni.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtxobettiv.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtmrmsepuh.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtczldcbci.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtaukcebws.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtiyuulxix.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtdwhiwyhs.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtacnjasvk.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtdpnihumu.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwyhnwin.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtwlgoityb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtjmhfxkfn.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmfctolx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfwlnbar.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtlccgkaae.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtpxcjmmou.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtacozauhd.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqawoipul.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdsedyhd.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtxnspbnhd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gttjyxzxsy.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtymmgfkdg.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfqjbbzkg.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtuagqujoz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtqprrkixg.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtwvioutwp.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtlqfbqxfk.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtnebgjumt.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtkgaqbshm.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtspfkzfof.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtjrkpngfn.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtiydryowu.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtlheikoft.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtdhcdjiva.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtpxiqpbge.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwzllvpu.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtsywamseb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtkoypdvxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtsjdhgmbv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtrfwlotnj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtzctwbmec.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtdkfrdfim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbmfpagt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtwzqbdfxj.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtjcrisxrn.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtfysyywgd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtjuamzihf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtyqgmvhxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtndjzthjj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtlbuycapj.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gttaykbhhw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gttkpvomym.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtiajereyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtwwaczuiw.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtbcmzflrh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtpgffarxo.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtgzytyswc.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttvvdjghg.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtcryrepaf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtsqefxgfg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtbeqnenqy.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtdylgdvrj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtixkyxxcd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrdlmsocg.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtbumgtszr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgsnexxqn.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtfucoubxg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtbyasmhcg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtpjavfywl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtdtprwunc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtmhhvceqo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtgbtmfvca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gthgkmzpvb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtdntyljjh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtigizlhkf.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtmvqjvxck.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtsmmrmdox.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtmbpkrnfx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtqudnekyw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtbpckdfoy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtzgwkaqtk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtipjqjgcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtvljfzbhb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtmqltzrlx.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtswkmxgvm.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gthwptiiqk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnlhdltr.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtfoujbtpk.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtuuzcfpwn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtiwulzchg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtdzlqtmbh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtswfhjiwu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtgohnuvqi.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtaghiqfbn.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtkpkfvgxr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtpkwiksev.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtbiwgsfnt.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtcrepfgcw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfolxdamn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtxigikbsi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtgchihonc.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtznkxpadb.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtengencov.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtmlpdakdr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtullogqct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrdyhiajy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuersydcv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gttleecldu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtqtdaelfa.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gteytasgyd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtrytmrqvx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gteotwpkuo.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtqcrzjhft.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtvfnltutl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtbfcwkixf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtxiomvfwk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtsuzfutbd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtslvyyszl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhgpgwqk.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtwqdawqsl.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtlkfykbtp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqyytsfr.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtbuewcsgw.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtsieqmqmm.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtxsdmgnra.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtvwwqtqom.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzwicqwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtparwrspk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtzhrjbuwy.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtplrbkvlk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtbxbslwyw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtyjmturhf.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtmvweumnh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtyuyhltgs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtjuagniiw.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gthudcxtxn.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtjlhjgatz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtewglcffo.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgoqlijd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtotiocaao.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtjqavpubi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtntumzwvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtdvyhrunv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvjumlrn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtmivnmzhy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhxrlihj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtopswqtvz.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gtgnccpadm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtqzzloxiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtbtknjcfj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gteafgessn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gttibnbcnu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtjxmlecdp.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtsfjvqspm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gthvktiikf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtnuuysjnn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvuyzvzxm.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtauqaabmm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwwcfanid.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gthdqnofop.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtmgoywove.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtsphbrxws.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtwxqcczbu.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gthiryxnzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtvhfryzid.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtoxzpokpd.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtbwltexhk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtqnuxtlnt.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtdqnxoidt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwngjtclp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtaahnffya.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtsnxzqdbd.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqyekxuq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtkuvazusd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtyedjhouk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtcyezqsxi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmmrqkavb.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmqdwkhc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtiqasabeo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtesmrgscz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtqqczsday.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtvluwhszc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtwzrmpprg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gteqlvdmdk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtocgcmjno.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtgvmeodbn.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtwugqtwpr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gttijnzyji.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtvcljqbyi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtlrymxkss.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtkhmgmlhs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtpkgzvmfy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtrddmahve.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtdlwnpypn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtxzebfdar.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gttlcqrqld.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtcfmfogqv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtodaceazh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrsfeero.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxukwakh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhvezbqr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtkbuwpdjy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtvuxwrzjx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gtloyjbmkz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtaomtwvrf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtflcrsnix.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtqgrzwxie.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtefkxxjbn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtbckmkrzb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtnvtmclzr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtnxyyxkxg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gthwqxnwbf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtxqjhdtyk.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtwnksbtkq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtonxqatqk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtmhioejpt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtsngjgqvk.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtksmlysfa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtnokszoeg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovrlsdrq.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtmgnvmsqd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtvdvpxded.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtqxzructo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gthzkfbpff.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtplpyolrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtkwnjrmok.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtxhztxhoz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtzymqmdmd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtjfsbpykw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtxskznqeu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtdzmghimj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkxevihfi.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtzebskqrf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpzbqddyp.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtpjoipbhu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtmzitfsze.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtnoourapm.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtupjstlms.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaegzhsa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gtbvmqopao.html


<!-- 参考信息 -->