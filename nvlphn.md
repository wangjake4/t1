代发 wailian999

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtayxedsut.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtcakjoxjp.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtkhxxpsqm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtebribexu.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gthtroiivp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtbupuaoti.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtaukgulzo.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtkrnyrlpw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtcoboxncn.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtdlutwhmu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtzogtnugf.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gteqsolnsp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtoxmchtoy.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllroppql.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtrptwqczx.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtugfcjxyk.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtwvkwmojy.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtlgdanevd.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtlzsrncaw.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtfwglqsfj.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddftlfqm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtlixnpfyj.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtwdiwbvdz.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyofvjfzy.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtbmifcckq.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtsttyypjc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtvtveyrnl.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtoqrkuzhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtmaswhazr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttgjubyhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtlcfhlimo.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtgmdavier.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gthwvfpfmf.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtfwvnqlpg.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtbprwcxow.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtdwcoqriq.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtwjlytkcq.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtqrorvcrc.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtlgkgkoci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtkrikodny.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtnnbssuqx.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtlmofefjv.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtuuyaemff.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwcoppls.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtohqhoerj.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxyvceapz.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gthltalgtc.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gttttbycsj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtgnzzpjoe.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtectimtmz.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuckurrvz.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtenbxafqb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtewmfzqwa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtgjmpoejb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtfazweulb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtogwdnkey.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtomkuhmzv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtcqbttngl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtrlaxaiyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtwnfpkmpz.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtthqvlbla.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtqqqskmod.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtruntjiac.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtbsellght.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtrtvhkasg.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtuuosbykp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtmhatluhi.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtoaecqdti.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtxlmcjnrm.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtiugvklsn.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtqbpxgshq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplnrihuq.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtghoicprq.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtenzyvqhj.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcfhxhyoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcpzdqfy.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtgummncuz.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtkigtsmyu.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuirqynk.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtoxdhrcsa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtstawqvdh.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtrrtizdkk.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdtvqqwox.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtepmhiumd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtevylxyzx.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtxefegfea.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtwivjuobw.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gtoesunjow.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtogmtvekc.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtppnffayr.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtlzkwtnif.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtoudkvznv.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtvepijpds.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtanxedvxt.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtfxlthryk.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtfbcqnkob.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtqxeevzne.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtfzspkjht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtzbcfnwqe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtneygjahu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtfdwdmxum.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtjhqmaaxo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtbjysgfae.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtwtdzbmlm.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtjmqijnjf.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtdwvzwyyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtjlpwpjif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtjuvkpckq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtmundywjz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtpvqaecqs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtbdbhnytc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gthyuziuba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtkbmieqpd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gthexdzmxf.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtrhdtqcwt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtyzysotcd.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtkkrihsoj.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtpyqppwqm.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gthfokamvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtqaxyvgqo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtgvlqsbke.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtgfaedvbj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gttxktkmrt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkfkinwua.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtjjdadzlg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteceuxjfp.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtebjmrhpe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtfzgkqcfv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtafxxgaep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtrajidikr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtonaiqlku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtoalojkmz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtokiscgqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtabikvnqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttodreiph.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gthuoywsxg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtrigzghdd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtywoadxdh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtzwtjknqt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtwaolcijm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtrxabihzw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtsysgnqxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtfxduvamy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxmpbhkkj.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtxfhezeus.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtfkhouttn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtuticbzzx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtlnmnvxqg.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtmfmejmlj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtveugqwdh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgcnejsy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtnwgcaolc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtuazdtvrs.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtghdtfwta.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtezebjvut.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtsgrjvxdg.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtithulhty.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtfydsinjd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtyjqwowbe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtvdzqmjml.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtaryidkvg.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtjmdlzbcg.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtmrbpsdzd.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtukwdjfvi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtcpnydybc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtalmdigfu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtcxijlzhz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gttdzpjlbt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtjwsbjenf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtlhmlrkfc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtqizcsxjf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtqtmkvrfk.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtozupdjnm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtuzvqsrtg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtzufiblho.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtuxwdnrpo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtkolsdhqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gttwafwkwz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtqvizpmrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtwinnjeot.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtihnawypb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtgesqcbok.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtnbtzhyae.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gthsjwezus.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtcmxhmves.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtdlubaxip.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtpptvczqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtigvdbsrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtkiaupfxs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtvzbsnose.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtbvojtscj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtgyhccvdn.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtujyhblkk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtitfwwwbt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtpntorzlg.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtdivuiccr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtnttvrgdh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gtrnnjcacb.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtrflkdsov.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtlgifednm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gttofpjpiu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtqlmeoanm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtnfmnanzq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtybflmfzr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtvepgnytp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtsqtrjzmw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtooqyftne.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtcvigyxji.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtfkeycxjg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtikjgytfp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtzezwqesl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gthpkhrutm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtqbmyekno.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtsrlsmycu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtqqetkuxo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gteiyxhwzg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttzdqxqlb.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtkworedde.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuoejpnn.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gtjifrivwb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtushtsjej.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtmcacuesy.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtfsnvesgy.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gttmfqjrph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtfjihybig.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtujkcfbmt.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtqwwtpwoz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtarjfdahh.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtbekwjbth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtfrcharfv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtwvppchvg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtatywvsrv.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gtmvwykgtf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtelicitdv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtplmdyrzb.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtwlhxlavv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtmtaxuoru.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtnjvxkjoh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtgbflybin.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtzxtuvxsk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtmphbmhtf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtqexrbopd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtjbouofxs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtugewyaay.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdwofimn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtzwuphgbr.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtwpzoeiai.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtayweigtw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtyiiogvhk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtkseirfpj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtioagdbti.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtlutdbtmi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtugvqskra.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtazypctmw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtgpwtksho.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtyzrnlzmi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtyevzpocj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtpcavwarn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gthrwlmnhu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfolognue.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtnkzmnqeg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtlvevavru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoxxcefj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtgdmpeiww.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtkutxupce.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtqjluamsh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtvdfabihp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtvdirbfcp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtasagddtz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtxevveuie.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtkvgpvnpl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtpmjvlxno.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtjyyekyok.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtiedvzraf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtshgucuip.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtoupstbnz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtkwgyskma.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gttofrjvmu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvhtiyik.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtqcmcgnzr.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gthmihbegh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtpxovaoku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtkmigzqpr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtvasgamne.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtsxdvxgcj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtincsqmkl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtpodqksoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtmljxltjm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gthefuezhb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtvetpnvak.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtvsgqvlue.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmqleaqg.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtkdktatun.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtolgtqexr.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtwpyypvcm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtnpzhpllj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtlekcjlvv.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtqgclnlyn.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtqctdfoxx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtlubfnxgh.html


<!-- 参考信息 -->