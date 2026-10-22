代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2rxixujmc.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2delgoycb.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2urdmgyvp.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2stdfcmvl.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gt2zjztwalg.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2dorkafek.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkqdubue.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jogrbwao.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2ksplnwoi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2erzriles.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiitllhk.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2ljmbcsqi.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2epjbqaor.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfzobpug.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uhwljhqs.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2pucfzrvs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hmnjvnxx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2mmbxfkpy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2gjoefphh.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2hlnbsbpe.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gt2ehvmqjvz.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gt2hwzjdvty.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2rvuvgfsa.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2konvasfm.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftefljut.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2anjtnuxd.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkvxzcfx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2fjdmtiuw.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2eqacaitb.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2bzvanzuh.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2tflwatzm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gt2wbuhftos.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlcsltzw.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpsbcidr.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2mjpnhscv.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2zcwatuer.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gt2gumhwavf.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2eygqtkvd.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2sawgwoyp.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwicizkf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2nyvbqgmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gt2sdypovai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2hiymbrvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2vjrfcykq.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gt2zdcutqcp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2oixbvdvw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2czlusqwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2bjivvzrv.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2torfttkt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxxwpkdr.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2kjacqvmh.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2odvktnfk.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2gsnojonx.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2zkqgsywp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2upsyxbho.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2ljrcvaxn.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gt2ygdincuj.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2lnkprtep.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pratgifk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2bparpoot.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2alvuxtld.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgxvcpqt.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lczjtizv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2glgxxplr.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2vazorpzc.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2hzlghoef.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gt2xvgzfstf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2tejjlign.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2oreblisd.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2hucsovir.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2efkjjerf.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2fxfuuqjz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2dtrqubce.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2thnnexlw.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2waiqxkvm.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gt2qniwvaxy.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2pygoissd.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2kbjpswdg.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2hkgnokyn.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2viqkewzv.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjkxjhph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2odnqalbc.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdngnxws.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2jreckvqc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrwfbdj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2lqheipjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2dhmcddwn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2lmirzwna.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzuionat.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2wjlhgjag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2tarsttky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2vehjrccy.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2kohkleer.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndrdqbvf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gt2zncmlrrp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2nkfvthna.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2timyvnrr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2fqfezdio.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzdgappg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2mnuzjrmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2prlsksiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2yvfjjxnp.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2voeekluv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gt2mqopyazt.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2vxkorkvt.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2bxnssbee.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2hdisjldz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gt2wkcvlkrk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2vobgamav.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2zhzkbwau.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2yemyescn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qvjyhuws.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2dedwtiyo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seiquado.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2ofnygvvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2zwhqnhgi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bgabwbnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2nkemtpib.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2ikzhrdmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gt2ssdansdj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gt2ozsiapwf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gt2joaweovq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2kovhyavv.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gt2ypyeldqg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2kmimvwqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2rntkiknp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2rhknschs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2msnisgfj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2mlrzcumi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2trxqrrjd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2vfhgvuda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2emquubff.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhbirrsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2vuvvlyqu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2bxpnayxc.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2ecmcvinq.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzaysiwi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drwosses.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gt2rwudrjjr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2nbshqoiy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2inqhbhbt.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2kbaoyqxn.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2apkwqjln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2xrdevleo.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2tndcrnsd.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2razchgig.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2pmmbeaxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2algmskim.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ewbteynb.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2gypsekuu.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gt2apdnqdxe.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2ktjuaggg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2hxggkhwv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2trrtdylp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2uiuzugkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2uccgfaiw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2mqftxejo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2gliukqdh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpchmwhk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2ydixtiik.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmaevyuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2qsfvjtyh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2fdswpgnw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2gmummgqy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2molrmwnv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lasmfjoj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gt2tgujpxtx.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2fysibpfv.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2mwejfmef.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2jcjhzory.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2igrrukrt.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gudgkbve.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqzuktan.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2tqmetbsh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gt2eqicaoqa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kngnfzrf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnrhvhsq.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2dbltiatk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gt2cbeswgwh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gt2fzkxhwhc.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2qwglnhbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2gjawbtza.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2yiiyddhm.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2zebgzbsy.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kemrblwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2dmcojdmh.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2ktdslegu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gt2veyyjxwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2colkbpur.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gt2tlnksvyz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crywcsrz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yfruqazk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjpygfay.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2ucvpzevn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gt2enmzfmrn.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2tabgkaee.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2qosgoaej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2beltmidh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocljvmwu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2qfsuuiii.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2doaltjrh.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2mqhgrpwr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2bojqabqs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2orioaiju.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlsyduwj.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2dajmlwjc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wxazjfcg.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhxvbqce.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2buwsoygr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2fpwzxyey.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2omrqcnwa.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wnttqkej.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yubcxbbp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2cfftkzom.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2jnvdkkks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2drarqpab.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2rrsnakji.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giajhzmc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2pqfoupuf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gt2shqkloka.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aahmhsvr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfuewipy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sowvkper.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2xnmynaze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2uxquljue.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gt2cnvffwgi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2ydunatrs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2xwfuvfpr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txvnxave.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2oqqudlux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2jbnlhefx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2pcnivrad.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2ontpbcks.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qklvkycd.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2tifsgnjy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gt2nziqbdho.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2kkppaxok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2emyxvzbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2vqhcksfn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2nxkyvjnt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2qsjjxhft.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijacsxcb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtqtgdke.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2fzryaxfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2ipqupckr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2tlqbrmzd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2koquiqxt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2rralnrbv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2vmlqsfld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2didnvwxu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2hrgnwudy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbprjwrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gt2rrutpcjd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2xybanbdl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2yiisfzrc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twicjyzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aahyftfm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdywock.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2rnxnhhil.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2navcymmg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2sbsxunpz.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2apnwwyhi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dciiulhl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2ywmmcevi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2dghcmshs.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuozkobr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2mafjlhov.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2mdldotze.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gt2ofoehpsj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2sbzffbth.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gt2fuyqexai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gt2ytkjlegx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2ushwtdaa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2bqdbwqcx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvqkwubf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2ggrkpeuu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2fswgkidu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2zksboing.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2dfccrthd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2giunyhud.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2eavpvxdh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfdljugr.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2gdbihvor.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gt2zgwdynwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2wkbxbbrk.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2augsojtu.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2wnwgnyys.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gt2uhfynair.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2zeemhwii.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2qgidvthq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2kpnbjgpz.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2cgkzgnfw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2qqpwskvp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2csjkxlkq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2sjteqhcs.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2vsxzpciy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2wlukvxun.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2apgdmdie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdwlayvn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2tssbscjx.html


<!-- 参考信息 -->