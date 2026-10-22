代发 wailian999

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2ghfdaywo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2qtrgmspy.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2nhfjoxkg.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2otkcwgzb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2tepxmkun.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2kevlwnxm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fywgnjyf.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2lklzykoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2dhzmsnif.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2llmkargc.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2bjxwrhlm.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2iekosgtx.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2lcpnvlib.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2tddooghf.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2waqrxomu.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2icxnngln.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2smmvnwnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2cohhcsdh.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2hegfopvn.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxklbmxc.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gt2rijbgjbs.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gt2txilrmbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yzdfjgmn.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2qjwempka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2tbbxevnk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2vkdghzax.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2akphlwtj.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2gpzqfztz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2bcwlhkak.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esbqmeov.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2ajndnwff.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2bqbvgzdx.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2cbpbwgui.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2obgcycfd.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2eeqfevwp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ajhzbron.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2wvqtyxzo.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2zutyrqwd.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2mjepgcvv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2xnwisapr.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2datsfthl.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gt2qsndgclv.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2dgwreaeo.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gt2zubuymdf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2hgumigft.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2zvzabbfm.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2cgbwjrso.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2ejdybsvf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gt2ehorybnd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gt2otsckvcx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gt2lirmgpfb.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gt2ovdimcmh.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2esvrioez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gt2watlwwlq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2qndgemcf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2arjwlpzl.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gt2gkyhqewy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gt2rhslxidi.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2msochblc.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2ibkddqih.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2sifufrty.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gt2vpoufwfw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2caqwtthj.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2towsezdd.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2imuqsymm.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2intnoozw.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2nkdnehcy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2yihdsgaz.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2aizuwbxc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yivfwlbj.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjptwtdr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2dsmkhyqe.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2agzvucsp.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2ayhnvuvy.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2kkyvhkns.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2luabdjyv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2tiuncrrj.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2efmkrzef.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2lmniozln.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2szkudxqv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2hbvzzlpv.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2yqfliwdu.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2yjuhcwkd.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmpjzkdt.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkctuefe.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2wepcmrac.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2mvaojukk.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2kediampf.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkhvhxvf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2zjikduug.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2dhcbcgvc.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2uxusedjn.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2arshqrkb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2gevwgucp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gt2tcisvcwp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2adtwevxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2emgselbs.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2lsmzoppf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2aswmscbi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2ssquujla.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onishlyu.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2qfadudne.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gt2ooynuqge.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gt2obwoaego.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2ogxextmh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2mvisnxfr.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iblnzlty.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gt2kuqiheax.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2cwoofwmj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2fblounje.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gt2dgrvsefg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2ducaello.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2cmfboqnw.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2vrgtqcor.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2nxpgtjst.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2noxulpov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gt2kkdfejlg.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2vpzqwucj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2wvgcwpar.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fuhdsqqg.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2shioongc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2uvutrhgx.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2lctgrxrn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjkoxzog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2dvjqebxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2tetnhqcu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2lvqhuxgy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2hoarajdc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gt2ryhwsuec.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2yskzjitq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gt2hpwcebvc.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2xlqgltpw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2vtsqgjze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2zsfxioso.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nzvahchj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ceyedjty.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjxxwofy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2lscpvdya.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vputujte.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onvqgsgh.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2ccrbauan.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2akxibqxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2xtzqvxzx.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2fxsavasy.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2cjtlydea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ildnljnl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2ezhedbqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibjvrhyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2pctqztca.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2sbbrcbaa.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2kmvjptbf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gt2aqahhlut.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhzauaqh.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2lkzxdkgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhetensa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2mjodhceo.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmtqhxbv.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2bdjieiou.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmlghlty.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbeudqih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkbkozjh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yhrqsrap.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2qzsidapr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2iaegocol.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2cnzqrjwq.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gt2ygivqkpv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbxxlloh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2xilrcwxp.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncpfnswm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2itdkursv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izsfyztf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2eqgjjyoj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2euxtscrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gt2lyatifet.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2yxxqzjfy.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2escjwkew.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2yfytpqpn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2pzzpkups.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2xiobftpe.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2quhpixvq.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2otnjypzp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2tcpslogi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gt2mhylshgl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2cmmwsgnw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2hmxodgkx.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2uyhnefqd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2fxspnehq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2iutbwqux.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2wnnkffeu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nspbroqu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2naxofznn.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhdfxjys.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gt2kjceoahe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2nexrvbpm.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2skjmqoxs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cflooqtt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2tzvhqynv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2ljzwgtse.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gt2xslsduuf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2xsqyxshq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2cydfzosk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2lrexveth.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2mxflxqxl.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2fqxvbcwz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2zbititwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gt2pgqesyxy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2yoozxalt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2vcozhlrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gt2ijfcifhh.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2oflvvltw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gt2qkfggoeo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2mqlqjbnf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzgahgyk.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2dlvtegkr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2uhfwfpeh.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2hhrncsrh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2nmfivbjm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2xlkaiybj.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2xwwkrjyd.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2eooouvzn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2lziqngst.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2nbbdotal.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2bohsjgze.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2texfaghf.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gt2wyamcozc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2sztumapd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwjrdpoi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gt2mtrzotvk.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2vruoxspk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2ioqqiftf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2fhxdkkaa.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2xrxmwxqq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2wyjxctqa.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gt2wpezgseg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2nfoagopd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2osmlbfis.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2absrlnmd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2rlafotsr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtslllvt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gt2jdikyzef.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gt2kbuhytjr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2ptqgkmwa.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gt2knbtlswv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2kksyofsf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2hccsblaf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2nibfmusu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2xrmhhlwh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2utuzsicn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2vbiymyrc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhofcfvh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2dkrkccmh.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2lumoyulg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gt2gucilhdb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gt2epufkhto.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2shgeqgpo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2hcxoeopc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rggsdvuu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2nfxdafwj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2mlarrqht.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gt2tqjqrina.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2tshdjyna.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2kmlnshzn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2uzwiyrdr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2gvgqlefj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2gemjiiaq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2vdjodhit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2esnmfjhp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2wwawwhsa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2vmbogecw.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2jtkczxsb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2htgyziyv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2wmanpupb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2troxrfyn.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2zscocmph.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2twpyyeqj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2adodgkqb.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gt2kbvwwgru.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gt2lpvlasyj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2ledmrcaa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2wdizueev.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2wmlppiul.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2tdopzkjs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2htwjnxxn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2lhdleqzs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gt2cujjfuuj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2sumoffix.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2rhylsbay.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vdminnuy.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2qkopwwca.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ustfrprj.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2lljofgcg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gt2epnjymgq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2qklynouc.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2uftxtxqi.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2izknotvz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2jrudwdct.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2vnrgeacd.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2omlhswjv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnwzybhz.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2aisdhfjy.html


<!-- 参考信息 -->