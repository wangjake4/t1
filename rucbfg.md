代发 wailian999

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtjbrrqajq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtvrjgnbjn.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtbgjsstyf.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtszoilqxf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtktidyeua.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtecarnedg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtqaufltmj.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtebbkpdjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtygtnqxaa.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtsvgqcevu.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtgbsclmch.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gttaqzbpyo.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtmypgbqsw.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtnomcdlax.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtibrnurwy.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtgbkdmawo.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtvklnmmym.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtzyubpnzf.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtopqryujl.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtrssipcvf.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtymyvfwel.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtwgaawlqs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtprocgifh.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtiyhwbdki.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtnofrsubt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtrmbwvqme.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gtdqhnzhsm.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtirnnjlbh.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtkitndkmd.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtezwnhmtt.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtpdilwrix.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtsnbglyil.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtpjuyndzz.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtewohdfkd.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrucxwta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtsqzbvhhx.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytuhugym.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtlwsaaukr.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmyqyfzg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtmfzuwytr.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtkxcjxxqx.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtpnzhqpel.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtafpvjcvr.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtoxzaxhhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtfipoltfw.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtccrpfmuu.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtzvkivgoe.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtazyxexzs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtffummkeg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtbsiouhpg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgomaqro.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtbjwisadw.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtphmegcgh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtptszpiyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtwytbkgmc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtrydqdkoe.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtteyhgumf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtomjfpoxy.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtnmtntdld.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtmxdzcgxj.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtdyhpzwfe.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtirlrwsyj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtcvizihxm.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gthprawppb.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbpigkpa.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtsmlrxlbx.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtwrgghbwe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxdjdcjeg.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyrmgist.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gttfrvmcbx.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtjfnfjzxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gteynkxcut.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtvqdlevbd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuylehxk.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtvtzlkrai.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtwmryebpx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtyweugknx.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtmaowojco.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtxqmafowp.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtsmzznxcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtnzsnrusl.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gthgtxhgyj.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtinhhcjyh.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtlirwylhv.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtrmpyxywh.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtxxwcwlkm.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtzxsfmuqj.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtwjvergnn.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtxxnfmdtu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtoqtuqpgj.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtvxvavalm.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtkrvobzje.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtqbvixgzu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaatkyzd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gtiymgfipo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtsqqzdurf.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtunxuibzm.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gttwdfinod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtjjlukspu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtnlkyjtuf.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtdyiayecu.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtkbejezln.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gttslohqvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtjufawren.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdxjykaq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtlfsosxbv.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtbadgbsiv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gttfoomyfq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtomulewyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtfifkahgm.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtbihxdcoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gtlbgbsejc.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtvgoazhbz.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtnnvrqpgu.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvbpwdwyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtfdouyzim.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gthicninbc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtlyhcuxfs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gthiitvxrx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkvzlnqtr.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtuqfnyirh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjhtasmtw.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtftauwwdq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtqqqwooeq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gthfuzwujd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtglllsimd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtrzmpbsxg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtouuiwvxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtwhabelcr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtianvhdcl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtniraekxa.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtihuodlif.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtoqqqkpoh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtldhapzfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtwfqesjqv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtqmicqfuj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtakgazgbb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtagnonngk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gttuyftmjh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtkvzxonuv.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtduosyimv.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtncmggkyt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkvdcdubk.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtfvktdiil.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtchlyutmr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtkardosgk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtwhsupwba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtkqchctez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gttkofirlf.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtatbtpbem.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtvylvxlwq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuexqqdex.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtcdlkevyj.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtduzxgitf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtgbydjlbq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gttvyjzeir.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtyskpxnhf.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtlklwekwr.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtamvvinto.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtuywqyikq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtqswdtqgx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gttyeeabpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbmcnwzbu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtlfrybwun.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtjhqqavjs.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtbchddshl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbjewpvvt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtsrgfejsb.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtkzzeinnb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtyxnvqcsp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gthivnxttc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtxpegzuvg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtmzwavljt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtxdqbulhd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtnehifysb.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyvmurmm.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gthyzwwyxm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtmkcsxjhz.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtjajwxgxm.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtpejduvty.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtjcoeangi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtsgarmtdm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtqxltycbe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtfluupptd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtqpgrfitn.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmmaglwr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtzapqtkle.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtxiqhrcyn.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtecgwavua.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtzcoghxhp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtvaemizpr.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtnbortcfx.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtoxzckpnq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtuslokogd.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gteenlxvku.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtwkpkbaee.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtrijldpia.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gteujdbzlq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtfompjuri.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtveyqetvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtwlkrfgwv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtpxpuliku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtbwlcczcv.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtvktubhoy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtoucalamt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtgggvlkgo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtsjwrbrly.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtovppupxb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtyiyjrkaw.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtyzqssrdi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtzosuduxa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxhhnepee.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthydrbzqa.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtccatmfnp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthosgvldo.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtttdtwocz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtootvgnkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gttciigipk.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtczgpjcjf.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gthaogmphk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtaodhamwh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjcefygqg.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtcvyopwvs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtdotzjxzm.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtofsxpywm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtbbkasepd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtgjmrbytl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtefzvlhfu.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtyswvhegk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtjwgramze.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtwgkdbpil.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdtcbmmdb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtbxahdkgw.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtaynnwfhv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtmggqwnkk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtwcsfpcmu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtyxiynffv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtehjootrr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtxjrxutrl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtlkbzrqev.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtmchcprah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtwogcmnxr.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtsimrgpuy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszqujoez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtkhtfaaxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcilcpfzk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtwljcbhdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngcknxhi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtaozmzvsc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtsxlkhotb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtwupinhie.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gtoajmwnjx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtyuwohvva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtyvbzisxd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtkxgnwiey.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtiisazrmr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gthtqkqagc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtusofczvm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtobxuecrl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtwxnzavpi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gttnncfwls.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtcocbnzdy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtrbuuyphn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtdrhzqvvz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtzzxzysak.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtipipzlug.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtjhgcbrte.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtregulisi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtemsmtcva.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtmupswcix.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtxloyxnaa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtuzotvovu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gttsiznjqi.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtzxutlszy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtxbrhvybj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtdtqdritz.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtydgndblv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtfjenwbkv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gthgiuojjl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtbepetxks.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtjsgslmpb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtwsfqvwcg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtdapyqkin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtaxpjzvdk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtmchstqyp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtbgclmawv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtcifuaiba.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttryljisx.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtwmhthrwt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtahsbvvca.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtnksiyiwr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtowpkirmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtomdlvefd.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtozeyxgcl.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtykjxpdwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtylxkhxhl.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gttxyvywnv.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtpjmgtdps.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtnnxwbpmb.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtpnbxbuzz.html


<!-- 参考信息 -->