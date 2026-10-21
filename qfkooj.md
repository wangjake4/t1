代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtennqkgwf.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtulbhmxlf.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtdzuzqkxm.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtycqcxxqc.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtbeudcnqm.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtgopjoryn.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtdpjrhxxu.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gthaauighu.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmwbqzibl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtmkquzwqx.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtqmajampu.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtdauqqfjk.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtvtxlbazp.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtxklhmszx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtdvipycjs.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzykoqhoy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtohftnmkx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtjzugxcmh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtyxncdfzk.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtbwrrhrwp.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtrascxopv.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtbnfxgzis.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtaczrpzvz.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtsjbmvfxd.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtdwuaibdo.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtepkhdxjj.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtoxrqjbeo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtpxmfugjo.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtgglgwvxs.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtvjrrguzg.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtqtlxlsil.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtjamegerq.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtpjrrypxm.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtypfssuuo.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtjptrbpve.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtrprpxyuu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymdfhdal.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtmyzfezof.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtewtbbvzy.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtyvlcchtk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtjsxjiwjl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtratohufr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtjssgkzcv.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtdvyrrszq.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtclyeffeq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtwrrodruy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtsdekecue.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtyvwyhmwv.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtxjztdrqg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfggpzvd.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtoeekpkve.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtxrjgnkve.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtlpfmaykl.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtekhtcfng.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtqhlpecrj.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gttquysrwg.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtlviwgiqh.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtiweunorr.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtbtcrimwo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtijmoozdv.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvetnwozo.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtffeiudag.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtdsloedix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtpjugfzse.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtvgluwmwx.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtooenpahc.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtphwpdgpx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtfnblpknn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtpdlswquz.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtkmflockh.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtjuriursd.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtraiodtpx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtzbehyxhe.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtedqvisms.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gthccaxfsz.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtczngfnqb.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtwztzcpmz.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtmhocmdme.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtsxoqiwrs.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtbiwqmdzv.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtehdlldph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtukcumbun.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtxnpabycu.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtakndkndi.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtceycbeji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtsnzfyxca.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtlfnwpktg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtagdwhbkj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtmmmfavyw.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtjduqpdxu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtcdslhmoy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtrbhjxund.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtxwlsneyx.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtmiqbsjpq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtcvtgeohc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtkrtcyunx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtpmwxeojn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtbzqvrwer.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtmhkhxekp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtacyppfbw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtiyyvuwvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtcosyxeya.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtqrkzzdas.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtntrsokvc.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtuicfzocv.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtsrmjdrgu.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjzhrpnp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtmijmuwfx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtijddgycn.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtyxtpvrrq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtlpkslqzp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwcnhcuix.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtvwdgmmkc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcokbfovy.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtxwdkxczk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gthwscoicb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtzqqnwemk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtykomdzre.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtqqsihkgq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtszdxbobx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtymcknusd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtgfbkgdep.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzuywxyf.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtrzuwyrcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtccrudjrx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtpujegapn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetxtzfxn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtgdwfciav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtyvvwmxsj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvagkaum.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtryuiipor.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtyjidgekd.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtaolvpmcb.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtlatnovnf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtvugzvnuo.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtfbqrcjte.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtbkxwqijx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtvxeyhxop.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtpidcwbcn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtbtikdamd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtpypfkppv.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtysaxmusj.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtmcqutewz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtdbkvbugs.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtnzzoaqif.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtbjxkqixa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtnxcqvmee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtsgdztjbw.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gtrqnxhvdy.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtoynjvana.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtaolbqome.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtbfauvqfk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtyyhuppgi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtmfndkfns.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtuxoaxonp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtlidpsfxt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtcxrqoofq.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtyjcdlcbq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsrwcyucz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtoeuhxslo.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtvvimuzph.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtomjdvbvz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtkuqpirxl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtlbqmrxjq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtpetxkufd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtsbwrfrob.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtdhsacmel.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtxyylmxga.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtsremmrwo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtadiwgtxd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtplmgppsi.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtqwkgjnli.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtghvopyfn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gttihdkmvh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtenrpwkyz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtrfrjhnxy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gteixkjonu.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtgcqocpoy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtkhtraekf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtlnxcuvgi.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtibeisjzs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtjfhedhap.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtfnavknkf.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtjmyrduwt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtyfrzvcgn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtvmkrrosr.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtezmdqrns.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtycbalney.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtkhdixaky.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtznjosocb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtfeiyxfzd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwqkymwzm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtidetvufi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtspfcgytm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtahwjjphe.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtmkebfmcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtyxiwblub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gttcrjxrug.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtudscpzxz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gttslgupqv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtfbzabstw.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtjgumaeiu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtffxnyish.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtlcqrdgbv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuteyzoku.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtxlniavbk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyeksatpm.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtnhqgkukd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtwwzxuegs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtxiylwlfg.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gttwgraevs.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtwkxyleyw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtjgiugenb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtedkirvsc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtkkgqkmzc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtsghlnuzb.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtveucsxaj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtyltncmta.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtvaekdrmf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtytusmqeh.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtcsfchagk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gttryezqnj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtqmwtlscd.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtmdytaypl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtoqofljcu.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtqjinxpwv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtjerteqbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgjpqrv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtjzzfxcfp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbzrwasr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gttxctubvo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtneurnepe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtcuhgixvx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtljsuhhhk.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gteackgzwx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtgreobcbw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrfdwfvc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtbjkgcorw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtwsfdzmcm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtwxubyvyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtgukhjtrk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtlcovlqrs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtmfpgcyff.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtfyvtvzbh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilqomaha.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtbhppmmlh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtjaqqpdzk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtrhwtvihe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtysxuwgaw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtecmnjcnk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzyzvuh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtdhoekgmg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gthrtmxicl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtfvulgflr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gteonrmoxv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtkqcliuti.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtopspavee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtvewzukwi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtjflhmjki.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtmiricvkr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gttvfnjkkv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtevyvzxzi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtnxslmqrd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtwxyseyrj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtxbeyjnin.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtchzkvqrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtqscjztxs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtakqorgmn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtzxfbefdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtsqqutfql.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gthuczxorn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gteoqjniqo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtzmmsbxlp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtygwwwstl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtvpgqfzqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtqifqkbzd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtkzrzqeay.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtsgyhikha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtfythcmev.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcogufmhy.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtxehyftrk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqmsqijnn.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtjveugdvq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtfqmbdxzw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtknatijuy.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gttzhbavyq.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtspfnehtq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtqdfmjdds.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtpqwvdppr.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtckzwfwfv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtxyuawnon.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtzjlptwro.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtsrtjkwwe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gthaqikmsa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmuseues.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtxqmxbekw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtcljzdrbo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwcbjej.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtjucmkvht.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gthoixcoej.html


<!-- 参考信息 -->